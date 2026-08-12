# Qiryna PWA

Prototype PWA mobile (HTML/CSS/JS statique) — orientation scolaire, logement, admission, etc.

## Structure

```
pwa/          ← racine du site à déployer
  index.html  ← hub de navigation / écrans
  pages/      ← écrans
  css/        ← styles
  js/         ← scripts
  assets/     ← images et icônes
  sw.js       ← service worker
```

## Déploiement Vercel

1. Importer le repo [UzaLab/qiryna](https://github.com/UzaLab/qiryna) sur [vercel.com](https://vercel.com)
2. **Root Directory** : `pwa`
3. **Framework Preset** : Other
4. **Build Command** : *(laisser vide)*
5. **Output Directory** : *(laisser vide)*
6. Deploy

Chaque push sur `main` redéploie automatiquement.

## Développement local

```bash
cd pwa
python3 -m http.server 8765
```

Puis ouvrir `http://localhost:8765`
