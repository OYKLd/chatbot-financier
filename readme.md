/chatbot-financier
│── /frontend       # Interface utilisateur (site web)
│   ├── /assets     # Images, icônes, fichiers CSS
│   ├── index.html  # Page principale
│   ├── styles.css  # Styles CSS
│   ├── script.js   # Logique frontend (Appel API, vocal, affichage)
│   ├── chat.js     # Gestion du chatbot (envoi des messages, affichage)
│   ├── speech.js   # Gestion du vocal (reconnaissance + lecture)
│── /backend        # API Node.js (Chatbot)
│   ├── /config     # Fichiers de configuration (Firebase, API Keys)
│   ├── /routes     # Routes API (chatbot, utilisateur)
│   │   ├── chatbot.js  # Route pour gérer les requêtes OpenAI
│   │   ├── user.js     # Route pour gérer les utilisateurs
│   ├── /controllers   # Logique métier (traitement des données)
│   ├── /models        # Modèles pour les données (si besoin)
│   ├── /utils         # Fonctions utiles (traduction, notifications)
│   ├── server.js  # Fichier principal du backend (Express.js)
│   ├── package.json  # Dépendances du backend (Node.js)
│── /firebase        # Firebase Functions (si backend hébergé sur Firebase)
│   ├── index.js     # Point d'entrée des fonctions Firebase
│── .gitignore       # Exclure node_modules, API keys
│── README.md        # Explication du projet
