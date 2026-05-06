# 🖥️ Tecboard — HTML, CSS: Ambiente, Estrutura e Estilo

Landing page do **Tecboard App**, um aplicativo fictício de monitoramento de sistemas em tempo real. Projeto desenvolvido para praticar estruturação semântica de HTML, estilização com CSS e boas práticas de SEO.

## 📸 Preview

A página exibe:
- Logo do Tecboard no cabeçalho
- Título principal com destaque em roxo
- Parágrafo descritivo e botão de CTA
- Imagem do app em dispositivos móveis

## 🎯 Objetivos do Projeto

- Estruturar uma landing page semântica com HTML5
- Aplicar fontes customizadas via `@font-face` (Unbounded e Poppins)
- Criar layout responsivo com Media Queries (desktop, tablet e mobile)
- Configurar meta tags de SEO e compartilhamento social via Open Graph
- Registrar o site no Google Search Console

## 🛠️ Tecnologias

- HTML5
- CSS3
- Fontes locais: `Unbounded-Bold.ttf` e `Poppins-Regular.ttf`

## 📁 Estrutura de Arquivos

```
HTML-E-CSS-ambiente-estrutura-e-estilo/
├── index.html
├── styles/
│   └── styles.css
├── assets/
│   ├── celulares-sobrepostos-desktop.png
│   ├── celulares-sobrepostos-mobile.png
│   ├── logo-techboard-branco.png
│   ├── modo-branco.png
│   └── modo-escuro.png
└── fonts/
    ├── Poppins-Regular.ttf
    └── Unbounded-Bold.ttf
```

## 📱 Responsividade

O layout se adapta a três breakpoints:

| Breakpoint | Comportamento |
|---|---|
| Desktop (`> 768px`) | Layout padrão com imagens e texto centralizados |
| Tablet (`≤ 768px`) | Ajuste de margens e largura do parágrafo |
| Mobile (`≤ 375px`) | Tamanhos de fonte e imagem reduzidos para caber na tela |

## 🔍 SEO

As seguintes meta tags foram configuradas para otimização em buscadores e redes sociais:

```html
<meta name="description" content="...">
<meta name="og:title" content="Tecboard App">
<meta name="og:description" content="...">
<meta name="og:image" content="...">
<meta name="og:type" content="website">
<meta name="og:url" content="...">
<meta name="google-site-verification" content="...">
```

## 🚀 Como Executar

Abra o arquivo `index.html` diretamente no navegador ou use o **Live Server** no VS Code.
