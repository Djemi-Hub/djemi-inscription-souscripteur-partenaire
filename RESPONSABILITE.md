# Djemi

## Perimetre

- Inscription et creation de compte.
- Parcours souscripteur : informations primaires, documents et informations complementaires.
- Statuts du compte : brouillon, en verification, valide ou a completer.
- Espace partenaire : demandes de prise en charge, prestations, factures, paiements et profil.

## Dossiers principaux

- `src/app/features/auth/`
- `src/app/features/partner/`
- `src/app/core/auth/`
- `src/app/core/models/`
- `src/app/fonctionnalites/authentification/`
- `src/app/fonctionnalites/souscriptions/`
- `src/app/fonctionnalites/partenaires/`

## Regle metier d'inscription

La creation initiale demande les informations primaires. Les documents et donnees complementaires peuvent etre fournis plus tard. Le compte ne devient valide qu'apres verification.

## Limites

Ne pas modifier les layouts ni les ecrans compagnie et particulier sauf accord d'integration. Documenter les contrats necessaires au backend.

## Verification

`npm install` puis `npm run build`
