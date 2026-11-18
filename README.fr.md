<p align="center">
  <a href="README.md">English</a>
  &nbsp;·&nbsp;
  <a href="README.fr.md"><b>Français</b></a>
  &nbsp;·&nbsp;
  <a href="README.es.md">Español</a>
</p>

# n8n-render (mode simple)

Fork de [antoineDsh/n8n-render-lamachine](https://github.com/antoineDsh/n8n-render-lamachine).

Fichiers : `Dockerfile`, `render.yaml`, `README.md`.

Déployer n8n sur render.com :

1. Cliquer le bouton Render du README anglais
2. Choisir un nom de blueprint, par exemple « n8n »
3. Cliquer sur « Create New Ressources »
4. Appliquer
5. Aller dans Dashboard > n8n (nom du service) > Environment
6. Copier l'URL (lien violet de l'en-tête)
7. Coller cette URL comme valeur de `WEBHOOK_URL`
8. Attendre une minute la mise à jour
9. L'instance est prête

Le README anglais indique que l'instance est gratuite 90 jours, puis 7 $/mois pour la base. Il est signé Antoine Deschamps pour La Machine.
