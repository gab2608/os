# os
# App Lunettes (Web client)

Page web statique pour envoyer du texte à un serveur WebSocket sécurisé (wss). 

## Déploiement
- Publier ce repo sur GitHub.
- Activer GitHub Pages (branch `main` → `/ (root)`).
- Obtenir une URL `https://<user>.github.io/<repo>/`.

## Utilisation
1. Lance le proxy WebSocket→TCP (`proxy.py`) sur ton PC/serveur (voir proxy.py).
2. Expose le proxy via `ngrok http 8765` → récupère l'URL `https://<id>.ngrok.io`.
3. Dans la page web (sur iPhone), renseigne l'adresse WSS: `wss://<id>.ngrok.io`.
4. Connecte puis envoie ton texte.
