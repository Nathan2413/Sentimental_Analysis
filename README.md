Voici la mise à jour de votre fichier README.md pour inclure les étapes pour installer l'application sur un téléphone :

```markdown
# Sentimental Analysis - Application Amusante

Ce projet est une application Flutter pour l'analyse sentimentale, conçue pour détecter l'humeur des personnes à partir d'images. L'application utilise la technologie de reconnaissance faciale de Google ML Kit pour analyser les visages dans les images et déterminer leur humeur.

## Configuration du Projet

### Clonage du Projet
1. Clonez le projet à partir de GitHub en utilisant la commande suivante :
```
git clone https://github.com/Nathan2413/Sentimental_analysis_FunnyApp.git
```

### Installation des Dépendances
2. Ouvrez le fichier "Sentimental_analysis_funnyapp" dans Visual Studio Code.
3. Ouvrez une terminal dans Visual Studio Code et exécutez la commande suivante pour installer les dépendances Flutter :
```
flutter pub get
```

### Mise à Jour des Dépendances
4. Mettez à jour le fichier "pubspec.yaml" en modifiant les versions des packages suivants :
   - cupertino_icons: ^1.0.2
   - google_ml_kit: ^0.16.3
   - image_picker: ^1.0.7
   - flutter_lints: ^3.0.1

### Vérification et Analyse du Projet
5. Vérifiez si des packages nécessitent une mise à jour en utilisant la commande :
```
flutter pub outdated
```
Suivez les instructions pour mettre à jour les packages.

6. Une fois que tous les packages sont à jour, vérifiez les erreurs dans le projet en utilisant la commande :
```
flutter analyze
```

### Exécution de l'Application
7. Si aucune erreur n'est détectée, lancez l'application en utilisant la commande :
```
flutter run
```

## Installation sur Téléphone

### Build de l'APK
Pour installer l'application sur votre téléphone, suivez ces étapes :
1. Exécutez la commande `flutter build apk` pour générer un fichier APK de votre application. Cette commande générera un fichier APK dans le répertoire `build/app/outputs/flutter-apk/`.

### Installation sur Téléphone
2. Une fois la construction terminée, recherchez le fichier APK généré dans le répertoire `build/app/outputs/flutter-apk/`.
3. Transférez le fichier APK sur un appareil Android et installez-le pour tester votre application.

## Contributions et Problèmes
Les contributions au projet sont les bienvenues ! Si vous rencontrez des problèmes ou si vous avez des suggestions d'amélioration, veuillez les signaler en créant une "issue" sur GitHub.

Merci d'utiliser notre application Sentimental Analysis ! Amusez-vous bien ! 🚀

**Auteur :** Nathan RC et Lahizarre P
```

Cela inclut maintenant les étapes pour générer le fichier APK et l'installer sur un téléphone Android.
