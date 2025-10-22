# Portfolio de Ciência de Dados

Bem-vindo ao meu portfólio de Ciência de Dados!

## Sobre Mim

Olá! Meu nome é **Suelen Regina**, tenho 20 anos e sou graduanda em **Análise e Desenvolvimento de Sistemas**. Tenho me dedicado cada vez mais ao aperfeiçoamento em **Ciência de Dados** e **Inteligência Artificial**, desenvolvendo projetos práticos com o objetivo de construir um portfólio sólido, rico em conteúdo e alinhado com as demandas do mercado. Minha paixão está em áreas como **Machine Learning**, **Estatística**, **Matemática** e **Inteligência Artificial (IA)**, e é nelas que concentro meus estudos e projetos.


<img width="500" height="285" alt="image" src="https://github.com/user-attachments/assets/6b2e4303-2cdc-4a2b-8b61-5798f4672db9" />


---

## Projetos

### 1. **Regressão e Clusterização: Prevendo Crimes em Recife**

[**Link para o repositório**](https://github.com/susuregis/Previs-o_crimes)  

#### Descrição do Projeto

Neste projeto, realizei a previsão de crimes na cidade do Recife, focando no tráfico de drogas. Utilizei tanto **análise supervisionada** (regressão) quanto **não supervisionada** (clusterização), com o objetivo de prever a quantidade de crimes em um determinado mês. A análise foi realizada com base em dados históricos e a previsão foi feita considerando o aumento do tráfico de drogas, especialmente após apreensões significativas.

A **Análise Exploratória de Dados (EDA)** foi feita para identificar padrões entre os dados, seguida pela construção e treinamento dos modelos.

#### Problema do Negócio

Em março de 2025, aproximadamente **R$ 300 mil** em drogas foram apreendidas no **Centro de Tratamento de Encomendas dos Correios em Recife**, o que evidenciou uma nova rota interestadual de tráfico:

- **Rota**: SP → Recife → Interior do Nordeste
- **Método**: Uso de encomendas disfarçadas

A apreensão gerou preocupação nas autoridades, e foi identificado que a polícia necessitava de um modelo preditivo para ajudar a reduzir o tráfico de drogas nos bairros de Recife.

#### Objetivos

- Identificar **insights** a partir dos dados.
- Criar um **modelo preditivo** eficaz para ajudar na redução do tráfico de drogas.
- Fornecer **dicas e recomendações** para a polícia sobre como agir de forma mais eficiente.

#### Resultados

O modelo obteve uma boa performance, com os seguintes resultados:

- **Random Forest**:
  - **MAE (Erro Absoluto Médio)**: 0.23
  - **R²**: 88% (Explicação da variabilidade dos dados)
  - **Conclusão**: O modelo teve um bom desempenho e conseguiu prever com precisão os resultados, explicando 88% da variabilidade nos dados.

- **HistGradientBoostingRegressor**:
  - **MAE**: 0.29
  - **R²**: 86%
  - **Conclusão**: Embora o **Random Forest** tenha tido um desempenho ligeiramente melhor, o **HistGradientBoostingRegressor** teve uma performance muito boa, com uma explicação da variabilidade em 86%.

- **K-means Clustering**:
  - Foram criados **4 clusters** para segmentar os dados e ajudar a entender melhor as zonas de risco. O modelo K-means também apresentou uma boa performance.

#### Visualizações

![Imagem 1](https://github.com/user-attachments/assets/6c394632-b77a-48eb-bd6e-95f9eeffb905)

*Gráfico de Análise e Previsão de Crimes em Recife.*

![Imagem 2](https://github.com/user-attachments/assets/294b8566-8ccd-428e-beff-e5c19a1a6120)

*Modelo de Previsão de Crimes.*

![Imagem 3](https://github.com/user-attachments/assets/fc95cbdf-1fce-4b24-8be5-7102a9c1e721)

*Análise de Clustering com K-means.*

---

## Link para o Repositório

[**Clique aqui para acessar o projeto completo no GitHub**](https://github.com/susuregis/Previs-o_crimes) 

---

## Tecnologias Usadas

- **Python**
- **Pandas** (para manipulação de dados)
- **Scikit-learn** (para treinamento e avaliação de modelos)
- **Matplotlib** e **Seaborn** (para visualizações)
- **HistGradientBoostingRegressor** (para regressão)
- **RandomForestRegressor** (para regressão)
- **K-means** (para clustering)

---


Agradeço pela visita ao meu portfólio! :)
