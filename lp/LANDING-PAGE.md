# Audaces Connection 2027: Landing Page (RD Station)

> Figma (fonte da verdade): arquivo **Connection 2027**, página **Landing page**, frame **Frame 26**
> https://www.figma.com/design/S9qABGwk7yIfxLNVkXpTqu/Connection-2027?node-id=642-3540
>
> Identidade visual: ver `../Connection.md`. Se este MD divergir do Figma, vale o Figma.

A LP é montada no RD Station com **3 blocos de HTML**, colados um embaixo do outro, nesta ordem:

| # | Arquivo | O que é | Figma |
|---|---|---|---|
| 1 | `01-faixa-data.html` | Faixa animada com data e local (letreiro) | node `648:18631` |
| 2 | `02-hero.html` | Hero: logo, chamada, CTA, ícones pixel, cronômetro e globo | node `642:3614` |
| 3 | `03-programacao.html` | Programação dos dias 01 e 02 + chamada final "Nos vemos no Connection 2027!" | node `693:10253` |

`preview.html` junta os três blocos para visualizar no navegador (simula a coluna estreita do RD). Não vai para o RD.

> Havia um bloco 04 (paisagem synthwave). Ele foi **descartado**: o card final passou para o bloco 3. Os arquivos estão no histórico do Git.

---

## 1. Como publicar no RD Station

1. Para cada arquivo, crie um bloco de **HTML** no editor e cole o conteúdo **inteiro** do arquivo.
2. Ordem: faixa → hero → programação.
3. Não é preciso subir nenhum arquivo: logo e fonte vão **embutidos** no HTML (base64).
4. Zere margens e paddings dos blocos/colunas nas configurações do RD, se houver, para não aparecer espaço entre eles.
5. **O editor do RD não executa JavaScript.** Lá dentro o cronômetro aparece `00:00:00:00` e o globo e as animações de entrada não aparecem. É normal. Confira na **visualização** ou na página publicada.

### Regras técnicas que todos os blocos seguem
- **Largura total:** cada bloco escapa da coluna estreita do RD com `width:100vw; margin-left:calc(50% - 50vw)` e `box-sizing:border-box`. Há `html,body{overflow-x:hidden}` para não gerar rolagem lateral.
- **Classes com prefixo `cx-`**, para não conflitar com o CSS do RD.
- **Emenda "infinita":** todos os blocos começam e terminam no navy puro `#090F2B`. Brilhos, grades e globo se dissolvem antes das bordas, então não aparece linha entre blocos.
- **Acessibilidade:** `prefers-reduced-motion` desliga as animações. Textos repetidos do letreiro e elementos decorativos usam `aria-hidden`.
- **Mobile:** breakpoint em `767px`. Margem lateral de 32 px no hero e na programação. Testado em 360, 390 e 430 px.

---

## 2. Tokens

| Token | Valor |
|---|---|
| Fundo da página | `#090F2B` |
| Azul | `#0064FD` |
| Ciano | `#00D3FD` |
| Roxo | `#7727F0` |
| Magenta | `#F9039B` |
| Branco gelo | `#F5F5F9` |
| Easing padrão | `cubic-bezier(.2,.8,.2,1)` |
| Gradiente de traço (marca) | `#00D3FD → #0064FD 28% → #7727F0 59% → #F9039B` |
| Cromado de títulos | `linear-gradient(180deg,#fff 0%,#fff 30%,#c9ccd1 46%,#fff 54%,#fff 62%,#8b8e94 72%,#fff 90%)` + `drop-shadow(0 0 18px rgba(255,255,255,.3))` |

### Fontes
- **QB One ExtraBold Expanded** (títulos): embutida como WOFF2 de ~4 KB (`assets/fontes/qb-one-extrabold-expanded.woff2`). Foi gerada da **QB One Variable** (wght 800, wdth 100), só com os caracteres usados (ASCII + acentos PT-BR).
  - O arquivo variável original tem dados corrompidos em alguns glifos: `( > [ \ { ¡ ¿ É × Š Ž — ' " › »`. O **É** foi recomposto (E + acento). Se um título precisar de parênteses, aspas curvas ou travessão, é preciso corrigir esses glifos antes.
  - A fonte não tem itálico. A inclinação é feita com `transform:skewX(-11deg)` num `<span>` interno.
  - ⚠️ Confirmar se a licença da QB One permite uso em web.
