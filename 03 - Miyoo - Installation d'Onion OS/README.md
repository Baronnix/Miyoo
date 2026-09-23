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

## 📥 Télécharger et installer Rufus

1. Rendez-vous sur le site officiel : https://rufus.ie
2. Téléchargez la dernière version standard de Rufus.
3. Double-cliquez sur le fichier téléchargé.
4. Autorisez l'exécution si Windows demande une confirmation.
5. Suivez l'assistant d'installation.

## 🧽 Formater la carte SD

1. Connecter la carte microSD à votre ordinateur via un lecteur de cartes.
2. Lancez Rufus.
3. Dans Périphérique, sélectionnez votre carte microSD.
4. Choisis :
    * Type de démarrage: Non amorçable
    * Schéma de partition: MBR
    * Système de fichiers: FAT32 (obligatoire)
    * Taille d'unité d'allocation : 32 kilooctets (32K)
    * Nom de volume: Décocher
4. Lancer le formatage: Cliquez sur Démarrer.

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


## Quelques sites de homebrew

* https://www.tyranight.fr/homebrewroms.php
* https://www.gamebrew.org/

## Quelques sites de d'abandonware

* https://www.abandonware-france.org

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