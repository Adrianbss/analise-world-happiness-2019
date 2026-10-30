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

### 4.1 Descrição das colunas

A base de dados contém nove variáveis:

| Coluna | Significado |
|---|---|
| Overall rank | Posição do país no ranking de felicidade. |
| Country or region | Nome do país ou região. |
| Score | Pontuação de felicidade atribuída ao país. |
| GDP per capita | Indicador relacionado à produção econômica por pessoa. |
| Social support | Indicador de apoio social. |
| Healthy life expectancy | Expectativa de vida saudável. |
| Freedom to make life choices | Percepção de liberdade para tomar decisões na vida. |
| Generosity | Indicador relacionado à generosidade. |
| Perceptions of corruption | Percepção sobre a corrupção. |

## Fonte dos dados

A base de dados utilizada neste projeto foi obtida no Kaggle, no conjunto **World Happiness Report**.

- **Fonte:** [World Happiness Report — Kaggle](https://www.kaggle.com/datasets/unsdsn/world-happiness?select=2019.csv)
- **Arquivo utilizado:** `2019.csv`
- **Ano analisado:** 2019

Para obter os dados, acesse o link, faça o download do conjunto de dados e utilize o arquivo `2019.csv`.

O arquivo deve estar disponível na mesma pasta do notebook para que a análise seja executada corretamente.

A utilização e a distribuição dos dados devem respeitar a licença e as condições informadas na página do Kaggle.

## 5. Limpeza e preparação dos dados

Inicialmente, foi realizada uma análise da estrutura do conjunto de dados utilizando a biblioteca Pandas.

Foram identificados:

- 156 registros, correspondentes aos países e regiões analisados.
- 9 colunas com informações econômicas e sociais.
- Nenhum valor ausente.
- Nenhum registro duplicado.

Também foram verificados os tipos de dados de cada coluna.

Como não foram identificados valores ausentes ou duplicados, não foi necessário remover registros. Os dados foram mantidos para a realização das análises estatísticas e visualizações.

## 6. Análises realizadas

- Análise exploratória dos dados.
- Verificação de valores ausentes e duplicados.
- Cálculo de média e mediana.
- Identificação dos países com maiores e menores pontuações.
- Análise de correlação entre os indicadores.
- Criação de gráficos e matriz de correlação.

## 7. Principais resultados

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

## 8. Conclusão

A análise identificou relações positivas fortes entre a pontuação de felicidade e indicadores como PIB per capita, apoio social e expectativa de vida saudável.

Os resultados permitem compreender melhor as associações entre fatores econômicos, sociais e a pontuação de felicidade dos países.

## 9. Limitações

- Os dados correspondem ao ano de 2019.
- A análise considera somente as variáveis disponíveis na base.
- Correlação não comprova relação de causa e efeito.
- Os resultados não representam necessariamente a situação atual dos países.

## 10. Como executar o projeto

1. Baixe ou clone este repositório.
2. Instale as bibliotecas necessárias.
3. Abra o notebook no Google Colab ou Jupyter Notebook.
4. Disponibilize o arquivo `2019.csv`.
5. Execute as células na ordem apresentada.

## 11. Autor

- **Nome:** Adrian Breno Dos Santos Silva
- **Curso:** Ciência da Computação
- **Instituição:** UNINASSAU
- **Período:** 2º Período