- **Chakra Petch** (400/500/600/700): via Google Fonts, `display=swap`.

---

## 3. Bloco 1: Faixa de data (`01-faixa-data.html`)

**Conteúdo:** "07 e 08 de janeiro de 2027" ✦ "Auditório da FIESC, Florianópolis", repetidos.

| | Desktop | Mobile |
|---|---|---|
| Altura | 48 px | 38 px |
| Fonte | Chakra Petch Bold 16 px, `letter-spacing .08em`, caixa alta | 12 px |
| Estrela pixel | 24 px | 16 px |
| Velocidade (uma volta) | 45 s | 32 s |

**Efeitos**
- Letreiro contínuo da direita para a esquerda: dois grupos idênticos, `translate3d(0 → -50%)`, acelerado pela GPU.
- Pausa ao passar o mouse **só em dispositivos com mouse** (`@media (hover:hover) and (pointer:fine)`). No celular o toque não pausa. Antes, um toque congelava a faixa.
- Fundo em gradiente azul → roxo → magenta → roxo → azul, deslizando (12 s, vai e volta).
- Reflexo de luz atravessando a faixa a cada 7 s.
- Estrelas pixel (SVG) pulsando com brilho ciano, fora de sincronia.
- `box-shadow:0 6px 0 #090F2B` com `z-index:0`: se o RD deixar um vão entre a faixa e o hero, ele fica navy em vez de branco. Quando não há vão, o hero cobre a sombra.

**Ajustar:** velocidade em `--cx-velocidade` (maior = mais lento).

---

## 4. Bloco 2: Hero (`02-hero.html`)

### Conteúdo
- Logo Audaces Connection 2027: PNG/WebP 2x exportado do **vetor** do Figma (node `681:9995`), embutido em base64.
- Selo: "**Audaces** celebra **35 anos de história**"
- Título (H1): "Uma edição especial está chegando!"
- Texto: "Faça parte do grupo do **Connection 2027** e receba todas as atualizações sobre o evento em primeira mão."
- CTA "Entrar no grupo do evento" → formulário Microsoft (nova aba):
  `https://forms.cloud.microsoft/pages/responsepage.aspx?id=Pea-wGELFkKHeCdIUzWYFdltyA4ArOtFvHacF0teTvdUMTg2WUUyQ0ZYVUI1Q1pPU0lQVzcxWUs3VS4u&route=shorturl`
- Ícones pixel: **Audaces** e **Carinha** (SVG inline com o gradiente cromado da marca).
- Cronômetro: Dias · Horas · Minutos · Segundos.

### Tipografia e medidas
| Elemento | Desktop | Mobile |
|---|---|---|
| Título | QB One ExtraBold Expanded, `clamp(28px, 3vw+12px, 48px)`, skew −11°, cromado | `clamp(26px, (100vw−64px)/9.8, 38px)` |
| Quebras do título | "Uma edição especial / está chegando!" | "Uma edição / especial está / chegando!" (frame Mobile `684:10031`) |
| Selo | 18 px, `letter-spacing .24em` | 13 px; quebra "Audaces celebra 35 / anos de história" |
| Texto | 22 px | `min(18px, (100vw−64px)/20.6)`; quebra "…Connection 2027 e / receba todas as atualizações sobre o evento / em primeira mão." |
| Números do cronômetro | Chakra Petch Bold 64 px, cromado | `clamp(32px, 9.6vw, 46px)` |
| Rótulos do cronômetro | 13,5 px, `.08em` | 12 px |
| Traço sob o número | 32 × 2 px, gradiente da marca | 32 × 2 px |
| Pixels separadores | 7 px (ciano em cima, magenta embaixo) | 6 px |
| Gap entre unidades | 27 px | 4 px, unidades com `flex:1` |
| Margem lateral | n/a | 32 px |

### Cronômetro (JavaScript)
- Alvo: `data-alvo="2027-01-07T08:00:00-03:00"` (início do credenciamento, horário de Brasília). Para mudar, edite esse atributo.
- Atualiza a cada segundo. Cada número que muda entra com um mini-glitch ciano/magenta (`cx-tick`).
- Quando a data chega, os números são trocados por "O Connection 2027 começou!".

