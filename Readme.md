📝 Task Manager API
Este projeto é uma API para gerenciamento de tarefas, construída com Node.js e MongoDB. Ela suporta a criação, leitura, atualização e exclusão de tarefas, além de uma funcionalidade para marcar/desmarcar tarefas como concluídas.

🎯 Funcionalidades
Listar todas as tarefas 📋

Visualize uma lista completa de tarefas disponíveis.
Adicionar uma nova tarefa ➕

Crie tarefas com mensagens personalizadas para sucesso ou falha.
Atualizar uma tarefa existente 🔄

Modifique o conteúdo de uma tarefa específica.
Excluir uma tarefa 🗑️

Remova permanentemente uma tarefa da lista.
Marcar tarefas como concluídas ✅

Marque ou desmarque tarefas concluídas com apenas um clique.
🔧 Endpoints Principais
Listar Tarefas

GET /
Retorna a lista de todas as tarefas.
Criar Tarefa

POST /tasks
Adiciona uma nova tarefa.
Buscar Tarefa por ID

GET /tasks/:id/:method
Recupera uma tarefa específica para atualização ou exclusão.
Atualizar Tarefa

PUT /tasks/:id
Atualiza os dados de uma tarefa.
Excluir Tarefa

DELETE /tasks/:id
Remove uma tarefa da base de dados.
Alterar Status da Tarefa

POST /tasks/check/:id
Alterna entre concluído e não concluído.
🛠️ Tecnologias Utilizadas
Node.js 🚀: Framework backend rápido e escalável.
Express 🌐: Estrutura para construção de APIs robustas.
MongoDB 🗄️: Banco de dados NoSQL para persistência de dados.
Mongoose 🛢️: ODM para manipulação de dados MongoDB.

🖊️ Notas sobre o desenvolvimento
Parte do código deste projeto foi reutilizado de um conteúdo criado por CodeThi Thiago Lima, especialmente para criar as instâncias e funcionalidades do case apresentado no desafio. Essa abordagem foi fundamental para agilizar o desenvolvimento e alinhar com os requisitos esperados.
