# Sabor de Bragança — Restaurante & Pizzaria Artesanal

Landing page premium para o restaurante **Sabor de Bragança**, em Bragança Paulista, SP.
Single-file (`index.html`), sem build step.

## Sobre o Projeto

Site desenvolvido como demonstração de criação de landing pages da **Akamine Web Studio**.
Apresenta um restaurante fictício com identidade visual quente e apetitosa (espresso + dourado +
creme), focada em transmitir acolhimento, tradição e qualidade culinária.

## Tecnologias

- HTML5 semântico (single-file)
- Tailwind CSS (via CDN) com tema customizado e `@layer`
- Lucide Icons (via CDN)
- Google Fonts — **Fraunces** (display serifada) + **Manrope** (sans)
- JavaScript puro (sem frameworks pesados)

## Experiência & UI

- **Design premium**: glassmorphism, gradientes sutis, sombras em camadas, grid de agência
- **Tipografia fluida** com `clamp()` e hierarquia clara
- **Paleta refinada** mantendo a identidade gastronômica

## Animações

- Reveal on scroll com **Intersection Observer** (substitui o AOS)
- **Stagger** automático em grids de cards e galeria
- **Parallax** suave no hero
- Contadores animados nas estatísticas
- Micro-interações: hover lift, glow, image zoom, shine nos botões, marquee
- **Cursor customizado** (apenas em ponteiros finos)

## Responsividade

- Mobile-first com breakpoints precisos
- Menu hambúrguer **animado** com `aria-expanded`
- Áreas de toque confortáveis

## Performance

- `loading="lazy"` nativo nas imagens (e `fetchpriority="high"` no hero)
- `preconnect` / `dns-prefetch` para fontes, CDNs e bancos de imagens
- Animações apenas com `transform` / `opacity` (GPU-accelerated)

## Acessibilidade

- Contraste WCAG AA
- Skip link, landmarks semânticas (`header`/`main`/`footer`) e `aria-label`s
- Focus states visíveis e on-brand
- Scrollspy com `aria-current` na navegação
- `prefers-reduced-motion` respeitado (desativa animações e parallax)

## Seções

Hero (com estatísticas) · Faixa marquee · Destaques · Cardápio · Ambiente · Depoimentos · CTA · Footer

## Desenvolvimento

**Desenvolvido por:** [Akamine Web Studio](https://github.com/JulioAkaminee)
**Local:** Bragança Paulista, SP

---

> Site de demonstração. As informações de contato são fictícias.
