# DesignAI — Landing Page

Landing page fictícia de um assistente de design com inteligência artificial, desenvolvida como projeto de estudo e portfólio. O projeto explora boas práticas de front-end estático, SEO técnico e design responsivo.

## Visão Geral

A página simula o produto **DesignAI**, apresentando seções de hero, carrossel de logos de parceiros, fluxo de uso em etapas, planos de preço, blog de insights e call-to-action final.

## Tecnologias Utilizadas

- **HTML5** — estrutura semântica com uso de tags como `<header>`, `<main>`, `<section>`, `<footer>` e `<address>`
- **CSS3** — estilização completa sem frameworks, incluindo CSS Grid, Flexbox, animações com `@keyframes` e media queries para responsividade
- **JavaScript** — nenhuma lógica customizada; comportamentos visuais são implementados puramente via CSS
- **Font Awesome 6.6.0** — ícones via CDN
- **Google Fonts (Poppins)** — tipografia via import no CSS

## SEO Técnico

- Meta tags de descrição e Open Graph (`og:title`, `og:description`, `og:image`, `og:url`)
- Tag canônica (`<link rel="canonical">`) para evitar conteúdo duplicado
- Diretiva de indexação via `<meta name="robots" content="index, follow">`
- Dados estruturados com **JSON-LD** seguindo o schema `SoftwareApplication`, incluindo os três planos de preço (`Free`, `Basic`, `Pro`)
- **`robots.txt`** permitindo indexação completa e referenciando o sitemap
- **`sitemap.xml`** com a URL principal, data de última modificação e prioridade definida

## Estrutura do Projeto

```
/
├── index.html
├── robots.txt
├── sitemap.xml
├── css/
│   └── style.css
└── public/
    ├── future.webp
    ├── cta-img.webp
    ├── i-back1.webp
    ├── i-back2.webp
    ├── i-back3.webp
    ├── logo1.png
    ├── logo2.png
    ├── logo3.png
    ├── logo4.png
    ├── logo5.png
    └── logo6.png
```

## Como Executar

1. Clone o repositório:
   ```bash
   git clone https://github.com/seu-usuario/designai-landing.git
   ```

2. Accesse a pasta do projeto:
   ```bash
   cd designai-landing
   ```

3. Abra o arquivo `index.html` diretamente no navegador, ou utilize a extensão **Live Server** no VS Code para melhor experiência de desenvolvimento:
   - Clique com o botão direito em `index.html`
   - Selecione **"Open with Live Server"**

Nenhuma dependência ou instalação adicional é necessária.

## Responsividade

O layout foi desenvolvido com abordagem _desktop-first_ e adapta-se a diferentes tamanhos de tela por meio de breakpoints definidos no CSS:

| Breakpoint | Ajuste principal |
|---|---|
| 1565px | Redução de margens laterais |
| 1085px | Header e steps em coluna única |
| 740px | Planos em coluna única |
| 850px | Insights em coluna única |
| 560px | Paddings reduzidos para mobile |

## Autor

Mateus Hahn — mateushahn333@gmail.com