# FinFlow 6.2 — Assistente financeiro local

Versão de teste para GitHub Pages. Tudo permanece no `localStorage`.

## Assistente
O botão **Falar com o FinFlow** entende comandos naturais em português e registra diretamente nas categorias de Receitas ou Despesas.

Exemplos:
- `recebi 500,00 de uma venda` → Receita / Vendas / R$ 500,00
- `recebi 1500 de freelance` → Receita / Freelance / R$ 1.500,00
- `paguei 300 da conta de energia` → Despesa / Contas / R$ 300,00
- `gastei 1.500,00 no mercado` → Despesa / Alimentação / R$ 1.500,00
- `minha internet é 99,90 todo mês` → Recorrência mensal
- `comprei em 12x de 100` → Dívida inteligente de 12 parcelas

## Valores
O interpretador foi reforçado para o padrão brasileiro:
- `1500` → R$ 1.500,00
- `1.500` → R$ 1.500,00
- `1.500,00` → R$ 1.500,00
- `500,00` → R$ 500,00
- `R$ 1.500,00` → R$ 1.500,00

O número de parcelas em frases como `12x de 100` não é confundido com o valor da operação.

## Observação
Esta interpretação é local e determinística nesta fase. Quando o FinFlow ganhar backend/IA real, o mesmo fluxo poderá ser expandido para intenções mais complexas, mantendo confirmação antes de ações ambíguas.
