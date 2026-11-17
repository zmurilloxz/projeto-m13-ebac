# Projeto M13 - Fundamentos da Descoberta de Dados (EBAC)

Análise de produtos de um supermercado do Chile com estatística descritiva e visualizações.

## O que foi feito
- Média, mediana e desvio padrão de `Preco_Normal` por categoria
- Boxplot e outliers da categoria com maior desvio padrão (`lacteos`)
- Gráfico de barras com a média de desconto por categoria
- Mapa interativo (treemap) por categoria e marca com a média de desconto

## Decisões
- O CSV usa vírgula como separador.
- Produtos com `Preco_Normal = 0` (em promoção, sem preço normal) foram excluídos dos cálculos de preço.
- A média de desconto considera todos os produtos (0 = sem desconto).

## Arquivos
- `Profissao_Cientista_de_Dados_M13_Projeto.ipynb`: notebook com código, resultados e interpretações
- `MODULO7_PROJETOFINAL_BASE_SUPERMERCADO.csv`: base de dados
- `graficos/`: imagens (PNG) e mapa interativo (HTML)

Bibliotecas: pandas, matplotlib, plotly.
