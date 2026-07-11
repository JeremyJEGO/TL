[README.md](https://github.com/user-attachments/files/29916932/README.md)
# Transcendance Lab — Landing page

Ce dossier contient un seul fichier : `index.html`.
C'est une page autonome (HTML + CSS + JS dans le même fichier), aucune installation n'est nécessaire.

## Héberger sur GitHub Pages (gratuit)

**1. Créer un compte GitHub** (si tu n'en as pas déjà un) sur https://github.com

**2. Créer un nouveau dépôt (repository)**
- Clique sur "New repository"
- Nom du dépôt : par exemple `transcendance-lab` (ou n'importe quel nom)
- Laisse-le en "Public"
- Ne coche rien d'autre (pas de README, pas de .gitignore, on les a déjà)
- Clique sur "Create repository"

**3. Mettre en ligne le fichier `index.html`**

Option la plus simple, sans ligne de commande :
- Sur la page de ton nouveau dépôt, clique sur "uploading an existing file" (ou "Add file" > "Upload files")
- Glisse le fichier `index.html` (et `README.md` si tu veux)
- Clique sur "Commit changes"

**4. Activer GitHub Pages**
- Dans ton dépôt, va dans "Settings" (en haut)
- Dans le menu de gauche, clique sur "Pages"
- Sous "Build and deployment" > "Branch", choisis `main` et le dossier `/ (root)`
- Clique sur "Save"

**5. Récupérer ton lien**
- Après 1 à 2 minutes, GitHub affiche l'adresse de ton site, du type :
  `https://ton-nom-utilisateur.github.io/transcendance-lab/`
- C'est ce lien que tu peux partager ou relier à un nom de domaine personnalisé (voir plus bas).

## Relier un nom de domaine personnalisé (optionnel)

Si tu as acheté un nom de domaine (ex : transcendance-lab.com) :
- Dans "Settings" > "Pages" de ton dépôt, section "Custom domain", entre ton domaine
- Chez ton registrar (OVH, Namecheap, etc.), ajoute les enregistrements DNS indiqués par GitHub (en général un enregistrement `CNAME` pointant vers `ton-nom-utilisateur.github.io`)
- La propagation DNS peut prendre de quelques minutes à 24h

## Mettre à jour la page plus tard

Pour modifier le texte ou le design : édite le fichier `index.html` (avec un éditeur de texte, ou en redemandant les changements ici), puis remets-le en ligne de la même façon (upload + commit). GitHub Pages se met à jour automatiquement en 1 à 2 minutes.
