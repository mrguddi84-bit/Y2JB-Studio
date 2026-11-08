<div align="center">

<img src="assets/y2jb-studio-banner.png" alt="Y2JB Studio — FTP Manager, Y2JB Manager et Theme Manager" width="100%">

# Y2JB Studio

### Un espace de travail. Trois gestionnaires. Votre flux homebrew PS5.

**Vérifier · Télécharger · Installer · Créer · Transférer**  
Un flux homebrew PS5 guidé par boutons sous Windows.

**Langue :** [English](README.md) · [Deutsch](README.de.md) · [Español](README.es.md) · **Français** · [Português](README.pt.md)

[**Télécharger Y2JB Studio v1.0**](https://github.com/mrguddi84-bit/Y2JB-Studio/releases/latest) · [Démarrage rapide](#-démarrage-rapide) · [Fonctions](#-fonctions) · [Crédits](#-crédits-et-remerciements)

</div>

---

## ✨ Découvrez Y2JB Studio

Y2JB Studio réunit les vérifications de connexion PS5, la configuration FTP, la gestion Y2JB et la création de thèmes dans une application Windows. Ses gestionnaires guident les téléchargements, transferts et étapes de configuration pris en charge avec des indicateurs d’état clairs.

| FTP Manager | Y2JB Manager | Theme Manager |
| --- | --- | --- |
| Détecter FTP, télécharger des payloads pris en charge et configurer l’accès. | Vérifier les prérequis Y2JB, récupérer les fichiers nécessaires et guider leur transfert. | Créer des thèmes à partir de PNG, les générer et les transférer, et modifier les noms pris en charge. |
| **Détecter · Télécharger · Configurer · Connecter** | **Vérifier · Télécharger · Transférer · Mettre à jour** | **Créer · Générer · Charger · Renommer** |

> Y2JB Studio est un outil homebrew indépendant de la communauté. Il n’est ni affilié à Sony Interactive Entertainment, ni approuvé par cette société.

## 🚀 Fonctions

### 📊 Dashboard — connexion et état de préparation

- Afficher l’état de connexion PS5 et vérifier si un service FTP est accessible.
- Vérifier que l’ELF Loader configuré répond sur le port **9021**.
- Effectuer des vérifications en lecture seule des dossiers Y2JB, des icônes requises et de leur protection.
- Afficher les diagnostics de préparation des transferts de thèmes et les prérequis de l’éditeur de noms d’applications.
- Vérifier la disponibilité de `app.db` et `appinfo.db`.
- Voir l’état de FTP Manager, Y2JB Manager et Theme Manager au même endroit.

Les diagnostics sont en lecture seule et ne modifient pas intentionnellement les fichiers PS5.

### 🌐 FTP Manager — configuration guidée de payloads externes

- Vérifier si un service FTP est accessible sur la PS5.
- Télécharger au besoin des payloads pris en charge tels que [**ftpsrv**](https://github.com/ps5-payload-dev/ftpsrv) ou [**zftpd**](https://github.com/seregonwar/zftpd) depuis leurs projets d’origine. **Aucun de ces payloads n’est inclus dans Y2JB Studio.**
- Guider les étapes de transfert et de configuration prises en charge pour rendre un payload disponible dans Payload Manager sur PS5.
- Transférer des fichiers une fois qu’un serveur FTP fonctionne.

L’ELF Loader et un serveur FTP sont deux services différents. Pour une première configuration, Y2JB Studio peut utiliser l’ELF Loader accessible afin de démarrer un payload pris en charge.

### ⚙️ Y2JB Manager — installation et mises à jour

- Détecter la région de la console et sélectionner les fichiers Y2JB correspondants.
- Télécharger les fichiers requis et vérifier leurs sommes SHA-256.
- Guider les transferts FTP protégés vers la destination PS5 prévue.
- Vérifier l’état de l’installation YouTube/Y2JB et guider la configuration ou les mises à jour prises en charge.
- Le propriétaire du projet a confirmé les tests d’installation du PKG YouTube avec **Prospero Manager**.
- Modifier le nom de l’application Y2JB à l’aide de l’éditeur intégré et de ses sauvegardes.

### 🎨 Theme Manager — créer, générer, transférer et renommer

- Choisir des icônes et arrière-plans PNG depuis vos dossiers.
- Convertir et générer un paquet de thème compatible Y2JB.
- Enregistrer, ouvrir, importer et organiser des projets dans la bibliothèque de thèmes locale.
- Transférer les thèmes pris en charge vers la PS5 via FTP.
- Modifier les noms d’applications Y2JB pris en charge avec la procédure de sauvegarde.

### 🌍 Cinq langues d’interface

Deutsch · English · Español · Français · Português

L’application conserve la langue choisie pour les prochains démarrages.

## 📦 Prérequis

- Un **PC Windows**.
- Une **PS5 jailbreakée** avec **ELF Loader (elfldr) accessible sur le port 9021**.

Le PC et la PS5 doivent pouvoir communiquer sur le réseau. Y2JB Studio peut télécharger et configurer les autres composants FTP et Y2JB pris en charge depuis ses gestionnaires. Une connexion Internet est nécessaire pour les téléchargements.

## ⚡ Démarrage rapide

1. Télécharger **Y2JB_Studio_v1.0_Portable.exe** depuis [GitHub Releases](https://github.com/mrguddi84-bit/Y2JB-Studio/releases/latest).
2. Lancer l’EXE portable sous Windows ; aucun installateur n’est nécessaire.
3. Saisir l’adresse IP de la PS5 dans Dashboard et lancer les vérifications de connexion et de préparation.
4. Ouvrir **FTP Manager** pour vérifier FTP ou suivre la configuration guidée du payload.
5. Ouvrir **Y2JB Manager** pour vérifier la région, télécharger les fichiers requis et suivre la procédure guidée.
6. Ouvrir **Theme Manager** pour créer un thème à partir de PNG, le générer et le transférer par FTP.

Sauvegardez les données importantes de la console avant toute modification. Vérifiez la cible et les confirmations avant un transfert ou une modification de base de données.

## 🛡️ Sécurité et réseau

Les connexions FTP ne sont pas chiffrées. Utilisez un réseau local de confiance et vérifiez l’adresse PS5 avant tout transfert. La configuration, les transferts et la modification des noms peuvent changer les données de la console. Conservez vos sauvegardes.

## 🤝 Crédits et remerciements

Développé par **MrGee avec l’aide de l’IA**.

| Projet / contributeurs | Contribution |
| --- | --- |
| [itsPLK](https://github.com/itsPLK/ps5-y2jb-autoloader) | Y2JB Autoloader utilisé par le flux Y2JB |
| [Contributeurs ftpsrv](https://github.com/ps5-payload-dev/ftpsrv) | Payload FTP PS5 externe ; téléchargé si nécessaire, non inclus |
| [Seregon et contributeurs zftpd](https://github.com/seregonwar/zftpd) | Payload FTP PS5 externe ; téléchargé si nécessaire, non inclus |
| TheWizWikii / PS5-Stuff | Sources du PKG YouTube référencées par l’application |
| Contributeurs de Qt for Python, Python, Pillow, ispc_texcomp, certifi, Tcl/Tk et PyInstaller | Frameworks, runtime et empaquetage |

Plus d’informations : [CREDITS.md](CREDITS.md), [THIRD_PARTY_LICENSES.md](THIRD_PARTY_LICENSES.md) et [LICENSE](LICENSE). Les composants tiers conservent leurs licences respectives.

## 📄 Release et vérification

Le dépôt public contient la documentation et la bannière, pas le code source de l’application. L’application portable est distribuée dans les Releases. La somme SHA-256 figure dans [RELEASE_CHECKSUMS.txt](RELEASE_CHECKSUMS.txt).

## 📣 Releases et assistance

- [Télécharger les releases](https://github.com/mrguddi84-bit/Y2JB-Studio/releases)
- [Signaler un problème ou proposer une fonction](https://github.com/mrguddi84-bit/Y2JB-Studio/issues)

Pour signaler un problème, indiquez les versions de Studio et Windows, le gestionnaire concerné et les étapes de reproduction. Ne publiez pas vos identifiants de console ni des détails réseau privés.

