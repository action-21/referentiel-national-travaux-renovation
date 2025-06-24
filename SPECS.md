# Spécifications

## Front-end

### Sitemap

```text
/
/mon-espace
/mon-espace/declaration
/a-propos
/faq
/contact
/documentation (gitbook)
```

### UX

[Système de Design de l'État](https://www.systeme-de-design.gouv.fr/)

### UI

- Authentification
- Historique des travaux
  - Description des travaux
  - Lien de partage des travaux
- Référencement de nouveaux travaux

## API

### Standard

OpenAPI

### Opérations

#### GET /travaux

Recherche une liste de travaux de rénovation énergétique par critères.

#### GET /travaux/{uuid}

Recherche un ouvrage de rénovation énergétique par son identifiant unique.

#### POST /travaux

Publie un ouvrage de rénovation énergétique dans l'open data.
