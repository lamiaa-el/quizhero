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

✔️ Commit mit README.md

echo "# Mein QuizHero Projekt" > README.md
git add README.md
git commit -m "📝 Initial commit mit README"

✔️ git diff Beispiel

echo "neuer Text" >> README.md
git diff

✔️ git rm Beispiel

git rm test.txt
git commit -m "🗑️ Datei test.txt gelöscht"

✔️ git mv Beispiel

git mv alt.txt neu.txt
git commit -m "✏️ alt.txt in neu.txt umbenannt"


Experimentieren Sie mit Zeitreisen!

Commit-Historie: git log –oneline

Hash vom gewünschten Commit: git checkout d3a9d2a

Zurück auf Hauptstand: git checkout main

Ich habe eine alte Version der Datei wiederhergestellt, ohne das Repository zurückzusetzen: git restore --source=<commit-hash> -- README.md. Danach habe ich die Änderung mit einem neuen Commit dokumentiert.

Ich habe einen Commit bewusst rückgängig gemacht: git revert HEAD. Dies erstellt einen neuen Commit, der den letzten rückgängig macht.

Ich habe verschiedene Varianten ausprobiert:
git reset --soft HEAD~1      (Commit gelöscht, Änderungen gestaged)
git reset --mixed HEAD~1     (Commit gelöscht, Änderungen behalten)
git reset --hard HEAD~1      (Commit + Änderungen entfernt)

Mit: git reflog konnte ich alte Zustände anzeigen lassen. Ich habe z. B. mit: git checkout 

HEAD@{2} einen alten Zustand wiederhergestellt. 

Oder mit: git reset --hard 5c7c501 gezielt zurückgesetzt.
