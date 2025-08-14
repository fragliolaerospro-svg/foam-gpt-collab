# 📁 FOAM — Structure de collaboration multi-GPT (via GitHub)

Ce dépôt permet à plusieurs GPT spécialisés de collaborer sur le projet FOAM (créé initialement sur Lovable.dev) de manière structurée, efficace et sans conflits.

---

## 🔥 Objectif
Permettre à chaque GPT (dev, branding, legal...) de contribuer indépendamment via des dossiers dédiés, avec une intégration manuelle dans Lovable.dev au besoin.

---

## 🧠 GPTs actifs

| Dossier       | GPT responsable       | Rôle                                                    |
|---------------|------------------------|----------------------------------------------------------|
| `/dev/`       | `dev_foam.gpt`         | Optimisation du code frontend/backend, logique métier   |
| `/branding/`  | `brand_foam.gpt`       | Identité visuelle, copywriting, UX émotionnel           |
| `/legal/`     | `legal_foam.gpt`       | Création des CGU, politique de confidentialité, licences |
| `/lovable/`   | n/a (source)           | Export brut depuis Lovable.dev                          |

---

## 📂 Structure du repo

```plaintext
/foam-project
│
├── /lovable/          # Export du projet Lovable (code brut)
├── /dev/              # Modifications proposées par le GPT Dev
├── /branding/         # Recommandations et éléments UI/UX/marketing
├── /legal/            # Fichiers légaux (CGU, CGV, RGPD, licences)
├── /prompts/          # Historique et structure des prompts utilisés
└── README.md          # Vue d'ensemble du projet
