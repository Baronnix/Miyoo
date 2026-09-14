# ⭐ Installer Onion OS sur une autre carte SD

On passe maintenant à Onion OS, l’un des systèmes les plus populaires pour la Miyoo Mini+. Je vais te montrer comment l’installer sur une carte SD dédiée, comment le configurer, et pourquoi il change complètement l’expérience d’émulation.

# 📺 Vidéo

Lien Youtube: [https://www.youtube.com/@Baronnix/playlists](https://www.youtube.com/@Baronnix/playlists)

# 🎯 Objectifs de l’épisode

* Télécharger Onion OS
* Préparer une carte SD (formatage, copie des fichiers).
* Démarrer Onion OS pour la première fois.
* Configurer les modules essentiels (thèmes, émulateurs, options).
* Ajouter des jeux (sans fournir de fichiers protégés).
* Comparer rapidement avec Telmi OS pour comprendre les usages.

# 📦 Matériel nécessaire

* Miyoo Mini Plus
* Carte Micro-SD + lecteur
* Un ordinateur (tutoriel réalisé sur Windows)

# 1️⃣ Télécharger Onion OS

## 📥 Lien officiel

👉 Onion OS — GitHub officiel : https://github.com/OnionUI/Onion

## 📦 Fichiers à récupérer

Sur la page GitHub :
1. Clique sur Releases
2. Télécharge le fichier : Onion-OS-X.X.X.zip (version la plus récente)

Ce ZIP contient :
* Les fichiers système
* Les dossiers nécessaires à l’installation
* Les modules Onion

# 2️⃣ Préparer la carte SD

## 🧽 Formater la carte SD

1. Insère la carte SD dans ton PC.
2. Ouvre l’outil de formatage :
    * Windows : Explorateur → clic droit → Formater
    * macOS : Utilitaire de disque → Effacer
3. Choisis :
    * FAT32 (obligatoire)
    * Allocation : 32K (si disponible)
4. Lance le formatage.

## 🔍 Vérification

La carte doit être vide et propre avant installation.

# 3️⃣ Installer Onion OS

## 📁 Copier les fichiers

1. Ouvre le ZIP Onion OS
2. Copie tous les fichiers et dossiers à la racine de la carte SD
    * Pas de dossier supplémentaire
    * Pas de renommage
3. Éjecte proprement la carte SD

## 🔄 Premier démarrage

1. Insère la carte SD dans la Miyoo Mini+
2. Allume la console
3. Onion OS va :
    * Installer automatiquement les modules
    * Créer les dossiers /roms/, /bios/, /saves/
    * Redémarrer une fois l’installation terminée

# 4️⃣ Configurer Onion OS

## ⚙️ Paramétrage initial

Dans le menu Onion :
* Choisir le thème
* Régler la luminosité
* Configurer les boutons
* Activer/désactiver les modules (émulateurs, outils)

## 🧩 Modules importants

* SimpleMenu : interface simplifiée
* RetroArch : émulation avancée
* Onion Tools : gestion des sauvegardes, BIOS, etc.

# 5️⃣ Ajouter des jeux (ROMs)

## 📁 Structure des dossiers

Sur la carte SD, Onion crée automatiquement :
```
/roms/
/bios/
/saves/
```

## 📥 Copier les ROMs

1. Ouvre le dossier /roms/
2. Choisis la console (ex : gb, gba, psx, nes)
3. Copie tes ROMs dans le dossier correspondant

⚠️ Important  
Tu ne dois pas partager ou distribuer des ROMs protégées par copyright. Utilise les ROMs fournis sur l'OS initial.

## 📁 Ajouter les BIOS (si nécessaires)

Certaines consoles nécessitent un BIOS :
* PS1 → scph1001.bin
* GBA → facultatif
* NeoGeo → fichiers .zip spécifiques

Place-les dans :
```
/bios/
```

# 6️⃣ Optimisations recommandées

## 🚀 Performance

* Utiliser une carte SD rapide (Sandisk Ultra, Samsung Evo)
* Éviter les cartes SD noname
* Activer le frameskip pour les consoles exigeantes

## 🎨 Interface

* Installer des thèmes Onion supplémentaires via GitHub
* Activer les icônes animées (optionnel)

## 🛡️ Sécurité

* Toujours éjecter la carte SD proprement
* Faire une sauvegarde du dossier /saves/

# 7️⃣ Tester Onion OS

## Vérifications

* Lancer plusieurs émulateurs
* Tester les sauvegardes
* Vérifier les performances
* Tester les modules Onion Tools