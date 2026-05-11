<p align="center">
  <img src="logo.png" alt="EDcourse" width="120">
</p>

# EDcourse

**Français** | [English](#english)

---

## Français

EDcourse est une application de listes de courses disponible sur Windows, Linux, macOS et Android.

### Fonctionnalités

- Création de listes de courses personnelles ou partagées
- Ajout d'articles avec quantité, catégorie et prix
- Scan de code-barres et détection de prix par photo
- Suivi de progression des achats
- Synchronisation temps réel avec Socket.io
- Mode local hors connexion

### Plateformes

| Plateforme | Format |
|------------|--------|
| Windows | `.exe` (installeur NSIS) |
| Linux | `.tar.gz` |
| macOS | `.dmg` |
| Android | `.apk` |

### Installation

Télécharge la dernière version depuis les [releases GitHub](https://github.com/3yezz/course/releases).

### Stack technique

- **Interface** : React 18
- **Temps réel** : Socket.io
- **Scan produit** : ZXing, Tesseract.js
- **Documents** : jsPDF
- **Bureau** : Electron
- **Mobile** : Android natif (WebView)
- **Build** : electron-builder, Gradle

---

## English

EDcourse is a shopping list app available on Windows, Linux, macOS and Android.

### Features

- Personal or shared shopping lists
- Items with quantity, category and price
- Barcode scanning and price detection from photos
- Shopping progress tracking
- Real-time sync with Socket.io
- Offline local mode

### Platforms

| Platform | Format |
|----------|--------|
| Windows | `.exe` (NSIS installer) |
| Linux | `.tar.gz` |
| macOS | `.dmg` |
| Android | `.apk` |

### Installation

Download the latest version from the [GitHub releases](https://github.com/3yezz/course/releases).

### Tech stack

- **UI** : React 18
- **Real-time** : Socket.io
- **Product scanning** : ZXing, Tesseract.js
- **Documents** : jsPDF
- **Desktop** : Electron
- **Mobile** : Android native (WebView)
- **Build** : electron-builder, Gradle
