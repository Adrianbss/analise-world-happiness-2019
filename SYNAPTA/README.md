# Análise de Dados — World Happiness Report 2019

**Projeto desenvolvido para o desafio SYNAPTA 2026.**

## 1. Sobre o projeto

Este projeto tem como objetivo analisar os dados do World Happiness Report 2019, investigando a relação entre a pontuação de felicidade dos países e indicadores econômicos e sociais.

## 2. Objetivo

Identificar padrões nos dados e compreender quais indicadores apresentam maior associação com a pontuação de felicidade dos países.

## 3. Tecnologias utilizadas

- Python
- Pandas
- Matplotlib
- Seaborn
- Google Colab

## 4. Base de dados

O conjunto de dados utilizado contém informações de 156 países e 9 variáveis relacionadas à felicidade, economia e condições sociais.

Arquivo utilizado: `2019.csv`.

## 5. Análises realizadas

- Análise exploratória dos dados.
- Verificação de valores ausentes e duplicados.
- Cálculo de média e mediana.
- Identificação dos países com maiores e menores pontuações.
- Análise de correlação entre os indicadores.
- Criação de gráficos e matriz de correlação.

## 6. Principais resultados

As correlações com a pontuação de felicidade foram:

| Indicador | Correlação |
|---|---:|
| PIB per capita | 0,7939 |
| Apoio social | 0,7771 |
| Expectativa de vida saudável | 0,7799 |
| Generosidade | 0,0758 |

Os resultados indicam associações positivas entre a pontuação de felicidade e os três primeiros indicadores analisados.

A generosidade apresentou uma correlação linear muito fraca.

**Observação:** correlação não significa causalidade.

## 7. Conclusão

A análise identificou relações positivas fortes entre a pontuação de felicidade e indicadores como PIB per capita, apoio social e expectativa de vida saudável.

Os resultados permitem compreender melhor as associações entre fatores econômicos, sociais e a pontuação de felicidade dos países.

## 8. Limitações

- Os dados correspondem ao ano de 2019.
- A análise considera somente as variáveis disponíveis na base.
- Correlação não comprova relação de causa e efeito.
- Os resultados não representam necessariamente a situação atual dos países.

## 9. Como executar o projeto

1. Baixe ou clone este repositório.
2. Instale as bibliotecas necessárias.
3. Abra o notebook no Google Colab ou Jupyter Notebook.
4. Disponibilize o arquivo `2019.csv`.
5. Execute as células na ordem apresentada.

## 10. Autor

- **Nome:** Adrian Breno Dos Santos Silva
- **Curso:** Ciência da Computação
- **Instituição:** UNINASSAU
- **Período:** 2º Período