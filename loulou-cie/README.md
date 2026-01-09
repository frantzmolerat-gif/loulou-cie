# Loulou-cie — Site vitrine (GitHub Pages)

Ce dossier est un package prêt à pousser sur un repository GitHub existant (site statique).

## Fichiers
- `index.html` : page vitrine
- `styles.css` : styles
- `assets/` : logo + favicon
- `404.html` : page 404 (GitHub Pages)
- `CNAME` : domaine (loulou-cie.org)

## Déploiement GitHub Pages
1) Pousser ces fichiers à la racine du repo (branche `main`)
2) GitHub → Settings → Pages → Deploy from a branch → `main` + `/ (root)`
3) Activer **Enforce HTTPS** après propagation DNS

## DNS (chez Squarespace Domains / Google Domains)
- Enregistrements A (apex loulou-cie.org) :
  - 185.199.108.153
  - 185.199.109.153
  - 185.199.110.153
  - 185.199.111.153
- CNAME : `www` → `loulou-cie.org`
