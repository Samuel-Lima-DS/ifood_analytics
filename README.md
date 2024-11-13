# iFood - Análise de Dados

# 1 - Problema de Negócio

Considere uma empresa bem estabelecida que atua no setor de varejo de alimentos. Atualmente, eles têm cerca de vários milhares de clientes registrados e atendem quase um milhão de consumidores por ano. Eles vendem produtos de 5 grandes categorias: vinhos, carnes, frutas exóticas, peixes especialmente preparados e produtos doces. Estes podem ser divididos ainda mais em produtos de gold e regulares. Os clientes podem encomendar e adquirir produtos por meio de 3 canais de vendas: lojas físicas, catálogos e site da empresa. Globalmente, a empresa teve receitas sólidas e uma linha de fundo saudável nos últimos 3 anos, mas as perspectivas de crescimento dos lucros para os próximos 3 anos não são promissoras... Por esse motivo, várias iniciativas estratégicas estão sendo consideradas para inverter essa situação. Um deles é melhorar o desempenho das atividades de marketing, com foco especial em campanhas de marketing.

# 2 - Premissas de Negócio 
Os dados utilizados foram disponibizado no processo seletivo para Analista de Dados da empresa iFood, onde esta localizado neste link: [link_repositorio](https://github.com/ifood/ifood-data-business-analyst-test)

# 3 - Estratégia de Solução
O objetivo definido junto a equipe de marketing é separar os tipos de clientes com as informações de dados disponivéis , sendo assim podendo tomar decisões mais correta para que tipo de cliente e podendo descobrir o comportamento e caracteristicas de cada grupo(cluster).

# 4 - Insights
![clusters](
    img/clusters.png)

Análise por cluster:

- Cluster 0: 
  - Renda alta 
  - gasto alto 
  - muito provalmente não tem filhos
  - mais propenso a aceitar campanhas
  - cluster sem pessoas com escolaridade básica
  - sem um perfil de idade que se destaque
  

- Cluster 1: 
  - Renda baixa 
  - gasto baixo 
  - provalmente tem filhos
  - baixa propensão a aceitar campanhas
  - único cluster com porcentagem significativa de pessoas com escolaridade básica
  - pessoas mais jovens
  

- Cluster 2: 
  - Renda intermediária
  - gasto intermediário
  - provalmente tem filhos
  - pode aceitar campanhas
  - pessoas com idade mais elevada
 
# 5 - Conclusão
O marketing poderá agir de forma mais acertiva ao entrar em contatos com clientes, pois possue as informações que descrevem os comportamentos e características do grupo que o cliente pertence. 

# 6 - Para reproduzir o projeto

O projeto foi desenvolvido utilizando o Python 3.12.1. Para reproduzir o projeto, crie um ambiente virtual com o Conda, ou ferramenta similar, com o Python 3.12.1 e instale as bibliotecas abaixo:

-------------------- | ----------
      Package        |  Version  
-------------------- | ----------
Imbalanced-Learn     |     0.12.4
Matplotlib           |      3.9.2
NumPy                |      2.1.3
Pandas               |      2.2.3
Scikit-Learn         |      1.5.2
Seaborn              |     0.13.2





