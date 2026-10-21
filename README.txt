MoonBae — Live direct intégré au site

Fichier principal : index.html

Fonctionnement :
- Ouvrir l'espace créateur et cliquer sur « Démarrer mon live ».
- Autoriser la caméra et le micro.
- Garder cette page ouverte pendant toute la diffusion.
- Les visiteurs qui ouvrent le site essaient de se connecter automatiquement au live et voient la vidéo dans la section MoonBae LIVE, sans quitter le site et sans compte client.
- Cliquer sur « Terminer le live » pour couper la caméra et le micro.

Important :
- La caméra nécessite un site publié en HTTPS (ou localhost pour tester).
- Le direct utilise WebRTC et le serveur public de signalisation PeerJS chargé depuis Internet. Il n'y a pas de serveur vidéo dédié; le fonctionnement dépend des réseaux/navigateurs et de la disponibilité du service public. Certains réseaux peuvent empêcher la connexion, et le direct peut être limité si beaucoup de spectateurs se connectent.
- Teste avec deux appareils et deux réseaux avant de l'annoncer publiquement.
- Le lien fixe de diffusion est public : toute personne connaissant le site peut tenter de regarder pendant le live. Ne diffuse pas d'informations personnelles ni d'images privées.
- Le mot de passe de l'espace créateur est toujours présent côté navigateur dans ce prototype et n'est pas sécurisé pour une vraie exploitation.
- Le formulaire de commandes Netlify reste à configurer dans le tableau de bord Netlify.
