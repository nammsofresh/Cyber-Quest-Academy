cyber-fugitive/
├── 📄 README.md                     # Documentation principale
├── 📄 QUICK_START.md                # Guide de démarrage rapide ⭐
├── 📄 SETUP_COMPLETE.md             # Résumé détaillé
├── 📄 PROJECT_OVERVIEW.txt          # Vue visuelle du projet
├── 📄 .gitignore                    # Fichiers à ignorer Git
├── 📄 deploy.sh                     # Script de déploiement
├── 📄 docker-compose.local.yml      # Dev localhost
├── 📄 docker-compose.prod.yml       # Production VPS
│
├── 📁 backend/                      # API FastAPI (Python)
│   ├── 📄 README.md
│   ├── 📄 Dockerfile
│   ├── 📄 requirements.txt          # Toutes les dépendances
│   ├── 📄 .env.example
│   └── 📁 app/
│       ├── 📄 main.py               ✅ Point d'entrée FastAPI
│       ├── 📄 config.py             ✅ Configuration complète
│       ├── 📄 database.py           ✅ Connexion PostgreSQL
│       ├── 📁 models/               (à remplir)
│       ├── 📁 schemas/              (à remplir)
│       ├── 📁 routers/              (à remplir)
│       ├── 📁 services/             (à remplir)
│       └── 📁 utils/                (à remplir)
│
├── 📁 frontend/                     # Application Next.js
│   ├── 📄 README.md
│   ├── 📄 Dockerfile
│   ├── 📄 package.json              # Toutes les dépendances
│   ├── 📄 tailwind.config.js        ✅ Thème cyberpunk complet
│   ├── 📄 .env.example
│   ├── 📁 app/
│   │   ├── 📄 layout.js            ✅ Layout principal
│   │   ├── 📄 page.js              ✅ Landing page stylée
│   │   └── 📄 globals.css          ✅ Styles + animations
│   └── 📁 lib/
│       ├── 📄 api.js               ✅ Client API + JWT
│       └── 📄 constants.js         ✅ Rangs, catégories, helpers
│
├── 📁 challenges/                   # Challenges Docker
│   └── 📄 README.md                 ✅ Guide complet
│
└── 📁 backup/                       # Backups DB
