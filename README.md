# mobile-security-lab
Lab 1 Sécurité des applications mobiles – Mobexler & Genymotion
## Objectif
Mettre en place un environnement de test pour la sécurité des applications mobiles en utilisant Mobexler et Genymotion avec une connexion ADB.
## Environnement
- Hyperviseur : VirtualBox
- VM : Mobexler
- Émulateur : Genymotion
- Android : API 35
- Réseau :
  - Adapter 1 : NAT
  - Adapter 2 : Host-Only
## Étape 1 – Démarrage de Mobexler
![Mobexler Login](screenshots/1.png)
## Étape 2 – Création du snapshot CLEAN
![Snapshot CLEAN Baseline](screenshots/2.png)
## Étape 3 – Vérification de la configuration réseau de la VM Mobexler
![Configuration réseau Mobexler](screenshots/3.png)
## Étape 4 – Vérification de la table de routage de la VM Mobexler
![Table de routage Mobexler](screenshots/4.png)
## Étape 5 – Vérification de la connectivité Internet de la VM Mobexler
![Connectivité Internet Mobexler](screenshots/5.png)
## Étape 6 – Lancement de l’émulateur Android avec Genymotion
![Émulateur Android démarré sur Genymotion](screenshots/6.png)
## Étape 7 – Démarrage du système Android sur l’émulateur
![Écran d’accueil Android sur Genymotion](screenshots/7.png)
## Étape 8 – Informations du terminal Android sur Genymotion
![ADB Information](screenshots/8.png)
## Étape 9 – Connexion ADB réussie entre Mobexler et le terminal Genymotion
![ADB Connection](screenshots/9.png)
## Conclusion
Ce premier lab m'a permis de mettre en place un environnement fonctionnel pour l’analyse de la sécurité des applications mobiles en utilisant Mobexler et Genymotion. La configuration réseau ainsi que la connexion ADB entre la machine d’analyse et l’émulateur Android ont été validées avec succès. 
