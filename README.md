# SIGMA : Plateforme Numerique Scientifique

> Connecter l'innovation, structurer la connaissance.

## A propos

SIGMA est une plateforme academique centrale pour le Club SIGMA,
visant a transformer la gestion de l'innovation scientifique.

Document de conception prepare par **Dudley Jean-Pierre**

## Architecture du projet

sigma-plateforme/
- frontend/ (Site web - HTML/CSS/JS)
  - css/ (Styles)
  - js/ (Scripts)
  - assets/ (Images)
  - pages/ (Pages du site)
- backend/ (API REST - Spring Boot)
  - src/
- docs/ (Documentation)

## Modules

1. Institutionnel - A propos, Histoire, Vision, Equipe, Contact
2. Activites et Media - Evenements, Galerie media
3. Centre de Savoir - Projets, Recherches, Protocoles, Bibliotheque
4. Capital Humain - Membres, Recrutement, Organigramme
5. Engagement - Dons, Partenaires, Adhesion

## Equipe

| Role | Responsabilite | Technologies |
|------|----------------|-------------|
| Front-end | Pages web, design, formulaires | HTML, CSS, JavaScript |
| Back-end | API REST, base de donnees, securite | Java, Spring Boot, MySQL |
| Integration | Git, tests, deploiement | Git, Docker, Postman |

## Regles Git

- Branche principale : main
- Chaque membre travaille sur sa branche : feature/nom-tache
- Faire un Pull Request avant de fusionner dans main
- Messages de commit clairs

### Convention de commits

- feat: Nouvelle fonctionnalite
- fix: Correction de bug
- docs: Documentation
- style: CSS / mise en forme

## Installation

### Frontend
Ouvrir frontend/index.html dans le navigateur

### Backend
cd backend
./mvnw spring-boot:run

## Licence

Club SIGMA - Tous droits reserves
