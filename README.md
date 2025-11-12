# Gerador SOAP — Emagrecimento — v13

**Novidade: seleção de medicações para a página 2 (duas vias lado a lado)**

- Caixa de seleção para **incluir/excluir**:
  - ✅ Medicamento principal (Wegovy/Mounjaro) — gere pela máscara e clique **Adicionar principal**
  - ✅ **Ondansetrona 8 mg** (padrão)
  - ✅ **Polietilenoglicol 4000 (PEG-Lax)** (padrão)
- Campo para **adicionar item avulso** (texto livre). Você pode adicionar vários; aparece uma lista com botões de **remover**.
- Ao clicar **Salvar & Imprimir (2 páginas)**:
  - **Página 1:** SOAP puro.
  - **Página 2:** duas vias lado a lado com logo + Paciente + Data + **somente os itens selecionados** (na ordem: principal → ondansetrona → PEG-Lax → itens avulsos).

Mantém:
- IMC automático; campos #Comorbidade / #Alergias / #MUC; seções #S / #O / #P.
- Layout de via dobrada lado a lado, com fonte ≈11px e **assinatura centralizada** em cada via.

Sugestões futuras:
- Botão “compactar fonte” (10 px) caso a prescrição fique longa.
- Campo para número de **CRM digital** ou QR code opcional.
