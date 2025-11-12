# Gerador SOAP — Emagrecimento — v28
**Preservação de linhas em branco na impressão**

- A prévia (contenteditable) é lida como **HTML**, convertida com segurança para **texto plano** (div/br → \n, &nbsp; → espaço), e depois **escapada** e **reconvertida para `<br>`** ao imprimir. Isso mantém os **espaços entre medicações** exatamente como digitados.
- Removido `.trim()` para não apagar linhas em branco internas.
- Impressão em 2 páginas (SOAP + 2 vias), data dd/mm/aaaa, botões de compactar/expandir fonte.

Como salvar em PDF: clique **Baixar/Imprimir (2 páginas)** e selecione **Salvar como PDF**.
