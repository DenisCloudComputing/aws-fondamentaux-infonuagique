 02 — Les Modèles de Service : IaaS, PaaS, SaaS

 Vue d'ensemble
 ANALOGIE AVEC LA PIZZA :

 On-Premise (tout maison)
Tu fais TOUT : la pâte, la sauce, le four, la table
= Tu gères TOUTE l'infrastructure informatique

IaaS — Infrastructure as a Service (ex: AWS EC2)
Tu reçois un four et des ingrédients
Tu fais ta pizza toi-même
= AWS te donne des serveurs, TU installes le reste

 PaaS — Platform as a Service (ex: AWS Elastic Beanstalk)
Tu reçois une pizza prête à garnir
Tu ajoutes tes garnitures
= AWS gère le serveur, TU déploies ton application

 SaaS — Software as a Service (ex: Gmail, Office 365)
Tu commandes une pizza livrée chez toi
Tu manges, c'est tout
= Tu utilises le logiciel, AWS gère TOUT le reste


## Tableau comparatif

| Aspect   | On-Premise | IaaS | PaaS | SaaS |      |
|--------  |------------|------|------|------|      |
| Réseau                 | Toi | AWS  | AWS  | AWS  |
| Serveurs               | Toi | AWS  | AWS  | AWS  |
| Stockage               | Toi | AWS  | AWS  | AWS  |
| Données                | Toi | Toi  | Toi  | Toi  |

## Exemples concrets AWS

| Modèle | Service AWS | Tu gères | AWS gère |
|--------|-----------|----------|----------|
| IaaS | EC2 | OS, apps, données | Serveur physique, réseau |
| PaaS | Elastic Beanstalk | Code de l'app | Serveur, OS, scaling |
| SaaS | Amazon WorkMail | Tes emails | Absolument tout le reste |

 Lequel choisir ? 
Plus de CONTRÔLE ←──────────────→ Plus de FACILITÉ
IaaS                             PaaS                    SaaS
"Je veux tout contrôler" "Je veux un équilibre" "Je veux juste utiliser"


---
Notes de cours — Formation Cloud Computing, Collège de Bois-de-Boulogne
