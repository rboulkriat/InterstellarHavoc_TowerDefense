# Interstellar Havoc

Jeu de **Tower Defense** en Java / JavaFX, développé dans le cadre d'une **SAE** de développement.

> Défendez votre base spatiale contre des vagues d'envahisseurs
> en plaçant des tourelles sur la carte

## Principe du jeu

Des vagues d'ennemis suivent un chemin sur la carte. Le joueur place des tours pour
les arrêter avant qu'ils n'atteignent la base.

- **Objectif** : survivre à N vagues, protéger la base
- **Ressources** : argent gagné en éliminant des ennemis
- **Tours** : types, coûts, portée, dégâts
- **Ennemis** : types, vitesse, points de vie

## Technologies

| Outil | Version | Rôle |
|-------|---------|------|
| Java | 11 | Langage |
| JavaFX | 19 | Interface graphique |
| Maven | - | Gestion du projet et des dépendances |
| ControlsFX | 11.1.0 | Composants JavaFX supplémentaires |
| JUnit 5 | 5.8.1 | Tests unitaires |

## Structure du projet

```
├── src/              # Code source (Java + ressources)
├── Documentation/    # Documentation du projet (conception, diagrammes...)
├── pom.xml           # Configuration Maven
└── README.md
```

## Prérequis

- [JDK 11](https://adoptium.net/) ou plus récent
- [Maven](https://maven.apache.org/download.cgi) (ou celui intégré à IntelliJ IDEA)
- Un IDE conseillé : IntelliJ IDEA

Vérification :

```bash
java -version
mvn -version
```

## Installation et lancement

1. Cloner le dépôt :
   ```bash
   git clone https://github.com/rboulkriat/InterstellarHavoc_TowerDefense.git
   cd InterstellarHavoc_TowerDefense
   ```

2. Lancer le jeu avec Maven :
   ```bash
   mvn clean javafx:run
   ```

**Avec IntelliJ IDEA :** ouvrez le dossier (le `pom.xml` est détecté automatiquement),
attendez l'import Maven, puis lancez la classe principale `HelloApplication`

## Tests

```bash
mvn test
```

## Documentation

Les documents de conception se trouvent dans le dossier
[`Documentation/`](Documentation).

## Contexte

Projet réalisé dans le cadre de la SAÉ « dev » 
