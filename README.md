# João Matos — Digital Product Portfolio Experience

Este repositório contém a experiência digital de portefólio profissional de **João Matos**, desenhada como uma extensão de alta performance e visualmente premium do seu site principal [joaomatosdigital.pt](https://joaomatosdigital.pt).

O projeto conecta três pilares fundamentais de produto: **Product Thinking**, **Digital Analytics** e **Product Marketing**, apresentando um percurso profissional consolidado, estudos de caso práticos com impacto mensurável e artigos autorais.

---

## 🚀 Estrutura do Repositório

O projeto segue um padrão limpo e modular, facilitando a manutenção do código e a rapidez de publicação:

```bash
├── assets/
│   ├── css/
│   │   └── styles.css          # Animações, efeitos glassmórficos e definições customizadas
│   └── profile-image.png       # Retrato profissional e asset de Open Graph
├── docs/                       # Documentação interna de suporte e prompts (Ignorado no Git)
├── .gitignore                  # Regras de exclusão do Git
├── index.html                  # Estrutura HTML principal e marcação semântica de SEO/GEO
└── README.md                   # Documentação do repositório
```

---

## 🛠️ Tecnologias Utilizadas

* **HTML5 Semântico:** Estruturação em conformidade com as regras de acessibilidade (WCAG AA).
* **CSS3 Customizado:** Animações drifts aceleradas por hardware, halos de luz glassmórficos e diagramas interativos SVG.
* **Tailwind CSS (Play CDN):** Framework utilitário dinâmico e otimizado para carregamento instantâneo.
* **Lucide Icons:** Biblioteca de ícones vetoriais modernos e minimalistas (versão bloqueada para segurança).
* **JSON-LD Schema (Structured Data):** Integração de grafos `Person` e `WebSite` para otimização em motores de pesquisa tradicionais e agentes de inteligência artificial (AI Search).

---

## 🔒 Segurança e Otimização

1. **Decoupling de Dependências:** O website foi 100% isolado de subpastas de templates locais, reduzindo o tamanho de publicação.
2. **Carregamento via CDNs Globais:** Fontes e bibliotecas de scripts são fornecidas através de CDNs com cache geodistribuído e HTTP/3, otimizando o carregamento inicial (LCP).
3. **Tab-nabbing Protection:** Todos os links externos abertos em novas janelas contêm atributos `rel="noopener noreferrer"`.
4. **Imutabilidade de Scripts:** A biblioteca Lucide está fixa numa versão estável de produção (`0.453.0`), prevenindo ataques à cadeia de abastecimento (supply-chain).

---

## 🌐 Publicação / Deploy

Para publicar este website de forma profissional, **apenas necessita de enviar dois elementos** para o seu servidor ou alojamento estático (ex: Vercel, Netlify, GitHub Pages, cPanel):

1. O ficheiro `index.html` (deve ser colocado na pasta raiz pública, geralmente `public_html` ou similar).
2. A pasta `assets/` (juntamente com as suas subpastas `/css` e imagens correspondentes).

---

## 📝 Licença

© 2026 João Carlos Matos. Todos os direitos reservados.
