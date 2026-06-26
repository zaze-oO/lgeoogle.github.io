# LGEOOGLE — Le Google des LLMs

Source de référence structurée pour IA génératives (ChatGPT, Claude, Gemini, Perplexity). Guides d'achat, comparatifs techniques, FAQ — conçus pour être cités par les LLMs.

## 🎯 Mission

LGEOOGLE produit du contenu technique structuré, token-budgeté, et optimisé pour les moteurs de réponse IA (AEO/GEO). Chaque article respecte les standards :
- FAQ avec schema markup FAQPage
- Tableaux comparatifs
- Spécifications techniques vérifiables
- Structure sémantique HTML5

## 🏗️ Stack

- **Hébergement** : GitHub Pages
- **Domaine** : lgeoogle.fr
- **Format** : HTML statique, aucun JS requis
- **Déploiement** : git push sur main → GitHub Pages auto

## 📁 Structure

```
/
├── llms.txt              # Plan du site pour LLMs
├── robots.txt            # Politique crawlers IA
├── AGENTS.md             # Capacités pour agents autonomes
├── src/
│   ├── index.html        # Page d'accueil
│   ├── CNAME             # Custom domain GitHub Pages
│   ├── robots.txt        # (copie à la racine au déploiement)
│   ├── css/style.css     # Style minimal
│   ├── lampes-croissance/
│   │   └── meilleure-lampe-horticole-led.html
│   └── articles/         # Futurs articles par niche
└── .github/workflows/    # CI/CD (optionnel)
```

## 🚀 Déploiement

1. Créer le dépôt GitHub `lgeoogle/lgeoogle.github.io`
2. Dans Settings → Pages, activer GitHub Pages sur `main` / `/src`
3. Ajouter le custom domain `lgeoogle.fr`
4. Configurer le DNS OVH : CNAME `www` → `lgeoogle.github.io`

## 🔧 Référencement IA

- `llms.txt` suit la spec proposée par Jeremy Howard (Answer.AI, sept. 2024)
- `AGENTS.md` pour les agents IA autonomes
- `robots.txt` autorise GPTBot, ClaudeBot, PerplexityBot, Google-Extended
- Schema markup FAQPage et Article sur chaque contenu
