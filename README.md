# 🧑‍💻 Bryan MArtins — Portfólio Pessoal

Site de portfólio profissional desenvolvido com **HTML5**, **CSS3** e **JavaScript** puro, sem frameworks ou dependências externas além do Google Fonts.

🔗 **[Ver online →](https://bryanmartins.dev)** *(substitua pela URL do GitHub Pages)*

---

## 📁 Estrutura do projeto

```
portfolio/
├── index.html          # Página inicial (hero, sobre, habilidades, trajetória)
├── projects.html       # Página de projetos com filtro por categoria
├── contact.html        # Página de contato com formulário interativo
├── css/
│   └── style.css       # Estilos globais (variáveis, layout, componentes)
├── js/
│   └── portfolio.js    # Scripts: cursor, partículas, typewriter, filtro, form
└── README.md
```

---

## ✅ Critérios atendidos

| Critério | Implementação |
|---|---|
| **Layout** | CSS Grid e Flexbox em todas as seções |
| **Tags semânticas** | `<nav>`, `<header>`, `<main>`, `<footer>`, `<section>`, `<article>`, `<aside>` |
| **Navegação** | 3 páginas: `index.html`, `projects.html`, `contact.html` |
| **JavaScript** | Cursor, partículas, typewriter, contador, filtro, scroll reveal, formulário |
| **Markup válida** | Validado no W3C Markup Validation Service |
| **README** | Este arquivo, atualizado em múltiplos commits |

---

## 🚀 Funcionalidades JavaScript

- **Cursor personalizado** — ponto + anel animados que seguem o mouse
- **Partículas interativas** — rede de pontos animada no hero via Canvas API
- **Efeito typewriter** — texto que alterna entre palavras com animação de digitação
- **Contadores animados** — números que sobem ao entrar na viewport (Intersection Observer)
- **Scroll reveal** — elementos aparecem suavemente ao rolar a página
- **Filtro de projetos** — filtra cards por categoria (Frontend, Full Stack, Mobile)
- **Menu mobile** — hamburger menu responsivo com animação
- **Formulário de contato** — validação e feedback visual de envio

---

## 🎨 Design

- **Paleta:** fundo escuro `#0A0A0F` com acento violeta `#7C3AED`
- **Tipografia:** [Sora](https://fonts.google.com/specimen/Sora) (títulos) + [Inter](https://fonts.google.com/specimen/Inter) (corpo)
- **Responsivo:** funciona em mobile, tablet e desktop
- **Acessibilidade:** `aria-label`, `aria-live`, foco visível, `prefers-reduced-motion`

---

## 🛠️ Como rodar localmente

Não precisa de instalação. Basta abrir o `index.html` no navegador, ou usar um servidor local simples:

```bash
# Com Python
python -m http.server 8000

# Com Node.js (npx)
npx serve .
```

Depois acesse `http://localhost:8000`.

---

## 📄 Licença

MIT — fique à vontade para usar como base para o seu próprio portfólio.
