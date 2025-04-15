# My Notes App 📝

**My Notes App** est une application web full stack permettant la gestion de notes personnelles.  
Elle inclut un système d’authentification simple, un CRUD complet, une interface responsive, et l’ensemble est conteneurisé avec Docker.

## 🚀 Technologies utilisées

### Frontend
- Angular 15+
- TypeScript
- SCSS
- Angular Router & Reactive Forms

### Backend
- Java 17
- Spring Boot
- Spring Web & Spring Data JPA
- PostgreSQL
- Authentification via JWT

### Outils & Qualité
- JUnit / Mockito (backend)
- Karma / Jasmine (frontend)
- Docker & Docker Compose

## 🧪 Fonctionnalités prévues

- [ ] Création, lecture, modification et suppression de notes
- [ ] Authentification (JWT)
- [ ] Gestion des utilisateurs
- [ ] Recherche et filtrage des notes
- [ ] Interface responsive
- [ ] Tests unitaires
- [ ] Conteneurisation complète

## 📦 Structure du projet


## ⚙️ Lancement rapide (en développement)

```bash
# Clone du repo
git clone https://github.com/KBuannec/my-notes-app.git

# Backend
cd backend
./mvnw spring-boot:run

# Frontend
cd frontend
npm install
ng serve
