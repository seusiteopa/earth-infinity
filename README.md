# EARTH INFINITY — Vecorion

Filme em código (HTML único, Three.js): Terra dentro do arco direito do símbolo do infinito girando em 3D, zoom por continentes, países, cidades, noite, Lua, oceanos e relevo. Com linha do tempo, legendas e roteiro de narração (botão ☰).

## Arquivos
- `index.html` — o filme completo (abre direto no navegador)
- `texturas/` — pasta opcional para texturas da NASA (`dia.jpg`, `noite.jpg`, `nuvens.jpg`, `relevo.jpg`)
- `README.md` — este arquivo

## Publicar no GitHub
1. Crie um repositório novo (ex.: `earth-infinity`).
2. Envie `index.html`, `README.md` e a pasta `texturas/` (com as imagens, se baixar).
3. Settings → Pages → Branch `main` / pasta `/ (root)` → Save.
4. O link fica em `https://SEU-USUARIO.github.io/earth-infinity/`.
(Também funciona no Netlify: arraste a pasta.)

## Trilha sonora, teleprompter e gravação
Tudo é gerado por código, sem arquivos de áudio. Os botões ficam na barra de baixo.
- **🎵** liga a trilha (pad orquestral, baixo, arpejo, whoosh a cada cena, impacto nos títulos e clímax no final). O controle ao lado ajusta o volume.
- **📜 Teleprompter**: mostra o texto da cena em letras grandes, com a palavra atual destacada e a contagem de segundos. Serve para você gravar a sua voz acompanhando o filme. Some sozinho durante a gravação do vídeo.
- **🔊** narração por voz do navegador (opcional, só para teste).
- **⏺ Gravar**: use Chrome ou Edge no computador, com o site hospedado. Selecione **esta guia** e marque **"Compartilhar áudio da guia"**. O filme roda do início ao fim e baixa `earth-infinity.mp4` (ou `.webm`). Esc interrompe.

## Texturas (opcional, para mais qualidade)
- NASA Blue Marble (dia): https://science.nasa.gov/earth/earth-observatory/blue-marble-next-generation/base-map/
- NASA Blue Marble com relevo e batimetria: https://science.nasa.gov/earth/earth-observatory/blue-marble-next-generation/base-topography-bathymetry
- NASA Black Marble (noite): https://science.nasa.gov/earth/earth-observatory/earth-at-night/maps/
- Solar System Scope (dia, noite, nuvens, relevo 8K): https://phet.solarsystemscope.com/textures/
- Nuvens atualizadas: https://github.com/matteason/live-cloud-maps

Baixe o JPG de 5400x2700 (ou reduza para até 8192 px), renomeie e coloque em `texturas/`.

## Créditos
Imagens: NASA Earth Observatory / Blue Marble (Reto Stöckli). Fronteiras: Natural Earth. Texturas padrão: three-globe.
