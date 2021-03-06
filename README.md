# ignite-template-reactjs-conceitos-do-react

## Desafio - Conceitos do React

Esse repositório foi desenvolvido com base no curso de ReactJS Ignite - Rocketseat <br>

![Ignite](./public/ignite-react.jpg 'Curso em Video') <br>
# 💻 Sobre o desafio
Nesse desafio, você deverá criar uma aplicação para treinar o que aprendeu até agora no ReactJS

Essa será uma aplicação onde o seu principal objetivo é uma pequena aplicação de atividades a fazer, para treinar um pouco mais sobre manipulação do estado no React.

- Adicionar uma nova tarefa
- Remover uma tarefa
- Marcar e desmarcar uma tarefa como concluída

A seguir veremos com mais detalhes o que e como precisa ser feito 🚀
## Template da aplicação

Para realizar esse desafio, criamos para você esse modelo que você deve utilizar como um template do GitHub.

O template está disponível na seguinte URL:
[Rocketseat Education](https://github.com/rocketseat-education/ignite-template-reactjs-conceitos-do-react) 

## O que devo editar na aplicação?

Com o template já clonado, as depêndencias instaladas, você deve completar onde não possui código com o código para atingir os objetivos de cada teste. Nesse desafio, você deve editar apenas o seguinte arquivo para completar as funcionalidades da aplicação:

- [src/components/TaskList.tsx;](https://github.com/rocketseat-education/ignite-template-reactjs-conceitos-do-react/blob/main/src/components/TaskList.tsx)

### components/TaskList.tsx

Esse é o componente responsável por todas as funcionalidades da aplicação, é um componente simples, mas onde botaremos em prática várias partes da manipulação do estado.

Você deve criar as funcionalidades para as três funções presentes nesse arquivo, que são:

- **handleCreateNewTask**: Deve ser possível adicionar uma nova task no estado de `tasks`, com os campos `id` que deve ser gerado de forma aleatória,
    `title` que deve ser um texto e `isComplete` que deve iniciar como false.
- **handleToggleTaskCompletion:** Deve alterar o status de `isComplete` para uma task com um ID específico que é recebido por parâmetro.
- **handleRemoveTask:** Deve receber um ID por parâmetro e remover a task que contém esse ID do estado.

## Especificação dos testes
Em cada teste, tem uma breve descrição no que sua aplicação deve cumprir para que o teste passe. 
Para esse desafio, temos os seguintes testes:
### Teste TaskList.spec.tsx

- **should be able to add a task**

Para que esse teste passe, você deve permitir que task seja criada e com isso, exibida em tela. As taks criadas devem conter os atributos seguindo o padrão da interface, que é:
  interface Task {
    id: number;
    title: string;
    isComplete: boolean;
  }
  
 - **should not be able to add a task with an empty title**

Para que esse teste passe, antes de criar uma nova task, você deve validar se algo foi digitado no input e não permitir a criação da task caso o valor seja vazio,
caso o valor digitado seja vazio, você deve impedir a criação da task.

- **should be able to remove a task**

Para que esse teste passe, você deve permitir que ao clicar no botão com ícone de uma lixeira, a task relacionada a esse botão seja removida do estado da aplicação, 
consequentemente sendo removida da tela.

- **should be able to remove a task**

Para que esse teste passe, você deve permitir que ao clicar no botão com ícone de uma lixeira, a task relacionada a esse botão seja removida do estado da aplicação,
consequentemente sendo removida da tela.

---
### 🛠 Tecnologias

As seguintes ferramentas foram usadas no desafio do projeto:

- [React](https://reactjs.org/)
- [Typescript](https://www.typescriptlang.org/docs/handbook/react.html)
- [Sass](https://sass-lang.com/)



 <img src="https://img.shields.io/static/v1?label=DEV&message=Darcisio Almeida&color=7159c1&style=for-the-badge&logo=ghost"/>