### Fundo
- Fundo `#090F2B` com 4 brilhos radiais (azul, magenta, roxo) "respirando" (9 s), que se dissolvem antes do fim do bloco.
- **Grade lateral** (paredes): grade plana de 62 px em `rgba(0,100,253,.9)`, 1,5 px, opacidade .6, uma em cada lateral com máscara radial. Desce continuamente: **8 s por quadrado** no desktop, 36 px / 4,6 s no mobile.
- Quadrados de pixel azuis com brilho, piscando em intervalos (`steps`).
- Ruído (SVG `feTurbulence`) por cima, opacidade .07.
- **Globo wireframe em `<canvas>`** (HTML, não imagem): gira devagar, inclina levemente com o mouse e pausa fora da tela.
  - Grade em ciano .28 e contorno discreto (1,5 px, `rgba(230,251,255,.4)`).
  - Bloco com opacidade .6 e máscara que some na parte de baixo, para não brigar com o cronômetro.
  - Desktop: `translateY(25px)`, com o topo do globo cruzando o meio dos números. Mobile: termina ~60 px abaixo do cronômetro.

### Interações
- **Entrada:** logo → selo → título → texto → CTA → cronômetro → ícones, em cascata (fade + subir).
- **Ícones (sutil):** flutuam devagar (6 s) e acompanham o mouse de leve (parallax ±10 px). No hover sobem 6 px, crescem 5%, inclinam ±5° e o brilho aumenta. Sem giro nem explosão de pixels (removidos por serem "demais").
- **CTA:** gradiente azul → roxo → magenta que desliza no hover. Brilho suave (`0 0 18px rgba(0,100,253,.35), 0 0 40px rgba(249,3,155,.18)`). As 3 setas pixel piscam em sequência. O botão é levemente "imantado" ao cursor. Um reflexo branco leve (16%) passa a cada 4,5 s. No mobile, largura total.

### Posição dos ícones no mobile
Ao lado do selo, centralizados pela tela: Audaces em `left: calc(50% - 170px)` e Carinha em `left: calc(50% + 118px)`, 52 px. Até 380 px de largura, 44 px.

---

## 5. Bloco 3: Programação (`03-programacao.html`)

### Conteúdo (provisório, ainda não definido)
Datas deste ano: **07 de janeiro · quinta-feira** (Dia 01) e **08 de janeiro · sexta-feira** (Dia 02).

**Dia 01**
| Horário | Atividade |
|---|---|
| 8:00 – 9:00 | Credenciamento e boas-vindas |
| 9:00 – 9:30 | Abertura |
| 9:30 – 10:30 | Resultados 2025 Brasil e LATAM |
| 10:30 – 11:30 | Case de sucesso LATAM – Kiricocho |
| 11:30 – 12:00 | Destaque 2025: Vendedor que inspira – LATAM |
| 12:00 – 13:30 | *Almoço* (pausa) |
| 13:30 – 14:00 | Dinâmica |
| 14:00 – 15:00 | Case de sucesso – Kímika |
| 15:00 – 15:30 | Serviços – Audaces Attiva |
| 15:30 – 16:00 | *Coffee break* (pausa) |
| 16:00 – 17:00 | Customer Centric |
| 17:00 – 17:30 | Destaque 2025: Vendedor que inspira – Brasil |
| 17:30 – 18:30 | Palestra surpresa |

**Dia 02**
| Horário | Atividade |
|---|---|
| 8:00 – 8:30 | Boas-vindas |
| 8:30 – 10:00 | Movimentos estratégicos e metas 2026 |
| 10:00 – 11:30 | Novidades de produto – SW |
| 11:30 – 12:00 | Novidades de hardware |
| 12:00 – 13:30 | *Almoço* (pausa) |
| 13:30 – 14:30 | Estratégias de marketing para vencer |
| 14:30 – 15:30 | Palestra – Marcelo Caetano |
| 15:30 – 16:00 | *Coffee break* (pausa) |
| 16:00 – 17:30 | Premiação. Descrição: "Foto oficial · Mensagem final do CEO" |
| 17:30 | *Deslocamento para sede* (pausa) |

### Como editar a agenda
- Cada atividade é um `<li class="cx-item">` dentro de `<ol class="cx-agenda">`.
- Intervalos: `class="cx-item cx-item--pausa"` (opacidade .55).
- Descrição opcional: `<span class="cx-item__desc">texto</span>` dentro de `.cx-item__conteudo`.
- Componente equivalente no Figma: **LP/Programação — Item** (frame `03. COMPONENTS`), com propriedades Horário, Atividade, Descrição e Mostrar descrição.

