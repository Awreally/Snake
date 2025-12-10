# Snake
A multiplayer snake game


snake-multiplayer/
│
├── index.html
├── style.css
│
└── js/
    ├── main.js                    # Initierar och startar spelet
    ├── constants.js               # Alla konstanter (färger, storlekar, hastighet)
    ├── Snake.js                   # Snake-klass
    ├── GameBoard.js              # Spelplan + kollisioner
    ├── Game.js                   # Huvudspel-logik + game loop
    ├── Renderer.js               # Rita allt på skärmen
    ├── InputHandler.js           # Tangentbordshantering
    ├── ScoreManager.js           # localStorage + scoreboard
    ├── MultiplayerApi.js         # FÄRDIG (från utbildaren)
    └── MultiplayerManager.js     # Din multiplayer-logik