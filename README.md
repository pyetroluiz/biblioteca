
API de Biblioteca
gerenciar livros com autenticação e permissões.

Tambem tem uma collection nos arquivos para teste

Rotas

Público
POST /auth/register – Cadastrar usuário
Protegidas (Basic Auth)
GET /books – Listar todos os livros
GET /books/:id – Ver detalhes de um livro
POST /books/:id/borrow – Pegar livro emprestado
POST /books/:id/return – Devolver livro

Apenas Admin
POST /books – Criar livro
PATCH /books/:id – Editar livro
DELETE /books/:id – Deletar livro

Como rodar

npm install
npx prisma migrate dev 
npm run dev
