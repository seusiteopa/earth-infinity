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

## Gravar o vídeo (com voz)
Use **Chrome ou Edge no computador**, com o site hospedado (para carregar as texturas).
1. Abra o site e espere carregar. Se puder, deixe a janela em tela cheia (F11).
2. Escolha a voz no seletor (prefira "Google português do Brasil" ou uma voz "Natural").
3. Clique em **⏺ Gravar**. Na janela do navegador, selecione **esta guia** e marque **"Compartilhar áudio da guia"**.
4. O filme roda do início ao fim sozinho, narrando cada cena. A cena espera a voz terminar antes de passar para a próxima.
5. No final, o arquivo `earth-infinity.mp4` (ou `.webm`) é baixado automaticamente. Esc interrompe a gravação.

O botão 🔊 liga a narração sem gravar, para testar a voz. A voz é gerada pelo navegador (Web Speech API), então muda conforme o sistema.

## Texturas (opcional, para mais qualidade)
- NASA Blue Marble (dia): https://science.nasa.gov/earth/earth-observatory/blue-marble-next-generation/base-map/
- NASA Blue Marble com relevo e batimetria: https://science.nasa.gov/earth/earth-observatory/blue-marble-next-generation/base-topography-bathymetry
- NASA Black Marble (noite): https://science.nasa.gov/earth/earth-observatory/earth-at-night/maps/
- Solar System Scope (dia, noite, nuvens, relevo 8K): https://phet.solarsystemscope.com/textures/
- Nuvens atualizadas: https://github.com/matteason/live-cloud-maps

Baixe o JPG de 5400x2700 (ou reduza para até 8192 px), renomeie e coloque em `texturas/`.

## Créditos
Imagens: NASA Earth Observatory / Blue Marble (Reto Stöckli). Fronteiras: Natural Earth. Texturas padrão: three-globe.
