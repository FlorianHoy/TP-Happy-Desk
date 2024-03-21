# TP-Happy-Desk

## Étapes

1. **Créer le repository Github.**
2. **Créer une Web App sur Azure** et vérifier que dans la partie déploiement l'Authentification de base est activée.
3. Pour mettre en place la pipeline, il faudra aller sur le projet, puis dans la section **Actions** cliquer sur **New Workflow**.
4. Pour la configuration du Workflow, sélectionner **Deploy a Python app to an Azure Web App**. Ensuite dans le fichier YML, il faudra modifier le **AZURE_WEBAPP_NAME** avec le nom de votre web app Azure, puis changer la version de python si besoin.
5. Ensuite pour faire la connexion avec Azure, allez sur la Web App et télécharger le profil de publication. Sur Github, il faudra aller sur le projet dans **settings** puis cliquer sur **Secret and Variables** puis **Actions**.
6. Créer un **New Secret Repository AZURE_WEBAPP_PUBLISH_PROFILE** en mettant le contenu de votre profil de publication puis enregistrer.
7. Se rendre dans **Actions** sur le projet Github pour vérifier le bon fonctionnement de la pipeline.
8. Une fois que la pipeline est active, allez sur le domaine par défaut de Web App pour vérifier que son contenu s'affiche bien.
9. Pour vérifier que les modifications s'effectuent bien, il faudra modifier le contenu de **app.py** puis aller sur la page web pour vérifier.
