# Sistema de Empréstimo de Livros

Este é um sistema simples de gerenciamento de livros, que permite cadastrar, consultar, emprestar, devolver e remover livros. O sistema armazena informações sobre os livros e clientes, além de gerenciar a quantidade de exemplares disponíveis para empréstimo.

## Funcionalidades

1. **Cadastro de Livros**: Permite adicionar um novo livro ao sistema, garantindo que o ID do livro seja único, que o ano de publicação seja válido e que a quantidade de exemplares não exceda 10 unidades.
2. **Consulta de Livros**: Permite consultar livros cadastrados, seja listando todos os livros ou pesquisando por ID ou título.
3. **Empréstimo de Livros**: Permite que um cliente faça o empréstimo de um livro, desde que haja exemplares disponíveis e que o cliente ainda não tenha o livro emprestado.
4. **Devolução de Livros**: Permite que um cliente devolva um livro emprestado.
5. **Remoção de Livros**: Permite remover um livro do sistema, liberando o espaço para novos cadastros.

## Funções

### Cadastro de Livro
- Permite cadastrar um livro com informações como título, autor, número de páginas, ano de publicação e quantidade de exemplares.
- Verifica se o ID do livro já foi cadastrado e se o ano de publicação e a quantidade de exemplares são válidos.

### Consulta de Livros
- Permite listar todos os livros cadastrados ou pesquisar livros por ID ou título.

### Empréstimo de Livro
- Permite emprestar um livro para um cliente, verificando se o livro está disponível e se o cliente não tem o livro emprestado.

### Devolução de Livro
- Permite devolver um livro emprestado, atualizando a quantidade de exemplares disponíveis.

### Remoção de Livro
- Permite remover um livro do sistema, atualizando a lista de livros cadastrados.


## Exemplo de Uso

1. **Cadastrar um Livro**
   - O usuário informa o ID, título, autor, número de páginas, ano de publicação e quantidade de exemplares.
   
2. **Consultar Livros**
   - O usuário pode escolher entre listar todos os livros ou pesquisar por ID ou título.
   
3. **Empréstimo de Livro**
   - O usuário informa o ID do livro que deseja emprestar e os dados do cliente.
   
4. **Devolução de Livro**
   - O usuário informa o ID do livro e o ID do cliente que está devolvendo o livro.
   
5. **Remoção de Livro**
   - O usuário informa o ID do livro que deseja remover do sistema.

