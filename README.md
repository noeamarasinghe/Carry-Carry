# Carry Carry — Site de coaching League of Legends

Prototype interactif d'un site de coaching LoL : tunnel complet **Accueil → Connexion → Choisir son elo → Trouver un coach → Réserver → Paiement → Validation**.

## Aperçu en ligne (GitHub Pages)

1. Pousse ce dossier sur un dépôt GitHub.
2. Dans **Settings → Pages**, choisis la branche `main` et le dossier `/ (root)`.
3. Le site sera servi sur `https://<ton-user>.github.io/<ton-repo>/`.

## Lancer en local

Ouvre simplement `index.html` dans un navigateur, ou sers le dossier :

```bash
# Python
python3 -m http.server 8000
# puis ouvre http://localhost:8000
```

## Structure

```
index.html      → page unique (HTML + CSS inline + logique de navigation)
support.js      → moteur de rendu (requis par index.html)
assets/
  skull.png     → logo (crâne pixel)
  bg1..bg4.jpg  → fonds (splash arts) par page
```

## Identité visuelle

- **Couleurs** : noir `#08080a`, rouge `#ED1C24`, or `#c8aa6e`
- **Typographies** : Anton (titres), Archivo (textes) — chargées via Google Fonts

## Notes

- Les splash arts et l'imagerie League of Legends appartiennent à Riot Games et servent uniquement à la démonstration.
- La progression de navigation est sauvegardée dans le `localStorage` du navigateur.
