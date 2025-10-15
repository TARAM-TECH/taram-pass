# Taram Pass - Système de Gestion de Badges et Cartes

<div align="center">

![Version](https://img.shields.io/badge/version-1.0.0-blue.svg)
![Licence](https://img.shields.io/badge/licence-En_attente-orange.svg)
![Spring Boot](https://img.shields.io/badge/Spring_Boot-3.5-brightgreen.svg)

</div>

## 📝 Description

Taram Pass est une application web Spring Boot conçue pour la création et la gestion de documents d'identification. Notre solution permet de gérer :

- 🪪 Badges personnalisés
- 📇 Cartes d'étudiants
- 🎫 Cartes d'élèves
- 🗃️ Autres documents d'identification

## ✨ Fonctionnalités

### 📊 Gestion des données

- Saisie et validation des données personnelles
- Import/Export des informations (CSV, Excel)
- Gestion des photos avec recadrage automatique
- Validation des données en temps réel

### 🎨 Personnalisation

- Création de modèles de cartes personnalisables
- Bibliothèque de modèles préconçus
- Options de personnalisation avancées
- Prévisualisation en temps réel

### 🏭 Production

- Génération de documents PDF haute qualité
- Impression par lot optimisée
- Contrôle qualité intégré
- Export multi-formats (PDF, PNG, JPG)

## 🛠 Stack Technique

### Frontend

- JTE (Java Template Engine) v1.X
- Bootstrap 5.3
- HTML5/CSS3/JavaScript ES6+

### Backend

- Java 21
- Spring Boot 3.5
- Spring Security 6.X
- JOOQ pour l'accès aux données

### Base de données

- PostgreSQL 15+
- Liquibase pour les migrations

## 🚀 Installation

### Prérequis

- Java 21 ou supérieur
- PostgreSQL 15 ou supérieur
- Gradle 8.14.3 ou supérieur
- Git

### Configuration

1. Cloner le dépôt :

```bash
git clone https://github.com/dchaibou/taram-pass.git
cd taram-pass
```

2. Configurer l'environnement :

```bash
cp .env.example .env
```

3. Éditer le fichier `.env` :

```properties
PORT=8080
POSTGRES_URL=jdbc:postgresql://localhost:5432/tarampass
POSTGRES_USERNAME=votre_utilisateur
POSTGRES_PASSWORD=votre_mot_de_passe
```

4. Lancer l'application :

```bash
./gradlew bootRun
```

L'application sera accessible à l'adresse : `http://localhost:8080`

## 🧪 Tests

Exécuter les tests :

```bash
./gradlew test
```

## 📖 Documentation

- [Guide d'utilisation](docs/USER_GUIDE.md)
- [Documentation API](docs/API.md)
- [Guide de contribution](CONTRIBUTING.md)

## 🤝 Contribution

Les contributions sont les bienvenues ! Merci de consulter notre [guide de contribution](CONTRIBUTING.md).

## 📄 Licence

Ce projet est en attente de définition de licence.

## 📞 Support

- 🐛 [Signaler un bug](https://github.com/dchaibou/taram-pass/issues/new?template=bug_report.md)
- 💡 [Proposer une fonctionnalité](https://github.com/dchaibou/taram-pass/issues/new?template=feature_request.md)
- 📧 Contact : [djibrilchaibou.dc@gmail.com]

---

<div align="center">
Développé avec ❤️ par l'équipe Taram Tech
</div>
