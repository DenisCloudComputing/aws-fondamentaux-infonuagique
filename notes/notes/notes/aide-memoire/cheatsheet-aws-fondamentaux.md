# 📋 Aide-Mémoire — AWS Fondamentaux

## ☁️ Les 3 modèles de service
| Modèle | Toi tu gères | Exemple AWS |
|--------|-------------|-------------|
| IaaS | OS + Apps + Data | EC2 |
| PaaS | Apps + Data | Elastic Beanstalk |
| SaaS | Data seulement | WorkMail |

## 🌍 Régions principales
| Code               | Localisation  |
|--------------------|---------------|
| `ca-central-1`     | Montréal 🇨🇦   |
| `us-east-1`        | Virginie 🇺🇸   |
| `us-west-2`        | Oregon 🇺🇸     |
| `eu-west-3`        |  Services essentiels AWS
| Service | Catégorie | Ça fait quoi |
|---------|----------|-------------|
| EC2 | Calcul | Machine virtuelle dans le cloud |
| S3 | Stockage | Stockage de fichiers illimité |
| RDS  | Base de données | Base de données managée |
| VPC | Réseau | Réseau privé virtuel |
| IAM | Sécurité     | Gestion des accès et permissions |
| Lambda | Calcul    | Code sans serveur (serverless) |
| CloudWatch         | Monitoring | Surveillance et alertes |
| SNS                | Notification | Envoi de messages et alertes |
| CloudFormation | IaC | Infrastructure en code |
| Route 53 | DNS | Noms de domaine |

 Modèles de tarification
| Modèle | Explication | Exemple |
|--------|------------|---------|
| À la demande | Tu paies par heure/seconde | EC2 On-Demand |
| Réservé | Tu t'engages 1-3 ans = rabais | EC2 Reserved |
| Spot | Tu enchéris = très pas cher mais peut s'arrêter | EC2 Spot |
| Gratuit | Free Tier 12 mois | 750h EC2 t2.micro/mois |

 Responsabilité partagée

 AWS gère :                        Toi tu gères :
─────────────                      ──────────────
Matériel physique                   Tes données
Réseau mondial                      Tes applications
Hyperviseur                         Configuration sécurité
Électricité                         Permissions IAM
Refroidissement                     Mises à jour OS (si EC2)
Sécurité physique                    Chiffrement


---
Aide-mémoire mis à jour au fil de ma formation
