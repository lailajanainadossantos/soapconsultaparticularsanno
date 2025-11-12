# Gerador SOAP — Emagrecimento — v9

**Novo:** Ao salvar/imprimir, é gerada **apenas uma via única** contendo:
1) **SOAP completo** no topo (no formato que você exemplificou)
2) **Prescrição** abaixo (uma única via), preenchida pela máscara

Para a prescrição:
- Wegovy → multiplicadores editáveis (ex.: 1,1,2,2,4)
- Mounjaro → nº de doses editável (ex.: 4)

Fluxo:
1) Preencha o SOAP
2) Monte a prescrição na máscara → **Calcular / Gerar texto** → **Adicionar à prescrição**
3) Clique **Salvar & Imprimir (via única SOAP + via única Prescrição)**
