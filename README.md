🚀 Funcionalidades
✅ Cadastro de Tarefas
Permite criar novas tarefas com título e descrição.

✅ Integração com MySQL
Todos os dados são armazenados e gerenciados via banco de dados MySQL.

✅ Interface Responsiva
Layout em HTML + CSS que se adapta bem a diferentes dispositivos.

✅ Controle de Status
Marque tarefas como pendentes ou concluídas facilmente.

✅ Atualização e Remoção
Edite ou exclua tarefas conforme sua necessidade.

✅ Feedback Visual em Tempo Real
Alertas para ações como "tarefa adicionada" ou "removida com sucesso".

-----------------------------------------------------------
🛠️ Tecnologias Utilizadas
Node.js – Ambiente de execução JavaScript no servidor

Express – Framework web rápido e minimalista

Sequelize – ORM para abstração e manipulação do banco de dados

MySQL – Banco de dados relacional para armazenamento persistente

HTML + CSS – Interface limpa, responsiva e sem frameworks pesados


--------------------------------------------------------------
📸 Captura de tela
![Captura de tela 2025-06-24 215311](https://github.com/user-attachments/assets/aedc68b8-6106-42a6-a589-028032d32fee)

---------------------------------------------------------------
📥 Clone o repositório com git clone https://github.com/seu-usuario/seu-repositorio.git e entre na pasta do projeto com cd seu-repositorio.

📦 Instale as dependências do projeto executando npm install no terminal.

🛠️ Configure o banco de dados MySQL. Crie um banco (ex: tarefas_db) e ajuste as credenciais no arquivo .env ou config/config.json, incluindo informações como DB_HOST, DB_USER, DB_PASSWORD e DB_NAME.

🧱 Caso esteja utilizando Sequelize CLI, rode as migrações com npx sequelize db:migrate para criar as tabelas no banco de dados.

🚀 Inicie o servidor com node backend/server.js.

🌐 Após isso, abra seu navegador e acesse a aplicação em: http://localhost:3000


--------------------------------------------------------------------------------------------------------------------------
📚 Aprendizados
Durante o desenvolvimento, foram aplicados diversos conceitos importantes:

🔄 Migração de SQLite para MySQL

🔗 Relacionamento entre modelos com Sequelize

🌐 Criação de rotas RESTful com Express

🖥️ Desenvolvimento de UI responsiva com HTML + CSS

🧩 Separação de responsabilidades entre camadas (MVC)

🔍 Boas práticas de organização de código e estrutura de pastas
