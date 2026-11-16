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

### Camisetas vintage (página **Camiseta**, seção "Camisetas Vintage · Propostas")
Base: ringer marinho com gola e mangas brancas (`Camiseta Bicolor Azul 1`). Estampas pensadas para serigrafia: 3 a 4 cores chapadas, sem gradiente nem glow, desgaste em pixels já vazado na arte (a malha aparece pelos furos) e textos pequenos sem desgaste.

| Proposta | Frente | Costas | Cores |
|---|---|---|---|
| **01 · Sunset 1992** | Mini sol + grid no peito | Logo, sol listrado sobre chão grid, "EST. 1992 · 35 ANOS" | Branco gelo, amarelo sunset `#FFD47A`, magenta, azul elétrico |
| **02 · Varsity** | "AUDACES" em arco college + CONNECTION 2027 | "35" gigante com sombra magenta | Branco gelo, magenta, ciano |
| **03 · World Tour** | Globo wireframe vazado atrás do logo | Lista de turnê: 1992 / 7 e 8 JAN 2027 | Branco gelo, ciano, magenta |
| **04 · Mixtape Lado A/B** | Fita cassete pixel, "LADO A" | Capa de fita com player e faixas Lado A / Lado B | Branco gelo, magenta, ciano |
| **05 · Selo 35 anos** | Selo de peito | Selo grande + "O FUTURO DA MODA CONECTA AQUI" + logo | Branco gelo, ciano, magenta |
| **06 · Arcade Press Start** | Joystick + "PRESS START" | Barra LOADING + 6 ícones pixel + "INSERT COIN" | Branco gelo, magenta, ciano |

Obs.: no ambiente usado para montar as camisetas a QB One não estava disponível; os textos de apoio usam Chakra Petch e o "2027" foi vetorizado a partir do logo.

### Camisetas retrô collegiate (página **Camiseta**, seção "Camisetas Retrô Collegiate · Produção")
Inspiradas em camisetas ringer vintage (faixas anos 80, letreiro universitário, emblema oval). **Todas no ringer marinho com gola branca** (foco da marca), com estampas recoloridas para fundo escuro. Ano de fundação da Audaces: **1992** (35 anos em 2027).

| Peça | Malha | Frente | Cores |
|---|---|---|---|
| **Retrô A · Faixas 2027** | Off-white + gola marinho | "2027" itálico, sol magenta, faixas ciano/azul/roxo/magenta, CONNECTION ▸ | 5 cores |
| **Retrô B · Collegiate** | Off-white + gola azul | AUDACES CONNECTION em arco, pílula 2027 vazada, "CONECTA." | 1 cor (azul) |
| **Retrô C · Emblema oval** | Raglan off-white + vivo azul | Oval com CONNECTION ▸ e filete vazados, "AUDACES · 2027" | 1 cor (azul) ou bordado |
| **Retrô D · 35 anos** | Ringer marinho | "AUDACES · EST. 1992" em arco, "35" sobre faixas | 4 cores |
| **Retrô E · Made in 1992** | Ringer marinho | "AUDACES CONNECTION" em arco, "MADE IN", "1992" sobre faixas, "35 ANOS · FLORIANÓPOLIS · SC" | 4 cores |
| **Retrô S1 · Evento** | Off-white + gola azul | AUDACES CONNECTION / 2027 / FLORIANÓPOLIS. | 1 cor (azul) |
| **Retrô S2 · 35 anos** | Off-white + gola marinho | AUDACES CONNECTION / 1992 / 35 ANOS. | 1 cor (marinho) |
| **Retrô S3 · Moda conecta** | Off-white + gola magenta | MODA + TECNOLOGIA / 2027 / CONECTA. | 1 cor (azul) |
| **Retrô S4 · Marinho** | Ringer marinho | Igual à S1, em branco | 1 cor (branco) |

Costas: símbolo Audaces na nuca + assinatura AUDACES CONNECTION ▸ embaixo, em branco (D e E mantêm as costas do modelo original).

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
