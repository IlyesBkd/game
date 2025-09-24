# Landing Page NosTale - Offre CPA

## 🎮 Description
Landing page moderne et responsive pour une offre CPA de jeu vidéo NosTale, optimisée pour les conversions.

## 📁 Structure du Projet
```
Nostale/
├── index.html          # Page principale
├── styles.css          # Styles CSS
├── nostale-image.jpg   # Image de fond (à ajouter)
├── nostale-logo.png    # Logo du jeu (à ajouter)
└── README.md           # Ce fichier
```

## 🖼️ Intégration de Vos Images

### Étapes pour ajouter vos images :
1. **Image de fond** : Renommez en `nostale-image.jpg`
2. **Logo** : Renommez en `nostale-logo.png`
3. **Placez-les** dans le dossier racine du projet
4. **Formats supportés** : JPG, PNG, WebP
5. **Dimensions recommandées** :
   - Image de fond : 1920x1080px minimum
   - Logo : 400x200px maximum (sera redimensionné automatiquement)

### Alternative - Modifier les noms d'images :
Si vous souhaitez garder les noms originaux, modifiez dans `index.html` :
```html
<!-- Image de fond (ligne 14) -->
<img src="votre-image.jpg" alt="NosTale - Aventure Anime" class="hero-image">

<!-- Logo (ligne 22) -->
<img src="votre-logo.png" alt="NosTale Logo" class="game-logo">
```

## 🎯 Fonctionnalités CPA

### Tracking des Conversions
La page inclut un système de tracking pour mesurer les conversions :
- **Bouton "Jouer Maintenant"** : Conversion principale
- **Bouton "En Savoir Plus"** : Conversion secondaire
- **Bouton final CTA** : Conversion finale

### Personnalisation des Liens
Modifiez les liens d'affiliation dans le fichier `index.html` (lignes 95-99) :
```javascript
if (action === 'play-now' || action === 'final-cta') {
    window.open('https://VOTRE-LIEN-AFFILIATION.com', '_blank');
}
```

## 🎨 Personnalisation

### Couleurs Principales
- **Orange principal** : #ff6b35
- **Or** : #ffd700
- **Bleu foncé** : #1a1a2e

### Modifier les Textes
Tous les textes sont facilement modifiables dans `index.html` :
- Titre du jeu
- Description
- Fonctionnalités
- Boutons d'action

## 📱 Responsive Design
La page est entièrement responsive et optimisée pour :
- **Desktop** : 1200px+
- **Tablette** : 768px - 1199px
- **Mobile** : 320px - 767px

## 🚀 Déploiement

### Option 1 - Hébergement Simple
1. Uploadez tous les fichiers sur votre serveur web
2. Assurez-vous que `nostale-image.jpg` est dans le même dossier

### Option 2 - GitHub Pages
1. Créez un repository GitHub
2. Uploadez les fichiers
3. Activez GitHub Pages dans les paramètres

### Option 3 - Netlify/Vercel
1. Connectez votre repository
2. Déployez automatiquement

## 📊 Optimisations CPA

### Éléments de Conversion
- **Titre accrocheur** avec animation
- **Boutons CTA proéminents** avec effets hover
- **Indicateurs de confiance** (nombre de joueurs, notes)
- **Urgence** ("Gratuit", "Maintenant")
- **Garanties** ("Aucune carte de crédit requise")

### A/B Testing Suggestions
- Tester différents titres
- Varier les couleurs des boutons
- Modifier l'ordre des sections
- Tester différentes images

## 🔧 Maintenance

### Mise à Jour des Liens
Vérifiez régulièrement que vos liens d'affiliation fonctionnent.

### Analytics
Ajoutez Google Analytics ou votre outil de tracking préféré dans le `<head>` de `index.html`.

## 📞 Support
Pour toute question ou personnalisation, consultez la documentation ou contactez votre développeur.

---
*Créé pour optimiser les conversions CPA de jeux vidéo* 🎮
