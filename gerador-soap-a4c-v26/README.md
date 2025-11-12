# Gerador SOAP — Emagrecimento — v26
Endurecimentos e correções:
- Botão **Baixar/Imprimir (2 páginas)** revisado e ligado ao `window.print()` com tratamento de erro e preparação explícita das duas páginas antes de imprimir.
- **Wegovy** agora gera automaticamente linhas **padronizadas com ordinais em pt-BR** (“Na primeira/segunda/terceira/quarta/quinta semana aplicar X cliques”), mantendo formatação estável.
- **Contenteditable** da prévia segue sendo o **fonte único da impressão**; as quebras de linha são preservadas via `textContent` + `white-space: pre-wrap`.
- **Data** nas vias formatada `dd/mm/aaaa`.
