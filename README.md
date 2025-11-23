# Catálogo de Livros

Projeto simples de **catálogo de livros** usando **HTML**, **CSS**, **JavaScript**, **Bootstrap** e **LocalStorage**.

Permite adicionar livros manualmente ou buscar dados automaticamente pela **API da OpenLibrary**, visualizar em cards e filtrar por título, categoria e autor.

---

##  Funcionalidades

- **Adicionar livros** com título, autor, categoria, ano e capa  
- **Buscar automaticamente** pela *OpenLibrary API*  
- Exibir livros em **cards responsivos**  
- **Filtros disponíveis:**  
  -  **Título** (campo de busca)  
  -  **Categoria**  
  -  **Autor**  
- **Excluir livros individualmente**  
- Armazenamento em **LocalStorage** (não precisa backend)

---

##  Tecnologias Utilizadas

- **HTML5**  
- **CSS3 / Bootstrap 5**  
- **JavaScript (ES6)**  
- **OpenLibrary API**

---

##  Estrutura do Projeto

index.html - Catálogo com filtros e lista de livros

adicionarLivro.html - Página para adicionar novos livros

js/catalogo.js - Lógica do catálogo (renderizar, filtrar e excluir)

js/salvarLivro.js - Lógica de adicionar livros e buscar via API

##  Como utilizar

1. Abra o arquivo **index.html**
2. Clique em **“Adicionar Livro”**
3. Preencha os dados manualmente ou clique em **“Buscar”** para usar a OpenLibrary
4. Clique em **Salvar Livro**
5. O novo livro aparecerá no catálogo automaticamente
6. Utilize os filtros ou exclua livros quando quiser

