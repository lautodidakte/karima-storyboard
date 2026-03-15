# KARIMA S2 — Storyboard de Production

> Série animée éducative 2D · Village d'Illalsalam · Saison 2

## 🚀 Mise en place (une seule fois)

### 1. Créer le repository GitHub
- Aller sur https://github.com/new
- Nom : `karima-storyboard`
- Visibilité : **Private** (ou Public si l'équipe n'a pas de comptes GitHub)
- Cliquer **Create repository**

### 2. Uploader les fichiers
- Cliquer **Upload files** sur la page du repo
- Glisser-déposer **tout le contenu** de ce dossier :
  - `index.html`
  - `data.json`
  - `README.md`
  - Le dossier `images/` avec toutes les images
- Cliquer **Commit changes**

### 3. Activer GitHub Pages
- Aller dans **Settings** → **Pages**
- Source : **Deploy from a branch**
- Branch : **main** / dossier **/ (root)**
- Cliquer **Save**
- Attendre 1-2 minutes
- L'URL apparaît : `https://VOTRE-COMPTE.github.io/karima-storyboard/`

### 4. Partager avec l'équipe
Envoyez l'URL à Thierry, Ribar, Ayati, Majoie et les autres. Tout le monde peut consulter depuis n'importe quel appareil.

---

## 📁 Structure des fichiers

```
karima-storyboard/
├── index.html          ← Interface (ne change pas)
├── data.json           ← Données : liste images, compteurs
├── README.md           ← Ce fichier
└── images/
    ├── cover.png
    ├── E01S0_Village_AerienGeneral.png
    ├── E01S1_P1_ELeve_Sorte_Lycee.png
    ├── E01S1_P4_Karima_PlanRapproche_DevantLycee.png
    └── ... (toutes les images)
```

---

## ➕ Ajouter de nouvelles images

### Étape 1 — Déposer l'image
- Aller dans le dossier `images/` sur GitHub
- Cliquer **Add file** → **Upload files**
- Nommer l'image selon la convention : `E01S2_P03_Description.png`
- Commit

### Étape 2 — Mettre à jour data.json
- Ouvrir `data.json` sur GitHub (cliquer dessus → icône crayon ✏️)
- Dans la section `"images"`, ajouter une ligne :
```json
"E01S2_P03_Description": "images/E01S2_P03_Description.png",
```
- Mettre à jour le compteur `"imgDone"` (ex: de 22 à 23)
- Commit

### Étape 3 (optionnel) — Mettre à jour le HTML
Pour que l'image apparaisse dans la planche visuelle, demandez à Claude :
> "Ajoute l'image E01S2_P03 au storyboard GitHub Pages"

Claude régénérera uniquement la section concernée.

---

## 💾 Progression (checkboxes)

- Chaque membre de l'équipe a **sa propre progression** sauvegardée dans son navigateur (localStorage)
- Pour partager la progression : utiliser les boutons **Exporter / Importer** dans la barre de synchronisation
- Le fichier `data.json` peut aussi contenir une progression "officielle" partagée

---

## 🔧 Maintenance

| Action | Quoi faire |
|--------|-----------|
| Ajouter des images | Upload dans `/images/` + mettre à jour `data.json` |
| Corriger le HTML | Demander à Claude de régénérer `index.html` |
| Changer l'équipe | Modifier directement dans `index.html` |
| Passer à l'épisode 2 | Créer un nouveau repo ou un dossier `/e02/` |

---

## 👥 Équipe

**Coordination** : Kabo · Kadji (Zamzam)
**Technique** : Thierry (chef de mission) · Ayati (dessin) · Beria, Nadia, Asdjim (images IA) · Ribar (montage) · Majoie (scénario)

---

*Généré par Claude pour le projet Karima · Synergie Sahel*
