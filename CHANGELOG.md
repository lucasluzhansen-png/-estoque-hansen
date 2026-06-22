# Changelog - Estoque Hansen

## [2026-06-22] v1.3 - Melhorias de uso pessoal
- Adicionado: Backup/Restore via JSON (botoes no topo)
- Adicionado: Custo editavel direto na tabela de estoque
- Adicionado: Card "Gasto/mes" calculado a partir do historico de compras
- Adicionado: Botao "Registrar entrada" direto na tabela principal (antes só na aba Compras)

## [2026-06-22] v1.2 - Dados reais de mercado
- Atualizado: 22 itens da lista de compras com precos pesquisados (Dental Cremer, Surya Dental, Implafarma)
- Confirmado: precos de implantes Intraoss linha Conico batem com mercado
- Ajustado: Analogo Munhao Universal (R$12 -> R$26,40), Mini Pilar Singular (R$165,90 -> R$169,99)

## [2026-06-18] v1.1 - Catalogo expandido
- Adicionado: 65 produtos do PDF "Materiais Protese Dentaria" (Instituto Prime)
- Corrigido: bug de sintaxe que zerava o estoque (regex sed mal aplicado)

## [2026-06-17] v1.0 - Lancamento inicial
- 265 produtos cadastrados (3 planilhas de origem)
- Controle de estoque minimo/ideal, status automatico
- Lista de compras automatica
- Lixeira com restaurar/excluir definitivo
- Historico de entradas por produto
- Export CSV (estoque, compras, historico)
- Cotacao via Cloudflare Worker (requer API key)
