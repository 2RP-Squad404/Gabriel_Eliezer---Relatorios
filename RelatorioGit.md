# Relatório de Estudos

**Nome do Estagiário:** [Gabriel Eliezer Rodrigues]  
**Data:** [05/08/2024]
**Data:** [06/08/2024]
**Data:** [07/08/2024]

## Assuntos Vistos

- [VCS - Version Control System]
- [Fluxo GitFlow]
- [Comandos Git]
- [Historicos de Commit]

## O Que Entendi
Git é um sistema de controle de versões, usado principalmente em projetos onde é necessário o controle de versões. O Git facilita o trabalho de mais de uma pessoa em um mesmo projeto, além de ter diversas funcionalidades, como por exemplo, historicos de commit, onde é possível verificar, quem fez o commit, o que foi alterado de uma versão para outra, fazer merge de um código para outro para atualizar versão. Existe a forma de trabalhar com as branches no qual chamamos de GitFlow, onde temos uma branch main, develop, e as features que são criadas com base na develop... 

## Git

#### O que é?

  Git é um sistema de versionamento de código (SVM), existem diversos SVM sendo o GIT o mais conhecido e utilizado, dentre os SVM podemos citar alguns, git, subversion, mercurial, perforce helix core e bazaar. Cada sistema tem suas caracteristicas, com o Git temos o minitoramento das versões de commit, historico de commits, temos diversos comandos para auxiliar a forma de trabalhar com o GIT, dentre os comandos temos alguns que são interessantes de citar, como, "git diff", que mostra a diferença entre commits, "git commit" que cria um commit com os itens que foram adicionados pelo usuario. Existem diversos comandos que podem nos auxiliar.

 ##### GitHub:

  GitHub é uma plataforma de hospedagem de código-fonte, onde podemos armazenar nossos arquivos para projetos pessoais e trabalhar com o versionamento de código. O GitHub é bastante utilizado para projetos de pequena escala e por estudantes, podendo ser uma forma poderosa de aprender sobre o sistema Git, obter experiência com Versionamento de código e trabalhar com as pessoas em um mesmo projeto. GitHub tem ferramentas que possibilitam verificar como esta o fluxo das branchs desde o inicio do projeto até uma data determinada, é disponibilizado uma ferramenta com diversos recursos para os usuarios terem uma experiência incrível.
 

 #### Funcionalidades do Git:

 1) Histórico: temos acesso ao historico de versões dos códigos que subimos para a plataforma, caso ocorra algum erro é possível retornar uma versão anterior onde esse erro não existia, fazer a correção e subir uma nova versão corrigida.

2) Ramos: no sistema de git podemos trabalhar com os ramos (branchs), além de trbalharmos com as branchs temos o sistema de GitFlow, onde temos uma branch Main, uma develop e criamos as features com base na develop, a develop é uma branch onde sempre deve estar mais atualizada que a main ou igual, isso ocorre pois as atualizações são jogadas na develop e nao diretamente na main. Como funciona o GitFlow? No gitFlow temos a branch main e develop, as features são branchs criadas com base na develop, onde nas features criamos atualizações menores que são commitadas para o repositorio remoto e depois fazemos o merge que é juntar o código de uma feature com a develop. Sempre que criamos uma nova funcionalidade e subimos para a develop devemo excluir a branch em que estavamos trabalhando, o código que esta na branch da develop não pode simplesmente ser colocado na branch main, ele deve ser inserido em uma branch chamada Release que é criado com base na develop e nessa branch release fazemos os testes finais para saber se o codigo da develop está correto, também na branch release é feito os ajustes finais para o código, após terminar o código na release ele é jogado na branch develop e na main, após isso a branch main e develop estão iguais e é só seguir o fluxo do projeto normalmente.

3) Frente de Trabalho: Com o git é possível desenvolver aplicações em paralelo no mesmo projeto, uma pessoa consegue trabalhar em paralelo com outra no mesmo projeto, até mesmo em um arquivo igual.

4) Rastreabilidade: Quando se fala de rastreabilidade, queremos falar sobre tudo que ocorre no projeto, quando fazemos um commit, quando alteramos alguma parte em um código. É possível comparar versões de commits para saber o que elas tem de diferentes entre ambas, também podemos ver o historico de commits, quem fez o commit, quando a pessoa fez o commit, o que foi alterado da versao do commit dela para a anterior entre outros pontos. Cada commit gera um hash unico que é possivel utiizar para identificar o commit.

## Links Utilizados (se houver)

- [Coursera](https://www.coursera.org/learn/introduction-git-github)
- [Udemy](https://www.coursera.org/learn/introduction-git-github)
- [Atlassian](https://www.atlassian.com/br/git/tutorials/what-is-git)

  
## Trilha de Aprendizagem

**Objetivo da Trilha:**  
A trilha utilizada para desenvolver esse relatório foi a de GIT, o conteudo da trilha é bem raso e gerou duvidas que usei como norte para pesquisar sobre git e desenvolver o relatorio. 

**Módulos/Etapas Feitas:**  
1. **[Módulo/Etapa 1]:** Entender o que é Git, Sistemas de versionamento de Código, Git e GitHub.
2. **[Módulo/Etapa 2]:** Comandos Git, gerenciamento de Branch, GitFlow aplicado.

**Recursos Utilizados:**  
- [Coursera]
- [Udemy]
- [Atlassian]


**Desafios Encontrados:**  
Durante o desenvolvimento da trilha assim como as outras trilhas, me surgiram duvidas que consegui responder pesquisando, porém algumas respostas obtidas nem sempre eram esclarecedoras, então busquei outras fontes para desenvolver respostas.

**Feedback e Ajustes:**  
Objetivo da trilha é um campo que não entendi muito como formular um texto relevante e coeso para ser acrescentado em tal campo.

**Próximos Passos:**  
Aprender mais profundamente sobre os SVM e entender quais são mais utilizados no mercado de trabalho.
