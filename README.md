# GTA-grock
GTA - grand theft auto - grock AI
3D Open World Prototype

Petit prototype de jeu 3D en monde ouvert, inspiré de l'ambiance des jeux urbains en monde ouvert de l'ère PS2, avec un rendu réaliste tout en conservant une architecture légère et adaptée au navigateur.

«Statut : Prototype / développement actif»

🎮 Présentation

Ce projet est une petite expérience 3D jouable dans laquelle le joueur peut explorer un environnement urbain, se déplacer librement et interagir avec différents éléments du monde.

L'objectif est de créer une base technique permettant progressivement d'ajouter davantage de contenu : véhicules, bâtiments, interactions, environnement et fonctionnalités de gameplay.

Le projet utilise des technologies web 3D afin de pouvoir être exécuté directement dans un navigateur moderne.

✨ Fonctionnalités

🌆 Environnement

- Petit quartier urbain explorable
- Routes et zones accessibles
- Maisons et bâtiments
- Arbres et éléments de décoration
- Éclairage et ambiance 3D
- Limites autour de la zone de jeu

🚶 Joueur

- Vue à la troisième personne
- Déplacement libre
- Course
- Rotation de la caméra
- Caméra avec gestion des collisions
- Collision avec le terrain et les objets

🏠 Exploration des bâtiments

- Maison accessible
- Entrée dans le bâtiment
- Intérieur modélisé
- Meubles et éléments de décoration
- Collisions intérieures
- Entrée et sortie fonctionnelles

🚗 Véhicule

- Véhicule conduisible
- Entrée et sortie du véhicule
- Accélération
- Freinage
- Direction
- Caméra adaptée au véhicule
- Collisions avec l'environnement
- Physique simplifiée

📱 Contrôles

Le projet est conçu pour être utilisable dans un navigateur et peut notamment être adapté aux appareils mobiles avec des contrôles tactiles.

🛠️ Technologies

Le projet repose notamment sur :

- React
- TypeScript
- Three.js
- React Three Fiber
- React Three Drei
- TanStack
- Vite
- Tailwind CSS

🚀 Installation

Clone le dépôt :

git clone https://github.com/USERNAME/REPOSITORY.git
cd REPOSITORY

Installe les dépendances :

npm install

Lance le serveur de développement :

npm run dev

Puis ouvre l'adresse affichée par le terminal dans ton navigateur.

🏗️ Build

Pour créer une version de production :

npm run build

Pour tester la version de production localement :

npm run preview

🎯 Objectifs du projet

Le projet a pour objectif de développer progressivement un petit environnement 3D avec :

- monde ouvert compact ;
- exploration libre ;
- véhicules ;
- bâtiments accessibles ;
- interactions ;
- physique et collisions ;
- contrôles clavier et mobile ;
- optimisation des performances ;
- architecture permettant d'ajouter facilement de nouvelles fonctionnalités.

⚙️ Priorités techniques

La stabilité et la jouabilité sont prioritaires.

Le projet cherche notamment à éviter :

- les personnages traversant les murs ;
- les véhicules traversant les bâtiments ;
- les chutes sous la map ;
- les problèmes de caméra ;
- les objets sans collision ;
- les erreurs JavaScript bloquant le jeu ;
- les problèmes de chargement des assets ;
- les performances trop faibles sur mobile.

📁 Structure générale

.
├── .grok/
├── artifacts/
├── attachments/
├── migrations/
├── public/
├── src/
├── package.json
├── package-lock.json
├── vite.config.*
└── README.md

La structure exacte peut évoluer au fur et à mesure du développement.

🔮 Roadmap

Gameplay

- [ ] Améliorer les déplacements
- [ ] Ajouter davantage d'interactions
- [ ] Améliorer la conduite
- [ ] Ajouter plusieurs véhicules
- [ ] Ajouter davantage de bâtiments accessibles

Monde

- [ ] Agrandir progressivement la map
- [ ] Ajouter davantage de rues
- [ ] Ajouter davantage de végétation
- [ ] Ajouter des éléments urbains
- [ ] Ajouter des zones différentes

Technique

- [ ] Optimiser les performances mobiles
- [ ] Améliorer les collisions
- [ ] Optimiser le chargement des assets
- [ ] Améliorer le système de caméra
- [ ] Ajouter davantage de tests

📱 Compatibilité

Le projet est principalement destiné aux navigateurs modernes prenant en charge WebGL/WebGL2.

Il peut être exécuté sur :

- Windows
- Linux
- macOS
- Android
- autres appareils compatibles avec les technologies WebGL utilisées par le projet

Les performances peuvent varier selon l'appareil.

📜 Licence

Licence à définir.

Les assets, modèles, textures, sons et autres ressources ajoutés au projet doivent être originaux ou utilisés conformément à leur licence.

⚠️ Inspiration

Le projet s'inspire de l'esthétique générale des anciens jeux urbains en monde ouvert, notamment pour son ambiance et son approche du gameplay.

Il ne contient pas intentionnellement les assets propriétaires, personnages, véhicules, musiques, logos ou fichiers de Grand Theft Auto: San Andreas.

🤝 Contribution

Les contributions peuvent être proposées via :

- Issues
- Pull Requests
- améliorations du code
- corrections de bugs
- optimisation
- nouvelles fonctionnalités

Avant de proposer une modification importante, il est recommandé de vérifier qu'elle reste compatible avec l'architecture existante du projet.

---

Projet expérimental de jeu 3D — développement continu.
