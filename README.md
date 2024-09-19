# Projeto: Lista de Tarefas em React Native

## Descrição do Projeto

Este projeto consiste em uma aplicação de **lista de tarefas (To-Do List)** desenvolvida utilizando **React Native**. O objetivo da aplicação é permitir que os usuários gerenciem suas tarefas diárias de maneira simples e eficiente. O usuário pode adicionar, editar, marcar como concluída e excluir tarefas, oferecendo um controle intuitivo sobre seus afazeres.

## Funcionalidades

- **Adicionar tarefa**: O usuário pode adicionar uma nova tarefa com um título.
- **Listar tarefas**: Exibe uma lista de todas as tarefas adicionadas.
- **Marcar como concluída**: O usuário pode marcar uma tarefa como concluída, alterando o status visual da mesma.
- **Editar tarefa**: O usuário pode editar o título de uma tarefa existente.
- **Excluir tarefa**: O usuário pode remover uma tarefa da lista.
- **Persistência de dados**: As tarefas são armazenadas localmente, mantendo-se disponíveis mesmo após fechar e reabrir o aplicativo.
  
## Tecnologias Utilizadas

- **React Native**: Framework principal para desenvolvimento do aplicativo móvel.
- **Expo**: Plataforma utilizada para facilitar o desenvolvimento e execução do app em múltiplos dispositivos.
- **AsyncStorage**: Utilizado para armazenar as tarefas no dispositivo local, garantindo a persistência dos dados.
- **Hooks do React (useState, useEffect)**: Para gerenciamento do estado e ciclos de vida da aplicação.
  
## Componentes Principais

1. **TodoList**: Componente que exibe a lista de tarefas.
2. **TodoItem**: Cada item individual da lista, mostrando a tarefa, com opções para marcar como concluída, editar ou excluir.
3. **AddTodo**: Componente responsável por adicionar novas tarefas.
4. **EditTodo**: Tela/modal para edição de uma tarefa existente.

## Desafios

- **Persistência de dados**: Implementar o armazenamento local com **AsyncStorage** foi um ponto importante para garantir que o usuário não perdesse suas tarefas ao fechar o aplicativo.
- **Experiência do Usuário**: Tornar o fluxo de interação simples e intuitivo, especialmente no gerenciamento de tarefas, garantindo que ações como adicionar, editar ou excluir sejam claras.

## Melhorias Futuras

- **Integração com banco de dados remoto**: Possibilitar o backup das tarefas na nuvem.
- **Categorias e prioridades**: Permitir que o usuário categorize as tarefas e defina níveis de prioridade.
- **Notificações**: Implementar lembretes para as tarefas.
- **Modo escuro**: Adicionar suporte a temas escuros e claros, dependendo da preferência do usuário.

Este projeto é uma excelente introdução ao desenvolvimento de aplicações móveis com **React Native**, focando na interação com o usuário e manipulação de dados locais.