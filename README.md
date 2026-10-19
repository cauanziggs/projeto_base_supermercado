# Projeto M13 - Estatística descritiva e visualização (Supermercado)

Análise de uma base de produtos de supermercado do Chile.

## Conteúdo
- `Projeto_M13_Estatistica_Supermercado.ipynb`: código completo, resultados e interpretações
- `MODULO7_PROJETOFINAL_BASE_SUPERMERCADO.csv`: base de dados (separador vírgula)
- `graficos/`: boxplot, barras e mapa (PNG) + mapa interativo (HTML)

## O que foi feito
1. Média, mediana e desvio padrão de `Preco_Normal` por categoria
2. Boxplot e outliers (regra do IQR) da categoria com maior desvio padrão (`lacteos`)
3. Média de desconto por categoria (barras)
4. Mapa interativo (treemap) categoria > marca com média de desconto

Observação: `Preco_Normal = 0` foi tratado como dado ausente nas estatísticas de preço.

## Como executar
```
pip install -r requirements.txt
jupyter notebook Projeto_M13_Estatistica_Supermercado.ipynb
```
