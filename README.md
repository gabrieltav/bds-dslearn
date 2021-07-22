# bds-dslearn


## Visão Geral Do Sistema DSLearn

O sistema consiste em uma plataforma de ensino que mantém informações de cursos, suas turmas e alunos, bem como um fórum para perguntas e respostas sobre os conteúdos do curso. Os atores do sistema podem ser alunos e professores. Há também usuários administradores, que são os únicos autorizados a cadastrar cursos e turmas.

Um curso é composto de vários “recursos”, que são grupos de conteúdos. Estes recursos podem ser trilhas de aprendizado, bônus, links externos, e o próprio fórum de perguntas e respostas do curso. Cada recurso pode conter seções, e estas seções por sua vez é que vão conter as aulas, que podem ser conteúdos em vídeo e/ou texto, ou tarefas para serem entregues pelos alunos.

Uma tarefa pode ter um peso, uma data de entrega, um número de questões e a quantidade mínima de acertos necessários para ser aceita. Quando um aluno entrega a tarefa, esta fica aguardando pelo feedback do professor, e ela pode ser aceita ou rejeitada.

Cada nova turma do curso corresponde a uma oferta ou edição deste curso, que possui uma data de início e fim. Diferentes ofertas do mesmo curso podem ter pequenas variações no conteúdo, conforme a necessidade de customização para cada turma.

Os usuários (alunos e professores) devem receber notificações.

Com relação ao fórum de perguntas e respostas, este consiste em uma coleção de tópicos (com um título e a descrição da pergunta), e cada tópico pode ter várias respostas. Os requisitos gerais do fórum são:
- Listar tópicos, com as seguintes opções de filtro:
   - Por recurso/seção/aula
   - Por texto (título e/ou corpo do tópico)
   - Perguntas feitas apenas pelo usuário logado
- Criar tópico: título, corpo
- Responder tópico
- Marcar/desmarcar upvote em pergunta (não pode ser o autor)
- Marcar/desmarcar upvote em resposta (não pode ser o autor)
- Marcar/desmarcar melhor resposta (somente autor do tópico e instrutor)

<br>

## Diagramas

### Modelo conceitual sem forum
![modelo-conceitual-antes-do-forum](https://user-images.githubusercontent.com/82974806/126565421-715be246-55f3-4d2e-b78a-d75a159bfbd2.png)
<br>
### Modelo conceitual com forum
![modelo-conceitual-com-forum](https://user-images.githubusercontent.com/82974806/126565003-db0645de-666a-4c8c-936d-39b9ad054e97.png)

<br>

<h4 align="center"> 
 🚧 Sistema em Desenvolvimento 🚧
</h4>

<br>

### Pré-requisitos

Antes de começar, você vai precisar ter instalado em sua máquina as seguintes ferramentas:
[Git](https://git-scm.com), [Java jdk](https://www.oracle.com/br/java/technologies/javase/javase-jdk8-downloads.html), [Postman](https://www.postman.com/downloads/).
Além disto é bom ter um editor para trabalhar com o código como [Spring Tools](https://spring.io/tools) ou outro de sua preferência.



## 🚀 Tecnologias

Esse projeto está sendo desenvolvido com as seguintes tecnologias:

- [Java jdk](https://www.oracle.com/br/java/technologies/javase/javase-jdk8-downloads.html)
- [Spring Boot](https://spring.io/projects/spring-boot)


## 🔖 Layout

Você pode visualizar o layout do projeto através [desse link](https://www.figma.com/file/p8Hawp1w5g0pCZ3h3ZsCUd/DSLearn-Bootcamp). Lembrando que você precisa ter uma conta no [Figma](http://figma.com/) para acessá-lo.

## Collection Postman

Você pode destar as requisições atraves da [collection](https://www.getpostman.com/collections/b156d5adf224f89f6ca3).

<br>

### Autor

<div>
  <a href="https://github.com/gabrieltav">
  <img style="border-radius: 50%;" src="https://github.com/gabrieltav.png" width="100px;" alt=""/>
  <br />
  <sub><b>Gabriel Tavares.</b></sub></a>
</div>
