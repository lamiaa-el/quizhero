# Mein QuizHero Projekt 
## 🔁 Git-Befehle (DVC-E1 Nachweis)

| Befehl             | Zweck                                          |
|--------------------|-----------------------------------------------|
| `git init`         | Git-Repository lokal erstellt                 |
| `git status`       | Änderungen und Zustand geprüft                |
| `git add`          | Datei zum Staging-Bereich hinzugefügt         |
| `git commit`       | Commit mit Nachricht erstellt                 |
| `git push`         | Lokales Repository auf GitHub hochgeladen     |
| `git pull`         | Änderungen vom Remote-Repo geholt             |
| `git diff`         | Unterschiede zwischen Versionen angezeigt     |
| `git rm`           | Datei entfernt                                |
| `git mv`           | Datei umbenannt                               |



🧪 Git-Tests

#✔️ Commit mit README.md
#echo "# Mein QuizHero Projekt" > README.md
#git add README.md
#git commit -m "📝 Initial commit mit README"

✔️ git diff Beispiel
echo "neuer Text" >> README.md
git diff

✔️ git rm Beispiel
git rm test.txt
git commit -m "🗑️ Datei test.txt gelöscht"

✔️ git mv Beispiel
git mv alt.txt neu.txt
git commit -m "✏️ alt.txt in neu.txt umbenannt"

