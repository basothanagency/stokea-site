# Stokéa — Site web

## Comment modifier le site ?

### 1. Modifier un texte ou un prix
- Va sur ton repo GitHub
- Clique sur `index.html`
- Clique sur l'icône **crayon** (✏️) en haut à droite
- Modifie le texte directement dans le navigateur
- Descends en bas, clique **"Commit changes"**
- Vercel redéploie automatiquement en 30 secondes

### 2. Ajouter ou changer une image
- Place ton image dans le dossier `images/` (via GitHub : "Add file" → "Upload files")
- Dans `index.html`, utilise la balise :
  ```html
  <img src="images/nom-de-ton-image.jpg" alt="description">
  ```
- Commit, et c'est en ligne.

### 3. Voir le résultat avant de publier
GitHub propose un onglet **Preview** quand tu édites un fichier. Pour un aperçu plus fidèle, ouvre simplement `index.html` sur ton ordinateur en double-cliquant dessus.

## Structure du projet
```
STOKEA/
├── index.html       ← le site (texte, prix, structure)
├── images/          ← toutes les images du site
├── .gitignore       ← fichiers ignorés par Git
└── README.md        ← ce fichier
```

## Déploiement
Hébergé sur **Vercel**. Chaque commit sur la branche `main` déclenche un redéploiement automatique.
