petits_chevaux/
│
├── main.py                # Fichier principal pour exécuter le jeu
├── environment/
│   ├── ludo_env.py        # Classe de l'environnement Gymnasium
│   ├── board.py           # Gestion de la logique et des règles du jeu
│   ├── player.py          # Modèle pour un joueur (humain ou IA)
│   └── utils.py           # Fonctions utilitaires (gestion de dés, état, etc.)
├── training/
│   ├── train_agent.py     # Script pour entraîner un agent
│   ├── evaluate_agent.py  # Script pour tester un agent
│   └── agents/
│       ├── random_agent.py  # Exemple d'agent aléatoire
│       └── rl_agent.py      # Agent RL utilisant Stable-Baselines3
├── data/                  # (optionnel) Sauvegardes ou logs d'entraînement
└── README.md              # Documentation du projet
