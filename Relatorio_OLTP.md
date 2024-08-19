# Relatório de Estudos

**Nome do Estagiário:** [Gabriel Eliezer Rodrigues]  
**Data:** [14/08/2024]

**Módulos/Etapas Feitas:**  
1. **[OLTP]**
2. **[Conceito]**
3. **[Ferramentas]**

## Resumo dos módulos 

Cada um dos módulos aborda um aspecto do processamento de transações online (OLTP). OLTP é o processo que permite obter informações em tempo real sobre o que está acontecendo em uma transação, sendo especialmente importante em transações financeiras, como em caixas eletrônicos. OLTP é um tipo de processo que pode integrar diversas ferramentas com o objetivo de gerenciar e analisar transações em tempo real.

#### O que é OLTP?
Online transaction processing, é o processo onde ocorre a transferencia de grandes quantidades de dados com uma grande quantidade de pessoas. O Acesso ao banco de dados permite que várias pessoas peguem as mesmas informações. Em um sistema OLTP os dados são Indexados, isso permite consultas mais rápidas, melhor eficiencia em lidar com dados simultaneamente. O uso de index gera maior consistencia garantindo que as operações sejam executadas corretamente. Apesar dos indices tornar mais rápido as consultas, a construção dos index acaba tomando um tempo maior pois eles precisam ser atualizados a cada vez que os dados são modificados.

## Caracteristicas OLTP
- Alta Frequência de Transações
- Baixa Latência
- Atomicidade   <!-- Cada transação ou é Completamente Efetuada ou é Completamente Revertida, Não tem como perder dinheiro-->
- Consistência dos Dados
- Usuários Concomitantes
- Dados Relacionais
  

  ## OLAP e OLTP

  Muitas organizações usam o sistema OLTP para fornecer dados ao OLAP, é importantes entendermos a diferença entre os dois, OLAP é focado para analisar os dados e OLTP nas transações. O sistema OLTP fornece dados que são transformados em CUBOS pelo sistema OLAP assim facilitando para os analistas e engenheiros de dados trabalharem com os mesmos.

## Ferramentas OLAP
   1) Microsoft SQL Server Analysis Services
   2) Oracle OLAP
   3) IBM Cognos
   4) Tableau

## Ferramentas OLTP
1) MySQL
2) PostgreSQL
3) Microsoft SQL Server
4) Oracle Database
5) IBM Db2

**Recursos Utilizados:**  
- [Youtube](https://www.youtube.com/watch?v=iw-5kFzIdgY&t=164s)
- [IBM](https://www.ibm.com/br-pt/topics/oltp#:~:text=O%20que%20é%20OLTP%3F&text=IBM,outros%20no%20dia%20a%20dia.)



**Desafios Encontrados:**  
Enteneder como funciona a integração do sistema OLAP com OLTP é um passo importante porém não é tão simples. Entender as ferramentas que podem ser usadas nos processos de ETL para pegar dados OLTP e transformalos em OLAP é importante e complexo. Porém não é impossível de entender.


**Próximos Passos:**  
Acredito que os próximos passos seriam aprofundar mais nas ferramentas de ETL e entender melhor os conceitos de OLAP e OLTP aplicados em um sistema real.