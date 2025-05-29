# 🏘️ WindevGestionLocative

**WindevGestionLocative** est une application bureautique de gestion locative développée avec **WinDev**. Elle s’adresse aux propriétaires ou gestionnaires de biens immobiliers (appartements, maisons, etc.) pour assurer un suivi complet des locations, paiements, contrats et locataires.

---

## ✨ Fonctionnalités principales

- Gestion des biens immobiliers
- Gestion des locataires
- Suivi des contrats de location
- Paiement des loyers + génération de quittances
- Rapports sur l’occupation et les impayés
- Interface bureautique avec fenêtres WinDev

---

## 🛠️ Technologies utilisées

| Élément         | Détail            |
|-----------------|-------------------|
| Langage         | WLangage (WinDev) |
| IDE             | WinDev 28+        |
| Base de données | HFSQL             |
| Interface       | WinDev fenêtres   |
| Fichiers        | `.wdp`, `.wdd`, `.fic`, `.ndx` |

---

## 📁 Structure du projet

```
WindevGestionLocative/
├── BDD_GestionLocation.wdp # Fichier principal du projet WinDev
├── BDD_GestionLocation.wdd # Analyse des données (base HFSQL)
├── .gitignore # Fichiers à ignorer par Git
├── Exe/ # Fichiers exécutables compilés
├── Gabarits/ # Gabarits utilisés dans les impressions
├── Images/ # Logos et icônes de l'app
├── Sauvegarde/ # Backups du projet
├── STAT_GestionLocation.sta # Statistiques de l'analyse
└── README.md # Ce fichier de documentation
```

---

## ✅ Prérequis

- **Windows** 10/11
- **WinDev 28** ou version supérieure
- Git installé (pour cloner le dépôt)
- Aucune dépendance externe nécessaire

---

## 🚀 Installation et lancement

### 1. Cloner le projet

```bash
git clone https://github.com/MrSalifDiallo/WindevGestionLocative.git
```
2. Ouvrir avec WinDev
- Lancer WinDev
- Menu → Fichier → Ouvrir un projet
- Sélectionner BDD_GestionLocation.wdp dans le dossier cloné

3. Vérifier l’analyse
- Ouvrir BDD_GestionLocation.wdd
- Vérifier que toutes les tables HFSQL sont bien présentes
- Générer les fichiers de la base si besoin (.fic, .ndx)

4. Compiler le projet
- Dans WinDev : Projet → Compiler
- Cliquer ensuite sur le bouton GO pour exécuter

## 📌 Conseils d’amélioration
Voici quelques idées pour faire évoluer ton projet :

- 🔒 Ajouter un système de connexion (authentification)

- 📊 Ajouter des dashboards avec graphiques (taux d’occupation, retards, etc.)

- 🌐 Version web avec WebDev (ou Flutter pour mobile)

- 💾 Export CSV / PDF des rapports

- 🧪 Intégrer des tests unitaires ou de validation

## 🙌 Contribution
Les contributions sont bienvenues !

Forker le projet

Créer une branche :
````bash
git checkout -b nouvelle-fonctionnalite
````
Commit tes changements :
````bash
git commit -m "Ajout d'une fonctionnalité X"
````
Push ta branche :
````bash
git push origin nouvelle-fonctionnalite
````
Créer une Pull Request sur GitHub

## 👤 Auteur

**Salif Diallo**  
💼 Développeur && passionné par les solutions de gestion  
📧 [salifdiallo@esp.sn](mailto:salifdiallo@esp.sn)  
🔗 [GitHub - MrSalifDiallo](https://github.com/MrSalifDiallo)  
🌍 Basé à Dakar, Sénégal
