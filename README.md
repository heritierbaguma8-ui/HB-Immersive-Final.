HBIMMERSIVE-PORTFOLIO/
├── README.md
├── docs/
│   ├── ARCHITECTURE.md
│   ├── FEATURES.md
│   ├── MARKETING.md
│   └── ROADMAP.md
├── screenshots/
│   ├── fr/
│   └── en/
├── videos/
├── assets/
│   ├── logo.png
│   ├── banner.png
│   └── favicon.ico
├── site/          ← si tu as un mini-site web HTML/CSS
│   ├── index.html
│   ├── css/
│   ├── js/
│   └── assets/
├── netlify.toml   ← obligatoire pour éviter les 404
└── .gitignore[build]
  publish = "site"   # ou "." si index.html à la racine
  command = ""

[[redirects]]
  from = "/*"
  to = "/index.html"
  status = 200## 📂 Documentation Technique
- [Architecture détaillée](docs/ARCHITECTURE.md)
- [Liste complète des fonctionnalités](docs/FEATURES.md)
- [Stratégie marketing](docs/MARKETING.md)
- [Feuille de route 2026-2027](docs/ROADMAP.md)