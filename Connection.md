# Audaces Connection 2027: Identidade Visual

> Fonte: Figma, arquivo **Connection 2027**, página **KV**
> https://www.figma.com/design/S9qABGwk7yIfxLNVkXpTqu/Connection-2027?node-id=6-43

> **Fonte única da verdade:** o arquivo do Figma acima é a identidade **final** do Connection. Toda peça, texto ou código deve seguir sempre o Figma. Se este MD divergir do arquivo, vale o Figma, e o MD deve ser atualizado.
> Conferido em 13/11/2026: cores principais, estrutura de frames e peças batem com o Figma.

**Evento:** Audaces Connection 2027 · 7 e 8 de janeiro · Auditório da FIESC, Florianópolis
**Conceito:** os 35 anos da Audaces em uma estética retrô-tech/synthwave. Fundo azul-marinho profundo, grid neon em perspectiva, globo wireframe, ícones em pixel art, glitch e ruído, com gradiente ciano → azul → roxo → magenta.

---

## 1. Paleta de cores

### Cores principais (swatches do arquivo: `Frame 4`)

| Cor | Hex | Uso |
|---|---|---|
| Azul-marinho noite | `#090F2B` | Fundo base de todas as peças |
| Azul elétrico | `#0064FD` | Cor principal da marca: grids, luzes, glow |
| Ciano | `#00D3FD` | Brilhos, linhas de luz, início dos gradientes |
| Magenta | `#F9039B` | Acento quente: fim dos gradientes, destaques |
| Branco gelo | `#F5F5F9` | Textos e logo em versão sólida |

### Cores de apoio
| Hex | Uso |
|---|---|
| `#7727F0` | Roxo de transição nos gradientes e nas sombras |
| `#2A52FF` | Azul intermediário |
| `#040A2F` / `#040C34` | Variações mais escuras do fundo |
| `#FFFFFF` | Textos |

### Gradientes
| Nome | Composição |
|---|---|
| **Gradiente da marca** (`Rectangle 3`) | `#00D3FD` 0% → `#0064FD` 28% → `#7727F0` 59% → `#F9039B` 100% |
| Cromado do logo CONNECTION | `#F5F5F9` → `#9EC7FF` → `#3385FF` → `#FFFFFF` → `#4D94FF` → `#F7C7EB` → `#FA73C7` → `#F91AA3` |
| Cromado dos ícones | `#F5F5F9` → `#0064FD` → `#FFFFFF` → `#F9039B` |
| "2027" magenta | `#FFC7ED` → `#FC73C7` → `#F90F9E` |
| Pastel | `#F2FAFF` → `#B2D9FF` → `#FFBFFF` / `#66A8FF` → `#FA9EDB` |
| Fundo profundo | `#063C91` → `#051A56` → `#090F2B` |
| Sunset (halo laranja e magenta, nos crachás) | radial `#FFD47A` → `#FFA647` → `#FF5E33` → `#F724AD` → `#8014D9` |

### Efeitos
- **Glow / drop shadow** em ciano `#00D3FD`, azul `#0064FD`/`#064FFD`, roxo `#7727F0`/`#7D76FE` e branco: é o brilho neon de logo, ícones e linhas.
- **Glitch**: camada de distorção presente em todas as peças.
- **Ruído** (efeito Noise preto): textura granulada aplicada por cima de tudo.

---

## 2. Tipografia

| Fonte | Estilo | Uso |
|---|---|---|
| **QB One** | ExtraBold Expanded (e Bold Expanded) | Títulos dos posters, em caixa alta larga (ex.: "O FUTURO DA MODA CONECTA AQUI"), 92–106 px em peças de 1080×1440. O "2027" gigante do poster "Em breve" usa Bold Expanded a ~206 px. |
| **Blackfully** | Italic (licença *Personal Use*) | O "2027" em brush/caligrafia do logo. ⚠️ Licença pessoal: verificar a licença comercial antes de usar em produção. |
| **Chakra Petch** | Regular, Medium, Bold, Bold Italic | Textos de apoio, datas, local, "LOADING...", "EM BREVE MAIS INFORMAÇÕES" |

Os textos de apoio combinam pesos (ex.: "Há **35 anos** transformando a **indústria da moda**").

---

## 3. Logo

Estrutura em três níveis:
1. **AUDACES**: wordmark institucional, fino, acima
2. **CONNECTION ▸**: tipografia itálica, larga e geométrica, com um triângulo de "play" no fim
3. **2027**: em brush (Blackfully Italic), sobreposto no canto inferior direito

### Versões
- **Logo sólido**: tudo em branco (`#F5F5F9`) sobre o marinho
- **Logo cromado**: CONNECTION com gradiente cromado azul → rosa, "2027" em gradiente magenta e glow neon
- **Variação logo 03**: versão horizontal compacta (1206×221)

Frames no Figma: `Logo 2`, `Logo 3`, `Logo 4`, `Variação logo 03`.

---

## 4. Ícones Pixel (35 ícones)

Pixel art em contorno, com gradiente cromado azul → branco → magenta, sobre o marinho. Componentes nomeados `Ícone Pixel/<nome>`.

| Categoria | Ícones |
|---|---|
| **Mídia / player** | Play, Pausa, Avançar, Avançar rápido, Voltar, Anterior, Pular |
| **Interface / sistema** | Cursor, Foco, Ampulheta, Carregando (barra "LOADING..."), Pasta, Lixeira, Envelope, Sinal (wi-fi), Brilho, Pixels, Xadrez |
| **Tecnologia retrô** | Monitor, Teclado, Mouse, Disquete, CD, Fita cassete, Joystick, Foguete |
| **Moda** | Manequim, Cabide, Tesoura, Carretel |
| **Emoção / marca** | Carinha (smile), Coração, Globo, Audaces, Audaces sólido |

---

## 5. Globo wireframe

Globo em linhas de grid (wireframe) neon, símbolo de conexão global. Nove variações de ângulo (frame `Globo - variações`):

- Frontal (2 versões)
- Polo em cima (forte)
- Polo embaixo
- Polo embaixo esquerda
- Inclinado direita
- Inclinado esquerda
- Lateral
- Vista de cima

---

## 6. Elementos gráficos recorrentes

Estes elementos se repetem em todas as peças:

| Elemento | Descrição |
|---|---|
| **Chão** | Grid neon em perspectiva até o horizonte (estética synthwave) |
| **Parede Grid** | Grid vertical ao fundo, formando um "cômodo" digital com o chão |
| **Grid** | Grid plano de fundo |
| **Luz** | Feixes e halos de luz azul/ciano/magenta (formas booleanas com blur) |
| **Quadrados** | Blocos de pixels soltos nos cantos (azul/ciano/roxo), como se a imagem estivesse "se pixelando" |
| **Traços** | Linhas finas de luz horizontais |
| **Moldura** | Moldura vetorial que enquadra a peça (há uma versão de vetor único sem máscara a 50%) |
| **Manequim wireframe** | Busto de costura em grid neon (ponte entre moda e tecnologia) |
| **Computador retrô** | "Computador Retrô Audaces Neon" (iMac/PC dos anos 90 em neon) |
| **Sunset** | Halo radial laranja/magenta atrás do globo, nos crachás |
| **Glitch + Ruído** | Camadas finais de distorção e granulado |

---

## 7. Peças criadas

### Posters (1080×1440)
| Peça | Título | Texto de apoio | Destaque visual |
|---|---|---|---|
| **Poster 01** | TECNOLOGIA + MODA + INOVAÇÃO | "Um evento para conectar ideias, soluções e pessoas que movem a indústria" | Imagem + traços de luz |
| **Poster 02** | DO PASSADO QUE NOS CONECTA AO **FUTURO QUE CRIAMOS** | "Tecnologia, pessoas e inovação no principal encontro da Audaces." | Globo + ícones Avançar e Carinha |
| **Poster 03** | PESSOAS, TECNOLOGIA E MODA: **A EVOLUÇÃO CONTÍNUA** | n/a | Computador retrô neon |
| **Poster 04** | **O FUTURO DA MODA CONECTA AQUI** | "Há 35 anos transformando a indústria da moda" · Box: 7 e 8 de janeiro / Auditório da FIESC, Florianópolis ▸▸▸ | Manequim wireframe |
| **Poster 05** (save the date) | **2027** · A PRÓXIMA EDIÇÃO JÁ TEM DATA | "EM BREVE MAIS INFORMAÇÕES" · barra "LOADING..." | Moldura + ícone Carinha |

### Crachás
| Peça | Formato | Composição |
|---|---|---|
| **Crachá 00** | 1080×1440 | Exemplo com nome ("FERNANDA COSTA"), imagem, globo inclinado à esquerda |
| **Crachá Participante** | 1080×1440 | Globo + sunset, logo, ícones Voltar/Avançar, área em branco para o nome escrito à mão |
| **Crachá Staff** | 1080×1440 | Mesma base do participante, com variação de ícones |
| **Crachá Participante · Horizontal** | 1920×1080 | Versão horizontal |
| **Cordão Crachá 01** | 4410×157 | Grid + logo "2027" repetido + ícones Xadrez |
| **Cordão Crachá 02** | 4410×157 | Grid, sunset, quadrados e ícones Cursor, Foguete, Brilho, Audaces, Voltar, Globo |

### Backgrounds
| Peça | Formato |
|---|---|
| **BG**, **BG 01**, **BG 03** (com logo) | 1920×1080: chão + parede grid + luzes + quadrados |
| **BG Form** (sem logo, para formulário) | 1920×1080 |
| **BG - variação 7** e frame sem nome | 1920×1080 |
| **BG - variações 3, 4, 5, 6, 8, 9** | 1080×1080 (quadrado, para redes) |
| **Miniatura LP** | 1200×630 (thumbnail / Open Graph da landing page) |

### Mockups de aplicação (imagens no arquivo)
- Ícones neon pixel em tecido marinho
- Cordão e crachá retrô-tech neon
- Bucket hat Audaces Connection 2027
- Palco da conferência
- Ecobag com bottons
- Ecobag (mockup)
- Ecobag com pins de grid pixel neon
- Boné marinho com pins pixel art
- Boné marinho com bordado Audaces
- Coleção de pins brilhantes com ícones pixel

---

## 8. Assets de apoio gerados no Magnific (projeto "Connection")

Gerados em 06–08/11/2026 como apoio à identidade:

- **Wordmark CONNECTION 3D cromado**: itálico, azul/ciano com reflexos magenta, em fundo transparente e em fundo verde (para recorte)
- **CONNECTION em brush 3D**: gradiente azul → magenta, sobre fundo preto e sobre fundo branco
- **Fundo synthwave**: grid neon em perspectiva, marinho e azul elétrico, com estrelas
- **Ambiente digital**: grid + globo wireframe ciano/magenta no canto superior direito
- **Objetos dos anos 90 em 3D neon**: câmera Cyber-shot, Tamagotchi, Walkman, disquete 3,5" e iMac G3
- **Editoriais de moda em azul**: modelo de terno azul royal com cadeira laranja; modelo com peça de alta-costura em fibras azuis

---

## 9. Resumo rápido (para briefing)

