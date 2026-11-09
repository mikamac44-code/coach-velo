# Coach Vélo

Première version PWA du coach d'entraînement cycliste, en français.

## Fonctionnalités de cette version

- Planning hebdomadaire responsive (ordinateur et mobile).
- Sortie club du samedi matin conservée comme rendez-vous fixe.
- Indisponibilités datées et réorganisation simple des séances.
- Prise en compte des créneaux RPM et BodyPump configurables.
- Suivi quotidien de fatigue, sommeil et motivation.
- Retour après séance : durée réelle et RPE.
- Zones de puissance indicatives calculées depuis la FTP renseignée.
- Sauvegarde locale dans le navigateur et export/import JSON.
- Mise en cache PWA pour réouverture hors ligne après premier chargement.

## Mise en ligne sur GitHub Pages

Dans le dépôt GitHub : **Settings → Pages → Build and deployment → Deploy from a branch**. Choisir la branche `main` et le dossier `/ (root)`, puis enregistrer. Attendre la fin du déploiement. L'adresse du site sera de la forme :

`https://mikamac44-code.github.io/coach-velo/`

Sur iPhone : ouvrir cette adresse dans Safari → bouton **Partager** → **Sur l’écran d’accueil**.

## Limites connues — version 0.1

- Les données restent sur le navigateur/appareil : aucune synchronisation entre iPhone et ordinateur.
- Garmin Connect n'est pas connecté.
- Les fichiers FIT ne sont pas encore lus ; l'analyse des séries temporelles, puissance normalisée, fréquence cardiaque, TSS/IF et validation FTP restent à développer.
- La réorganisation est une première logique à règles, pas encore un coach physiologique complet. Elle ne remplace pas l'analyse de la charge réelle et de la récupération.
- La FTP de 206 W et le poids de 75 kg sont des valeurs de départ déclarées, à confirmer/actualiser.

Ne jamais ajouter de mot de passe, jeton Garmin, clé API ou fichier de données personnelles au dépôt public.
