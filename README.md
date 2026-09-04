# Mini-TP 3 — Observer le cycle de vie

:fr: Francais | :uk: English

---

## :fr: Francais

### Description

Ce projet est un mini-TP du module M1 - Developpement mobile Kotlin (Séance 3) de l'ITUniversity. Il porte sur l'anatomie d'une application Android : composants, cycle de vie, Intents et Logcat.

### Objectifs

- Predire la séquence exacte des callbacks du cycle de vie pour deux scénarios
- Observer la séquence au Logcat et comparer aux prédictions
- Compléter un Intent implicite de partage
- Juger le diagnostic d'une stack trace proposé par l'IA

### Scénarios étudiés

| Scénario | Séquence |
| --- | --- |
| Rotation de l'écran | onPause, onStop, onDestroy, onCreate, onStart, onResume |
| Accueil puis retour | onPause, onStop, onRestart, onStart, onResume |

### Technologies

- Kotlin
- Android SDK
- Logcat

### Utilisation

1. Ouvrir le projet dans Android Studio
2. Lancer l'application sur un émulateur ou appareil physique
3. Filtrer le Logcat avec `tag:CYCLE`
4. Jouer les scénarios et observer les callbacks

### Licence

Ce projet est sous licence AGPL-3.0. Voir le fichier `LICENSE` pour plus de détails.

---

## :uk: English

### Description

This project is a mini-TP from the M1 module - Kotlin Mobile Development (Session 3) at ITUniversity. It focuses on Android application anatomy: components, lifecycle, Intents, and Logcat.

### Objectives

- Predict the exact sequence of lifecycle callbacks for two scenarios
- Observe the sequence in Logcat and compare with predictions
- Complete an implicit sharing Intent
- Judge an AI-provided stack trace diagnosis

### Scenarios studied

| Scenario | Sequence |
| --- | --- |
| Screen rotation | onPause, onStop, onDestroy, onCreate, onStart, onResume |
| Home then back | onPause, onStop, onRestart, onStart, onResume |

### Technologies

- Kotlin
- Android SDK
- Logcat

### Usage

1. Open the project in Android Studio
2. Run the application on an emulator or physical device
3. Filter Logcat with `tag:CYCLE`
4. Play the scenarios and observe the callbacks

### License

This project is licensed under AGPL-3.0. See the `LICENSE` file for details.
