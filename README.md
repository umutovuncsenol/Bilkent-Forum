# Bilkent Forum

Bilkent Forum is a JavaFX desktop forum application designed for Bilkent University students. It provides a graphical environment where users can create accounts, publish posts, interact with content, manage profiles, and connect with other students.

## Features

- User registration and login
- User profiles and profile editing
- Post creation and chronological browsing
- Comments and post interactions
- Upvotes and bookmarked-post views
- Friend management
- Personalized home and activity views
- Persistent MySQL storage through Hibernate

## Tech Stack

| Area | Technologies |
|---|---|
| Language | Java |
| Desktop UI | JavaFX |
| Persistence | Hibernate ORM |
| Database | MySQL |
| Build tool | Maven |

## Project Structure

```text
demofx/demofx/
├── pom.xml
└── src/main/
    ├── java/com/example/
    │   ├── Login.java
    │   ├── HomePage.java
    │   ├── User.java
    │   ├── Post.java
    │   ├── Comment.java
    │   └── ...
    └── resources/
```

The application is organized around authentication, users, posts, comments, profiles, bookmarks, and friends. Hibernate maps the `User`, `Post`, and `Comment` entities to MySQL.

## Getting Started

### Prerequisites

- JDK 17
- Maven
- MySQL
- A Java IDE with JavaFX support

### Database Configuration

Configure your own MySQL connection in:

```text
demofx/demofx/src/main/java/hibernate.cfg.xml
```

Use local or environment-specific credentials and never commit real database passwords.

### Run the Application

1. Open `demofx/demofx` as a Maven project.
2. Allow Maven to resolve the JavaFX, Hibernate, and MySQL dependencies.
3. Configure the database connection.
4. Run `src/main/java/com/example/Login.java`.
5. Create an account or sign in with an existing user.

## My Contributions

My work on this team project included:

- Post-creation functionality and date handling
- Homepage refresh behavior
- User-panel and right-pane improvements
- Scrolling, filtering, and layout fixes
- General JavaFX interface refinement

## Project Background

Bilkent Forum was developed collaboratively by a four-person team. This repository preserves the original commit history and contributor attribution.

Original team repository: [eylulidilyildiz/Bilkent-Forum](https://github.com/eylulidilyildiz/Bilkent-Forum)
