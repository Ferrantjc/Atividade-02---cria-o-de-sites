# Projeto UC3 - Criação de Sites

## 🎯 Objetivo
Desenvolver um site com três páginas distintas, aplicando conceitos de **HTML** e **CSS**, explorando as diferenças entre **CSS Flexbox** e **CSS Grid**.

---

## 📂 Estrutura do Projeto
- **index.html** → Página inicial com navegação para as três seções.
- **filmes.html** → Lista de 10 filmes recomendados (usando **Flexbox**).
- **livros.html** → Lista de 10 livros recomendados (usando **Grid**).
- **musica.html** → Lista de 10 cantores/bandas (usando combinação de Flexbox + Grid).
- **css/** → Pasta com estilos separados para cada página.
- **img/** → Pasta com imagens organizadas em subpastas:
  - `/img/filmes/`
  - `/img/livros/`
  - `/img/musica/`

---

## 🎨 Estilização
- Cada página possui **identidade visual própria**:
  - **Filmes:** fundo escuro, estilo moderno, cards com hover.
  - **Livros:** fundo claro, fonte serifada, estilo literário.
  - **Música:** cores suaves, layout dinâmico.

---

## 🧩 Diferenças entre Flexbox e Grid

### Flexbox
- **Unidimensional**: organiza elementos em linha **ou** coluna.
- Ideal para menus, listas horizontais/verticais, barras de navegação.
- Exemplo aplicado:
  ```css
  .lista-filmes {
    display: flex;
    flex-wrap: wrap;
    justify-content: center;
    gap: 15px;
  }
