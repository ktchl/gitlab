# gitlab

Installation de l'environnement de deploiement de l'application avec un cluster Kubernetes. 
Ce cluster aura 4 environnements de deploiments: dev, QA, staging, et prod.
Création d'un fichier gitlab-ci.yml qui définira l'ensemble des Jobs à exécuter pour le pipeline.
Création des charts HELM à partir du fichier docker-compose.yml.
Deploiement de l'application manuellement si la branche concernée est la branche main.
Automatisation pour le pipeline CI/CD