- **Fundo:** marinho `#090F2B`
- **Cores-chave:** `#0064FD` · `#00D3FD` · `#F9039B` · `#F5F5F9`
- **Gradiente da marca:** ciano → azul → roxo → magenta
- **Fontes:** QB One Expanded (títulos) · Chakra Petch (apoio) · Blackfully Italic ("2027")
- **Símbolos:** globo wireframe, 35 ícones pixel, manequim wireframe, computador retrô
- **Texturas:** grid em perspectiva, quadrados de pixel, glow neon, glitch, ruído
- **Tom:** retrô-futurista, anos 80/90 digitais, moda + tecnologia + 35 anos de Audaces

---

## 10. Landing page · Bloco 03 (Programação)

Bloco HTML do RD Station, autocontido (fonte QB One embutida em base64). Figma: node `663:9540` (Landing page › Frame 26 › Frame 29).

**Estado atual (17/11/2026):** a programação ainda não está definida. A LP usa a versão **"Em breve"**, em [`lp/bloco-03-em-breve.html`](lp/bloco-03-em-breve.html): mesmo visual do bloco, com duas colunas, Dia 01 (07 de janeiro) e Dia 02 (08 de janeiro), cada uma com "EM BREVE", "EM BREVE MAIS INFORMAÇÕES" e barra "LOADING..." no lugar da agenda. O card final ("Nos vemos no Connection 2027!") e o botão foram mantidos.

**Quando a agenda sair:** cole no RD Station o HTML original abaixo e edite os horários. Cada atividade é um `<li class="cx-item">`, os intervalos usam `cx-item cx-item--pausa` e a descrição opcional vai em `<span class="cx-item__desc">`.

### 10.1 HTML original (com a programação)

````html
<!-- =========================================================
     CONNECTION 2027 · Bloco 03 — Programação (Dia 01 e Dia 02) + chamada final
     Figma: node 663:9540 (Landing page › Frame 26 › Frame 29)
     Colar como bloco HTML no RD Station. Autocontido.
     Para editar a agenda: cada atividade é um <li class="cx-item">.
     Intervalos (almoço, coffee break) usam  class="cx-item cx-item--pausa".
     Descrição opcional: <span class="cx-item__desc">texto</span>.
     ========================================================= -->
<link rel="preconnect" href="https://fonts.googleapis.com">
<link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
<link href="https://fonts.googleapis.com/css2?family=Chakra+Petch:wght@400;500;600;700&display=swap" rel="stylesheet">

