# Gerador SOAP — Emagrecimento — v27
**Correção definitiva do print e das linhas do Wegovy**

- Botão **Baixar/Imprimir (2 páginas)** agora:
  - Preenche SOAP (pág. 1) e as **duas vias** (pág. 2);
  - **Espera o layout renderizar** (duplo `requestAnimationFrame` + delay) antes de chamar `window.print()`;
  - Garante **page break** entre as páginas via `.break-after`.

- Prévia da prescrição usa **textContent** (não `innerText`) para estabilidade de quebras de linha.
- Wegovy gera automaticamente as linhas com **ordinais pt-BR** (“Na primeira/segunda/…”).
- Data das vias no formato **dd/mm/aaaa**.

Como salvar em PDF:
1) Clique **Baixar/Imprimir (2 páginas)**.
2) Na janela do navegador, escolha **Salvar como PDF**.
