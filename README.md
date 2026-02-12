# TechNews - Portal de Notícias

O TechNews é um portal de notícias de tecnologia desenvolvido para consolidar conhecimentos avançados em HTML e CSS, com foco total em design responsivo e organização de código através de múltiplos arquivos de estilo.

### Foco do Projeto: Responsividade

O principal diferencial deste projeto é a aplicação de técnicas de **Mobile First** e a adaptação fluida para diferentes resoluções. A interface foi construída para se comportar de três formas distintas:

* **Mobile**: Menu simplificado e visualização em lista única para facilitar a leitura em telas pequenas.
* **Tablet (Medium)**: Reorganização dos cards principais e seções secundárias em grades de duas colunas.
* **Desktop (Large)**: Layout completo em múltiplas colunas, com exibição de resumos de notícias e uma barra lateral dedicada a anúncios e recomendações.

### Tecnologias Utilizadas

* **HTML5**: Estruturação semântica de todas as seções.
* **CSS3**:
    * **CSS Grid & Flexbox**: Utilizados para criar o sistema de layout adaptável.
    * **Custom Properties (Variáveis)**: Centralização de cores e tipografia no arquivo global.
    * **Nesting**: Organização hierárquica dos seletores para maior clareza.
    * **Media Queries**: Pontos de interrupção estratégicos para mudanças de layout.

### 📁 Estrutura de Pastas

```text
.
├── assets
│   ├── icons
│   │   ├── ArrowRight-hover.svg
│   │   ├── ArrowRight.svg
│   │   ├── List.svg
│   │   ├── Logo.svg
│   │   └── MagnifyingGlass.svg
│   └── images
│       ├── Ads.png
│       └── Image 01.png ... Image 18.png
├── styles
│   ├── ai.css
│   ├── aside.css
│   ├── featured.css
│   ├── global.css
│   ├── header.css
│   ├── index.css
│   ├── sections.css
│   └── weekly.css
└── index.html
```

### Preview do Projeto
O layout apresenta uma área de destaques com tags de conteúdo, uma seção de "Mais lidas da semana" e um feed dedicado a IA com descrições detalhadas para telas grandes.

### Você pode visualizar o projeto ao vivo através do link abaixo:
https://jpfreitas-dev.github.io/portal-de-noticias/
