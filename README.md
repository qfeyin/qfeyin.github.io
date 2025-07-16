# QFey

## Possible Structure 

```markdown
username.github.io/                # Root domain (qfey.in)
├── index.html                     # Main homepage
├── about.html                     # About page
├── contact.html                   # Contact page (optional)
├── css/                           # Main site CSS
│   ├── styles.css                 # Main stylesheet
│   ├── components.css             # Reusable components
│   └── responsive.css             # Responsive design
├── js/                            # Main site JavaScript
│   ├── main.js                    # Main functionality
│   ├── navigation.js              # Navigation handling
│   └── utils.js                   # Utility functions
├── assets/                        # Global assets
│   ├── images/                    # Site images
│   │   ├── hero-bg.jpg
│   │   ├── profile.jpg
│   │   └── icons/
│   ├── documents/                 # PDFs, CVs, etc.
│   └── favicon.ico
├── scribe/                        # Blog SECTION
│   ├── _quarto.yml                # Blog configuration
│   ├── index.qmd                  # Blog homepage
│   ├── blog-unique.css            # Blog-specific CSS
│   ├── custom-blog.scss           # Blog SCSS theme
│   ├── create_post.py             # Post generator
│   ├── posts/                     # Blog posts
│   │   ├── 2024-01-20-neural-network-scratch/
│   │   │   ├── index.qmd
│   │   │   └── assets/
│   │   └── welcome/
│   │       └── index.qmd
│   ├── assets/                    # Blog-specific assets
│   │   └── post-templates/
│   └── _site/                     # Generated blog (git ignored)
├── bits/                          # RESEARCH SECTION
│   ├── _quarto.yml                # Research configuration
│   ├── index.qmd                  # Research homepage
│   ├── research-theme.css         # Research-specific CSS
│   ├── custom-research.scss       # Research SCSS theme
│   ├── papers/                    # Research papers
│   │   ├── 2025-<>/
│   │   │   ├── index.qmd
│   │   │   ├── paper.pdf
│   │   │   ├── data/
│   │   │   │   ├── dataset.csv
│   │   │   │   └── results.json
│   │   │   └── figures/
│   │   │       ├── figure1.png
│   │   │       └── figure2.png
│   │   └── working-papers/
│   │       ├── draft-<>/
│   │       │   ├── index.qmd
│   │       └── proposal-<>/
│   │           ├── index.qmd
│   ├── projects/                  # Research projects
│   │   └── qml/
│   │       ├── index.qmd
│   │       └── simulations/
│   ├── datasets/                  # Research datasets
│   ├── assets/                    # Research assets
│   │   └── templates/
│   └── _site/                     # Generated research site
├── books/                         # BOOKS SECTION
│   ├── _quarto.yml                # Books configuration
│   ├── index.qmd                  # Books homepage
│   ├── book-theme.css             # Books-specific CSS
│   ├── custom-book.scss           # Book SCSS theme
│   ├── deep-learning-guide/       # Book 1: Deep Learning Guide
│   │   ├── _quarto.yml            # Book-specific config
│   │   ├── index.qmd              # Book homepage
│   │   ├── preface.qmd            # Preface
│   │   ├── chapters/              # Book chapters
│   │   │   ├── 01-introduction.qmd
│   │   ├── appendices/            # Appendices
│   │   │   ├── a-mathematics.qmd
│   │   │   └── b-resources.qmd
│   │   ├── assets/                # Book assets
│   │   │   ├── cover.png
│   │   │   ├── figures/
│   │   │   └── code/
│   │   ├── data/                  # Book datasets
│   │   ├── references.bib         # Bibliography
│   │   └── _book/                 # Generated book
│   └── _site/                     # Generated books site
├── api/                           # API documentation (optional)
│   ├── _quarto.yml
│   ├── index.qmd
│   └── endpoints/
├── shared/                        # Shared resources
│   ├── css/                       # Shared CSS
│   │   ├── quarto-common.css      # Common Quarto styling
│   │   └── components.css         # Reusable components
│   ├── js/                        # Shared JavaScript
│   │   ├── analytics.js           # Analytics code
│   │   └── search.js              # Search functionality
│   ├── templates/                 # Shared templates
│   │   ├── post-template.qmd
│   │   └── paper-template.qmd
│   └── assets/                    # Shared assets
│       ├── logos/
│       └── icons/
├── .github/                       # GitHub Actions
│   └── workflows/
│       ├── deploy.yml             # Deployment workflow
│       └── build-quarto.yml       # Quarto build workflow
├── .gitignore                     # Git ignore file
├── README.md                      # Repository README
├── LICENSE                        # License file
└── robots.txt                     # SEO robots file


```
