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

Notes
- Le projet attend un service SOAP côté serveur. En développement, l'app utilise `10.0.2.2` pour atteindre le serveur local depuis l'émulateur Android.
- J'ai traduit les commentaires en français dans le code et les fichiers de ressources.
- J'ai ajouté des icônes placeholder adaptatives dans `app/src/main/res` nommées `ic_launcher_background_generic.xml` et `ic_launcher_foreground_generic.xml` et un fichier adaptatif dans `mipmap-anydpi-v26/ic_launcher_generic.xml`.

Changer les icônes
- Remplacez les drawables dans `app/src/main/res/drawable/` et mettez à jour les ressources `mipmap` si vous voulez des icônes personnalisées.

Contact
- Auteur : projet d'exemple
