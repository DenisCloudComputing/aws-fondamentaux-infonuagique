 03 — L'Infrastructure Mondiale AWS

 Vue d'ensemble

 LA PLANÈTE AWS :

 33+ Régions dans le monde
│
├── Chaque région = 2 à 6 Zones de Disponibilité (AZ)
│ │
│ ├── Chaque AZ = 1 ou plusieurs data centers
│ │
│ └── Les AZ sont reliées par réseau ultra-rapide
│ mais physiquement séparées (tremblement de terre,
│ inondation ne touche pas les 2 en même temps)
│
└── 600+ Points de présence (Edge Locations)
Pour le contenu rapide (CloudFront CDN)


## Régions importantes pour nous

| Code | Nom | Pourquoi c'est important |
|------|-----|-------------------------|
| `ca-central-1` | Canada (Montréal) 🇨🇦 | Notre région locale ! Données restent au Canada |
| `us-east-1` | Virginie du Nord 🇺🇸 | Région la plus ancienne, tous les services |
| `eu-west-3` | Paris 🇫🇷 | Pour les clients européens francophones |

## Comment choisir sa région ?

| Critère | Question à se poser |
|---------|-------------------|
| Conformité légale | Les données DOIVENT-elles rester au Canada ? |
| Latence | Mes utilisateurs sont-ils proches de cette région ? |
| Services disponibles | Le service dont j'ai besoin existe-t-il dans cette région ? |
| Coût | Les prix varient d'une région à l'autre |

## Pourquoi c'est important en Cloud ?
SCÉNARIO :
Ton client est une banque canadienne
→ Les données financières DOIVENT rester au Canada (loi)
→ Tu DOIS utiliser ca-central-1 (Montréal)
→ Tu NE PEUX PAS utiliser us-east-1 (USA)

C'est une question de CONFORMITÉ, pas juste de technique.


SCÉNARIO :
Ton client est une banque canadienne
→ Les données financières DOIVENT rester au Canada (loi)
→ Tu DOIS utiliser ca-central-1 (Montréal)
→ Tu NE PEUX PAS utiliser us-east-1 (USA)

C'est une question de CONFORMITÉ, pas juste de technique.


---
Notes de cours — Formation Cloud Computing, Collège de Bois-de-Boulogne
