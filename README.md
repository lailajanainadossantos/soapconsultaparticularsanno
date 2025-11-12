# Gerador SOAP — Emagrecimento — v15

**Novidades pedidas:**
- Botões **“Adicionar”** ao lado de **Ondansetrona**, **PEG-Lax** e **Item avulso**, que já vão **aparecendo na prévia** e compõem a prescrição final.
- Cabeçalho das vias: **“RECEITA MÉDICA — 1ª via”** e **“RECEITA MÉDICA — 2ª via”**.
- **Ajuste de espaçamento automático**: as vias são flexíveis (min-height ~185mm) e a assinatura fica **sempre alinhada ao rodapé**; o corpo da prescrição cresce para **preencher a página**, evitando “buraco” grande em branco.

**Fluxo:**
1) Monte o medicamento principal (pré-visualizar → **Adicionar principal**).
2) Use os botões **+ Adicionar Ondansetrona**, **+ Adicionar PEG-Lax** e **+ Adicionar** avulsos para compor a receita.
3) **Salvar & Imprimir**: Página 1 (SOAP) | Página 2 (2 vias lado a lado, horizontal).

Se quiser, adiciono um botão “Compactar fonte (10px)” para casos extremos de conteúdo muito longo.
