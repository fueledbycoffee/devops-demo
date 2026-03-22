# DevOps Demo

Repo de démo bootstrapé automatiquement pour la formation DevOps.

## Ce repo contient

- l'application fil rouge dans `app/`
- la pipeline GitHub Actions dans `.github/workflows/pipeline.yml`
- la publication d'image dans `ghcr.io/fueledbycoffee/devops-app`

## Flux attendu

1. push sur `main`
2. tests
3. scan de sécurité
4. publication de l'image GHCR avec le tag du commit
