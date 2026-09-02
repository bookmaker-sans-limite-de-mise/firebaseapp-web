# Firebase Hosting deployment

Firebase project: `bookmaker-sans-limite-de-mise`

The live site is deployed automatically on every push to `main` by `.github/workflows/firebase-hosting-deploy.yml`.

Required GitHub Actions secret:

`FIREBASE_SERVICE_ACCOUNT_BOOKMAKER_SANS_LIMITE_DE_MISE`

The secret must contain the Firebase service account JSON for this project. It can be created automatically by Firebase CLI with Hosting GitHub integration, or added manually in the repository Actions secrets.

Site files are inside `public/`.
