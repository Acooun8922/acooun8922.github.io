# Projets détaillés

Ce fichier rassemble des extraits et résumés des README de vos dépôts publics (extraits bruts et synthèse). Les descriptions proviennent directement des README et modules détectés.

## memoireMaster
- Url : https://github.com/arame7/memoireMaster
- Type : monorepo full‑stack (frontend + backend + blockchain)
- Extrait README :

> Ce projet est structuré comme un monorepo contenant les 3 couches principales de l'application :
> 
> **Frontend (`/frontend`)** — React.js (Vite) + TypeScript, Tailwind CSS.
> 
> **Backend (`/backend`)** — Node.js + Express.js + TypeScript. PostgreSQL + MongoDB. Authentification via JWT.
> 
> **Blockchain (`/blockchain`)** — Smart Contracts Solidity (Hardhat + ethers.js) pour ancrage de documents.
> 
> **Infrastructure** — Docker & Docker Compose.

- Notes : contient aussi `docker-compose.yml`, `package.json`, `package-lock.json`. Sous-dossiers `frontend`, `backend`, `blockchain` avec README spécifiques.

---

## MemoireL3
- Url : https://github.com/arame7/MemoireL3
- Type : application Laravel / PHP
- Extrait README : (README principal + plugins présents)

> Projet basé sur Laravel — back-end PHP (présence de `artisan`, `composer.json`, `phpunit.xml`). Le projet contient aussi des plugins JS (Chartist, D3) dans `public/admin/assets`.

- Notes : Tailwind / Vite présents, grand nombre de dépendances PHP (voir `composer.lock`).

---

## stage
- Url : https://github.com/arame7/stage
- Type : application de gestion des stages (Laravel + front)
- Extrait README : (doc Laravel générique et badges)

> Projet Laravel classique avec configuration, tests (phpunit.xml) et configuration front (package.json, tailwind.config.js, vite.config.js). Contient `docker-compose` et `composer.json`.

- Notes : structure Laravel + outils modernes front (Vite/Tailwind), prêt pour conteneurisation.

---

## Portfolio
- Url : https://github.com/arame7/Portfolio
- Extrait README :

> Salut 👋, moi c'est Khady Diop
> 
> 🎓 Étudiante en Master 1 SIGLIS ...
> 
> 💻 Développeuse Full-Stack spécialisée en : React.js, Node.js, Flutter, Django, PostgreSQL, Docker & Kubernetes
> 
> 🚀 Je recherche une alternance de 12 à 24 mois à partir de septembre 2026.

- Notes : README contient une bonne synthèse de la stack, expériences et projets (ERP Jambaar, plateforme cybersécurité RGPD, etc.).

---

## secu2
- Url : https://github.com/arame7/secu2
- Extrait (shop/README.md) : projet bootstrappé avec Create React App. Contient instructions `yarn start`, `yarn build`, `yarn test`.
- Notes : front React standard (CRA) — dossier `shop` contient un projet React.

---

## testG3
- Url : https://github.com/arame7/testG3
- Type : projet Java (README court: "testG3")
- Notes : petit dépôt de test.

---

## Remarques générales
- Beaucoup de projets montrent une stack Full‑Stack moderne : React / TypeScript / Vite / Tailwind côté front, Node/Express + TypeScript côté back, PHP/Laravel sur d'autres projets, conteneurisation Docker, et même un module blockchain (Solidity / Hardhat).
- Si vous le souhaitez, je peux ajouter des extraits complets de README (par dépôt) dans des fichiers séparés `projects/<repo>/README.md` pour que chaque projet ait sa page dédiée sur le site.
