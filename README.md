# Portfolio Professionnel

Un portfolio moderne et responsive créé avec HTML, CSS et JavaScript pour présenter vos projets et compétences aux recruteurs.

## 🚀 Fonctionnalités

- **Design moderne et responsive** : S'adapte à tous les écrans (desktop, tablette, mobile)
- **Navigation fluide** : Menu de navigation avec indicateur de section active
- **Animations** : Animations au scroll pour une expérience utilisateur agréable
- **Section Hero** : Présentation accrocheuse avec call-to-action
- **À propos** : Section pour vous présenter avec statistiques animées
- **Compétences** : Affichage visuel de vos compétences avec barres de progression
- **Projets** : Grille de projets avec overlay au survol
- **Contact** : Formulaire de contact fonctionnel avec validation
- **Réseaux sociaux** : Liens vers vos profils professionnels

## 📁 Structure du projet

```
portfolio/
├── index.html      # Structure HTML principale
├── style.css       # Styles CSS avec design moderne
├── script.js       # JavaScript pour interactions et animations
└── README.md       # Documentation du projet
```

## 🎨 Sections du portfolio

1. **Navigation** : Menu fixe en haut de page avec navigation fluide
2. **Hero** : Section d'accueil avec présentation et boutons d'action
3. **À propos** : Présentation personnelle avec statistiques
4. **Compétences** : Affichage de vos compétences techniques
5. **Projets** : Galerie de vos projets avec descriptions
6. **Contact** : Formulaire de contact et informations de contact
7. **Footer** : Pied de page avec copyright

## 🛠️ Personnalisation

### Modifier vos informations personnelles

1. **Nom et titre** : Dans `index.html`, section hero
   ```html
   <span class="name">Votre Nom</span>
   <span class="role">Développeur Web</span>
   ```

2. **Description** : Modifiez les paragraphes dans la section "À propos"

3. **Compétences** : Ajustez les compétences et leurs niveaux dans la section "Compétences"
   - Modifiez les noms des compétences
   - Ajustez les valeurs `data-progress` pour les pourcentages

4. **Projets** : Ajoutez/modifiez vos projets dans la section "Projets"
   - Changez les titres, descriptions et tags
   - Ajoutez les liens vers vos projets et code source
   - Remplacez les placeholders par de vraies images

5. **Contact** : Mettez à jour vos informations de contact
   - Email, téléphone, adresse
   - Liens vers vos réseaux sociaux (LinkedIn, GitHub, Twitter)

### Modifier les couleurs

Les couleurs sont définies dans `style.css` avec des variables CSS :

```css
:root {
    --primary-color: #6366f1;
    --primary-dark: #4f46e5;
    --secondary-color: #8b5cf6;
    /* ... autres couleurs ... */
}
```

Modifiez ces valeurs pour personnaliser la palette de couleurs.

### Ajouter des images

1. Créez un dossier `images/` dans votre projet
2. Ajoutez vos images de projets
3. Remplacez les placeholders dans le HTML :
   ```html
   <img src="images/votre-image.jpg" alt="Description">
   ```

## 📱 Responsive Design

Le portfolio est entièrement responsive et s'adapte à :
- **Desktop** : Layout en grille avec plusieurs colonnes
- **Tablette** : Adaptation des grilles à 2 colonnes
- **Mobile** : Layout en une seule colonne avec menu hamburger

## 🚀 Déploiement

### Option 1 : GitHub Pages

1. Créez un repository GitHub
2. Uploadez vos fichiers
3. Activez GitHub Pages dans les paramètres du repository
4. Votre portfolio sera accessible à `https://votre-username.github.io/portfolio`

### Option 2 : Netlify

1. Créez un compte sur [Netlify](https://www.netlify.com)
2. Glissez-déposez votre dossier ou connectez votre repository GitHub
3. Netlify déploiera automatiquement votre site

### Option 3 : Vercel

1. Créez un compte sur [Vercel](https://vercel.com)
2. Importez votre projet
3. Déployez en un clic

## 📝 Notes importantes

- **Formulaire de contact** : Le formulaire actuel affiche une alerte. Pour un fonctionnement réel, vous devrez :
  - Utiliser un service comme [EmailJS](https://www.emailjs.com/)
  - Ou [Formspree](https://formspree.io/)
  - Ou connecter à votre propre backend

- **Images** : Les images de projets sont actuellement des placeholders. Remplacez-les par vos vraies images.

- **SEO** : N'oubliez pas de :
  - Modifier la balise `<title>` et la meta description
  - Ajouter des alt text à vos images
  - Optimiser vos images pour le web

## 🎯 Prochaines étapes

- [ ] Ajouter vos vraies images de projets
- [ ] Configurer le formulaire de contact avec un service d'email
- [ ] Ajouter un mode sombre (dark mode)
- [ ] Optimiser les performances (lazy loading, compression d'images)
- [ ] Ajouter Google Analytics pour le suivi des visiteurs
- [ ] Créer un CV téléchargeable en PDF

## 📄 Licence

Ce projet est libre d'utilisation pour votre portfolio personnel.

## 👤 Auteur

Créez votre portfolio professionnel et présentez vos projets avec style !

---

**Bon courage avec votre portfolio ! 🎨✨**

