# Sources, crédits et ressources d'apprentissage

> Ce document liste toutes les ressources utilisées pour construire ce portfolio, et recommande des sites pour apprendre à coder. Si tu lis ce fichier, c'est que tu t'intéresses au code — bienvenue. Tout ce qui est ici est gratuit, ouvert, et accessible à tous. Sers-toi, apprends, et construis tes propres projets.

---

## Un mot pour ceux qui lisent ce dépôt

Ce portfolio a été construit par un lycéen de 17 ans avec 6 mois de pratique. Le code n'est pas parfait, et c'est normal. L'important, c'est de commencer, de casser des trucs, de comprendre pourquoi ça casse, et de recommencer.

Si tu débutes en développement web :
1. Copie ce projet, modifie-le, fais-en le tien
2. Consulte les ressources listées plus bas — elles sont toutes gratuites
3. N'aie pas peur de lire le code source des sites que tu visites (clic droit → "Inspecter")
4. Pose des questions sur les forums, personne ne naît développeur

---

## Crédits et sources utilisées dans ce portfolio

### Données et API

| Ressource | Utilisation | Lien |
|-----------|-------------|------|
| **PokéAPI** | Données des 251 Pokémon (noms, types, stats, capacités, images) pour le projet PokéDex | [pokeapi.co](https://pokeapi.co) |
| **PokéAPI Sprites** | Images officielles des Pokémon (official artwork) hébergées sur GitHub | [github.com/PokeAPI/sprites](https://github.com/PokeAPI/sprites) |

La PokéAPI est une API REST gratuite, open source, sans clé d'authentification. Elle est parfaite pour apprendre à utiliser `fetch()` et le code asynchrone.

### Typographies (polices de caractères)

| Police | Style | Utilisation | Lien |
|--------|-------|-------------|------|
| **Syne** | Display, sans-serif | Titres et texte principal | [fonts.google.com/specimen/Syne](https://fonts.google.com/specimen/Syne) |
| **DM Mono** | Monospace | Code, données, labels techniques | [fonts.google.com/specimen/DM+Mono](https://fonts.google.com/specimen/DM+Mono) |

Les deux sont servies par **Google Fonts** ([fonts.google.com](https://fonts.google.com)), un service gratuit qui héberge des centaines de polices open source. Il suffit d'ajouter un `<link>` dans le `<head>` de ta page HTML.

### Images et médias

| Ressource | Utilisation | Licence | Lien |
|-----------|-------------|---------|------|
| **Unsplash** | Photo du skyline de Dubaï (fond du Lap Timer) | Licence Unsplash (gratuite, usage libre) | [unsplash.com](https://unsplash.com) |
| **Fichier audio F1** | Son de moteur de Formule 1 pour le Lap Timer | Usage personnel / éducatif | Fichier local `lap-timer/data/f1-race.mp3` |

**Unsplash** propose des photos haute qualité gratuites pour tout usage. Créditer le photographe est recommandé (c'est fait dans le footer du Lap Timer).

### Icônes

Les icônes utilisées dans la page d'accueil (GitHub, Instagram) sont des **SVG inline** dessinés à la main dans le HTML, inspirés du style de [Feather Icons](https://feathericons.com) (MIT License). Les emojis standard Unicode sont utilisés pour les icônes des projets.

---

## Technologies utilisées — détail et documentation

### HTML5

| Concept utilisé | Documentation officielle |
|-----------------|--------------------------|
| Structure sémantique (`header`, `nav`, `footer`, `section`) | [MDN — HTML elements](https://developer.mozilla.org/fr/docs/Web/HTML/Element) |
| Formulaires (`input`) | [MDN — input](https://developer.mozilla.org/fr/docs/Web/HTML/Element/input) |
| Attributs (`id`, `class`, `data-*`) | [MDN — Global attributes](https://developer.mozilla.org/fr/docs/Web/HTML/Global_attributes) |
| Balise `<audio>` | [MDN — audio](https://developer.mozilla.org/fr/docs/Web/HTML/Element/audio) |
| SVG inline | [MDN — SVG](https://developer.mozilla.org/fr/docs/Web/SVG) |
| Meta viewport (responsive) | [MDN — Viewport meta tag](https://developer.mozilla.org/fr/docs/Web/HTML/Viewport_meta_tag) |

**Norme officielle :** [W3C HTML Standard](https://html.spec.whatwg.org/)

### CSS3

| Concept utilisé | Documentation officielle |
|-----------------|--------------------------|
| Variables CSS (Custom Properties) | [MDN — Using CSS custom properties](https://developer.mozilla.org/fr/docs/Web/CSS/Using_CSS_custom_properties) |
| Flexbox | [MDN — Flexbox](https://developer.mozilla.org/fr/docs/Web/CSS/CSS_flexible_box_layout) |
| CSS Grid | [MDN — Grid](https://developer.mozilla.org/fr/docs/Web/CSS/CSS_grid_layout) |
| Animations `@keyframes` | [MDN — CSS Animations](https://developer.mozilla.org/fr/docs/Web/CSS/CSS_animations) |
| Transitions | [MDN — CSS Transitions](https://developer.mozilla.org/fr/docs/Web/CSS/CSS_transitions) |
| Pseudo-éléments (`::before`, `::after`) | [MDN — Pseudo-elements](https://developer.mozilla.org/fr/docs/Web/CSS/Pseudo-elements) |
| `clamp()` (responsive) | [MDN — clamp()](https://developer.mozilla.org/fr/docs/Web/CSS/clamp) |
| `backdrop-filter` | [MDN — backdrop-filter](https://developer.mozilla.org/fr/docs/Web/CSS/backdrop-filter) |
| `box-shadow` / `text-shadow` | [MDN — box-shadow](https://developer.mozilla.org/fr/docs/Web/CSS/box-shadow) |
| `linear-gradient` / `radial-gradient` | [MDN — gradient](https://developer.mozilla.org/fr/docs/Web/CSS/gradient) |
| `offset-path` (animation sur tracé SVG) | [MDN — offset-path](https://developer.mozilla.org/en-US/docs/Web/CSS/offset-path) |
| Media queries / responsive design | [MDN — Media queries](https://developer.mozilla.org/fr/docs/Web/CSS/CSS_media_queries) |

**Norme officielle :** [W3C CSS Standards](https://www.w3.org/Style/CSS/)

### JavaScript (ES6+)

| Concept utilisé | Documentation officielle |
|-----------------|--------------------------|
| `const`, `let` (variables) | [MDN — let](https://developer.mozilla.org/fr/docs/Web/JavaScript/Reference/Statements/let) |
| Fonctions fléchées `() => {}` | [MDN — Arrow functions](https://developer.mozilla.org/fr/docs/Web/JavaScript/Reference/Functions/Arrow_functions) |
| Template literals `` `${}` `` | [MDN — Template literals](https://developer.mozilla.org/fr/docs/Web/JavaScript/Reference/Template_literals) |
| Spread operator `...` | [MDN — Spread syntax](https://developer.mozilla.org/fr/docs/Web/JavaScript/Reference/Operators/Spread_syntax) |
| Destructuring `{ a, b }` | [MDN — Destructuring](https://developer.mozilla.org/fr/docs/Web/JavaScript/Reference/Operators/Destructuring_assignment) |
| `.map()`, `.filter()`, `.forEach()` | [MDN — Array methods](https://developer.mozilla.org/fr/docs/Web/JavaScript/Reference/Global_Objects/Array) |
| `.sort()` (mélange aléatoire) | [MDN — Array.sort](https://developer.mozilla.org/fr/docs/Web/JavaScript/Reference/Global_Objects/Array/sort) |
| `.indexOf()`, `.includes()` | [MDN — Array.includes](https://developer.mozilla.org/fr/docs/Web/JavaScript/Reference/Global_Objects/Array/includes) |
| Objets et JSON | [MDN — Working with objects](https://developer.mozilla.org/fr/docs/Web/JavaScript/Guide/Working_with_objects) |
| DOM manipulation | [MDN — Document](https://developer.mozilla.org/fr/docs/Web/API/Document) |
| `getElementById`, `querySelector` | [MDN — getElementById](https://developer.mozilla.org/fr/docs/Web/API/Document/getElementById) |
| `createElement`, `appendChild` | [MDN — createElement](https://developer.mozilla.org/fr/docs/Web/API/Document/createElement) |
| Événements (`onclick`, `oninput`) | [MDN — Events](https://developer.mozilla.org/fr/docs/Web/Events) |
| `fetch()` (requêtes HTTP) | [MDN — Fetch API](https://developer.mozilla.org/fr/docs/Web/API/Fetch_API) |
| `async` / `await` | [MDN — async function](https://developer.mozilla.org/fr/docs/Web/JavaScript/Reference/Statements/async_function) |
| `Promise.allSettled()` | [MDN — Promise.allSettled](https://developer.mozilla.org/fr/docs/Web/JavaScript/Reference/Global_Objects/Promise/allSettled) |
| `requestAnimationFrame` | [MDN — requestAnimationFrame](https://developer.mozilla.org/fr/docs/Web/API/window/requestAnimationFrame) |
| `performance.now()` | [MDN — Performance.now](https://developer.mozilla.org/fr/docs/Web/API/Performance/now) |
| `Audio()` (Web Audio) | [MDN — Audio()](https://developer.mozilla.org/fr/docs/Web/API/HTMLAudioElement/Audio) |
| `Math.floor()`, `Math.min()`, `Math.random()` | [MDN — Math](https://developer.mozilla.org/fr/docs/Web/JavaScript/Reference/Global_Objects/Math) |
| `String.padStart()` | [MDN — padStart](https://developer.mozilla.org/fr/docs/Web/JavaScript/Reference/Global_Objects/String/padStart) |

**Norme officielle :** [ECMAScript Standard (ECMA-262)](https://tc39.es/ecma262/)

---

## Outils utilisés

| Outil | Rôle | Lien |
|-------|------|------|
| **VS Code** | Éditeur de code | [code.visualstudio.com](https://code.visualstudio.com) |
| **Git** | Versionnement du code | [git-scm.com](https://git-scm.com) |
| **GitHub** | Hébergement du dépôt | [github.com](https://github.com) |
| **Vercel** | Hébergement et déploiement du site | [vercel.com](https://vercel.com) |
| **OVH** | Registrar du nom de domaine gibibi.tech | [ovh.com](https://www.ovh.com) |
| **Chrome DevTools** | Débogage, inspection, test responsive | Intégré à Chrome (F12) |

---

## Ressources recommandées pour apprendre

### Pour commencer (niveau débutant)

| Site | Ce qu'on y apprend | Langue | Lien |
|------|---------------------|--------|------|
| **MDN Web Docs** | LA référence pour HTML, CSS et JavaScript. Documentation complète, exemples, tutoriels. C'est le site le plus fiable et le plus complet. | FR / EN | [developer.mozilla.org](https://developer.mozilla.org/fr/) |
| **W3Schools** | Tutoriels interactifs avec éditeur en ligne pour tester directement. Idéal pour les premiers pas. | EN (simple) | [w3schools.com](https://www.w3schools.com) |
| **freeCodeCamp** | Cours gratuit et complet (HTML, CSS, JS, APIs, Node.js...) avec des exercices pratiques et des certifications. | EN / FR | [freecodecamp.org](https://www.freecodecamp.org) |
| **The Odin Project** | Parcours d'apprentissage complet et structuré, du débutant au développeur. Projets concrets à construire. | EN | [theodinproject.com](https://www.theodinproject.com) |
| **Codecademy** | Cours interactifs pas à pas. La version gratuite suffit pour commencer. | EN | [codecademy.com](https://www.codecademy.com) |
| **OpenClassrooms** | Cours en français, parcours structurés, certains avec certificat. | FR | [openclassrooms.com](https://openclassrooms.com) |

### Pour approfondir JavaScript

| Site | Description | Lien |
|------|-------------|------|
| **JavaScript.info** | Le meilleur tutoriel JS en ligne. Clair, progressif, exhaustif. Du débutant à l'avancé. | [javascript.info](https://javascript.info) |
| **Eloquent JavaScript** (livre gratuit) | Livre en ligne gratuit. Excellent pour comprendre les concepts en profondeur. | [eloquentjavascript.net](https://eloquentjavascript.net) |
| **MDN — Guide JavaScript** | La section "Guide" de MDN, plus pédagogique que la référence. | [MDN JS Guide](https://developer.mozilla.org/fr/docs/Web/JavaScript/Guide) |

### Pour le CSS et le design

| Site | Description | Lien |
|------|-------------|------|
| **CSS-Tricks** | Articles, guides et astuces CSS. Le guide Flexbox et Grid sont des classiques. | [css-tricks.com](https://css-tricks.com) |
| **Flexbox Froggy** | Jeu pour apprendre Flexbox en positionnant des grenouilles. Oui, vraiment. Et c'est efficace. | [flexboxfroggy.com](https://flexboxfroggy.com) |
| **Grid Garden** | Même principe, mais pour CSS Grid. | [cssgridgarden.com](https://cssgridgarden.com) |
| **Can I Use** | Vérifie si une fonctionnalité CSS/JS est supportée par les navigateurs. | [caniuse.com](https://caniuse.com) |
| **Google Fonts** | Catalogue de polices gratuites avec guide d'intégration. | [fonts.google.com](https://fonts.google.com) |
| **Coolors** | Générateur de palettes de couleurs. | [coolors.co](https://coolors.co) |

### Pour pratiquer et s'inspirer

| Site | Description | Lien |
|------|-------------|------|
| **CodePen** | Éditeur en ligne pour tester du HTML/CSS/JS. Énorme communauté avec des milliers d'exemples. | [codepen.io](https://codepen.io) |
| **Frontend Mentor** | Défis de design à coder. On te donne une maquette, tu codes le résultat. | [frontendmentor.io](https://www.frontendmentor.io) |
| **Exercism** | Exercices de programmation avec mentoring gratuit. | [exercism.org](https://exercism.org) |
| **LeetCode** (plus tard) | Algorithmes et structures de données. Pour préparer les entretiens techniques. | [leetcode.com](https://leetcode.com) |

### Pour comprendre Git et GitHub

| Site | Description | Lien |
|------|-------------|------|
| **GitHub Skills** | Cours interactifs officiels de GitHub. | [skills.github.com](https://skills.github.com) |
| **Oh My Git!** | Jeu pour apprendre Git visuellement. | [ohmygit.org](https://ohmygit.org) |
| **Git — le guide simple** | Une page, pas de blabla, l'essentiel de Git. | [rogerdudler.github.io/git-guide](https://rogerdudler.github.io/git-guide/index.fr.html) |
| **Pro Git** (livre gratuit) | Le livre officiel de Git. Complet et gratuit en ligne. | [git-scm.com/book/fr](https://git-scm.com/book/fr/v2) |

### Pour les API

| Site | Description | Lien |
|------|-------------|------|
| **PokéAPI** | L'API utilisée dans ce portfolio. Documentation claire, parfaite pour débuter. | [pokeapi.co](https://pokeapi.co) |
| **Public APIs** | Liste de centaines d'API gratuites classées par catégorie (musique, météo, jeux...). | [github.com/public-apis/public-apis](https://github.com/public-apis/public-apis) |
| **JSONPlaceholder** | Fausse API REST pour s'entraîner à faire des requêtes. | [jsonplaceholder.typicode.com](https://jsonplaceholder.typicode.com) |
| **REST Countries** | API gratuite avec les données de tous les pays du monde. Bon projet d'entraînement. | [restcountries.com](https://restcountries.com) |

### L'IA comme outil d'apprentissage

L'intelligence artificielle, c'est un accélérateur — pas un remplaçant. Utilise-la pour comprendre un concept, déboguer un bout de code, ou te faire expliquer une erreur. Mais ne copie-colle jamais sans comprendre. Le but c'est d'apprendre, pas de tricher.

| Outil | Ce qu'il fait | Lien |
|-------|---------------|------|
| **Grok** (xAI) | Assistant IA. Pose-lui des questions sur du code, il explique bien. | [grok.com](https://grok.com) |
| **Perplexity** | Moteur de recherche IA. Donne des réponses sourcées, parfait pour des questions techniques. | [perplexity.ai](https://www.perplexity.ai) |
| **Qwen Coder** | Modèle IA spécialisé code, open source. Bon pour générer et expliquer du code. | [huggingface.co/Qwen](https://huggingface.co/Qwen) |
| **ChatGPT** (OpenAI) | Le plus connu. Version gratuite disponible. | [chatgpt.com](https://chatgpt.com) |
| **Claude** (Anthropic) | Assistant IA. Très bon pour expliquer du code étape par étape. | [claude.ai](https://claude.ai) |

> Tant que c'est gratuit, profites-en. A petites doses. L'IA t'aide à aller plus vite, mais c'est toi qui conduis. Vamos!

### Pour aller plus loin (après le BUT)

| Site | Description | Lien |
|------|-------------|------|
| **React** | Le framework JS le plus utilisé. À apprendre après avoir maîtrisé le JS vanilla. | [react.dev](https://react.dev) |
| **Next.js** | Framework React pour des sites web complets (front + back). | [nextjs.org](https://nextjs.org) |
| **Node.js** | JavaScript côté serveur. Pour créer des API et des applications back-end. | [nodejs.org](https://nodejs.org) |
| **Supabase** | Base de données + authentification gratuite. Alternative open source à Firebase. | [supabase.com](https://supabase.com) |

---

## Normes et standards du web

| Organisme | Rôle | Lien |
|-----------|------|------|
| **W3C** (World Wide Web Consortium) | Organisme qui définit les standards du web (HTML, CSS, accessibilité). | [w3.org](https://www.w3.org) |
| **WHATWG** | Maintient la spécification vivante de HTML. | [whatwg.org](https://whatwg.org) |
| **TC39** | Comité qui fait évoluer JavaScript (ECMAScript). | [tc39.es](https://tc39.es) |
| **WCAG** | Directives d'accessibilité web. Pour que les sites soient utilisables par tous. | [w3.org/WAI/WCAG21](https://www.w3.org/WAI/WCAG21/quickref/) |

---

## Licence et droits

- **Le code de ce portfolio** est open source. Tu peux le lire, le copier, t'en inspirer.
- **PokéAPI** : gratuite, open source (licence MIT). Pas de clé requise. Merci à [Paul Shortino](https://github.com/phPokemon) et la communauté.
- **Google Fonts** (Syne, DM Mono) : licences open source (OFL / Apache 2.0). Utilisation libre.
- **Unsplash** : licence Unsplash — gratuite pour usage personnel et commercial, attribution appréciée.
- **Feather Icons** (inspiration SVG) : licence MIT.

---

> _"Le meilleur moment pour commencer à coder, c'était il y a 6 mois. Le deuxième meilleur moment, c'est maintenant."_
>
> Si ce document t'a été utile, construis quelque chose et partage-le. C'est comme ça que la communauté avance.

