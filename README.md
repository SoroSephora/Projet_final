# Notes App - Application de Gestion de Notes

Une application Flutter moderne pour la gestion de notes personnelles avec authentification utilisateur.

## 🚀 Fonctionnalités

- **Authentification sécurisée** : Inscription et connexion utilisateur
- **Gestion des notes** : Création, modification, suppression et recherche de notes
- **Interface moderne** : Design Material 3 avec dégradés et animations
- **Base de données locale** : Stockage SQLite pour la persistance des données
- **Recherche** : Recherche en temps réel dans les titres et contenus
- **Responsive** : Interface adaptée à différentes tailles d'écran

## 📁 Structure du Projet

```
lib/
├── main.dart                 # Point d'entrée de l'application
├── models/
│   ├── user.dart            # Modèle utilisateur
│   └── note.dart            # Modèle note
├── services/
│   ├── auth_service.dart    # Service d'authentification
│   └── database_service.dart # Service de base de données
└── screens/
    ├── login_screen.dart    # Écran de connexion
    ├── register_screen.dart # Écran d'inscription
    ├── notes_screen.dart    # Écran principal des notes
    └── edit_note_screen.dart # Écran d'édition des notes
```

## 🛠️ Améliorations Apportées

### 1. **Architecture Refactorisée**
- Séparation des modèles, services et écrans
- Code plus maintenable et organisé
- Respect des bonnes pratiques Flutter/Dart

### 2. **Correction du Bug Critique**
- ✅ Correction du bug de l'userId hardcodé dans `EditNoteScreen`
- ✅ Gestion correcte de l'association utilisateur-note

### 3. **Interface Utilisateur Améliorée**
- Design Material 3 moderne
- Dégradés et couleurs attrayantes
- Animations et transitions fluides
- Interface de recherche intuitive
- Messages d'état vides améliorés

### 4. **Fonctionnalités Ajoutées**
- Recherche en temps réel dans les notes
- Confirmation de suppression avec dialogue
- Indicateurs de chargement
- Messages de succès/erreur avec SnackBar
- Formatage intelligent des dates
- Menu contextuel pour les actions sur les notes

### 5. **Sécurité et Validation**
- Validation des champs de saisie
- Gestion des erreurs robuste
- Vérification de l'existence des utilisateurs
- Protection contre les doublons

## 🚀 Installation et Exécution

1. **Prérequis**
   - Flutter SDK (version 3.9.0 ou supérieure)
   - Dart SDK
   - Android Studio / VS Code avec extensions Flutter

2. **Installation des dépendances**
   ```bash
   flutter pub get
   ```

3. **Exécution**
   ```bash
   flutter run
   ```

## 📱 Captures d'Écran

L'application propose :
- Un écran de connexion avec design moderne
- Un écran d'inscription avec validation
- Une interface principale avec recherche
- Un éditeur de notes intuitif

## 🔧 Technologies Utilisées

- **Flutter** : Framework de développement mobile
- **SQLite** : Base de données locale (via sqflite)
- **Material 3** : Design system moderne
- **Dart** : Langage de programmation

## 📝 Utilisation

1. **Première utilisation** : Créez un compte via l'écran d'inscription
2. **Connexion** : Connectez-vous avec vos identifiants
3. **Créer une note** : Appuyez sur le bouton "+" pour créer une nouvelle note
4. **Modifier une note** : Appuyez sur une note existante pour la modifier
5. **Rechercher** : Utilisez la barre de recherche pour filtrer vos notes
6. **Supprimer** : Utilisez le menu contextuel pour supprimer une note

## 🐛 Corrections Apportées

- **Bug critique** : L'userId était hardcodé à 1, maintenant correctement géré
- **Architecture** : Code monolithique refactorisé en architecture modulaire
- **UI/UX** : Interface basique remplacée par un design moderne
- **Gestion d'erreurs** : Amélioration de la robustesse de l'application

## 🔮 Améliorations Futures Possibles

- Synchronisation cloud
- Catégorisation des notes
- Export/Import des notes
- Thèmes sombre/clair
- Notifications
- Partage de notes
- Pièces jointes (images, fichiers)

---

**Développé avec ❤️ en Flutter**