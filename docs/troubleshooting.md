# ⚠️ Dépannage des problèmes fréquents

## Problème de ports occupés (Docker)
- Vérifier si les ports (`8080`, `3306`, `3000`) sont disponibles avant de lancer Docker.

## Docker ne démarre pas
- Vérifier que Docker est bien lancé.
- Redémarrer Docker Desktop si besoin.

## Erreurs `npm`
- Vérifier que la version de Node.js est compatible (LTS recommandée).
- Supprimer le dossier `node_modules` et refaire `npm install`.

```bash
rm -rf node_modules package-lock.json
npm install
