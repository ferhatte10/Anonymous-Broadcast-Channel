## Description
Le but de cette deuxième (TP) est d'implémenter un mécanisme de génération de secret via l'implémentation d'un canal de diffusion anonyme. Un canal de diffusion anonyme permet d'envoyer un message à tous les participants d'un réseau sans révéler l'identité de l'expéditeur (à moins que celui-ci ne choisisse d'inclure explicitement son identité dans le message). Un exemple concret d'un tel canal est un forum sur Internet qui autorise le dépôt de messages sans nécessiter d'identification. À noter que dans ce cas, le canal possède la propriété supplémentaire d'être asynchrone, ce qui signifie qu'il ne nécessite pas la présence des utilisateurs en ligne au moment de l'envoi des messages, tout en permettant à quiconque de consulter les messages ultérieurement.

Pour ce TP, nous travaillons dans un modèle où l'adversaire est passif, c'est-à-dire qu'il se contente d'écouter les communications, telles que le canal de diffusion anonyme, sans chercher activement à tromper en postant par exemple de faux messages. Le TP lui-même est divisé en trois parties.

## Auteur
- [**Ferhat SAIDOUN**](https://github.com/ferhatte10)
- [**Zakaria RAJI**](https://github.com/RAJI-Zakaria)