<style>
  html,body{overflow-x:hidden}
  .cx-hero,.cx-prog{margin-top:0 !important; margin-bottom:0 !important}
  @font-face{font-family:'CX QB One'; font-weight:800; font-style:normal; font-display:swap;
    src:url(data:font/woff2;base64,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) format('woff2')}
  .cx-prog{
    --cx-navy:#090F2B; --cx-azul:#0064FD; --cx-ciano:#00D3FD; --cx-roxo:#7727F0; --cx-magenta:#F9039B; --cx-branco:#F5F5F9;
    --cx-ease:cubic-bezier(.2,.8,.2,1); --cx-fonte:'Chakra Petch',sans-serif;
    position:relative; overflow:hidden; isolation:isolate; box-sizing:border-box;
    width:100vw; max-width:100vw; margin-left:calc(50% - 50vw); margin-right:calc(50% - 50vw);
    padding:32px 24px 120px; background:var(--cx-navy); color:var(--cx-branco); font-family:var(--cx-fonte);
    -webkit-font-smoothing:antialiased;
  }
  .cx-prog *,.cx-prog *::before,.cx-prog *::after{box-sizing:border-box}

  /* Fundo */
  .cx-prog__brilhos{position:absolute; inset:0; z-index:-2; pointer-events:none;
    -webkit-mask-image:linear-gradient(transparent 0%,#000 14%,#000 82%,transparent 100%); mask-image:linear-gradient(transparent 0%,#000 14%,#000 82%,transparent 100%)}
  .cx-prog__brilhos span{position:absolute; border-radius:50%; filter:blur(10px); animation:cx-p-respira 10s ease-in-out infinite alternate}
  .cx-prog__brilhos .b1{left:-38%; top:5%; width:85%; height:90%; filter:blur(60px); background:radial-gradient(closest-side,rgba(0,100,253,.4),rgba(0,100,253,.14) 45%,rgba(0,100,253,.04) 72%,transparent)}
  .cx-prog__brilhos .b2{right:-35%; bottom:-15%; width:85%; height:95%; filter:blur(60px); background:radial-gradient(closest-side,rgba(249,3,155,.2),rgba(119,39,240,.14) 40%,rgba(119,39,240,.05) 70%,transparent); animation-delay:-4s}
  .cx-prog__ruido{position:absolute; inset:0; z-index:3; pointer-events:none; opacity:.07; mix-blend-mode:overlay;
    background-image:url("data:image/svg+xml,%3Csvg xmlns='http://www.w3.org/2000/svg' width='160' height='160'%3E%3Cfilter id='n'%3E%3CfeTurbulence type='fractalNoise' baseFrequency='.9' numOctaves='2' stitchTiles='stitch'/%3E%3C/filter%3E%3Crect width='100%25' height='100%25' filter='url(%23n)'/%3E%3C/svg%3E")}

  /* Título */
  .cx-prog__titulo{margin:0 0 64px; text-align:center; font:800 48px/1.02 'CX QB One',var(--cx-fonte); font-synthesis:none; text-transform:uppercase;
    filter:drop-shadow(0 0 18px rgba(255,255,255,.3))}
  .cx-prog__titulo span{display:inline-block; transform:skewX(-11deg);
    background:linear-gradient(180deg,#fff 0%,#fff 30%,#c9ccd1 46%,#fff 54%,#fff 62%,#8b8e94 72%,#fff 90%);
    -webkit-background-clip:text; background-clip:text; color:transparent}

  /* Cards */
  .cx-prog__dias{position:relative; z-index:1; display:grid; grid-template-columns:1fr 1fr; gap:32px; max-width:1090px; margin:0 auto}
  .cx-dia{position:relative; padding:44px; border-radius:23px; background:rgba(255,255,255,.08);
    box-shadow:0 0 18px rgba(119,39,240,.6);
    transition:transform .45s var(--cx-ease),box-shadow .45s var(--cx-ease),background .45s var(--cx-ease)}
  .cx-dia::before{ /* borda em gradiente */
    content:""; position:absolute; inset:0; border-radius:inherit; padding:1.5px; pointer-events:none;
    background:linear-gradient(var(--cx-ang,150deg),#F5F5F9 0%,#0064FD 40%,#fff 72%,#F9039B 100%);
    -webkit-mask:linear-gradient(#000 0 0) content-box,linear-gradient(#000 0 0); -webkit-mask-composite:xor;
            mask:linear-gradient(#000 0 0) content-box exclude,linear-gradient(#000 0 0)}
  .cx-dia--2{--cx-ang:330deg}
  .cx-dia:hover{transform:translateY(-4px); background:rgba(255,255,255,.1); box-shadow:0 0 22px rgba(119,39,240,.7),0 14px 44px rgba(0,211,253,.22)}
  .cx-dia--2:hover{box-shadow:0 0 22px rgba(119,39,240,.7),0 14px 44px rgba(249,3,155,.22)}

  .cx-dia__data{display:flex; align-items:center; gap:10px; margin:0 0 12px; color:var(--cx-ciano);
    font:500 15px/1.2 var(--cx-fonte); letter-spacing:.16em; text-transform:uppercase}
  .cx-dia__data::before{content:""; width:8px; height:8px; flex-shrink:0; background:var(--cx-ciano); box-shadow:0 0 10px rgba(0,211,253,.8)}
  .cx-dia__nome{margin:0; font:700 48px/1 var(--cx-fonte); text-transform:uppercase;
    background:linear-gradient(180deg,#fff 0%,#fff 32%,#c9ccd1 46%,#fff 56%,#fff 64%,#9a9da3 74%,#fff 92%);
    -webkit-background-clip:text; background-clip:text; color:transparent; filter:drop-shadow(0 0 18px rgba(255,255,255,.3))}
  .cx-dia__divisor{height:1px; margin:28px 0 10px; background:linear-gradient(90deg,rgba(0,211,253,.9),rgba(0,211,253,0))}

  .cx-agenda{list-style:none; margin:0; padding:0}
  .cx-item{position:relative; display:grid; grid-template-columns:122px 2px 1fr; gap:16px; align-items:stretch; padding:18px 0;
    border-bottom:1px solid rgba(255,255,255,.1); transition:background .3s var(--cx-ease)}
  .cx-item:last-child{border-bottom:0}
  .cx-item::before{content:""; position:absolute; inset:0 -12px; border-radius:10px; pointer-events:none; opacity:0;
    background:linear-gradient(90deg,rgba(0,211,253,.10),rgba(119,39,240,.06) 60%,transparent); transition:opacity .3s var(--cx-ease)}
  .cx-item__hora{white-space:nowrap; font:600 20px/1 var(--cx-fonte); color:var(--cx-branco); text-shadow:0 0 30px rgba(255,255,255,.3); padding-top:2px; transition:color .3s}
  .cx-item__traco{width:2px; border-radius:1px; background:linear-gradient(180deg,#00D3FD,#0064FD 28%,#7727F0 59%,#F9039B);
    box-shadow:0 0 8px rgba(0,211,253,.6); transition:box-shadow .3s}
  .cx-item__conteudo{display:flex; flex-direction:column; gap:4px; transition:transform .3s var(--cx-ease)}
  .cx-item__titulo{font:600 20px/1.2 var(--cx-fonte); color:#fff}
  .cx-item__desc{font:400 16px/1.3 var(--cx-fonte); color:rgba(245,245,249,.6)}
  .cx-item--pausa .cx-item__hora,.cx-item--pausa .cx-item__titulo{opacity:.55}
  .cx-item:hover::before{opacity:1}
  .cx-item:hover .cx-item__hora{color:var(--cx-ciano)}
  .cx-item:hover .cx-item__traco{box-shadow:0 0 14px rgba(0,211,253,1),0 0 26px rgba(249,3,155,.5)}
  .cx-item:hover .cx-item__conteudo{transform:translateX(4px)}


  /* chão em grade (perspectiva synthwave, animado) */
  .cx-prog__parede{
    position:absolute; bottom:0; height:1000px; width:42%; z-index:-1; pointer-events:none;
    background-image:
      linear-gradient(rgba(0,100,253,.9) 1.5px,transparent 1.5px),
      linear-gradient(90deg,rgba(0,100,253,.9) 1.5px,transparent 1.5px);
    background-size:62px 62px; background-position:0 100%;
    opacity:.6;
    -webkit-mask-image:radial-gradient(ellipse 100% 110% at var(--cx-mx) 100%,#000 22%,rgba(0,0,0,.45) 42%,transparent 62%),linear-gradient(0deg,#000 0%,#000 60%,transparent 98%);
    -webkit-mask-composite:source-in;
            mask-image:radial-gradient(ellipse 100% 110% at var(--cx-mx) 100%,#000 22%,rgba(0,0,0,.45) 42%,transparent 62%),linear-gradient(0deg,#000 0%,#000 60%,transparent 98%);
            mask-composite:intersect;
    animation:cx-grade-sobe 8s linear infinite}
  .cx-prog__parede--esq{left:0; --cx-mx:0%}
  .cx-prog__parede--dir{right:0; --cx-mx:100%}
  @keyframes cx-grade-sobe-m{from{background-position:0 100%}to{background-position:0 calc(100% - 36px)}}
  @keyframes cx-grade-sobe{from{background-position:0 100%}to{background-position:0 calc(100% - 62px)}}

  /* card final */
  .cx-prog__final{position:relative; z-index:1; max-width:1090px; margin:78px auto 0; display:flex; align-items:center; justify-content:space-between; gap:28px;
    padding:44px 44px 44px 66px; border-radius:23px; background:rgba(255,255,255,.08);
    -webkit-backdrop-filter:blur(6px); backdrop-filter:blur(6px); box-shadow:0 0 18px rgba(119,39,240,.6);
    transition:transform .45s var(--cx-ease),box-shadow .45s var(--cx-ease),background .45s var(--cx-ease)}
  .cx-prog__final::before{content:""; position:absolute; inset:0; border-radius:inherit; padding:1.5px; pointer-events:none;
    background:linear-gradient(330deg,#F5F5F9 0%,#0064FD 40%,#fff 72%,#F9039B 100%);
    -webkit-mask:linear-gradient(#000 0 0) content-box,linear-gradient(#000 0 0); -webkit-mask-composite:xor;
            mask:linear-gradient(#000 0 0) content-box exclude,linear-gradient(#000 0 0)}
  .cx-prog__final:hover{transform:translateY(-4px); background:rgba(255,255,255,.1);
    box-shadow:0 0 22px rgba(119,39,240,.7),0 14px 44px rgba(249,3,155,.22),0 6px 30px rgba(0,211,253,.14)}
  .cx-prog.cx-js .cx-prog__final.is-visivel:hover{transform:translateY(-4px)}
  .cx-prog__final-titulo{margin:0; font:800 38px/1.1 'CX QB One',var(--cx-fonte); font-synthesis:none; text-transform:uppercase;
    filter:drop-shadow(0 0 18px rgba(255,255,255,.3))}
  .cx-prog__final-titulo span{display:inline-block; transform:skewX(-11deg);
    background:linear-gradient(180deg,#fff 0%,#fff 30%,#c9ccd1 46%,#fff 54%,#fff 62%,#8b8e94 72%,#fff 90%);
    -webkit-background-clip:text; background-clip:text; color:transparent}
  .cx-prog .cx-cta{position:relative; flex-shrink:0; display:inline-flex; align-items:center; gap:16px; overflow:hidden;
    padding:20px 24px 20px 32px; border-radius:8px; text-decoration:none; color:#fff;
    font:600 16px/1 var(--cx-fonte); letter-spacing:.08em; text-transform:uppercase;
    background:linear-gradient(100deg,#2E7BFF 0%,#0064FD 18%,#643DD5 58%,#F9039B 100%,#643DD5 140%,#0064FD 180%);
    background-size:200% 100%; background-position:0% 0;
    transition:background-position .6s var(--cx-ease),box-shadow .3s var(--cx-ease),transform .25s var(--cx-ease)}
  .cx-prog .cx-cta::before{content:""; position:absolute; inset:0; pointer-events:none;
    background:linear-gradient(100deg,transparent 35%,rgba(255,255,255,.16) 50%,transparent 65%);
    transform:translateX(-120%); animation:cx-p-reflexo 4.5s var(--cx-ease) infinite 2s}
  .cx-prog .cx-cta svg{width:28px; height:28px; flex-shrink:0; filter:drop-shadow(0 0 2px rgba(0,211,253,.6))}
  .cx-prog .cx-cta:hover,.cx-prog .cx-cta:focus-visible{background-position:100% 0; box-shadow:0 0 18px rgba(0,100,253,.35),0 0 40px rgba(249,3,155,.18)}
  .cx-prog .cx-cta:hover .s1,.cx-prog .cx-cta:focus-visible .s1{animation:cx-p-seta .9s steps(1) infinite}
  .cx-prog .cx-cta:hover .s2,.cx-prog .cx-cta:focus-visible .s2{animation:cx-p-seta .9s steps(1) infinite .3s}
  .cx-prog .cx-cta:hover .s3,.cx-prog .cx-cta:focus-visible .s3{animation:cx-p-seta .9s steps(1) infinite .6s}
  .cx-prog .cx-cta:active{transform:scale(.97)}
  .cx-prog .cx-cta:focus-visible{outline:3px solid #00D3FD; outline-offset:4px}
  @keyframes cx-p-seta{0%{opacity:1}33%{opacity:.25}}
  @keyframes cx-p-reflexo{0%,55%{transform:translateX(-120%)}100%{transform:translateX(120%)}}

  /* Revelação ao rolar (só quando o JS roda) */
  .cx-prog.cx-js [data-cx-revela]{opacity:0; transform:translateY(28px); transition:opacity .7s var(--cx-ease),transform .7s var(--cx-ease); transition-delay:var(--d,0ms)}
  .cx-prog.cx-js [data-cx-revela].is-visivel{opacity:1; transform:none}
  .cx-prog.cx-js .cx-dia.is-visivel{transform:none}
  .cx-prog.cx-js .cx-dia.is-visivel:hover{transform:translateY(-4px)}

  @keyframes cx-p-respira{from{opacity:.7; transform:scale(1)}to{opacity:1; transform:scale(1.08)}}

  /* Tablet */
  @media (max-width:1100px){
    .cx-prog__final{padding:36px}
    .cx-prog__final-titulo{font-size:clamp(24px,3vw,34px)}
    .cx-dia{padding:32px}
    .cx-item{grid-template-columns:104px 2px 1fr; gap:14px}
    .cx-item__hora,.cx-item__titulo{font-size:18px}
  }
  /* Mobile */
  @media (max-width:767px){
    .cx-prog{padding-bottom:72px !important}
    .cx-prog__parede{width:45%; height:460px; opacity:.35; background-size:36px 36px; animation-name:cx-grade-sobe-m; animation-duration:4.6s}
    .cx-prog__final{flex-direction:column; text-align:center; gap:24px; margin-top:40px; padding:32px 18px; border-radius:18px}
    .cx-prog__final-titulo{font-size:clamp(20px,calc((100vw - 104px)/11.5),28px)}
    .cx-prog__final-titulo br{display:none}
    .cx-prog .cx-cta{width:100%; justify-content:center; min-height:56px; padding:18px 14px; gap:10px; font-size:clamp(12px,3.4vw,15px); letter-spacing:.05em; white-space:nowrap}
    .cx-prog .cx-cta svg{width:22px; height:22px}
    .cx-prog{padding:24px 32px 80px !important}
    .cx-prog__titulo{font-size:clamp(24px,calc((100vw - 64px)/9.6),36px); margin-bottom:36px}
    .cx-prog__dias{grid-template-columns:1fr; gap:24px}
    .cx-dia{padding:28px 20px; border-radius:18px}
    .cx-dia__data{font-size:12px; letter-spacing:.14em}
    .cx-dia__nome{font-size:36px}
    .cx-dia__divisor{margin:22px 0 6px}
    .cx-item{grid-template-columns:auto 2px 1fr; gap:12px; padding:14px 0}
    .cx-item__hora{font-size:14px; min-width:98px}
    .cx-item__titulo{font-size:16px}
    .cx-item__desc{font-size:13px}
    .cx-item::before{inset:0 -8px}
  }
  @media (prefers-reduced-motion:reduce){
    .cx-prog *,.cx-prog *::before{animation:none!important; transition:none!important}
    .cx-prog.cx-js [data-cx-revela]{opacity:1; transform:none}
  }
</style>

<section class="cx-prog" id="cx-prog" aria-labelledby="cx-prog-titulo">
  <div class="cx-prog__brilhos" aria-hidden="true"><span class="b1"></span><span class="b2"></span></div>
  <div class="cx-prog__parede cx-prog__parede--esq" aria-hidden="true"></div>
  <div class="cx-prog__parede cx-prog__parede--dir" aria-hidden="true"></div>
  <div class="cx-prog__ruido" aria-hidden="true"></div>

  <h2 class="cx-prog__titulo" id="cx-prog-titulo" data-cx-revela><span>Programação</span></h2>

  <div class="cx-prog__dias">
    <article class="cx-dia cx-dia--1" data-cx-revela style="--d:100ms" aria-labelledby="cx-dia1">
      <p class="cx-dia__data">07 de janeiro · quinta-feira</p>
      <h3 class="cx-dia__nome" id="cx-dia1">Dia 01</h3>
      <div class="cx-dia__divisor" aria-hidden="true"></div>
      <ol class="cx-agenda">
        <li class="cx-item"><span class="cx-item__hora">8:00 – 9:00</span><span class="cx-item__traco" aria-hidden="true"></span><span class="cx-item__conteudo"><span class="cx-item__titulo">Credenciamento e boas-vindas</span></span></li>
        <li class="cx-item"><span class="cx-item__hora">9:00 – 9:30</span><span class="cx-item__traco" aria-hidden="true"></span><span class="cx-item__conteudo"><span class="cx-item__titulo">Abertura</span></span></li>
        <li class="cx-item"><span class="cx-item__hora">9:30 – 10:30</span><span class="cx-item__traco" aria-hidden="true"></span><span class="cx-item__conteudo"><span class="cx-item__titulo">Resultados 2025 Brasil e LATAM</span></span></li>
        <li class="cx-item"><span class="cx-item__hora">10:30 – 11:30</span><span class="cx-item__traco" aria-hidden="true"></span><span class="cx-item__conteudo"><span class="cx-item__titulo">Case de sucesso LATAM – Kiricocho</span></span></li>
        <li class="cx-item"><span class="cx-item__hora">11:30 – 12:00</span><span class="cx-item__traco" aria-hidden="true"></span><span class="cx-item__conteudo"><span class="cx-item__titulo">Destaque 2025: Vendedor que inspira – LATAM</span></span></li>
        <li class="cx-item cx-item--pausa"><span class="cx-item__hora">12:00 – 13:30</span><span class="cx-item__traco" aria-hidden="true"></span><span class="cx-item__conteudo"><span class="cx-item__titulo">Almoço</span></span></li>
        <li class="cx-item"><span class="cx-item__hora">13:30 – 14:00</span><span class="cx-item__traco" aria-hidden="true"></span><span class="cx-item__conteudo"><span class="cx-item__titulo">Dinâmica</span></span></li>
        <li class="cx-item"><span class="cx-item__hora">14:00 – 15:00</span><span class="cx-item__traco" aria-hidden="true"></span><span class="cx-item__conteudo"><span class="cx-item__titulo">Case de sucesso – Kímika</span></span></li>
        <li class="cx-item"><span class="cx-item__hora">15:00 – 15:30</span><span class="cx-item__traco" aria-hidden="true"></span><span class="cx-item__conteudo"><span class="cx-item__titulo">Serviços – Audaces Attiva</span></span></li>
        <li class="cx-item cx-item--pausa"><span class="cx-item__hora">15:30 – 16:00</span><span class="cx-item__traco" aria-hidden="true"></span><span class="cx-item__conteudo"><span class="cx-item__titulo">Coffee break</span></span></li>
        <li class="cx-item"><span class="cx-item__hora">16:00 – 17:00</span><span class="cx-item__traco" aria-hidden="true"></span><span class="cx-item__conteudo"><span class="cx-item__titulo">Customer Centric</span></span></li>
        <li class="cx-item"><span class="cx-item__hora">17:00 – 17:30</span><span class="cx-item__traco" aria-hidden="true"></span><span class="cx-item__conteudo"><span class="cx-item__titulo">Destaque 2025: Vendedor que inspira – Brasil</span></span></li>
        <li class="cx-item"><span class="cx-item__hora">17:30 – 18:30</span><span class="cx-item__traco" aria-hidden="true"></span><span class="cx-item__conteudo"><span class="cx-item__titulo">Palestra surpresa</span></span></li>
      </ol>
    </article>

    <article class="cx-dia cx-dia--2" data-cx-revela style="--d:250ms" aria-labelledby="cx-dia2">
      <p class="cx-dia__data">08 de janeiro · sexta-feira</p>
      <h3 class="cx-dia__nome" id="cx-dia2">Dia 02</h3>
      <div class="cx-dia__divisor" aria-hidden="true"></div>
      <ol class="cx-agenda">
        <li class="cx-item"><span class="cx-item__hora">8:00 – 8:30</span><span class="cx-item__traco" aria-hidden="true"></span><span class="cx-item__conteudo"><span class="cx-item__titulo">Boas-vindas</span></span></li>
        <li class="cx-item"><span class="cx-item__hora">8:30 – 10:00</span><span class="cx-item__traco" aria-hidden="true"></span><span class="cx-item__conteudo"><span class="cx-item__titulo">Movimentos estratégicos e metas 2026</span></span></li>
        <li class="cx-item"><span class="cx-item__hora">10:00 – 11:30</span><span class="cx-item__traco" aria-hidden="true"></span><span class="cx-item__conteudo"><span class="cx-item__titulo">Novidades de produto – SW</span></span></li>
        <li class="cx-item"><span class="cx-item__hora">11:30 – 12:00</span><span class="cx-item__traco" aria-hidden="true"></span><span class="cx-item__conteudo"><span class="cx-item__titulo">Novidades de hardware</span></span></li>
        <li class="cx-item cx-item--pausa"><span class="cx-item__hora">12:00 – 13:30</span><span class="cx-item__traco" aria-hidden="true"></span><span class="cx-item__conteudo"><span class="cx-item__titulo">Almoço</span></span></li>
        <li class="cx-item"><span class="cx-item__hora">13:30 – 14:30</span><span class="cx-item__traco" aria-hidden="true"></span><span class="cx-item__conteudo"><span class="cx-item__titulo">Estratégias de marketing para vencer</span></span></li>
        <li class="cx-item"><span class="cx-item__hora">14:30 – 15:30</span><span class="cx-item__traco" aria-hidden="true"></span><span class="cx-item__conteudo"><span class="cx-item__titulo">Palestra – Marcelo Caetano</span></span></li>
        <li class="cx-item cx-item--pausa"><span class="cx-item__hora">15:30 – 16:00</span><span class="cx-item__traco" aria-hidden="true"></span><span class="cx-item__conteudo"><span class="cx-item__titulo">Coffee break</span></span></li>
        <li class="cx-item"><span class="cx-item__hora">16:00 – 17:30</span><span class="cx-item__traco" aria-hidden="true"></span><span class="cx-item__conteudo"><span class="cx-item__titulo">Premiação</span><span class="cx-item__desc">Foto oficial · Mensagem final do CEO</span></span></li>
        <li class="cx-item cx-item--pausa"><span class="cx-item__hora">17:30</span><span class="cx-item__traco" aria-hidden="true"></span><span class="cx-item__conteudo"><span class="cx-item__titulo">Deslocamento para sede</span></span></li>
      </ol>
    </article>
  </div>

  <div class="cx-prog__final" data-cx-revela style="--d:150ms">
    <h2 class="cx-prog__final-titulo"><span>Nos vemos no <br>Connection 2027!</span></h2>
    <a class="cx-cta" href="https://forms.cloud.microsoft/pages/responsepage.aspx?id=Pea-wGELFkKHeCdIUzWYFdltyA4ArOtFvHacF0teTvdUMTg2WUUyQ0ZYVUI1Q1pPU0lQVzcxWUs3VS4u&amp;route=shorturl" target="_blank" rel="noopener">
      Entrar no grupo do evento
      <svg viewBox="0 0 28 28" aria-hidden="true" fill="#fff">
        <path class="s1" d="M5.1 21.3H3.5v-1.6h1.6zM6.7 19.7H5.1v-1.6h1.6zM8.3 18H6.7v-1.6h1.6zM10 16.4H8.3v-1.6H10zM11.6 14.8H10v-1.6h1.6zM10 13.2H8.3v-1.6H10zM8.3 11.6H6.7V9.95h1.6zM6.7 9.95H5.1V8.3h1.6zM5.1 8.3H3.5V6.7h1.6z"/>
        <path class="s2" d="M11.6 21.3H10v-1.6h1.6zM13.2 19.7h-1.6v-1.6h1.6zM14.8 18h-1.6v-1.6h1.6zM16.4 16.4h-1.6v-1.6h1.6zM18 14.8h-1.6v-1.6H18zM16.4 13.2h-1.6v-1.6h1.6zM14.8 11.6h-1.6V9.95h1.6zM13.2 9.95h-1.6V8.3h1.6zM11.6 8.3H10V6.7h1.6z"/>
        <path class="s3" d="M18 21.3h-1.6v-1.6H18zM19.7 19.7H18v-1.6h1.7zM21.3 18h-1.6v-1.6h1.6zM22.9 16.4h-1.6v-1.6h1.6zM24.5 14.8h-1.6v-1.6h1.6zM22.9 13.2h-1.6v-1.6h1.6zM21.3 11.6h-1.6V9.95h1.6zM19.7 9.95H18V8.3h1.7zM18 8.3h-1.6V6.7H18z"/>
      </svg>
    </a>
  </div>
</section>

<script>
(function(){
  var sec = document.getElementById('cx-prog');
  if(!sec || !('IntersectionObserver' in window)) return;
  sec.classList.add('cx-js');
  // linhas da agenda entram em cascata
  sec.querySelectorAll('.cx-agenda').forEach(function(ol){
    ol.querySelectorAll('.cx-item').forEach(function(li, i){
      li.setAttribute('data-cx-revela',''); li.style.setProperty('--d', (200 + i*45) + 'ms');
    });
  });
  var io = new IntersectionObserver(function(entries){
    entries.forEach(function(e){ if(e.isIntersecting){ e.target.classList.add('is-visivel'); io.unobserve(e.target); } });
  }, {threshold:.15, rootMargin:'0px 0px -40px 0px'});
  sec.querySelectorAll('[data-cx-revela]').forEach(function(el){ io.observe(el); });
})();
</script>
````

---

## 11. Landing page · Bloco 01 (Faixa data)

Letreiro animado com data e local, em gradiente azul → roxo → magenta. Bloco HTML do RD Station, autocontido. Figma: node `648:18631` (Landing page › Frame 26).

Ajustes rápidos nas variáveis CSS de `.cx-faixa`: `--cx-velocidade` (tempo de uma volta, maior = mais lento), `--cx-altura`, `--cx-fonte`, `--cx-gap`. Para mudar o texto, edite os `<p class="cx-faixa__item">` nos dois grupos (o segundo é a cópia que fecha o loop sem emenda).

````html
<!-- =========================================================
     CONNECTION 2027 · Bloco 01 — Faixa data (letreiro animado)
     Figma: node 648:18631 (Landing page › Frame 26)
     Colar como bloco HTML no RD Station. Autocontido.
     ========================================================= -->
<link rel="preconnect" href="https://fonts.googleapis.com">
<link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
<link href="https://fonts.googleapis.com/css2?family=Chakra+Petch:wght@700&display=swap" rel="stylesheet">

<style>
  html,body{overflow-x:hidden}
  .cx-faixa{
    --cx-branco:#F5F5F9; --cx-azul:#0064FD; --cx-roxo:#7727F0; --cx-magenta:#F9039B; --cx-ciano:#00D3FD;
    --cx-altura:48px; --cx-fonte:16px; --cx-gap:32px; --cx-brilho:24px;
    --cx-velocidade:45s;               /* tempo de uma volta completa: maior = mais lento */
    position:relative; box-sizing:border-box; width:100vw; max-width:100vw; margin-left:calc(50% - 50vw); margin-right:calc(50% - 50vw);
    height:var(--cx-altura); overflow:hidden; z-index:0; margin-bottom:0;
    box-shadow:0 6px 0 0 #090F2B; /* cobre qualquer espaço branco entre a faixa e o bloco de baixo */
    display:flex; align-items:center;
    background:linear-gradient(90deg,var(--cx-azul) 0%,var(--cx-roxo) 25%,var(--cx-magenta) 50%,var(--cx-roxo) 75%,var(--cx-azul) 100%);
    background-size:200% 100%;
    animation:cx-fluxo 12s ease-in-out infinite alternate;
    -webkit-font-smoothing:antialiased;
  }
  /* reflexo de luz que atravessa a faixa */
  .cx-faixa::after{
    content:""; position:absolute; inset:0; pointer-events:none;
    background:linear-gradient(100deg,transparent 35%,rgba(255,255,255,.18) 50%,transparent 65%);
    transform:translateX(-100%);
    animation:cx-reflexo 7s ease-in-out infinite;
  }
  .cx-faixa__trilho{
    display:flex; flex-shrink:0; width:max-content;
    animation:cx-letreiro var(--cx-velocidade) linear infinite; will-change:transform; backface-visibility:hidden;
  }
  @media (hover:hover) and (pointer:fine){ .cx-faixa:hover .cx-faixa__trilho{animation-play-state:paused} }
  .cx-faixa__grupo{display:flex; align-items:center; gap:var(--cx-gap); padding-right:var(--cx-gap); flex-shrink:0}
  .cx-faixa__item{
    margin:0; white-space:nowrap; color:var(--cx-branco);
    font:700 var(--cx-fonte)/1 'Chakra Petch',sans-serif; letter-spacing:.08em; text-transform:uppercase;
  }
  .cx-faixa__brilho{
    width:var(--cx-brilho); height:var(--cx-brilho); flex-shrink:0; color:#fff;
    filter:drop-shadow(0 0 2.5px rgba(0,211,253,.5));
    animation:cx-pisca 2.4s ease-in-out infinite;
  }
  .cx-faixa__brilho:nth-of-type(3n+2){animation-delay:-.8s}
  .cx-faixa__brilho:nth-of-type(3n){animation-delay:-1.6s}

  @keyframes cx-letreiro{from{transform:translate3d(0,0,0)}to{transform:translate3d(-50%,0,0)}}
  @keyframes cx-fluxo{from{background-position:0% 0}to{background-position:100% 0}}
  @keyframes cx-reflexo{0%,60%{transform:translateX(-100%)}100%{transform:translateX(100%)}}
  @keyframes cx-pisca{
    0%,100%{transform:scale(.85); opacity:.75; filter:drop-shadow(0 0 2px rgba(0,211,253,.4))}
    50%{transform:scale(1.1); opacity:1; filter:drop-shadow(0 0 8px rgba(0,211,253,.95)) drop-shadow(0 0 2px #fff)}
  }

  /* Mobile */
  @media (max-width:767px){
    .cx-faixa{--cx-altura:38px; --cx-fonte:12px; --cx-gap:18px; --cx-brilho:16px; --cx-velocidade:32s}
  }

  /* Acessibilidade: quem pede menos movimento vê a faixa parada */
  @media (prefers-reduced-motion:reduce){
    .cx-faixa,.cx-faixa::after,.cx-faixa__trilho,.cx-faixa__brilho{animation:none}
    .cx-faixa::after{display:none}
  }
</style>

<div class="cx-faixa" role="region" aria-label="Data e local do evento">
  <svg width="0" height="0" style="position:absolute" aria-hidden="true">
    <symbol id="cx-brilho" viewBox="0 0 34 34">
      <path fill="currentColor" d="M16 0h2v2h-2zM16 2h2v2h-2zM16 4h2v2h-2zM14 7h2v2h-2zM19 7h2v2h-2zM14 9h2v2h-2zM19 9h2v2h-2zM12 11h2v2h-2zM21 11h2v2h-2zM7 14h2v2h-2zM9 14h2v2h-2zM23 14h2v2h-2zM25 14h2v2h-2zM0 16h2v2h-2zM2 16h2v2h-2zM5 16h2v2h-2zM28 16h2v2h-2zM30 16h2v2h-2zM32 16h2v2h-2zM7 18h2v2h-2zM9 18h2v2h-2zM23 18h2v2h-2zM25 18h2v2h-2zM12 20h2v2h-2zM21 20h2v2h-2zM14 23h2v2h-2zM19 23h2v2h-2zM14 25h2v2h-2zM19 25h2v2h-2zM16 27h2v2h-2zM16 30h2v2h-2zM16 32h2v2h-2z"/>
    </symbol>
  </svg>

  <div class="cx-faixa__trilho">
    <!-- Grupo lido por leitores de tela -->
    <div class="cx-faixa__grupo">
      <p class="cx-faixa__item">07 e 08 de janeiro de 2027</p>
      <svg class="cx-faixa__brilho" aria-hidden="true"><use href="#cx-brilho"/></svg>
      <p class="cx-faixa__item">Auditório da FIESC, Florianópolis</p>
      <svg class="cx-faixa__brilho" aria-hidden="true"><use href="#cx-brilho"/></svg>
      <p class="cx-faixa__item" aria-hidden="true">07 e 08 de janeiro de 2027</p>
      <svg class="cx-faixa__brilho" aria-hidden="true"><use href="#cx-brilho"/></svg>
      <p class="cx-faixa__item" aria-hidden="true">Auditório da FIESC, Florianópolis</p>
      <svg class="cx-faixa__brilho" aria-hidden="true"><use href="#cx-brilho"/></svg>
      <p class="cx-faixa__item" aria-hidden="true">07 e 08 de janeiro de 2027</p>
      <svg class="cx-faixa__brilho" aria-hidden="true"><use href="#cx-brilho"/></svg>
      <p class="cx-faixa__item" aria-hidden="true">Auditório da FIESC, Florianópolis</p>
      <svg class="cx-faixa__brilho" aria-hidden="true"><use href="#cx-brilho"/></svg>
    </div>
    <!-- Cópia idêntica para o loop sem emenda -->
    <div class="cx-faixa__grupo" aria-hidden="true">
      <p class="cx-faixa__item">07 e 08 de janeiro de 2027</p>
      <svg class="cx-faixa__brilho"><use href="#cx-brilho"/></svg>
      <p class="cx-faixa__item">Auditório da FIESC, Florianópolis</p>
      <svg class="cx-faixa__brilho"><use href="#cx-brilho"/></svg>
      <p class="cx-faixa__item">07 e 08 de janeiro de 2027</p>
      <svg class="cx-faixa__brilho"><use href="#cx-brilho"/></svg>
      <p class="cx-faixa__item">Auditório da FIESC, Florianópolis</p>
      <svg class="cx-faixa__brilho"><use href="#cx-brilho"/></svg>
      <p class="cx-faixa__item">07 e 08 de janeiro de 2027</p>
      <svg class="cx-faixa__brilho"><use href="#cx-brilho"/></svg>
      <p class="cx-faixa__item">Auditório da FIESC, Florianópolis</p>
      <svg class="cx-faixa__brilho"><use href="#cx-brilho"/></svg>
    </div>
  </div>
</div>
````

---

## 12. Landing page · Bloco 02 (Hero)

Hero com logo, chamada, botão "Entrar no grupo do evento", ícones pixel (Audaces e Carinha), cronômetro regressivo até 07/01/2027 às 8h (`data-alvo` no `#cx-crono`) e globo wireframe animado em canvas. Bloco HTML do RD Station. Figma: node `642:3614` (Landing page › Frame 26 › 01 · Hero). O cronômetro e o globo usam JavaScript: o editor do RD não executa scripts, então confira na visualização ou na página publicada.

> ⚠️ **Logo incompleto neste arquivo.** No HTML original o logo é uma imagem WebP embutida em base64 (cerca de 40 mil caracteres). Para não correr o risco de corromper o código ao transcrevê-lo, o `src` do `<img class="cx-hero__logo">` está como `LOGO_WEBP_BASE64_REMOVIDO`. Antes de usar este HTML, substitua esse texto pelo logo (data URI `data:image/webp;base64,...` do original, ou exporte o logo do Figma, node do Logo, e embuta de novo).

````html
<!-- =========================================================
     CONNECTION 2027 · Bloco 02 — Hero (logo, chamada, CTA, cronômetro e globo)
     Figma: node 642:3614 (Landing page › Frame 26 › 01 · Hero)
     Colar como bloco HTML no RD Station. Autocontido.

     O logo já vai embutido (WebP 2x, gerado do vetor do Figma).
     O bloco ocupa a largura inteira da tela mesmo dentro da coluna do RD.
     Cronômetro e globo usam JavaScript: confira na visualização / página
     publicada (o editor do RD não executa scripts).
     ========================================================= -->
<link rel="preconnect" href="https://fonts.googleapis.com">
<link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
<link href="https://fonts.googleapis.com/css2?family=Chakra+Petch:ital,wght@0,400;0,600;0,700;1,700&display=swap" rel="stylesheet">

<style>
  html,body{overflow-x:hidden}
  .cx-hero,.cx-prog{margin-top:0 !important; margin-bottom:0 !important}
  @font-face{font-family:'CX QB One'; font-weight:800; font-style:normal; font-display:swap;
    src:url(data:font/woff2;base64,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) format('woff2')}
  .cx-hero{
    --cx-navy:#090F2B; --cx-azul:#0064FD; --cx-ciano:#00D3FD; --cx-roxo:#7727F0;
    --cx-magenta:#F9039B; --cx-branco:#F5F5F9;
    --cx-ease:cubic-bezier(.2,.8,.2,1);
    --cx-fonte:'Chakra Petch',sans-serif;
    position:relative; overflow:hidden; isolation:isolate;
    box-sizing:border-box; width:100vw; max-width:100vw; margin-left:calc(50% - 50vw); margin-right:calc(50% - 50vw);
    min-height:900px; padding:78px 24px 0;
    background:var(--cx-navy); color:var(--cx-branco);
    font-family:var(--cx-fonte); text-align:center;
    -webkit-font-smoothing:antialiased;
  }
  .cx-hero *,.cx-hero *::before,.cx-hero *::after{box-sizing:border-box}

  /* ---------- Fundo: brilhos, grade, quadrados, ruído ---------- */
  .cx-hero__brilhos{position:absolute; inset:0; z-index:-3; pointer-events:none; -webkit-mask-image:linear-gradient(#000 0%,#000 62%,transparent 96%); mask-image:linear-gradient(#000 0%,#000 62%,transparent 96%);}
  .cx-hero__brilhos span{position:absolute; border-radius:50%; filter:blur(10px); animation:cx-respira 9s ease-in-out infinite alternate}
  .cx-hero__brilhos .b1{left:-22%; top:35%; width:55%; height:90%;
    background:radial-gradient(closest-side,rgba(0,100,253,.75),rgba(0,100,253,.25) 55%,transparent)}
  .cx-hero__brilhos .b2{right:-20%; top:-30%; width:55%; height:80%;
    background:radial-gradient(closest-side,rgba(249,3,155,.45),rgba(119,39,240,.25) 55%,transparent); animation-delay:-3s}
  .cx-hero__brilhos .b3{left:25%; top:-25%; width:50%; height:70%;
    background:radial-gradient(closest-side,rgba(0,100,253,.22),transparent); animation-delay:-6s}
  .cx-hero__brilhos .b4{right:-15%; bottom:-30%; width:45%; height:70%;
    background:radial-gradient(closest-side,rgba(119,39,240,.35),transparent); animation-delay:-1.5s}

  .cx-hero__parede{
    position:absolute; top:0; height:100%; width:30%; z-index:-2; pointer-events:none;
    background-image:
      linear-gradient(rgba(0,100,253,.9) 1.5px,transparent 1.5px),
      linear-gradient(90deg,rgba(0,100,253,.9) 1.5px,transparent 1.5px);
    background-size:62px 62px;
    opacity:.6;
    -webkit-mask-image:radial-gradient(ellipse 100% 75% at var(--cx-mx) 25%,#000 15%,transparent 75%),linear-gradient(#000 55%,transparent 90%);
    -webkit-mask-composite:source-in;
            mask-image:radial-gradient(ellipse 100% 75% at var(--cx-mx) 25%,#000 15%,transparent 75%),linear-gradient(#000 55%,transparent 90%);
            mask-composite:intersect;
    animation:cx-grade 8s linear infinite;
  }
  .cx-hero__parede--esq{left:0; --cx-mx:0%}
  .cx-hero__parede--dir{right:0; --cx-mx:100%}

  .cx-hero__quadrados{position:absolute; inset:0; z-index:-1; pointer-events:none; -webkit-mask-image:linear-gradient(#000 0%,#000 62%,transparent 96%); mask-image:linear-gradient(#000 0%,#000 62%,transparent 96%);}
  .cx-hero__quadrados i{
    position:absolute; width:var(--q,55px); height:var(--q,55px); background:var(--cx-azul);
    box-shadow:0 0 30px rgba(0,100,253,.85);
    animation:cx-pisca-q 4s steps(1) infinite;
  }
  .cx-hero__quadrados .q1{left:var(--q,55px); top:calc(var(--q,55px)*10.6)}
  .cx-hero__quadrados .q2{left:0; top:calc(var(--q,55px)*11.6)}
  .cx-hero__quadrados .q3{left:calc(var(--q,55px)*2); top:calc(var(--q,55px)*11.6)}
  .cx-hero__quadrados .q4{left:0; top:calc(var(--q,55px)*13.6)}
  .cx-hero__quadrados .q5{right:calc(var(--q,55px)*2); top:0}
  .cx-hero__quadrados .q6{right:var(--q,55px); top:var(--q,55px)}
  .cx-hero__quadrados .q7{right:0; top:calc(var(--q,55px)*2)}
  .cx-hero__quadrados i:nth-child(2){animation-delay:-1.1s}
  .cx-hero__quadrados i:nth-child(3){animation-delay:-2.3s}
  .cx-hero__quadrados i:nth-child(4){animation-delay:-.6s}
  .cx-hero__quadrados i:nth-child(5){animation-delay:-3.1s}
  .cx-hero__quadrados i:nth-child(6){animation-delay:-1.8s}
  .cx-hero__quadrados i:nth-child(7){animation-delay:-2.7s}

  .cx-hero__ruido{position:absolute; inset:0; z-index:5; pointer-events:none; opacity:.07; mix-blend-mode:overlay;
    background-image:url("data:image/svg+xml,%3Csvg xmlns='http://www.w3.org/2000/svg' width='160' height='160'%3E%3Cfilter id='n'%3E%3CfeTurbulence type='fractalNoise' baseFrequency='.9' numOctaves='2' stitchTiles='stitch'/%3E%3C/filter%3E%3Crect width='100%25' height='100%25' filter='url(%23n)'/%3E%3C/svg%3E")}

  /* ---------- Globo (canvas) ---------- */
  .cx-hero__globo{
    position:absolute; left:50%; bottom:0; z-index:0; pointer-events:none;
    width:min(1205px,125vw); aspect-ratio:1205/280; transform:translateX(-50%); opacity:.6;
    -webkit-mask-image:linear-gradient(#000 25%,transparent 74%);
            mask-image:linear-gradient(#000 25%,transparent 74%);
  }
  .cx-hero__globo canvas{display:block; width:100%; height:100%}
  @media (min-width:768px){ .cx-hero__globo{transform:translateX(-50%) translateY(25px)} }

  /* ---------- Conteúdo ---------- */
  .cx-hero__conteudo{position:relative; z-index:2; max-width:780px; margin:0 auto; display:flex; flex-direction:column; align-items:center}
  .cx-hero__logo{display:block; width:293px; height:auto; max-width:70%; height:auto; margin:0 0 44px}
  .cx-hero__selo{margin:0 0 22px; font-size:18px; line-height:1.3; letter-spacing:.24em; text-transform:uppercase; font-weight:400}
  .cx-hero__selo strong{font-weight:700}
  .cx-hero__titulo{
    margin:0 0 26px; font:800 clamp(28px,3vw + 12px,48px)/1.02 'CX QB One',var(--cx-fonte); font-synthesis:none; text-transform:uppercase;
    filter:drop-shadow(0 0 18px rgba(255,255,255,.3));
  }
  .cx-hero__titulo-in{display:inline-block; transform:skewX(-11deg);
    background:linear-gradient(180deg,#fff 0%,#fff 30%,#c9ccd1 46%,#fff 54%,#fff 62%,#8b8e94 72%,#fff 90%);
    -webkit-background-clip:text; background-clip:text; color:transparent;
  }
  .cx-hero__texto{margin:0 0 40px; max-width:600px; font-size:22px; line-height:1.3; color:var(--cx-branco); text-shadow:0 0 30px rgba(255,255,255,.3)}
  .cx-hero__texto strong{font-weight:700}

  /* ---------- Botão ---------- */
  .cx-cta{
    position:relative; display:inline-flex; align-items:center; gap:16px; overflow:hidden;
    padding:20px 24px 20px 32px; border-radius:8px; text-decoration:none; color:#fff;
    font:600 16px/1 var(--cx-fonte); letter-spacing:.08em; text-transform:uppercase;
    background:linear-gradient(100deg,#2E7BFF 0%,#0064FD 18%,#643DD5 58%,#F9039B 100%,#643DD5 140%,#0064FD 180%);
    background-size:200% 100%; background-position:0% 0;
    box-shadow:0 0 0 rgba(0,211,253,0);
    transition:background-position .6s var(--cx-ease),box-shadow .3s var(--cx-ease),transform .25s var(--cx-ease);
    transform:translate(var(--cx-ix,0),var(--cx-iy,0));
  }
  .cx-cta::before{ /* reflexo que passa */
    content:""; position:absolute; inset:0; pointer-events:none;
    background:linear-gradient(100deg,transparent 35%,rgba(255,255,255,.16) 50%,transparent 65%);
    transform:translateX(-120%); animation:cx-reflexo-cta 4.5s var(--cx-ease) infinite 2s;
  }
  .cx-cta svg{width:28px; height:28px; flex-shrink:0; filter:drop-shadow(0 0 2px rgba(0,211,253,.6))}
  .cx-cta svg path{animation:none}
  .cx-cta:hover,.cx-cta:focus-visible{background-position:100% 0; box-shadow:0 0 18px rgba(0,100,253,.35),0 0 40px rgba(249,3,155,.18)}
  .cx-cta:hover svg .s1,.cx-cta:focus-visible svg .s1{animation:cx-seta 0.9s steps(1) infinite}
  .cx-cta:hover svg .s2,.cx-cta:focus-visible svg .s2{animation:cx-seta 0.9s steps(1) infinite .3s}
  .cx-cta:hover svg .s3,.cx-cta:focus-visible svg .s3{animation:cx-seta 0.9s steps(1) infinite .6s}
  .cx-cta:active{transform:translate(var(--cx-ix,0),var(--cx-iy,0)) scale(.97)}
  .cx-cta:focus-visible{outline:3px solid var(--cx-ciano); outline-offset:4px}

  /* ---------- Ícones pixel ---------- */
  .cx-icone{position:absolute; z-index:3; animation:cx-flutua 6s ease-in-out infinite}
  .cx-icone--audaces{left:calc(50% - 548px); top:318px; width:166px}
  .cx-icone--carinha{left:calc(50% + 338px); top:425px; width:169px; animation-delay:-3s}
  .cx-icone__alvo{display:block; width:100%;
    transform:translate(var(--cx-px,0),var(--cx-py,0)); transition:transform .4s var(--cx-ease)}
  .cx-icone svg{display:block; width:100%; height:auto; overflow:visible;
    filter:drop-shadow(0 0 8px rgba(0,211,253,.5));
    transition:transform .6s var(--cx-ease),filter .6s var(--cx-ease)}
  .cx-icone:hover svg{filter:drop-shadow(0 0 14px rgba(0,211,253,.85)) drop-shadow(0 0 26px rgba(249,3,155,.3))}
  .cx-icone--audaces:hover svg{transform:translateY(-6px) scale(1.05) rotate(-5deg)}
  .cx-icone--carinha:hover svg{transform:translateY(-6px) scale(1.05) rotate(5deg)}

  /* ---------- Cronômetro ---------- */
  .cx-crono{position:relative; z-index:2; display:flex; justify-content:center; align-items:flex-start; gap:27px; margin:72px auto 0; padding-bottom:110px}
  .cx-crono__unidade{display:flex; flex-direction:column; align-items:center; gap:10px; min-width:2.4ch}
  .cx-crono__num{
    display:block; font:700 64px/1 var(--cx-fonte); font-variant-numeric:tabular-nums; letter-spacing:.02em;
    background:linear-gradient(180deg,#fff 0%,#fff 32%,#c9ccd1 46%,#fff 56%,#fff 64%,#9a9da3 74%,#fff 92%);
    -webkit-background-clip:text; background-clip:text; color:transparent;
    filter:drop-shadow(0 0 18px rgba(255,255,255,.3));
  }
  .cx-crono__num.is-tick{animation:cx-tick .55s var(--cx-ease)}
  .cx-crono__traco{width:32px; height:2px; border-radius:2px; background:linear-gradient(90deg,#00D3FD,#0064FD 28%,#7727F0 59%,#F9039B); box-shadow:0 0 10px rgba(0,211,253,.6)}
  .cx-crono__rotulo{font:600 13.5px/1.3 var(--cx-fonte); letter-spacing:.08em; text-transform:uppercase}
  .cx-crono__sep{display:flex; flex-direction:column; gap:9px; padding-top:20px}
  .cx-crono__sep i{width:7px; height:7px; animation:cx-batida 1s steps(1) infinite}
  .cx-crono__sep i:first-child{background:var(--cx-ciano); box-shadow:0 0 12px var(--cx-ciano)}
  .cx-crono__sep i:last-child{background:var(--cx-magenta); box-shadow:0 0 12px var(--cx-magenta); animation-delay:.5s}
  .cx-crono__fim{display:none; font:italic 700 clamp(24px,3vw,44px)/1.1 var(--cx-fonte); text-transform:uppercase; color:#fff; text-shadow:0 0 24px rgba(0,211,253,.7)}
  .cx-crono.is-fim .cx-crono__unidade,.cx-crono.is-fim .cx-crono__sep{display:none}
  .cx-crono.is-fim .cx-crono__fim{display:block}
  .cx-hero .cx-m{display:none}
  .cx-sr{position:absolute; width:1px; height:1px; overflow:hidden; clip:rect(0 0 0 0); white-space:nowrap}

  /* ---------- Entrada ---------- */
  .cx-hero [data-cx-entra]{animation:cx-entra .8s var(--cx-ease) both; animation-delay:var(--d,0ms)}

  /* ---------- Keyframes ---------- */
  @keyframes cx-entra{from{opacity:0; transform:translateY(24px)}to{opacity:1; transform:none}}
  @keyframes cx-respira{from{opacity:.7; transform:scale(1)}to{opacity:1; transform:scale(1.08)}}
  @keyframes cx-grade{from{background-position:0 0}to{background-position:0 62px}}
  @keyframes cx-grade-m{from{background-position:0 0}to{background-position:0 36px}}
  @keyframes cx-pisca-q{0%,100%{opacity:1}12%{opacity:.35}16%{opacity:1}55%{opacity:.6}58%{opacity:1}}
  @keyframes cx-flutua{0%,100%{transform:translateY(0)}50%{transform:translateY(-12px)}}
  @keyframes cx-tick{
    0%{opacity:0; transform:translateY(-35%) skewX(-8deg); filter:drop-shadow(-4px 0 0 rgba(0,211,253,.95)) drop-shadow(4px 0 0 rgba(249,3,155,.95)) blur(2px)}
    60%{opacity:1; transform:translateY(4%)}
    100%{transform:none; filter:drop-shadow(0 0 18px rgba(255,255,255,.3))}
  }
  @keyframes cx-batida{0%{opacity:1}50%{opacity:.25}}
  @keyframes cx-seta{0%{opacity:1}33%{opacity:.25}}
  @keyframes cx-reflexo-cta{0%,55%{transform:translateX(-120%)}100%{transform:translateX(120%)}}

  /* ---------- Tablet ---------- */
  @media (max-width:1180px){
    .cx-icone--audaces{left:3%; width:120px}
    .cx-icone--carinha{left:auto; right:3%; width:120px}
  }

  /* ---------- Mobile ---------- */
  @media (max-width:767px){
    .cx-hero{min-height:0; padding:48px 32px 0 !important}
    .cx-hero__logo{width:min(236px,60vw); margin-bottom:40px}
    .cx-hero__selo{font-size:13px; letter-spacing:.18em; line-height:1.6; margin-bottom:20px}
    .cx-hero .cx-m{display:inline}
    .cx-hero .cx-d{display:none}
    .cx-hero__titulo{margin-bottom:20px; font-size:clamp(26px,calc((100vw - 64px)/9.8),38px)}
    .cx-hero__texto{font-size:min(18px,calc((100vw - 64px)/20.6)); margin-bottom:32px}
    .cx-cta{width:100%; justify-content:center; min-height:56px; padding:18px 20px; font-size:clamp(13px,3.9vw,15px); letter-spacing:.06em; white-space:nowrap}
    .cx-icone--audaces{left:calc(50% - 170px); top:148px; width:52px}
    .cx-icone--carinha{left:calc(50% + 118px); right:auto; top:152px; width:52px}
    .cx-hero__parede{width:45%; height:60%; background-size:36px 36px; animation:cx-grade-m 4.6s linear infinite}
    .cx-hero__quadrados{--q:22px}
    .cx-hero__quadrados .q1,.cx-hero__quadrados .q2,.cx-hero__quadrados .q3,.cx-hero__quadrados .q4{display:none}
    .cx-crono{gap:4px; margin-top:48px; padding-bottom:64px; max-width:400px}
    .cx-hero__conteudo>div{width:100%}
    .cx-crono__unidade{gap:8px}
    .cx-crono__unidade{min-width:0; flex:1 1 0}
    .cx-crono__num{font-size:clamp(32px,9.6vw,46px)}
    .cx-crono__traco{width:32px; height:2px}
    .cx-crono__rotulo{font-size:12px; letter-spacing:.06em}
    .cx-crono__sep{gap:7px; padding-top:calc(clamp(32px,9.6vw,46px)*.3)}
    .cx-crono__sep i{width:6px; height:6px}
    .cx-hero__globo{width:170vw; aspect-ratio:1205/330; bottom:-86px;
      -webkit-mask-image:linear-gradient(#000 22%,transparent 56%); mask-image:linear-gradient(#000 22%,transparent 56%)}
  }

  @media (max-width:380px){
    .cx-icone--audaces{left:calc(50% - 160px); width:44px}
    .cx-icone--carinha{left:calc(50% + 116px); width:44px}
  }

  /* ---------- Menos movimento ---------- */
  @media (prefers-reduced-motion:reduce){
    .cx-hero *,.cx-hero *::before,.cx-hero *::after{animation:none!important; transition:none!important}
  }
</style>

<section class="cx-hero" id="cx-hero" aria-labelledby="cx-hero-titulo">
  <!-- Fundo -->
  <div class="cx-hero__brilhos" aria-hidden="true"><span class="b1"></span><span class="b2"></span><span class="b3"></span><span class="b4"></span></div>
  <div class="cx-hero__parede cx-hero__parede--esq" aria-hidden="true"></div>
  <div class="cx-hero__parede cx-hero__parede--dir" aria-hidden="true"></div>
  <div class="cx-hero__quadrados" aria-hidden="true">
    <i class="q1"></i><i class="q2"></i><i class="q3"></i><i class="q4"></i>
    <i class="q5"></i><i class="q6"></i><i class="q7"></i>
  </div>
  <div class="cx-hero__globo" aria-hidden="true"><canvas id="cx-globo"></canvas></div>
  <div class="cx-hero__ruido" aria-hidden="true"></div>

  <!-- Ícones pixel interativos -->
  <div class="cx-icone cx-icone--audaces" aria-hidden="true" data-cx-entra style="--d:900ms">
    <span class="cx-icone__alvo">
      <svg viewBox="0 0 166 166" aria-hidden="true">
        <defs><linearGradient id="cx-g-aud" x1="4.25" y1="22.45" x2="161.26" y2="143.06" gradientUnits="userSpaceOnUse"><stop stop-color="#F5F5F9"/><stop offset=".4" stop-color="#0064FD"/><stop offset=".72" stop-color="#fff"/><stop offset="1" stop-color="#F9039B"/></linearGradient></defs>
        <path fill="url(#cx-g-aud)" d="M113.78 139.874L114.993 149.129L68.7233 155.196L67.5097 145.941L113.78 139.874ZM67.5097 145.941L49.0012 148.369L47.7877 139.115L66.2962 136.688L67.5097 145.941ZM140.328 126.979L131.075 128.193L132.288 137.447L113.78 139.874L112.566 130.62L131.074 128.193L129.86 118.939L139.115 117.726L140.328 126.979ZM47.7877 139.115L38.5339 140.328L37.3204 131.074L46.5742 129.861L47.7877 139.115ZM37.3203 131.074L28.0655 132.287L25.6386 113.78L34.8933 112.566L37.3203 131.074ZM55.8279 128.647L46.5741 129.86L44.1471 111.352L53.4009 110.139L55.8279 128.647ZM148.369 116.511L129.861 118.938L127.434 100.431L145.942 98.0037L148.369 116.511ZM25.6386 113.78L16.3848 114.993L10.317 68.7222L19.5708 67.5087L25.6386 113.78ZM60.2275 90.417L61.4421 99.6716L62.6556 108.925L53.4009 110.139L50.9738 91.6304L60.2275 90.417ZM125.006 81.9222L126.221 91.1769L127.434 100.431L118.179 101.644L115.752 83.1357L125.006 81.9222ZM151.555 69.0278L151.556 69.0277L152.768 78.2816L153.983 87.5363L155.196 96.79L145.942 98.0037L139.874 51.7338L149.128 50.5203L151.555 69.0278ZM69.4824 89.2043L60.2286 90.4178L57.8015 71.9093L67.0553 70.6958L69.4824 89.2043ZM115.752 83.1357L106.498 84.3492L104.071 65.8417L113.325 64.6282L115.752 83.1357ZM76.3091 69.4823L67.0553 70.6958L64.6282 52.1872L73.882 50.9737L76.3091 69.4823ZM104.071 65.8417L94.8176 67.0552L92.3905 48.5466L101.644 47.3331L104.071 65.8417ZM35.6524 46.5741L26.3986 47.7876L28.8257 66.2961L19.571 67.5097L17.1438 49.0012L26.3976 47.7877L25.1841 38.5339L34.4389 37.3203L35.6524 46.5741ZM139.874 51.7338L130.62 52.9473L128.193 34.4387L137.447 33.2252L139.874 51.7338ZM92.3905 48.5466L83.1367 49.7601L81.9232 40.5063L81.9222 40.5065L80.7088 31.2527L89.9635 30.0391L92.3905 48.5466ZM128.193 34.4387L118.938 35.6524L117.725 26.3986L126.98 25.185L128.193 34.4387ZM52.9463 34.8923L34.4388 37.3193L33.2253 28.0655L51.7328 25.6385L52.9463 34.8923ZM98.0037 19.5708L79.4951 21.9979L80.7086 31.2517L71.4548 32.4652L70.2414 23.2114L51.7338 25.6384L50.5203 16.3846L96.7902 10.317L98.0037 19.5708ZM117.725 26.3976L99.2172 28.8246L98.0037 19.5708L116.511 17.1438L117.725 26.3976Z"/>
      </svg>
    </span>
  </div>
  <div class="cx-icone cx-icone--carinha" aria-hidden="true" data-cx-entra style="--d:1050ms">
    <span class="cx-icone__alvo">
      <svg viewBox="0 0 169 169" aria-hidden="true">
        <defs><linearGradient id="cx-g-car" x1="35.06" y1="-1.84" x2="133.21" y2="170.11" gradientUnits="userSpaceOnUse"><stop stop-color="#F5F5F9"/><stop offset=".4" stop-color="#0064FD"/><stop offset=".72" stop-color="#fff"/><stop offset="1" stop-color="#F9039B"/></linearGradient></defs>
        <g fill="url(#cx-g-car)">
          <path d="M36.6347 134.047L72.6468 143.886L70.1871 152.889L34.174 143.05L36.6347 134.047L27.6307 131.587L30.0904 122.584L39.0944 125.044L36.6347 134.047Z"/>
          <path d="M99.6569 151.266L97.1972 160.269L70.1871 152.889L72.6468 143.886L99.6569 151.266Z"/>
          <path d="M108.661 153.726L99.6569 151.266L102.117 142.262L111.121 144.722L108.661 153.726Z"/>
          <path d="M23.5473 111.121L32.5504 113.58L30.0904 122.584L21.0867 120.123L23.5473 111.121L14.5433 108.661L17.0033 99.6567L26.0073 102.117L23.5473 111.121Z"/>
          <path d="M120.124 147.181L111.121 144.722L113.581 135.719L122.584 138.178L120.124 147.181Z"/>
          <path d="M131.588 140.638L122.584 138.178L125.045 129.175L134.048 131.634L131.588 140.638Z"/>
          <path d="M17.0033 99.6567L8 97.1979L15.3794 70.1878L24.3825 72.6475L17.0033 99.6567Z"/>
          <path d="M80.0262 116.876L53.0171 109.497L55.4771 100.493L82.4862 107.872L80.0262 116.876Z"/>
          <path d="M98.0333 121.796L80.0262 116.876L82.4862 107.872L100.493 112.792L98.0333 121.796Z"/>
          <path d="M143.05 134.095L134.048 131.634L141.427 104.625L150.43 107.085L143.05 134.095Z"/>
          <path d="M55.4771 100.493L46.474 98.0333L48.9338 89.0302L57.9368 91.49L55.4771 100.493Z"/>
          <path d="M109.497 115.252L100.493 112.792L102.953 103.789L111.957 106.249L109.497 115.252Z"/>
          <path d="M24.3825 72.6475L15.3794 70.1878L25.2188 34.1737L34.2218 36.6335L24.3825 72.6475Z"/>
          <path d="M150.43 107.085L141.427 104.625L151.266 68.6111L160.269 71.0708L150.43 107.085Z"/>
          <path class="cx-olho" d="M71.8595 75.9426L53.8535 71.0232L58.7719 53.0169L76.779 57.9365L71.8595 75.9426Z"/>
          <path class="cx-olho" d="M121.795 70.2354L116.877 88.2417L98.8696 83.322L103.789 65.316L121.795 70.2354Z"/>
          <path d="M43.2246 39.0941L34.2218 36.6335L36.6816 27.6304L45.6846 30.0901L43.2246 39.0941Z"/>
          <path d="M151.266 68.6111L142.262 66.152L144.722 57.148L153.726 59.608L151.266 68.6111Z"/>
          <path d="M54.6886 32.5501L45.6846 30.0901L48.1446 21.0861L57.1486 23.5461L54.6886 32.5501Z"/>
          <path d="M144.722 57.148L135.719 54.6883L138.179 45.6843L147.182 48.1441L144.722 57.148Z"/>
          <path d="M66.1523 26.007L57.1486 23.5461L59.6083 14.5431L68.6123 17.003L66.1523 26.007Z"/>
          <path d="M131.635 34.2216L140.639 36.6813L138.179 45.6843L129.175 43.2253L131.635 34.2216L104.625 26.8422L107.085 17.8391L134.095 25.2185L131.635 34.2216Z"/>
          <path d="M104.625 26.8422L68.6123 17.003L71.072 8L107.085 17.8391L104.625 26.8422Z"/>
        </g>
      </svg>
    </span>
  </div>

  <!-- Conteúdo -->
  <div class="cx-hero__conteudo">
    <img class="cx-hero__logo" data-cx-entra style="--d:0ms" src="LOGO_WEBP_BASE64_REMOVIDO" width="293" height="98" alt="Audaces Connection 2027">
    <p class="cx-hero__selo" data-cx-entra style="--d:150ms"><strong>Audaces</strong> celebra <strong>35 <br class="cx-m">anos de história</strong></p>
    <h1 class="cx-hero__titulo" id="cx-hero-titulo" data-cx-entra style="--d:300ms"><span class="cx-hero__titulo-in">Uma edição <br class="cx-m">especial <br class="cx-d">está <br class="cx-m">chegando!</span></h1>
    <p class="cx-hero__texto" data-cx-entra style="--d:450ms">Faça parte do grupo do <strong>Connection 2027</strong> e <br class="cx-m">receba todas as atualizações sobre o evento <br class="cx-m">em primeira mão.</p>
    <div data-cx-entra style="--d:600ms">
      <a class="cx-cta" href="https://forms.cloud.microsoft/pages/responsepage.aspx?id=Pea-wGELFkKHeCdIUzWYFdltyA4ArOtFvHacF0teTvdUMTg2WUUyQ0ZYVUI1Q1pPU0lQVzcxWUs3VS4u&amp;route=shorturl" target="_blank" rel="noopener">
        Entrar no grupo do evento
        <svg viewBox="0 0 28 28" aria-hidden="true" fill="#fff">
          <path class="s1" d="M5.1 21.3H3.5v-1.6h1.6zM6.7 19.7H5.1v-1.6h1.6zM8.3 18H6.7v-1.6h1.6zM10 16.4H8.3v-1.6H10zM11.6 14.8H10v-1.6h1.6zM10 13.2H8.3v-1.6H10zM8.3 11.6H6.7V9.95h1.6zM6.7 9.95H5.1V8.3h1.6zM5.1 8.3H3.5V6.7h1.6z"/>
          <path class="s2" d="M11.6 21.3H10v-1.6h1.6zM13.2 19.7h-1.6v-1.6h1.6zM14.8 18h-1.6v-1.6h1.6zM16.4 16.4h-1.6v-1.6h1.6zM18 14.8h-1.6v-1.6H18zM16.4 13.2h-1.6v-1.6h1.6zM14.8 11.6h-1.6V9.95h1.6zM13.2 9.95h-1.6V8.3h1.6zM11.6 8.3H10V6.7h1.6z"/>
          <path class="s3" d="M18 21.3h-1.6v-1.6H18zM19.7 19.7H18v-1.6h1.7zM21.3 18h-1.6v-1.6h1.6zM22.9 16.4h-1.6v-1.6h1.6zM24.5 14.8h-1.6v-1.6h1.6zM22.9 13.2h-1.6v-1.6h1.6zM21.3 11.6h-1.6V9.95h1.6zM19.7 9.95H18V8.3h1.7zM18 8.3h-1.6V6.7H18z"/>
        </svg>
      </a>
    </div>
  </div>

  <!-- Cronômetro -->
  <div class="cx-crono" id="cx-crono" role="timer" aria-label="Contagem regressiva para o Connection 2027" data-cx-entra style="--d:750ms"
       data-alvo="2027-01-07T08:00:00-03:00">
    <div class="cx-crono__unidade"><span class="cx-crono__num" data-u="d">00</span><span class="cx-crono__traco"></span><span class="cx-crono__rotulo">Dias</span></div>
    <div class="cx-crono__sep" aria-hidden="true"><i></i><i></i></div>
    <div class="cx-crono__unidade"><span class="cx-crono__num" data-u="h">00</span><span class="cx-crono__traco"></span><span class="cx-crono__rotulo">Horas</span></div>
    <div class="cx-crono__sep" aria-hidden="true"><i></i><i></i></div>
    <div class="cx-crono__unidade"><span class="cx-crono__num" data-u="m">00</span><span class="cx-crono__traco"></span><span class="cx-crono__rotulo">Minutos</span></div>
    <div class="cx-crono__sep" aria-hidden="true"><i></i><i></i></div>
    <div class="cx-crono__unidade"><span class="cx-crono__num" data-u="s">00</span><span class="cx-crono__traco"></span><span class="cx-crono__rotulo">Segundos</span></div>
    <p class="cx-crono__fim">O Connection 2027 começou!</p>
  </div>
</section>

<script>
(function(){
  var hero = document.getElementById('cx-hero');
  if(!hero) return;
  var reduz = window.matchMedia && window.matchMedia('(prefers-reduced-motion: reduce)').matches;

  /* ---------- Cronômetro ---------- */
  var crono = document.getElementById('cx-crono');
  var alvo = new Date(crono.getAttribute('data-alvo')).getTime();
  var els = {}; ['d','h','m','s'].forEach(function(k){ els[k] = crono.querySelector('[data-u="'+k+'"]'); });
  function dois(n){ return (n < 10 ? '0' : '') + n; }
  function atualiza(){
    var falta = Math.max(0, alvo - Date.now());
    if(falta === 0){ crono.classList.add('is-fim'); return false; }
    var t = Math.floor(falta/1000);
    var v = { d: Math.floor(t/86400), h: Math.floor(t%86400/3600), m: Math.floor(t%3600/60), s: t%60 };
    for(var k in v){
      var txt = k === 'd' ? String(v[k]).padStart(2,'0') : dois(v[k]);
      if(els[k].textContent !== txt){
        els[k].textContent = txt;
        if(!reduz){ els[k].classList.remove('is-tick'); void els[k].offsetWidth; els[k].classList.add('is-tick'); }
      }
    }
    return true;
  }
  if(atualiza()){
    var timer = setInterval(function(){ if(!atualiza()) clearInterval(timer); }, 1000);
  }

  /* ---------- Parallax suave dos ícones e "ímã" do botão (só mouse) ---------- */
  var cta = hero.querySelector('.cx-cta');
  if(!reduz && window.matchMedia('(pointer: fine)').matches){
    hero.addEventListener('pointermove', function(e){
      var h = hero.getBoundingClientRect();
      var nx = (e.clientX - h.left)/h.width - .5, ny = (e.clientY - h.top)/h.height - .5;
      hero.querySelectorAll('.cx-icone__alvo').forEach(function(el, i){
        var f = i ? -10 : 10;
        el.style.setProperty('--cx-px', (nx*f)+'px'); el.style.setProperty('--cx-py', (ny*f)+'px');
      });
    });
    cta.addEventListener('pointermove', function(e){
      var r = cta.getBoundingClientRect();
      cta.style.setProperty('--cx-ix', ((e.clientX - r.left)/r.width - .5)*10+'px');
      cta.style.setProperty('--cx-iy', ((e.clientY - r.top)/r.height - .5)*8+'px');
    });
    cta.addEventListener('pointerleave', function(){ cta.style.setProperty('--cx-ix','0px'); cta.style.setProperty('--cx-iy','0px'); });
  }

  /* ---------- Globo wireframe girando (canvas) ---------- */
  var cv = document.getElementById('cx-globo'), ctx = cv.getContext('2d');
  var W, H, R, CX, CY, dpr, giro = 0, inclina = 0.42, alvoInclina = 0.42, visivel = true, ultimo = 0;
  function mede(){
    dpr = Math.min(window.devicePixelRatio || 1, 2);
    W = cv.clientWidth; H = cv.clientHeight;
    cv.width = W*dpr; cv.height = H*dpr; ctx.setTransform(dpr,0,0,dpr,0,0);
    R = W*0.483; CX = W/2; CY = R + H*0.06;
  }
  function proj(lat, lon){
    var x = Math.cos(lat)*Math.sin(lon), y = Math.sin(lat), z = Math.cos(lat)*Math.cos(lon);
    var y2 = y*Math.cos(inclina) - z*Math.sin(inclina), z2 = y*Math.sin(inclina) + z*Math.cos(inclina);
    return [CX + x*R, CY - y2*R, z2];
  }
  function linha(pontos){
    ctx.beginPath(); var on = false;
    for(var i=0;i<pontos.length;i++){
      var p = pontos[i];
      if(p[2] < 0){ on = false; continue; }
      if(!on){ ctx.moveTo(p[0],p[1]); on = true; } else ctx.lineTo(p[0],p[1]);
    }
    ctx.stroke();
  }
  function desenha(){
    ctx.clearRect(0,0,W,H);
    // atmosfera
    var atm = ctx.createRadialGradient(CX,CY,R*0.9,CX,CY,R);
    atm.addColorStop(0,'rgba(0,100,253,0)'); atm.addColorStop(1,'rgba(0,100,253,.22)');
    ctx.fillStyle = atm; ctx.beginPath(); ctx.arc(CX,CY,R,0,Math.PI*2); ctx.fill();
    // grade
    ctx.lineWidth = 1; ctx.strokeStyle = 'rgba(0,211,253,.28)';
    ctx.shadowColor = 'rgba(0,211,253,.5)'; ctx.shadowBlur = 4;
    var lat, lon, pts, i;
    for(lat=-75; lat<=75; lat+=15){
      pts = []; for(i=0;i<=120;i++){ pts.push(proj(lat*Math.PI/180, i/120*Math.PI*2)); } linha(pts);
    }
    for(lon=0; lon<360; lon+=15){
      pts = []; for(i=0;i<=60;i++){ pts.push(proj((-90 + i*3)*Math.PI/180, lon*Math.PI/180 + giro)); } linha(pts);
    }
    // contorno com brilho neon
    ctx.beginPath(); ctx.arc(CX,CY,R,0,Math.PI*2);
    ctx.lineWidth = 6; ctx.strokeStyle = 'rgba(0,100,253,.22)'; ctx.shadowColor = 'rgba(0,100,253,.6)'; ctx.shadowBlur = 24; ctx.stroke();
    ctx.lineWidth = 1.5; ctx.strokeStyle = 'rgba(230,251,255,.4)'; ctx.shadowColor = 'rgba(0,211,253,.6)'; ctx.shadowBlur = 8; ctx.stroke();
    ctx.shadowBlur = 0;
  }
  function loop(t){
    if(visivel){
      var dt = Math.min(64, t - (ultimo || t)); ultimo = t;
      giro += dt*0.00012; inclina += (alvoInclina - inclina)*0.05;
      desenha();
    } else ultimo = 0;
    requestAnimationFrame(loop);
  }
  mede(); desenha();
  window.addEventListener('resize', function(){ mede(); desenha(); });
  if(!reduz){
    if('IntersectionObserver' in window){
      new IntersectionObserver(function(en){ visivel = en[0].isIntersecting; }).observe(cv);
    }
    hero.addEventListener('pointermove', function(e){
      var h = hero.getBoundingClientRect();
      alvoInclina = 0.42 + ((e.clientY - h.top)/h.height - .5)*0.25;
    });
    requestAnimationFrame(loop);
  }
})();
</script>
````
