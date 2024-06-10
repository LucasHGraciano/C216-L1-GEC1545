# Sistema CRUD Bibliotecário

# Descrição
Este projeto é uma aplicação CRUD (Create, Read, Update, Delete) para a gestão de um sistema bibliotecário. A aplicação permite que os usuários realizem operações básicas em um banco de dados de livros, categorias e autores.

# Funcionalidades
- Adicionar novos registros: Permite adicionar novos livros, categorias e autores ao sistema.
- Consultar registros existentes: Permite visualizar os registros existentes no banco de dados.
- Atualizar registros: Permite modificar informações de livros, categorias e autores.
- Deletar registros: Permite remover livros, categorias e autores do sistema.

# Tecnologias Utilizadas
- Frontend > HTML
- Backend > Node.js com Express
- Banco de Dados > PostgreSQL
- Gerenciamento de Dependências > npm (Node Package Manager)
- Contêinerização > Docker / Docker Compose

# Endpoints Principais
- POST /inserir: Adiciona um novo livro, categoria e autor.
- GET /listar: Retorna a lista de todos os livros juntamente com sua categoria e autor. Também possibilita executar alguma ação (excluir ou atualizar).
- POST /excluir: Exclui um livro juntamente com sua categoria e autor.
- POST /atualizar/id: Atualiza alguma das informações do livro (nomem, categoria ou autor).
- DEL /reset: Deleta a lista dos livros (reseta o banco de dados).

# Exemplo de Uso
- Execute o docker-compose
  
docker-compose up --build
