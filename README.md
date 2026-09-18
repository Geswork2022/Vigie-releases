# VIGIE — Console Micrologic

Application de test, de lecture et de configuration des déclencheurs **Schneider Micrologic**
(MasterPacT MTZ / Micrologic X, MasterPacT NW·NT et Compact NSX via boîtier Service Interface LV485500).

> 📦 Ce dépôt ne contient **que les téléchargements** (dossier `downloads/`). Le code source n'est pas public.

**➡️ Page de téléchargement : https://geswork2022.github.io/Vigie-releases/**

---

## ⬇️ Téléchargement direct

| Plateforme | Fichier |
|---|---|
| **Windows 10 / 11** | [VIGIE-Console-Windows-x64.exe](https://github.com/Geswork2022/Vigie-releases/raw/main/downloads/VIGIE-Console-Windows-x64.exe) |
| **macOS Apple Silicon** (M1/M2/M3/M4) | [VIGIE-Console-macOS-arm64.tar.gz](https://github.com/Geswork2022/Vigie-releases/raw/main/downloads/VIGIE-Console-macOS-arm64.tar.gz) |
| **macOS Intel** | [VIGIE-Console-macOS-x64.tar.gz](https://github.com/Geswork2022/Vigie-releases/raw/main/downloads/VIGIE-Console-macOS-x64.tar.gz) |

### Windows
Application autonome : téléchargez le `.exe` et lancez-le. Aucun runtime requis.

### macOS
1. Décompressez l'archive, puis double-cliquez **`Installer VIGIE.command`**.
2. L'application n'étant **pas notarisée par Apple**, macOS peut la bloquer au 1ᵉʳ lancement.
   Ouvrez  → **Réglages Système** → **Confidentialité et sécurité** → **« Ouvrir quand même »** (une seule fois).
3. Pour une **Micrologic X en USB direct** : `brew install libusb` (inutile avec la valise LV485500).

---

## 🔐 Habilitation & responsabilité

Le poste doit être **habilité** par Geswork au premier lancement. Le logiciel est un outil d'assistance
fourni « en l'état » ; l'utilisateur reste seul responsable de son utilisation et doit vérifier l'exactitude
des informations. CGU consultables dans l'application.

## Éditeur

**GESWORK SAS** — Données personnelles : protection-donnees@gsme.fr
