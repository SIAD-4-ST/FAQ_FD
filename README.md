Assistant FAQ – Flavescence dorée (POC)
🎯 Objectif
Ce projet est un prototype web (POC) d’assistant FAQ dédié à la flavescence dorée, à destination des viticulteurs et acteurs de la filière Champagne.
Il permet de :

Rechercher une réponse à partir d’une question libre / Explorer les questions par thématiques / Afficher une réponse principale ainsi que des questions proches

👉 L’objectif est de faciliter l’accès à l’information réglementaire et opérationnelle, sans authentification ni back‑office.

🧩 Fonctionnalités

✅ Recherche plein texte dans une base FAQ locale
✅ Gestion de variantes de questions (synonymes, reformulations)
✅ Navigation par catégories :

Connaissances & formation / Prospection / Lutte / Prélèvements & arrachage / Certification

✅ Interface responsive, légère et autonome
✅ Dépliage des questions/réponses type FAQ
✅ Fonctionnement 100 % côté client (HTML / CSS / JavaScript)

🏗️ Architecture
Le projet est volontairement simple et auto‑contenu :
/
├── index.html   # Application complète (HTML + CSS + JS)
└── README.md

Points clés

Aucun framework / Aucun appel API / Aucune donnée personnelle / Les données FAQ sont intégrées directement dans le fichier (DEFAULT_FAQ_WRAPPER en JavaScript)

🔐 Sécurité & données

✅ Aucune donnée utilisateur n’est stockée
✅ Aucun cookie, tracker ou analytics
✅ Aucune donnée sensible ou personnelle exposée
✅ Compatible avec une mise en ligne sur GitHub Pages

Ce POC est conforme à un usage informatif et non transactionnel.

⚠️ Limites connues

Données figées dans le code / Pas de gestion multi‑utilisateurs / Pas de moteur sémantique avancé (type IA) / Maintenance manuelle du contenu

📌 Statut du projet
✅ POC / Prototype fonctionnel
❌ Non destiné à un usage industriel sans refonte (sécurité, gouvernance, maintenance)

👤 Auteur : Hugo Moutte - Prototype réalisé dans un cadre d’accompagnement métier / innovation digitale
