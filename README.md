# Documentation
## Schritt 1
- Erstelle ein Repository auf GitHub.
- Dann lokal mit `git init` und verbinde es mit dem Repository auf GitHub mit dem Befehl `git remote add origin "repo"`.
- `touch onMain.md` zum erstellen der Datei.
- `git add onMain.md` um die Datei in die stagging area zu bringen.
- `git commit -m "message"` um einen commit mit einer Commit Message zu machen.
- `git push` um den neuen commit auf das remote Repository zu übertragen
## Schritt 2
- Erstelle mit `git branch a-feature` einen neuen Branch namens *a-feature*
- Dann mit `git checkout a-feature` auf den neuen Branch wechseln.
- Mit `git add .`, `git commit -m "initial commit"` und `git push --set-upstream origin a-feature` den neuen Branch initzalisieren.
- Dann mit `touch onBranch.md` eine neue file erzeugen.
- Diese dann wieder mit `git add onBranch.md`hinzufügen und mit `git commit -m "added file onBranch.md"` committen und mit `git push` pushen.  
