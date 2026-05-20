Active Directory Enterprise Lab
Objectif

Déploiement d’une infrastructure Active Directory simulant un environnement d’entreprise sous Windows Server dans GNS3.

Objectifs :

segmentation logique des équipes,
gestion centralisée des utilisateurs,
sécurisation des accès,
permissions NTFS,
stratégies GPO,
redondance Active Directory.

━━━━━━━━━━━━━━━

Architecture
NAT
│
Switch
├── DC1
├── DC2
└── SRV1

Puis :

DC1 : contrôleur principal
DC2 : contrôleur secondaire + Global Catalog
SRV1 : serveur fichiers

━━━━━━━━━━━━━━━

Technologies utilisées
Windows Server 2022
Active Directory
DNS
GPO
NTFS
AGDLP
GNS3

━━━━━━━━━━━━━━━

Structure Active Directory
stellar.local
├── Stellar Teams
│   ├── Engineering
│   ├── Marketing
│   └── HR
├── Servers
├── Groups
└── Policies

━━━━━━━━━━━━━━━

Gestion utilisateurs et groupes

Mise en place du modèle AGDLP :

utilisateurs,
groupes globaux,
groupes locaux domaine,
permissions NTFS.

Exemple :

GG_Engineering_Read
DL_Share_Engineering

━━━━━━━━━━━━━━━

Serveur fichiers & permissions NTFS

Partages :

Permissions :

accès restreint par groupes AD,
isolation entre départements,
permissions NTFS sécurisées.

━━━━━━━━━━━━━━━

Group Policy Objects

GPO configurées :

WallpaperPolicy
SecurityPolicy
PasswordPolicy

Fonctionnalités :

désactivation CMD,
restriction registre,
verrouillage compte,
mot de passe minimum,
mapping lecteurs réseau via GPP.

━━━━━━━━━━━━━━━

Sécurité et redondance
Double Domain Controller
DNS intégré
Global Catalog
Test résilience après arrêt DC1

━━━━━━━━━━━━━━━

Compétences développées
Administration Active Directory
Gestion GPO
Permissions NTFS
DNS Windows
Gestion identité et accès
Architecture Windows entreprise
Sécurité opérationnelle

━━━━━━━━━━━━━━━
