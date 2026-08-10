VoxPDF PWA

Como testar localmente em um computador:
1. Entre nesta pasta.
2. Rode um servidor HTTP simples, por exemplo: python3 -m http.server 8080
3. Abra http://localhost:8080

Para usar no iPhone sem Mac, hospede esta pasta em um serviço HTTPS estático (GitHub Pages, Netlify, Cloudflare Pages etc.).
Depois, no Safari do iPhone:
1. Abra o endereço HTTPS do VoxPDF.
2. Toque em Compartilhar.
3. Toque em Adicionar à Tela de Início.
4. Abra o VoxPDF pelo ícone criado.

Observações:
- PDFs normais com camada de texto funcionam melhor.
- PDFs escaneados como imagem precisarão de OCR em uma futura versão.
- O Safari/iOS pode interromper síntese de voz em segundo plano ou com a tela bloqueada.
