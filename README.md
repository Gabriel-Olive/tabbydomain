# Tab Volume by Domain (Chrome Extension)

Extensão simples para controlar o volume por domínio e lembrar a preferência automaticamente.

Funcionalidades
- Ajusta o volume de elementos `<audio>` e `<video>` com base no domínio.
- Lembra o volume por domínio (armazenamento `chrome.storage.sync`).
- Slider no popup para ajustar e salvar o volume.
- Detecta mudanças de volume na página e salva automaticamente.

Instalação (modo desenvolvedor)
1. Abra `chrome://extensions/` no Chrome.
2. Ative o "Modo do desenvolvedor" no canto superior direito.
3. Clique em "Carregar sem compactação" e escolha a pasta do projeto (`c:\Users\Gabriel\python_projetos\chrome_extension`).

Observações
- Nem todos os sites usam elementos HTML `<video>`/`<audio>` diretamente (alguns usam WebAudio). Para esses casos a extensão pode não controlar todos os fluxos.
- Ajustes futuros: suporte a domínios com TLDs complexos, UI por-aba e persistência local/offline.