### Layout
| | Desktop | Mobile |
|---|---|---|
| Padding do bloco | 32 px (topo) · 24 px · 120 px (base) | 24 · 32 · 72 px |
| Título "PROGRAMAÇÃO" | QB One 48 px, skew −11°, cromado | `clamp(24px, (100vw−64px)/9.6, 36px)` |
| Cards | 2 colunas, gap 32 px, máx. 1090 px | 1 coluna, gap 24 px |
| Card | padding 44 px, raio 23 px, `rgba(255,255,255,.08)`, borda 1,5 px em gradiente (`#F5F5F9 → #0064FD → #fff → #F9039B`; Dia 02 em ângulo oposto), glow `0 0 18px rgba(119,39,240,.6)` | padding 28/20 px, raio 18 px |
| Data do dia | Chakra Petch Medium 15 px, `.16em`, ciano, com pixel 8 px | 12 px |
| "DIA 01/02" | Chakra Petch Bold 48 px, cromado | 36 px |
| Linha da agenda | grid `122px · 2px · 1fr`, gap 16 px, padding 18 px; horário e atividade 20 px | `auto · 2px · 1fr`, gap 12; horário 14 px (sem quebra), atividade 16 px |

### Card final "Nos vemos no Connection 2027!"
- 78 px abaixo dos dias, mesma largura (1090 px). Mesmo vidro, borda em gradiente e glow dos cards, com `backdrop-filter: blur(6px)`.
- Título em QB One **38 px** (tablet até 34 px, mobile até 28 px), skew −11°, cromado. Quebra "Nos vemos no / Connection 2027!" (no mobile, centralizado e quebrando livre).
- CTA igual ao do hero, mesmo link do formulário. No mobile, coluna com botão de largura total.

### Fundo
- Brilhos laterais grandes e **difusos** (sem efeito "bola"): azul à esquerda, rosa/roxo à direita, `blur(60px)`. Somem no topo e na base. Sem brilho atrás do título.
- **Grade lateral = a da hero invertida:** ancorada na base, 62 px, uma em cada lateral (largura 42%), **subindo** continuamente (8 s por quadrado; mobile 36 px / 4,6 s, opacidade .35, altura 460 px).
  - Altura 1000 px no desktop. Vai até o fim do bloco, sem fade inferior.
  - Some para cima e **em direção ao centro** com máscara radial suave (`#000 22% → .45 em 42% → transparente em 62%`), sem corte reto, quase invisível atrás dos cards.
- Ruído por cima, opacidade .07.

### Interações
- Ao rolar, título, cards e card final sobem com fade, e as linhas da agenda entram em cascata (45 ms entre elas).
- Hover no card do dia: sobe 4 px e o glow fica mais forte (ciano no Dia 01, magenta no Dia 02).
- Hover na linha: fundo suave, horário em ciano, traço aceso e o texto desliza 4 px.
- Hover no card final: sobe 4 px, o vidro clareia e o glow fica magenta + ciano.

---

## 6. Histórico de decisões
- Fontes: o título começou em Chakra Petch Bold Italic até a QB One ser enviada. Não usar o título como imagem.
- Ícones: animação de giro, gelatina e explosão de pixels considerada exagerada e trocada por hover sutil.
- Globo: começou mais forte. Ficou mais esmaecido, com contorno suave, e foi reposicionado para cruzar o meio do cronômetro.
- Botão: o brilho branco era forte demais e foi suavizado.
- Chão da programação: perspectiva 3D (synthwave) testada em várias versões, mas esticava e tremia. Substituída pela grade da hero invertida.
- Faixa: reduzida (estava "estourada") e com pausa só para mouse (no celular ela parava).
- Emenda entre blocos: brilhos e grades dissolvem antes das bordas, globo com fade final, sem brilho atrás do título da programação.

## 7. Assets
| Arquivo | Uso |
|---|---|
| `assets/logo-connection-2027@2x.webp` | Logo embutido no hero |
| `assets/logo-connection-2027@3x.png` | Logo em alta (exportado do vetor do Figma) |
| `assets/fontes/qb-one-extrabold-expanded.woff2` | Fonte embutida (subset) |
| `assets/fontes/qb-one-variable.woff2` | QB One variável completa (fonte original) |
