# AEVUM ONE — Landing Page Premium

> **"O tempo é seu. Use-o com distinção."**

Uma landing page de e-commerce de alto padrão para o smartwatch de luxo fictício **AEVUM ONE**, construída com HTML5, CSS3 e JavaScript Vanilla puro em um único arquivo `index.html`.

---

## 🎯 Objetivo

Apresentar e vender o AEVUM ONE — um smartwatch de luxo de edição limitada — com foco máximo em conversão, sofisticação visual e autoridade de marca. Inspirado na estética de Apple, Rolex e Tesla.

---

## ✅ Funcionalidades Implementadas

### Design & UX
- [x] **Cursor personalizado** com ponto dourado e círculo seguidor com efeito lag
- [x] **Barra de progresso de scroll** dourada no topo
- [x] **Sticky header** transparente que muda para escuro ao rolar
- [x] **Menu mobile** hamburguer com overlay full-screen
- [x] **Smooth scroll** entre seções via links de âncora
- [x] **Animações de entrada** (fade-in, fade-left, fade-right) ativadas por IntersectionObserver
- [x] **Delays escalonados** nas animações para efeito cascata
- [x] **Parallax sutil** no visual hero ao rolar
- [x] **Botão "voltar ao topo"** que aparece após scroll
- [x] **Scrollbar customizada** dourada

### Seções da Página
- [x] **Hero Section** — headline impactante, badge de edição limitada, watch SVG animado com orbits decorativas e efeito float
- [x] **Storytelling** — história emocional da marca com layout imagem + texto
- [x] **Produto** — galeria com 3 variantes (Midnight Black, Champagne Gold, Arctic Silver), seletor de cores interativo, preço e CTAs
- [x] **Features** — 6 cards com ícones SVG, estatísticas e hover effects
- [x] **Vídeo Demonstrativo** — placeholder elegante com botão play animado e grid decorativo
- [x] **Provas Sociais** — 4 depoimentos, counters de estatísticas, logos de mídia (Forbes, GQ, Vogue, etc.)
- [x] **Comparação Premium** — tabela 10 linhas vs smartwatches comuns
- [x] **Exclusividade** — countdown timer persistente (localStorage), contador de unidades restantes, 3 cards de materiais premium
- [x] **FAQ** — 6 perguntas com accordion animado
- [x] **CTA Final** — fundo escuro, urgência, botão grande, microcopy com 4 garantias
- [x] **Footer** — 4 colunas, redes sociais, links legais

### Interatividade JavaScript
- [x] **Countdown timer** com data persistente em localStorage
- [x] **Contador de unidades** que decresce aleatoriamente ao longo do tempo
- [x] **Notificações de compra** popup que aparecem periodicamente simulando outros compradores
- [x] **Seletor de variantes** sincronizado entre thumbnails e botões de cor
- [x] **Feedback visual no botão** "Adicionar ao Carrinho"
- [x] **Animação de contadores numéricos** nas estatísticas ao entrar em viewport

---

## 📁 Estrutura do Projeto

```
index.html          ← Página completa (tudo em um arquivo)
README.md           ← Esta documentação
```

---

## 🗺️ URIs / Âncoras da Página

| Seção | Âncora |
|---|---|
| Hero | `#hero` |
| Storytelling | `#story` |
| Produto | `#product` |
| Features | `#features` |
| Vídeo | `#video` |
| Provas Sociais | `#social-proof` |
| Comparação | `#comparison` |
| Exclusividade | `#exclusivity` |
| FAQ | `#faq` |
| CTA Final | `#cta-final` |

---

## 🎨 Design System

| Token | Valor |
|---|---|
| Background principal | `#FAFAF8` |
| Background escuro | `#0E0E0C` |
| Texto primário | `#1A1A1A` |
| Dourado | `#C9A84C` |
| Dourado claro | `#E8C97A` |
| Bege | `#F5F0E8` |
| Cinza | `#8A8A8A` |
| Fonte serif | Playfair Display |
| Fonte sans | DM Sans / Inter |

---

## 🛍️ Produto

| Campo | Valor |
|---|---|
| Nome | AEVUM ONE |
| Slogan | "O tempo é seu. Use-o com distinção." |
| Preço | R$ 4.997 |
| Parcelamento | 12x de R$ 416,41 |
| Edição | Limitada — 500 unidades |
| Variantes | Midnight Black · Champagne Gold · Arctic Silver |

---

## 📦 Próximas Etapas Recomendadas

- [ ] **Integrar vídeo real** substituindo o placeholder `.video-placeholder` por `<video>` ou embed YouTube/Vimeo
- [ ] **Adicionar imagens reais** do produto (substituir SVGs pelos renders 3D do relógio)
- [ ] **Integrar gateway de pagamento** (Stripe, PagSeguro, Mercado Pago)
- [ ] **Conectar formulário** para captura de leads/e-mails (Mailchimp, HubSpot)
- [ ] **Adicionar tracking** (Google Analytics 4, Meta Pixel, Google Tag Manager)
- [ ] **SEO avançado** — schema.org markup para produto, breadcrumbs
- [ ] **Testes A/B** nas headlines e CTAs
- [ ] **Página de obrigado** pós-compra
- [ ] **Adicionar chat de suporte** (Intercom, Zendesk)
- [ ] **Lazy loading** para imagens quando forem adicionadas

---

## 💻 Tecnologias

- HTML5 semântico
- CSS3 (variáveis, grid, flexbox, animações, gradientes)
- JavaScript Vanilla (ES6+)
- Google Fonts (Playfair Display + DM Sans)
- SVGs inline para todos os ícones e ilustrações do produto
- IntersectionObserver API para animações de scroll
- localStorage para persistência do countdown e contador

---

*© 2024 AEVUM Luxury Timepieces — Projeto de demonstração*
