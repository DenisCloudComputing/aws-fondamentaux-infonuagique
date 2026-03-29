 aws-fondamentaux-infonuagique
Concepts fondamentaux du cloud computing AWS  (IaaS, PaaS, SaaS, régions, services) — Formation Cloud Computing - Automatisation 

  AWS — Fondamentaux de l'Infonuagique

> Mes notes et travaux pratiques sur les concepts fondamentaux
> du cloud computing et des services AWS.

---

  Description

Ce repository documente mon apprentissage des concepts clés
du cloud computing : les modèles de service (IaaS, PaaS, SaaS),
l'infrastructure mondiale AWS, les services principaux et
les bonnes pratiques de l'industrie.

---

  Objectifs d'apprentissage

- Comprendre ce qu'est le cloud computing et ses avantages
- Différencier les modèles IaaS, PaaS et SaaS
- Connaître l'infrastructure mondiale AWS (régions, zones)
- Identifier les services AWS essentiels
- Comprendre le modèle de responsabilité partagée
- Naviguer dans la console AWS

---

  Technologies utilisées

| Technologie | Usage |
|-------------|-------|
| AWS Console | Interface de gestion cloud |
| AWS Free Tier | Compte gratuit pour pratiquer |
| Git | Versionnement des notes |

---

  Structure du repository

```
aws-fondamentaux-infonuagique/
│
├── README.md
├── .gitignore
├── LICENSE
│
├── notes/
│   ├── 01-quest-ce-que-le-cloud.md
│   ├── 02-modeles-iaas-paas-saas.md
│   ├── 03-infrastructure-mondiale-aws.md
│   ├── 04-services-essentiels-aws.md
│   └── 05-responsabilite-partagee.md
│
├── labs/
│   ├── lab-01-console-aws/
│   │   ├── README.md
│   │   └── captures/
│   └── lab-02-premier-service/
│       ├── README.md
│       └── captures/
│
├── diagrammes/
│   └── modeles-cloud.md
│
└── aide-memoire/
    └── cheatsheet-aws-fondamentaux.md
```

---

  Concepts clés

 Les 3 modèles de service cloud

```
┌─────────────────────────────────────────────────────────────┐
│                                                             │
│  CE QUE TU GÈRES vs CE QUE AWS GÈRE                        │
│                                                             │
│  On-Premise     IaaS          PaaS          SaaS            │
│  (tout toi)     (EC2)         (Elastic      (Gmail)         │
│                               Beanstalk)                    │
│                                                             │
│  ┌──────────┐  ┌──────────┐  ┌──────────┐  ┌──────────┐   │
│  │Application│  │Application│  │Application│  │██████████│   │
│  │          │  │          │  │██████████│  │██████████│   │
│  │ Runtime  │  │ Runtime  │  │██████████│  │██████████│   │
│  │          │  │          │  │██████████│  │██████████│   │
│  │    OS    │  │    OS    │  │██████████│  │██████████│   │
│  │          │  │          │  │██████████│  │██████████│   │
│  │ Serveur  │  │██████████│  │██████████│  │██████████│   │
│  │          │  │██████████│  │██████████│  │██████████│   │
│  │ Réseau   │  │██████████│  │██████████│  │██████████│   │
│  └──────────┘  └──────────┘  └──────────┘  └──────────┘   │
│                                                             │
│  Blanc = Toi    █ = AWS gère pour toi                       │
│                                                             │
│  Plus tu vas vers la droite, moins tu gères,                │
│  plus AWS fait le travail pour toi.                         │
│                                                             │
└─────────────────────────────────────────────────────────────┘
```

 L'infrastructure mondiale AWS

```
┌──────────────────────────────────────────────────────────┐
│                                                          │
│  AWS = Des data centers partout dans le monde             │
│                                                          │
│   Régions (Regions)                                     │
│  │  = Zones géographiques (ex: Canada, Paris, Virginie)  │
│  │  = Chaque région est INDÉPENDANTE                     │
│  │                                                       │
│  ├──  Zones de disponibilité (Availability Zones)      │
│  │   │  = 2-3+ data centers par région                   │
│  │   │  = Si un data center tombe, les autres prennent   │
│  │   │    la relève                                      │
│  │   │                                                   │
│  │   ├── ca-central-1a                                   │
│  │   ├── ca-central-1b                                   │
│  │   └── ca-central-1d                                   │
│  │                                                       │
│  Exemples de régions :                                    │
│  ca-central-1    = Canada (Montréal) 🇨🇦 ← La nôtre !   │
│  us-east-1       = Virginie du Nord 🇺🇸                   │
│  eu-west-3       = Paris 🇫🇷                              │
│  ap-northeast-1  = Tokyo 🇯🇵                              │
│                                                          │
└──────────────────────────────────────────────────────────┘
```

---

  Contenu

| # | Sujet | Description | Statut |
|---|-------|------------|--------|
| 01 | Qu'est-ce que le cloud | Définition, avantages, histoire |  Complété |
| 02 | Modèles IaaS PaaS SaaS | Les 3 modèles de service |  Complété |
| 03 | Infrastructure mondiale | Régions, AZ, edge locations |  En cours |
| 04 | Services essentiels AWS | EC2, S3, RDS, VPC, IAM |  À venir |
| 05 | Responsabilité partagée | Qui gère quoi entre toi et AWS |  À venir |

---

  Comment utiliser ce repo

```bash
# Cloner le repository
git clone https://github.com/DenisCloudComputing/aws-fondamentaux-infonuagique.git

# Accéder au dossier
cd aws-fondamentaux-infonuagique

# Lire les notes
cat notes/01-quest-ce-que-le-cloud.md
```

---

  Références

- [AWS Cloud Practitioner Essentials](https://aws.amazon.com/training/digital/aws-cloud-practitioner-essentials/)
- [AWS Well-Architected Framework](https://aws.amazon.com/architecture/well-architected/)
- [AWS Infrastructure mondiale](https://aws.amazon.com/about-aws/global-infrastructure/)
- [AWS Free Tier](https://aws.amazon.com/free/)

---

 👤 Auteur

Denis Eloundou — Étudiant en Cloud Computing
-  Collège de Bois-de-Boulogne
-  denielound@gmail.com
-  [Mon GitHub](https://github.com/DenisCloudComputing)

---

>  Ce repository fait partie de mon portfolio de formation en Cloud Computing
