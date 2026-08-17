# Aristide Works — Dashboard

Portfolio statique présentant les productions publiques d’Aristide.

## Développement local

Le site n’a aucune dépendance. Il suffit de servir le dossier `public` :

```sh
python3 -m http.server 8080 --directory public
```

Puis ouvrir <http://localhost:8080>.

## Déploiement Vercel

Importer le dépôt `aristidew1/dashboard` dans Vercel avec le preset **Other**.
Le fichier `vercel.json` publie directement le dossier `public`.

La route `/poker` redirige actuellement vers
`https://pokercard-nine.vercel.app`. Après configuration du sous-domaine,
remplacer cette destination par l’adresse définitive, par exemple
`https://poker.example.com`.
