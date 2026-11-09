# 🚀 FlySerial — Console Dédiée

> **Terminal Série Interactif Haute Performance**  
> *Développé et conçu par **Florian G.** — Tous droits réservés.*

[![Version](https://img.shields.io/badge/Version-1.0.0-blue.svg)](https://github.com/flylemodo/FlySerial/releases)
[![Téléchargement](https://img.shields.io/badge/Télécharger-FlySerial__Setup.exe-brightgreen.svg?logo=windows)](https://github.com/flylemodo/FlySerial/releases/latest)
[![Licence](https://img.shields.io/badge/Licence-Propriétaire-red.svg)](LICENSE.txt)
[![Plateforme](https://img.shields.io/badge/OS-Windows%2010%20%2F%2011-0078D6.svg)](https://github.com/flylemodo/FlySerial)

---

### 📥 [👉 Cliquez ici pour télécharger la dernière version (FlySerial_Setup.exe)](https://github.com/flylemodo/FlySerial/releases/latest)

---

## 📌 Présentation

**FlySerial** est une application Windows moderne et épurée conçue pour les développeurs, techniciens et passionnés d'électronique et de systèmes embarqués. 

Contrairement aux moniteurs série traditionnels dotés d'une barre de saisie séparée, **FlySerial offre une véritable expérience de console directe** : vous écrivez directement dans le terminal, et chaque frappe est transmise instantanément au matériel connecté avec une latence quasi-nulle.

---

## ✨ Fonctionnalités Principales

- **⌨️ Frappe interactive directe :** Interagissez avec votre équipement comme sur une véritable console physique (style VT100 / Linux / Cisco).
- **🔌 Ciblage matériel strict :** Pré-configuré d'usine pour se lier immédiatement au port **COM9** (9600 bauds, 8 bits de données, 1 bit d'arrêt, sans parité).
- **🔄 Détection dynamique à chaud :** Bouton de rafraîchissement rapide (`↻`) pour détecter instantanément tout adaptateur USB branché en cours d'utilisation.
- **↵ Gestion intelligente des commandes :** Conversion automatique de la touche **Entrée** en retour chariot complet `CRLF` (`\r\n`).
- **🛑 Signaux matériels & Interruption :** Prise en charge native de **Ctrl+C** (interruption matérielle ETX `0x03` ou copie intelligente si du texte est sélectionné), **Échap**, **Tab** et **Retour arrière**.
- **🎨 Interface Sombre Moderne :** Thème *Dark Studio* reposant pour les yeux, avec texte vert rétro haute lisibilité et auto-scroll.

---

## 🛠️ Matériels Compatibles

- **Microcontrôleurs :** Arduino, ESP32, ESP8266, STM32, PIC, Raspberry Pi Pico / RP2040, etc.
- **Automates & Équipements Réseau :** Consoles de routeurs et commutateurs (Cisco, HP, Mikrotik).
- **Adaptateurs USB-Série :** FTDI FT232, CH340, CP2102, PL2303.
- **Modems et modules de communication :** Modules GSM/4G, GPS, Bluetooth HC-05/06, Zigbee.

---

## 📦 Téléchargement & Installation

1. Rendez-vous dans la section **[Releases](https://github.com/flylemodo/FlySerial/releases)** et téléchargez **`FlySerial_Setup.exe`**.
2. Lancez le fichier et suivez l'assistant d'installation guidé pas à pas :
   - Choix du dossier de destination.
   - Création facultative de raccourcis sur le Bureau et dans le Menu Démarrer.
   - Pré-configuration de votre port favori.
3. Branchez votre équipement sur le port **COM9** (ou sélectionnez votre port) et cliquez sur **CONNECTER**.

---

## 📄 Licence & Propriété Intellectuelle

Ce logiciel est distribué sous **Licence Propriétaire Commerciale** (Closed Source).  
**Il n'est pas open source.** 

Toute décompilation, ingénierie inverse, modification ou redistribution sans autorisation écrite expresse de l'auteur est formellement interdite.

Consultez le fichier complet [LICENSE.txt](LICENSE.txt) pour plus de détails.

---

**Made by Florian G.** — Copyright © 2026 Florian G. Tous droits réservés.
