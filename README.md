# Portfolio — Yann Kounkoud

Site portfolio d'étudiant en BTS SIO option SISR (Solutions d'Infrastructure, Systèmes et Réseaux).

Site statique : HTML, CSS et JavaScript, sans dépendance ni étape de build.

## Structure

- `index.html` — contenu du site (à propos, compétences, projets, parcours, certifications, contact)
- `style.css` — styles, thème clair/sombre automatique, responsive
- `script.js` — menu mobile, lien actif dans la navigation, animations d'apparition
- `vercel.json` — configuration du déploiement Vercel

## Lancer en local

Ouvrir `index.html` dans un navigateur, ou servir le dossier :

```bash
python3 -m http.server 8000
```

puis aller sur http://localhost:8000.

## Déploiement

Le site est déployé sur Vercel. Chaque push sur la branche de production déclenche un nouveau déploiement.
