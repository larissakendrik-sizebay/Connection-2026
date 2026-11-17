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

**Estado atual (17/11/2026):** a programação ainda não está definida. A LP usa a versão **"Em breve"**, em [`lp/bloco-03-em-breve.html`](lp/bloco-03-em-breve.html): mesmo visual do bloco, com card "EM BREVE MAIS INFORMAÇÕES" e barra "LOADING..." no lugar dos dias. O card final ("Nos vemos no Connection 2027!") e o botão foram mantidos.

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
