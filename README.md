# 🍳 ZookCook - Site de Recettes Culinaires

Bienvenue sur **ZookCook**, un site moderne et intuitif pour découvrir les meilleures recettes culinaires du moment !

## 🌟 Caractéristiques

- **Catalogue de recettes** : Découvrez une collection variée de recettes tendance
- **Recherche et filtres** : Trouvez facilement les recettes par catégorie, difficulté et mots-clés
- **Détails complets** : Ingrédients, instructions étape par étape, temps de préparation
- **Système de favoris** : Sauvegardez vos recettes préférées localement
- **Design responsive** : Fonctionne parfaitement sur tous les appareils
- **Interface moderne** : Design élégant et facile à utiliser

## 📂 Structure du projet

```
zookcook/
├── index.html      # Page principale HTML
├── styles.css      # Feuille de styles CSS
├── script.js       # Logique JavaScript
└── README.md       # Ce fichier
```

## 🚀 Démarrage rapide

1. **Cloner le repository** :
   ```bash
   git clone https://github.com/NMBR45/zookcook.git
   cd zookcook
   ```

2. **Ouvrir le site** :
   - Double-cliquez sur `index.html` ou
   - Utilisez un serveur local (recommandé) :
     ```bash
     python -m http.server 8000
     ```
   - Ouvrez `http://localhost:8000` dans votre navigateur

## 🍽️ Recettes disponibles

Le site inclut actuellement **6 recettes populaires** :

1. **Pâtes à la Carbonara** 🍝 - Facile (20 min)
2. **Buddha Bowl Méditerranéen** 🥗 - Facile (15 min)
3. **Tiramisu Classique** 🍰 - Moyen (30 min)
4. **Tacos Al Pastor** 🌮 - Moyen (40 min)
5. **Smoothie Acai Bowl** 🍓 - Facile (10 min)
6. **Soupe à l'Oignon Gratinée** 🍲 - Moyen (45 min)

## 🔧 Fonctionnalités

### Recherche et Filtrage
- Recherche par texte dans le titre et la description
- Filtrage par catégorie (Entrée, Plat, Dessert, Boisson)
- Filtrage par difficulté (Facile, Moyen, Difficile)

### Détails de chaque recette
- Titre et emoji représentatif
- Catégorie et niveau de difficulté
- Temps de préparation et nombre de portions
- Note/évaluation
- Description complète
- Liste des ingrédients
- Instructions étape par étape
- Bouton pour ajouter aux favoris

### Favoris
Les favoris sont sauvegardés dans le stockage local (localStorage) de votre navigateur

## 🎨 Design

- **Couleurs principales** :
  - Primaire : Rouge-Coral (#FF6B6B)
  - Secondaire : Turquoise (#4ECDC4)
  - Sombre : Bleu foncé (#2C3E50)

- **Typography** : Segoe UI pour une lisibilité optimale
- **Responsive** : Adaptés aux smartphones, tablettes et ordinateurs de bureau

## 💻 Technologies utilisées

- **HTML5** : Structure sémantique
- **CSS3** : Styling moderne et animations
- **JavaScript Vanilla** : Logique interactive sans dépendances
- **localStorage** : Persistance des données client

## 📱 Responsive Design

Le site est optimisé pour tous les appareils :
- 📱 Téléphones mobiles
- 📱 Tablettes
- 💻 Ordinateurs de bureau

## 🌱 Prochaines évolutions

- [ ] Ajouter plus de recettes
- [ ] Système de notation utilisateur
- [ ] Partage de recettes personnelles
- [ ] Authentification utilisateur
- [ ] Importer des recettes du monde entier
- [ ] Génération de listes d'achats
- [ ] Intégration avec des APIs de recettes
- [ ] Mode sombre

## 📝 Comment ajouter une recette

Pour ajouter une nouvelle recette, modifiez le tableau `recipes` dans `script.js` et ajoutez un objet avec la structure suivante :

```javascript
{
    id: 7,
    title: "Titre de la recette",
    category: "plat", // ou "entrée", "dessert", "boisson"
    difficulty: "facile", // ou "moyen", "difficile"
    time: 30,
    servings: 4,
    rating: 4.5,
    emoji: "🍕",
    description: "Description courte",
    ingredients: ["Ingrédient 1", "Ingrédient 2", ...],
    instructions: ["Étape 1", "Étape 2", ...]
}
```

## 📄 Licence

Ce projet est open source et disponible sous la licence MIT.

## 👨‍💻 Auteur

Créé par **NMBR45**

## 📧 Contact et Support

Pour toute question ou suggestion, veuillez ouvrir une issue sur ce repository GitHub.

---

**Bon appétit et happy cooking!** 👨‍🍳👩‍🍳
