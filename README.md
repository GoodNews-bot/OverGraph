# OverGraph Studio

**Free · 100% local · No account · No cloud**

> Animated overlay & infographic editor for your videos.  
> One single HTML file. Open it in any browser and create.

[![Live Demo](https://img.shields.io/badge/Live%20Demo-GitHub%20Pages-7c6cff?style=for-the-badge)](https://goodnews-bot.github.io/OverGraph/)
[![Version](https://img.shields.io/badge/Version-4.8-22d3ee?style=for-the-badge)](#)
[![License](https://img.shields.io/badge/License-Free-34d399?style=for-the-badge)](#)

---

## English

### What is OverGraph Studio?

**OverGraph Studio** is a free, fully offline animated infographic and overlay editor designed for video creators, social media managers, educators, and anyone who needs polished animated graphics.

Everything runs **entirely in your browser**. There is no installation, no account, no tracking, and no data ever leaves your machine.

You open one file → you create → you export. That’s it.

### Key Features

| Feature | Description |
|---------|-------------|
| **Single file** | The entire studio is one self-contained HTML file (HTML + CSS + JS). Zero external dependencies. |
| **100% local & private** | No server, no telemetry, no cookies. Your projects stay on your disk. |
| **69 ready-to-use templates** | Stats, rankings, countdowns, quotes, dashboards, sale banners, how-to steps, calendars, and much more. All provided as open `.json` files. |
| **Timeline & keyframes** | Animate entrances, exits, counters and properties frame by frame. Video + audio tracks, loop, adjustable duration. |
| **Professional exports** | • Standalone HTML<br>• Transparent PNG sequence (ZIP)<br>• WebM with alpha channel<br>• Copy-ready code |
| **Powerful editor tools** | Unlimited undo/redo, magnetic guides, safe zones, rectangle multi-select, precise alignment, scene background color. |
| **Every format** | 9:16 (TikTok / Reels / Shorts), 16:9, 1:1, 4:5 or custom dimensions with adapted safe zones. |
| **Fonts & stickers** | Drop your own fonts (`.ttf`, `.otf`, `.woff`…) and images into the `fonts/` and `stickers/` folders. The app detects them automatically when served over HTTP. |
| **Extensible templates** | Create your own templates inside the studio, export them as `.json` and share them. Completely open format. |

### How to use

1. Open **`index.html`** (presentation page) or **`OverGraph.html`** (studio) in any modern browser.
2. Or serve the folder locally for full font/sticker support:
   ```bash
   python -m http.server 8080
   ```
   Then go to `http://localhost:8080`
3. Click **Browse templates** inside the app and select any `.json` from the `templates/` folder (or drag & drop).
4. Edit texts, colors, animations, durations… everything is fully editable.
5. Export when you’re ready.

> Tip: the presentation page (`index.html`) has a language switcher (EN / FR flag, top right) and can launch the studio in fullscreen.

### Template library (69 templates)

A/B test · Agenda · API stats · Bar comparison · Before / After · Behind the scenes · Big stat · Birthday post · Book quote · Break even · Budget allocation · Bug fixed · Chapter title · Collab card · Comment highlight · Conference speaker · Content calendar · Conversion funnel · Countdown · Coupon code · Definition card · Donut stats · End screen · Event schedule · Fact card · Feature callout · Flash sale · Follower goal · Funding round · Giveaway · Glossary term · Growth chart · Holiday greeting · How-to steps · Invoice summary · KPI dashboard · Lower third · Meetup card · Milestone · Motivation · Myth vs fact · New episode · News ticker · Payroll stats · Podcast clip · Pro tip · Product launch · Profit split · Quarterly results · Rating breakdown · Recipe card · Revenue counter · Sale / promo · Server status · Shoutout · Star rating · Stat drop · Stock ticker · Subscribe button · Team cards · Top 3 ranking · Travel stats · Version release · Versus battle · Video stats · We are live · Weather today · Webinar invite · Workout timer

### Support the project

OverGraph is completely free and will stay free.  
If it helps you, a coffee helps the development:

- **PayPal**: [paypal.me/OverGraphCofee](https://paypal.me/OverGraphCofee)
- Crypto addresses are shown inside the app and on the presentation page.

No subscription, no locked features, no watermark. The downloaded file is identical with or without a donation.

---

## Français

### Qu’est-ce qu’OverGraph Studio ?

**OverGraph Studio** est un éditeur d’infographies et d’overlays animés gratuit, 100 % local, conçu pour les créateurs de vidéos, community managers, formateurs et tous ceux qui ont besoin de graphiques animés soignés.

Tout fonctionne **entièrement dans votre navigateur**. Aucune installation, aucun compte, aucun tracking, et aucune donnée ne quitte jamais votre machine.

Vous ouvrez un fichier → vous créez → vous exportez. C’est tout.

### Fonctionnalités principales

| Fonctionnalité | Description |
|----------------|-------------|
| **Fichier unique** | Le studio complet tient dans un seul fichier HTML (HTML + CSS + JS). Zéro dépendance externe. |
| **100 % local & privé** | Pas de serveur, pas de télémétrie, pas de cookies. Vos projets restent sur votre disque. |
| **69 modèles prêts à l’emploi** | Stats, classements, compte à rebours, citations, tableaux de bord, bannières promo, tutoriels, calendriers… Tous fournis en fichiers `.json` ouverts. |
| **Timeline & images-clés** | Animez les entrées, sorties, compteurs et propriétés image par image. Pistes vidéo + audio, boucle, durée ajustable. |
| **Exports professionnels** | • HTML autonome<br>• Séquence PNG transparente (ZIP)<br>• WebM avec canal alpha<br>• Code prêt à coller |
| **Outils d’édition puissants** | Annuler/rétablir illimité, guides magnétiques, zones sûres, sélection multiple par rectangle, alignement précis, couleur de fond de scène. |
| **Tous les formats** | 9:16 (TikTok / Reels / Shorts), 16:9, 1:1, 4:5 ou dimensions personnalisées avec zones sûres adaptées. |
| **Polices & stickers** | Déposez vos polices (`.ttf`, `.otf`, `.woff`…) et images dans les dossiers `fonts/` et `stickers/`. L’app les détecte automatiquement en HTTP. |
| **Modèles extensibles** | Créez vos propres templates dans le studio, exportez-les en `.json` et partagez-les. Format complètement ouvert. |

### Comment l’utiliser

1. Ouvrez **`index.html`** (page de présentation) ou **`OverGraph.html`** (le studio) dans n’importe quel navigateur moderne.
2. Ou servez le dossier en local pour le support complet des polices/stickers :
   ```bash
   python -m http.server 8080
   ```
   Puis allez sur `http://localhost:8080`
3. Cliquez sur **Browse templates** dans l’application et choisissez un fichier `.json` du dossier `templates/` (ou glissez-déposez).
4. Modifiez les textes, couleurs, animations, durées… tout est entièrement éditable.
5. Exportez quand vous êtes prêt.

> Astuce : la page de présentation (`index.html`) possède un sélecteur de langue (drapeau EN / FR en haut à droite) et peut lancer le studio en plein écran.

### Bibliothèque de modèles (69 templates)

A/B test · Agenda · API stats · Bar comparison · Before / After · Behind the scenes · Big stat · Birthday post · Book quote · Break even · Budget allocation · Bug fixed · Chapter title · Collab card · Comment highlight · Conference speaker · Content calendar · Conversion funnel · Countdown · Coupon code · Definition card · Donut stats · End screen · Event schedule · Fact card · Feature callout · Flash sale · Follower goal · Funding round · Giveaway · Glossary term · Growth chart · Holiday greeting · How-to steps · Invoice summary · KPI dashboard · Lower third · Meetup card · Milestone · Motivation · Myth vs fact · New episode · News ticker · Payroll stats · Podcast clip · Pro tip · Product launch · Profit split · Quarterly results · Rating breakdown · Recipe card · Revenue counter · Sale / promo · Server status · Shoutout · Star rating · Stat drop · Stock ticker · Subscribe button · Team cards · Top 3 ranking · Travel stats · Version release · Versus battle · Video stats · We are live · Weather today · Webinar invite · Workout timer

### Soutenir le projet

OverGraph est entièrement gratuit et le restera.  
Si l’outil vous aide, un café aide le développement :

- **PayPal** : [paypal.me/OverGraphCofee](https://paypal.me/OverGraphCofee)
- Les adresses crypto sont visibles dans l’application et sur la page de présentation.

Pas d’abonnement, pas de fonctionnalités verrouillées, pas de filigrane. Le fichier téléchargé est identique avec ou sans don.

---

## Project structure

```
OverGraph/
├── index.html          # Presentation page (EN/FR toggle + live studio)
├── OverGraph.html      # The full studio (single file)
├── README.md           # This file
├── templates/          # 69 ready-to-use .json templates
├── fonts/              # Drop your custom fonts here
└── stickers/           # Drop your images / stickers here
```

## License & credits

Free to use for personal and commercial projects.  
No attribution required (but always appreciated).

Made with care for creators who value privacy and simplicity.

---

**Live demo**: [https://goodnews-bot.github.io/OverGraph/](https://goodnews-bot.github.io/OverGraph/)
