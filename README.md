# SOAPCompteApp

Application Android d'exemple pour gérer des comptes via un service SOAP.

Résumé
- Petite application Android écrite en Kotlin.
- Communique avec un service SOAP (URL de dev: `http://10.0.2.2:8082/services/ws`).
- Affiche une liste de comptes, permet d'ajouter et supprimer des comptes.

Comment construire et exécuter
1. Ouvrez un terminal à la racine du projet (là où se trouvent `gradlew`/`gradlew.bat`).

Windows (PowerShell) :

```powershell
./gradlew.bat assembleDebug
./gradlew.bat installDebug
```

Linux/Mac :

```bash
./gradlew assembleDebug
./gradlew installDebug
```

Exécuter les tests

```powershell
./gradlew.bat test
./gradlew.bat connectedAndroidTest
```

