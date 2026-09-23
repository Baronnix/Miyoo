# ⭐ Installer Telmi OS + Ajouter des histoires du Store

Dans cet épisode, on transforme complètement la Miyoo Mini+ avec Telmi OS. On va installer le système sur une nouvelle carte SD, découvrir son interface, et surtout ajouter des histoires interactives depuis le Store Telmi pour enrichir l’expérience.

# 📺 Vidéo

Lien Youtube: [https://www.youtube.com/@Baronnix/playlists](https://www.youtube.com/@Baronnix/playlists)

# 🎯 Objectifs de l’épisode

* Télécharger Telmi OS et préparer une carte SD propre.
* Installer l’OS et effectuer le premier démarrage.
* Explorer l’interface Telmi : menus, options, thèmes.
* Accéder au Store Telmi :
    * télécharger des histoires,
    * les organiser sur la carte SD,
    * les lancer sur la console.
* Optimiser la carte SD : structure des dossiers, bonnes pratiques.

# 📦 Matériel nécessaire

* Miyoo Mini Plus
* Carte Micro-SD + lecteur
* Un ordinateur (tutoriel réalisé sur Windows)

# 1️⃣ Télécharger Telmi OS

## 📥 Lien de téléchargement

👉 Telmi OS (site officiel): https://telmi.app/download  

Remarque: Si le lien change, il est toujours accessible via le menu “Download” du site Telmi.

## 📦 Fichiers à récupérer

Tu dois télécharger le fichier ZIP contenant :
* Le dossier TelmiOS
* Les fichiers système à copier sur la carte SD

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

# 3️⃣ Installer Telmi OS sur la carte SD

## 📁 Copier les fichiers

1. Ouvre le ZIP téléchargé.
2. Copie tous les fichiers et dossiers à la racine de la carte SD.
    * Pas de dossier supplémentaire
    * Pas de renommage
3. Éjecte proprement la carte SD.

## 🔄 Premier démarrage

1. Insère la carte SD dans la Miyoo Mini+.
2. Allume la console.
3. Telmi OS va :
    * Initialiser les fichiers
    * Créer les dossiers nécessaires
    * Lancer l’interface Telmi

## ⚙️ Configuration initiale

* Choix de la langue
* Réglage de la luminosité
* Sélection du thème
* Vérification du stockage

# 4️⃣ Découvrir le Store Telmi

## 🛒 Accès au Store

Dans Telmi OS :
1. Menu principal
2. Section Store
3. Catégories disponibles :
    * Histoires
    * Packs interactifs
    * Contenus éducatifs
    * Contenus audio

## 📥 Télécharger une histoire

1. Choisis une histoire dans le Store.
2. Télécharge-la.
3. Le fichier obtenu est généralement :
    * .telmi
    * ou un dossier contenant texte + images

# 5️⃣ Installer les histoires sur la carte SD

## 📁 Structure des dossiers Telmi OS

Sur la carte SD, tu trouveras un dossier :
```
/stories/
```

## 📥 Étape 1 — Copier les histoires

1. Place chaque histoire dans un dossier dédié :

Exemple :
```
/stories/mon_histoire/
```

2. Vérifie que le fichier .telmi ou les fichiers texte/images sont bien présents.

## 🧪 Étape 2 — Tester sur la console

1. Insère la carte SD dans la Miyoo.
2. Lance Telmi OS.
3. Va dans Histoires.
4. Ouvre l’histoire installée.
5. Vérifie :
    * Le texte
    * Les images
    * Les transitions
    * La fluidité

# 6️⃣ Optimisations recommandées

## 📂 Organisation

* Une histoire = un dossier
* Pas d’espaces dans les noms (évite les bugs)
* Exemple :
```
/stories/histoire_foret_magique/
```

## 🛡️ Sécurité des fichiers

* Toujours éjecter la carte SD proprement
* Faire une copie de sauvegarde de la carte SD Telmi

## 🚀 Performance

* Utiliser une carte SD de marque (Sandisk, Samsung)
* Éviter les cartes SD trop lentes (classe 4 ou moins)


https://github.com/DantSu/Telmi-Sync/
https://telmi.fr/

https://github.com/DantSu/Telmi-story-teller


Rufus
https://rufus.ie/fr/
https://wiki.telmi.fr/


https://www.tyranight.fr/homebrewroms.php
https://www.abandonware-france.org/ltf_abandon/ltf_listes_jeux.php?format=setuppc&rub=&multi=&annee=&pays=&langue=&ordre=alpha&search=0