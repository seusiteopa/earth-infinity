# EARTH INFINITY — Vecorion

**Uma viagem de cerca de 10 minutos pelo planeta Terra, desenhada inteiramente por código.**
Filme em HTML único (Three.js) que sai do símbolo do infinito, mostra a Terra girando em 3D e desce por oceanos, continentes, montanhas, países e cidades, com narração, trilha eletrônica e legendas. Foi feito para ser assistido do começo ao fim e gravado em vídeo pelo próprio site.

## Sobre o vídeo
- **Duração:** 9 min 54 s na versão completa (29 cenas) e 8 min 6 s na versão curta (23 cenas).
- **Tom:** documentário cinematográfico, com narração conversada que fala com quem assiste, faz perguntas e responde.
- **Estilo visual:** Terra realista com atmosfera azul, noite com luzes douradas, vinheta e granulação de filme, tarjas pretas de cinema e títulos animados.
- **Câmera:** conduzida pelo filme, com balanço leve, órbitas e movimentos de aproximação. O público não dá zoom nem arrasta.
- **Trilha:** eletrônica a 124 BPM, sintetizada por código. Alterna trechos calmos com groove de deep house e picos mais fortes, com build-ups e drops entre as cenas.
- **Narração:** 29 arquivos de voz, um por cena, com legendas frase por frase.
- **Extras na tela:** cartões de dados (área dos continentes, altura do Everest, população das cidades) e perguntas "VOCÊ SABIA?" no momento em que são feitas.

## Roteiro das cenas (versão completa)
| # | Cena | Início | Duração |
|---|------|--------|---------|
| 1 | Abertura ("Vecorion apresenta") | 0:00 | 19 s |
| 2 | EARTH INFINITY | 0:19 | 23 s |
| 3 | Dia e noite | 0:42 | 31 s |
| 4 | A Lua | 1:13 | 25 s |
| 5 | Amanhecer | 1:38 | 21 s |
| 6 | Clima (simulação) * | 1:59 | 26 s |
| 7 | Oceanos (simulação) | 2:25 | 26 s |
| 8 | América do Sul | 2:51 | 19 s |
| 9 | África | 3:10 | 20 s |
| 10 | Europa | 3:30 | 19 s |
| 11 | Ásia | 3:49 | 18 s |
| 12 | Oceania | 4:07 | 19 s |
| 13 | Antártida | 4:26 | 20 s |
| 14 | América do Norte | 4:46 | 17 s |
| 15 | Relevo: Himalaia e Nepal | 5:03 | 26 s |
| 16 | Relevo: Andes e Chile * | 5:29 | 17 s |
| 17 | Floresta Amazônica | 5:46 | 22 s |
| 18 | Deserto do Saara e Nilo | 6:08 | 19 s |
| 19 | Regiões polares: Groenlândia * | 6:27 | 14 s |
| 20 | Geografia: Paris | 6:41 | 17 s |
| 21 | Nova York | 6:58 | 18 s |
| 22 | São Paulo | 7:16 | 17 s |
| 23 | Tóquio | 7:33 | 16 s |
| 24 | Cidades à noite | 7:49 | 21 s |
| 25 | Rede global (simulação) | 8:10 | 19 s |
| 26 | Dubai * | 8:29 | 18 s |
| 27 | Sydney * | 8:47 | 12 s |
| 28 | Modo científico * | 8:59 | 21 s |
| 29 | Final: "Um único planeta. Bilhões de histórias. E possibilidades infinitas." | 9:20 | 34 s |

\* Cenas que não entram na versão curta.
As cenas de clima, oceanos e rede global usam elementos simulados (furacões, correntes, embarcações, tráfego), e a narração avisa isso. Os números dos cartões são aproximados.

## Como assistir
- Abra o site e clique em **▶ INICIAR** (o navegador só libera o som depois de um clique). Use fones de ouvido.
- **Versão curta:** o botão "Versão completa/curta" na barra de baixo, ou `?v=curta` no endereço.
- **Explorar livremente:** `?livre=1` no endereço libera zoom e arrasto da câmera.

## Botões da barra de baixo
| Botão | Função |
|-------|--------|
| ⏸ ⏮ ⏭ e linha do tempo | Pausar, cena anterior, próxima, navegar |
| Seletor de cena | Ir direto a uma cena |
| CC | Liga e desliga as legendas |
| ☰ | Roteiro de narração (com botão Copiar) |
| ⛶ | Tela cheia |
| Versão completa/curta | Alterna as versões |
| ✨ | Vinheta e granulação de filme (desligue se o computador estiver lento) |
| 🎵 e volume | Trilha sonora |
| 📜 | Teleprompter (texto grande para gravar a voz acompanhando o filme) |
| 🔊 | Liga e desliga a voz da narração |
| ⏺ Gravar | Grava o filme completo e baixa o vídeo |

## Como gravar o vídeo
1. Use **Chrome ou Edge no computador**, com o site hospedado (para carregar as texturas) e, se puder, em tela cheia.
2. Feche outras abas e programas pesados, para o vídeo não travar.
3. Clique em **⏺ Gravar**, escolha **esta guia** e marque **"Compartilhar áudio da guia"**.
4. O filme roda do início ao fim, com voz e trilha, e baixa `earth-infinity.mp4` (ou `.webm`). Esc interrompe.
5. Faça antes uma gravação curta de teste para conferir o som.

## Arquivos do projeto
- `index.html`: o filme completo.
- `audio/cena-01.mp3` a `cena-29.mp3`: a narração, uma por cena.
- `texturas/`: pasta opcional para texturas em alta resolução (`dia.jpg`, `noite.jpg`, `relevo.jpg`, `nuvens.jpg`).
- `README.md`: este arquivo.

## Publicar (deploy)
- **Netlify ou Vercel:** conecte o repositório, deixando build command e output vazios. Cada push na `main` publica sozinho.
- **GitHub Pages:** Settings, Pages, branch `main`, pasta `/ (root)`.

## Texturas em alta qualidade (opcional)
Sem os arquivos em `texturas/`, o filme usa as texturas padrão da biblioteca three-globe, e, se a internet falhar, uma Terra gerada por código. Para mais nitidez, baixe, reduza para no máximo 8192 px de largura e coloque em `texturas/` com os nomes exatos:
- Dia (`dia.jpg`): [NASA Blue Marble](https://science.nasa.gov/earth/earth-observatory/blue-marble-next-generation/base-map/)
- Noite (`noite.jpg`): [NASA Black Marble](https://science.nasa.gov/earth/earth-observatory/earth-at-night/maps/)
- Relevo (`relevo.jpg`): [Blue Marble com relevo e batimetria](https://science.nasa.gov/earth/earth-observatory/blue-marble-next-generation/base-topography-bathymetry)
- Nuvens (`nuvens.jpg`, em tons de cinza): [Solar System Scope](https://phet.solarsystemscope.com/textures/) ou [live-cloud-maps](https://github.com/matteason/live-cloud-maps)

Imagens globais em 8K melhoram a visão geral, mas não mostram ruas e prédios quando se aproxima muito.

## Créditos
Imagens: NASA Earth Observatory / Blue Marble (Reto Stöckli). Fronteiras: Natural Earth. Texturas padrão: three-globe. Código, trilha e narração: Vecorion.
