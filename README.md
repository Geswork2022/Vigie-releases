# VIGIE — Console Micrologic

Application de test, de lecture et de configuration des déclencheurs **Schneider Micrologic**
(MasterPacT MTZ / Micrologic X, MasterPacT NW·NT et Compact NSX via boîtier Service Interface LV485500).

> 📦 Cette page ne contient que les **téléchargements**. Le code source n'est pas public.

---

## ⬇️ Télécharger la dernière version

### Windows 10 / 11
**[Télécharger VIGIE Console pour Windows (.exe)](https://github.com/Geswork2022/Vigie-releases/releases/latest/download/VIGIE-Console-Windows-x64.exe)**

Aucune installation : téléchargez le fichier et lancez-le. Application autonome (aucun runtime .NET requis).

### macOS
- **Mac Apple Silicon (M1 / M2 / M3 / M4)** — [Télécharger (.tar.gz arm64)](https://github.com/Geswork2022/Vigie-releases/releases/latest/download/VIGIE-Console-macOS-arm64.tar.gz)
- **Mac Intel** — [Télécharger (.tar.gz x64)](https://github.com/Geswork2022/Vigie-releases/releases/latest/download/VIGIE-Console-macOS-x64.tar.gz)

1. Décompressez l'archive (double-clic).
2. Double-cliquez **`Installer VIGIE.command`** (prépare et lance l'application non notarisée).
3. Les fois suivantes, ouvrez directement **`VIGIE Console.app`**.

> Pour dialoguer avec une **Micrologic X branchée en USB direct** sur Mac, installez au préalable libusb :
> ```
> brew install libusb
> ```
> (La valise Service Interface LV485500 ne le nécessite pas.)

---

## 🔐 Habilitation du poste

Au premier lancement, l'application vérifie que le poste est **habilité**. Si ce n'est pas le cas,
un formulaire permet d'envoyer une demande d'accès au support Geswork. L'application ne démarre
qu'une fois le poste approuvé.

## ⚠️ Avertissement

Le logiciel est un outil d'assistance fourni « en l'état ». L'utilisateur est seul responsable de son
utilisation, notamment lors des opérations sur les dispositifs de protection (tests par injection,
écriture de réglages). Il doit vérifier l'exactitude des informations et respecter les prescriptions
du constructeur. Voir les Conditions Générales d'Utilisation dans l'application.

## Éditeur

**GESWORK SAS** — Demande relative aux données personnelles : protection-donnees@gsme.fr
