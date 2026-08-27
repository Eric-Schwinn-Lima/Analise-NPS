# Análise de NPS (Net Promoter Score)

[![Python](https://img.shields.io/badge/Python-3.14-3776AB?style=for-the-badge&logo=python&logoColor=white)](https://www.python.org/)
[![Pandas](https://img.shields.io/badge/Pandas-150458?style=for-the-badge&logo=pandas&logoColor=white)](https://pandas.pydata.org/)

## Integrante

Eric Schwinn Lima


## Sobre o Projeto

O Índice de NPS, é uma das métricas mais importantes para avaliar a satisfação, experiência e a lealdade dos clientes em relação a um produto, serviço ou a empresa. 

O objetivo deste projeto é processar e analisar dados de pesquisas de satisfação de clientes, categorizando as avaliações, calculando a pontuação geral e segmentada do NPS e gerando *insights* estratégicos para a tomada de decisão no negócio.

---

## Como o NPS é Calculado?

Os clientes respondem à pergunta: *"Em uma escala de 0 a 10, o quanto você recomendaria nossa empresa a um amigo ou colega?"*

- **Promotores (Notas 9 e 10):** Clientes altamente satisfeitos e leais e que possuem potencial de promover a marca.
- **Neutros (Notas 7 e 8):** Clientes satisfeitos, porém vulneráveis à concorrência.
- **Detratores (Notas 0 a 6):** Clientes insatisfeitos que podem prejudicar a imagem da marca.

---

## Funcionalidades e Análises

- [x] **Tratamento e Limpeza de Dados:** Remoção de duplicatas e tratamento de valores ausentes.
- [x] **Cálculo de NPS:** Determinação do NPS Geral e por categoria/departamento/produto.
- [x] **Segmentação de Clientes:** Distribuição percentual entre Promotores, Neutros e Detratores.
- [x] **Visualização de Dados:** Gráficos intuitivos para identificação rápida de tendências e áreas de melhoria.
- [x] **Relatório de Insights:** Identificação das principais causas de insatisfação entre os Detratores.

---

## Tecnologias Utilizadas

- **Linguagem:** Python 3.14
- **Manipulação de Dados:** `pandas`, `numpy`
- **Visualização de Dados:** `matplotlib`, `seaborn`
- **Ambiente de Desenvolvimento:** VS Code / Jupyter Notebook

---

## Estrutura do Repositório

- Pasta 	                    Descrição
- data/	                    Base de dados utilizada no projeto.
- docs/	                    README e documentação.
- notebooks/	                Notebook utilizado no projeto.
- reports/figures/	        Gráficos e visualizações gerados.
- reports/apresentacao/	    Apresentação em slides do projeto.


## Notebooks do Projeto

- Notebook	                Descrição
- NPS - EDA.ipynb	            Apresenta a EDA do projeto com todas análises e insights.
