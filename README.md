📚 Catálogo de Livros

Projeto simples de catálogo de livros usando HTML, CSS, JavaScript, Bootstrap e LocalStorage.

Permite adicionar livros manualmente ou buscar pela API da OpenLibrary, visualizar em cards e filtrar por título, categoria e autor.

🚀 Funcionalidades

Adicionar livros com título, autor, categoria, ano e capa

Buscar dados automaticamente via OpenLibrary API

Exibir livros em cards responsivos

Filtrar por:

Título (campo de busca)

Categoria

Autor

Excluir livros individualmente

Armazenamento em LocalStorage (não precisa backend)

🛠️ Tecnologias

HTML5

CSS3 / Bootstrap 5

JavaScript (ES6)

OpenLibrary API

📁 Estrutura
index.html               # Catálogo com filtros e lista
adicionarLivro.html      # Página para adicionar livros
js/catalogo.js           # Lógica do catálogo
js/salvarLivro.js        # Lógica de adicionar e buscar livros

💾 Armazenamento

Todos os livros são guardados em:

localStorage.setItem("livros", JSON.stringify(livros));


E recuperados ao carregar a página.

▶️ Como usar

Abra o index.html

Clique em Adicionar Livro

Cadastre manualmente ou clique em “Buscar”

Salve

Os livros aparecerão no catálogo

Use os filtros ou exclua quando quiser
