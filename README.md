# 🚀 Action-Build : OnePlus 13 SukiSU Ultra 📱

[![Build](https://img.shields.io/badge/GitHub%20Actions-Build-181717?logo=github&logoColor=white&style=flat-square)](https://github.com/Numbersf/Action-Build/actions/workflows/Build%20SukiSU%20Ultra%20OnePlus.yml)
[![OnePlus Kernel Manifest](https://img.shields.io/badge/OnePlus%20Kernel%20Manifest-EB0029?logo=oneplus&logoColor=white&style=flat-square)](https://github.com/OnePlusOSS/kernel_manifest)

**```Construction du noyau SukiSU Ultra pour OnePlus 13```**  
> Plus efficace, plus complet, plus rapide, plus stable 🚀

Ce projet a été localisé et optimisé spécifiquement pour le **OnePlus 13 (Android 16 / `oneplus_13_b`)**.

---

## 📖 Sommaire
1. [Instructions de Fork et Synchronisation](#-instructions-de-fork-et-synchronisation)
2. [Annonces et Informations Importantes](#-annonces-et-informations-importantes)
3. [Version et Codes de l'OS](#-versions-et-codes-de-los)
4. [Temps de Compilation Estimés](#-temps-de-compilation-estimés)
5. [Journal des Modifications](#-journal-des-modifications)

---

## 🔄 Instructions de Fork et Synchronisation

<details>
<summary><strong>📸 Cliquez pour voir comment Fork le projet</strong></summary>
<img src="pic/make.gif" width="500"/>
</details>

<details>
<summary><strong>📸 Cliquez pour voir comment synchroniser votre projet</strong></summary>
<p>
  <img src="pic/syncfork.png" width="150"/>
  <img src="pic/syncfork(2).png" width="150"/>
</p>
**Note :** Veuillez synchroniser régulièrement ! Certaines mises à jour peuvent rendre les versions obsolètes invalides. Si les erreurs persistent après synchronisation, supprimez et reforkez le projet.
</details>

---

## 📢 Annonces et Informations Importantes

> [!IMPORTANT]
> **Le OnePlus 13 est désormais le seul appareil supporté dans cette version localisée.** Les configurations pour les autres modèles ont été retirées pour plus de clarté.

> [!CAUTION]
> Lors de la mise à jour tout en conservant le **Root**, ne pas installer les modules via le volume bas au démarrage, utilisez le volume haut pour ignorer ! L'utilisation du `Module de complétement SukiSU Ultra` est recommandée.

> [!NOTE]
> Si vous activez l'algorithme **ZRAM**, installez le module ZRAM **AVANT** de redémarrer après avoir flashé `Anykernel3`.

---

## 🔢 Versions et Codes de l'OS

Le suffixe dans le fichier de configuration correspond au nom de code de votre version d'Android :

- `_b` : **Android 16 (Baklava)** 🍏
- `_v` : Android 15 (Vanilla Ice Cream) 🍦
- `_u` : Android 14 (Upside Down Cake) 🍰
- `_t` : Android 13 (Tiramisu) 🍪

> [!TIP]
> Pour le OnePlus 13, utilisez la configuration **`oneplus_13_b`** pour Android 16.

---

## ⏱️ Temps de Compilation Estimés

| Mode de construction | Temps Moyen | Maximum constaté |
| :--- | :--- | :--- |
| **Construction Rapide (CCache)** | **9 min ~ 19 min** | 42 min |
| Kernel 5.10-5.15 (Normal) | 29 min ~ 35 min | 45 min |
| Kernel 6.1-6.12 (Normal) | 59 min ~ 1h 12min | 1h 28min |

> [!NOTE]
> L'utilisation de **ccache** peut ralentir la première compilation. La vitesse s'améliore considérablement dès la seconde exécution.

---

## 🛠️ Journal des Modifications (Résumé)

- 🌍 **Localisation complète en Français** avec emojis partout !
- 📱 **Focus OnePlus 13** : Nettoyage des modèles obsolètes.
- ⚡ **Optimisation Fast Build** : Support de Clang ThinLTO et Ccache.
- 🛠️ **Correctifs Kernel** : Support de SUSFS, ZRAM, SCHED (Fengchi), et LSM_BBG.
- 📦 **Artefacts précis** : Les noms des fichiers zip incluent désormais la version précise d'Android.
- 🚀 **Automatisation** : Téléchargement automatique des derniers modules SUSFS (CI/Release) et de l'APK SukiSU Ultra.

---
*Projet maintenu pour les passionnés de performances et de personnalisation.* 🚀