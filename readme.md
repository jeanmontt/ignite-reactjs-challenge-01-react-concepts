<h1 align="center">
    <img alt="Ignite Reactjs" src="https://repository-images.githubusercontent.com/348025176/0ecc0000-858f-11eb-8a3c-ec496221cfd6" width="600px" />
    <br>
    Ignite - Desafio 01 - Conceitos do React
</h1>

# 🗒️ Sobre

Nesse desafio, foi entregue um template e solicitado que fosse adicionadas algumas funcionalidades para treinar o que foi aprendido até agora no ReactJS.

Essa é uma pequena aplicação de atividades a fazer, para treinar um pouco mais sobre manipulação do estado no React.

- Adicionar uma nova tarefa
- Remover uma tarefa
- Marcar e desmarcar uma tarefa como concluída

<br>

# 🎯 Objetivo

Adicionar funcionalidades para as três funções presentes no arquivo TaskList.tsx, que são:

- **handleCreateNewTask**: Deve ser possível adicionar uma nova task no estado de `tasks`, com os campos `id` que deve ser gerado de forma aleatória, `title` que deve ser um texto e `isComplete` que deve iniciar como false.
- **handleToggleTaskCompletion:** Deve alterar o status de `isComplete` para uma task com um ID específico que é recebido por parâmetro.
- **handleRemoveTask:** Deve receber um ID por parâmetro e remover a task que contém esse ID do estado.

Todas as funcionalidades deveriam passar nos testes.

<br>

# 💾 4 - Como baixar/testar o projeto

- Você irá precisar instalar o [Git](https://git-scm.com/), [NodeJS](https://www.notion.so/Instalando-o-Node-js-d40fdabe8f0a491eb33b85da93d90a2f) + [Yarn](https://www.notion.so/Instalando-o-Yarn-eca6a13be5b3467d8d2f7be15c60f322):

```bash
# Versões mínimas ou superiores.
$ node -v
v14.17.1

$ yarn -v
1.22.4
```

- Para configurar, no bash digite os seguinte códigos:

```bash
# Clonar o repositório
$ git clone https://github.com/jeanmontt/ignite-reactjs-challenge-01-react-concepts.git

#Entrar no diretório
$ cd ignite-reactjs-challenge-01-react-concepts

#Instalar as dependências
$ yarn

#Utilizar o teste no terminal
$ yarn test

#Após finalizar o teste aperte digite "q" para sair
$ q

#Iniciar o local host
$ yarn dev
```
- Por último abra seu navegador e digite:

```
localhost:8080
```

<br>

#### Desenvolvido por:

***Jean Monteiro*** 
<br/> 
<a href="https://www.linkedin.com/in/jeanmont/">
<img src="https://github.com/jeanmontt/NLW-1.0/blob/master/public/assets/linkedin.png?raw=true">
</a>