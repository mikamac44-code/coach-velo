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

## Onglet Forme — première estimation

- Charge interne simplifiée calculée à partir des séances renseignées (durée × RPE).
- Comparaison de la charge récente sur 7 jours avec une base sur 28 jours, à interpréter avec prudence.
- Historique du ressenti de fatigue, sommeil et motivation enregistré au fil des check-ins.
- Échéance de forme cible positionnée autour de l’Étape du Tour de France Femmes du 8 août 2027. La fenêtre affichée est un objectif de planification, pas une prédiction physiologique.
- L’adaptation du planning peut alléger une séance intense en cas de fatigue déclarée ou de hausse inhabituelle de charge ; le samedi club reste fixe.

## Limites connues — version 0.2

- Les données restent sur le navigateur/appareil : aucune synchronisation entre iPhone et ordinateur.
- Garmin Connect n'est pas connecté.
- Les fichiers FIT ne sont pas encore lus ; l'analyse des séries temporelles, puissance normalisée, fréquence cardiaque, TSS/IF et validation FTP restent à développer.
- La charge actuelle est une estimation interne minutes × RPE, pas un TSS/CTL/ATL validé. Les indicateurs de forme restent provisoires et dépendent de la saisie régulière des séances.
- Le pic de forme n’est pas prédit automatiquement : la date d’objectif sert actuellement de repère de planification.
- La FTP de 206 W et le poids de 75 kg sont des valeurs de départ déclarées, à confirmer/actualiser.

Ne jamais ajouter de mot de passe, jeton Garmin, clé API ou fichier de données personnelles au dépôt public.
