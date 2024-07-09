# Nome do Projeto

Descrição do projeto + imagem ilustrativa se possivel.

## CRCs

**Cartão CRC para a classe "Livro"**

**Class (Classe):** Livro

**Responsibility (Responsabilidades):**
1. Armazenar informações sobre o livro (título, autor, ISBN, etc.).
2. Manter o estado do livro (disponível, emprestado, reservado).
3. Gerenciar operações básicas do livro (emprestar, devolver, reservar).

**Collaborators (Colaboradores):**
1. Usuário - para pegar o livro emprestado e devolver.
2. Biblioteca - para verificar a disponibilidade e atualizar o estado.
3. Reservas - para gerenciar as reservas dos livros.

---

**Cartão CRC para a classe "Usuário"**

**Class (Classe):** Usuário

**Responsibility (Responsabilidades):**
1. Armazenar informações do usuário (nome, ID, informações de contato).
2. Gerenciar listas de livros emprestados e reservados pelo usuário.
3. Realizar operações de empréstimo e devolução de livros.

**Collaborators (Colaboradores):**
1. Livro - para emprestar e devolver.
2. Biblioteca - para atualizar o status do empréstimo e verificar penalidades.
3. Notificações - para alertar o usuário sobre datas de devolução e reservas disponíveis.

---

**Cartão CRC para a classe "Biblioteca"**

**Class (Classe):** Biblioteca

**Responsibility (Responsabilidades):**
1. Gerenciar o catálogo de livros.
2. Coordenar os empréstimos e devoluções de livros.
3. Gerenciar o estado dos livros e os usuários cadastrados.

**Collaborators (Colaboradores):**
1. Livro - para atualizar o estado dos livros.
2. Usuário - para registrar e gerenciar usuários.
3. Sistema de Notificações - para enviar alertas sobre devoluções e reservas.

## Referências
