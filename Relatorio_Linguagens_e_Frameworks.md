# Relatório de Estudos

**Nome do Estagiário:** [Gabriel Eliezer Rodrigues]  
**Data:** [19/08/2024]
**Data:** [20/08/2024]


## Assuntos Vistos
- [Python]
- [Apache Spark]
- [Apache Beam]
- [Apache Airflow]
- [Google Dataflow]

## O Que Entendi
Cada ferramenta tem suas funcionalidades, uma complementando a outra ou podendo trabalhar de forma paralela com a outra, o Spark, é uma ferramenta que suporta diversas linguagens de programação. O spark é desenvolvido em scala, então o suporte para scala é maior do que outras linguagens, é possível encontrar recursos mais otimizados em scala. Quando se fala PySpark, se refere a uma API que permite utilizar o Spark com a linguagem Python. 


## Apache Spark

É uma ferramenta poderosa para analise de grandes quantidades de dados. Ele é um sistema unificado, isso significa que ele trata dados em batch e em streaming dentro de uma mesma estrutura de código. O Spark é uma das principais plataformas de computação distribuida para processamento de grandes quantidades de dados. A grande velocidade de processamento do Spark acontece pois em vez da ferramenta ler os dados do disco, ele tenta manter os dados em memoria ram, isso reduz drasticamente o tempo de processamento comparado com outras ferramentas como o Hadoop MapReduce.

Com o Spark, é possível analisar as fontes de dados, processar as informações, criar analises e entregar essas informações para o BI, criando assim os insights para as empresas. 

#### Exemplo de Uso do Spark:

- Spotify: com o uso do spark é possível descobrir as musicas que estão mais sendo escutadas na semana ou quando você precisar.


## Apache Beam
O ApacheBeam é um framework para criação de pipelines de dados, tanto para dados em lote quanto streaming. Ele é considerado um framework unificado sendo possivel trabalhar com o mesmo programa para dados em batch e em streaming. É possivel criar e utilizar diferentes SDK's para a criação das pipelines, também te permite uma portabilidade simples para executar em diferentes ambientes.

## Google Dataflow
O Dataflow é um serviço de processamento de dados em streaming ou batch, o provisionamento, gerenciamento e escalonamento dos recursos necessarios para processar os dados são feitos automaticamente, as pipelines são feitas utilizando o apache beam SDK. Para criar pipelines que rodam no dataflow é necessário o uso do apache beam.

Vantagens de utilizar o Dataflow:
- Configuração rápida e simplificada das pipelines.
- Redução de custo com emprego otimizado de workers.
- Processamento sem servidor. <!--Processamento sem servidor significa que o Cluster é criado automaticamente e destruido automaticamente de acordo com o que for preciso de processamento-->

É possivel criar Dataflow jobs usando o Cloud Console UI, gCloud CLI ou APIs.

## Apache Airflow

O Apache Airflow, é uma ferramenta open source, seu principal objetivo é orquestrar pipelines de tarefas agendadas por meio de um arquivo python com instruções sequenciais definidas, essa ferramenta foi criada para monitorar, agendar e criar os fluxos de trabalho (workflows).

Existem 4 principios que o Airflow são definidos:

- Dinâmico: As pipelines são criadas de forma dinamica usando código python, o que permite gerar fluxos de trabalho de forma programatica
  
- Extensível: O Airflow é altamente modular, podendo atender diversas necessidades específicas.

- Elegante: O Código da pipeline deve ser facil de entender e seguir.

- Escalável: O Airflow pode ser dimensionado para lidar com grandes volumes de dados e complexidade.

Esses principios garantem que a ferramenta seja poderosa, flexivel e confiavel para automação e orquestração de pipelines em ambientes variados.

## Links Utilizados (se houver)
- [Apache Airflow](https://innowise.com/pt/blog/apache-airflow-introduction/)
- [Google Dataflow](https://www.youtube.com/watch?v=b0v0XzHZrVU) 
- [Apache Spark](https://www.youtube.com/watch?v=b0v0XzHZrVU)
- [Apache Beam](https://www.youtube.com/watch?v=Z981TlbknHY)


**Recursos Utilizados:**  
- ChatGPT 
- Youtube
- Udemy
  


**Desafios Encontrados:**  
São conteudos extensos para estudar tudo, porém deu para entender por cima o que cada ferramenta faz. Seria interessante pesquisar mais sobre cada uma individualmente.

**Próximos Passos:**  
Acredito que o correto seria estudar mais tempo cada uma das ferramentas de forma mais aprofundada e prática.