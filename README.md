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

## Versão curta e acabamento
- **Versão completa / curta**: o botão na barra de baixo alterna. A curta (`?v=curta` no endereço) tem 23 cenas e cerca de 6:45, em vez de 29 cenas e 10:13. Ela tira Clima, o segundo Relevo (Andes), Regiões polares, Dubai, Sydney e Modo científico, e ajusta a duração de cada cena ao tamanho da narração.
- **✨ Efeitos de cinema**: vinheta e granulação de filme. Desligue se o computador estiver lento.
- **Cartões**: "VECORION APRESENTA" na abertura e as três frases finais, com os créditos das imagens, no encerramento.
- **Cartões de dados**: números aproximados e conhecidos aparecem no canto direito em cada cena (área dos continentes, altura do Everest, população das cidades etc.).
- Os títulos das cenas entram com animação de desfoque e espaçamento.

## Novidades da versão dinâmica
- **Câmera travada**: o público não consegue dar zoom nem arrastar (nem o zoom do navegador). Para explorar livremente, abra com `?livre=1` no endereço.
- **Câmera viva**: balanço leve, "respiração" de distância, inclinação sutil, órbita extra em cada cena e curvas de movimento diferentes. Nas cenas com batida, a câmera dá um pequeno pulso a cada kick.
- **Trilha eletrônica** (124 BPM): cada cena tem uma energia. Há cenas calmas, outras com groove (deep house) e picos com baixo em semicolcheias. Antes de cada pico entra um build-up com riser e rufo de caixa, e o drop cai no início da cena seguinte. O pad "pulsa" junto com o kick (sidechain).
- **Narração nova**: texto conversado, com perguntas e respostas ("Você sabia?"). A pergunta também aparece na tela no momento em que é feita. A duração de cada cena se ajusta ao tamanho da fala.

## Texturas (opcional, para mais qualidade)
- NASA Blue Marble (dia): https://science.nasa.gov/earth/earth-observatory/blue-marble-next-generation/base-map/
- NASA Blue Marble com relevo e batimetria: https://science.nasa.gov/earth/earth-observatory/blue-marble-next-generation/base-topography-bathymetry
- NASA Black Marble (noite): https://science.nasa.gov/earth/earth-observatory/earth-at-night/maps/
- Solar System Scope (dia, noite, nuvens, relevo 8K): https://phet.solarsystemscope.com/textures/
- Nuvens atualizadas: https://github.com/matteason/live-cloud-maps

Baixe o JPG de 5400x2700 (ou reduza para até 8192 px), renomeie e coloque em `texturas/`.

## Créditos
Imagens: NASA Earth Observatory / Blue Marble (Reto Stöckli). Fronteiras: Natural Earth. Texturas padrão: three-globe.
