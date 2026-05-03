## Lesson 1: Git Basics, Gradle

# Aufgabe 1: Git status erklären

```
pm-lecture % git status
On branch b03

Changes not staged for commit:
(use "git add <file>..." to update what will be committed)
(use "git restore <file>..." to discard changes in working directory)
modified:   CONTRIBUTING.md
modified:   homework/b03.md

Untracked files:
(use "git add <file>..." to include in what will be committed)
foo.java

no changes added to commit (use "git add" and/or "git commit -a")
```

Bei der oben beschriebenen Fehler meldung gibt es mehrere Fehler.
1. Die files die geändert wurden, wurden nicht zum stage hinzugefügt
```
modified:   CONTRIBUTING.md
modified:   homework/b03.md
```
2. Es gibt eine untracked file die bei Git noch nicht existiert, aber lokal vorhanden ist. Mit **git add foo.java** würde man diese datei stagen und dann mit git commit commiten.
3. Die letzte Zeile ```no changes added to commit (use "git add" and/or "git commit -a")``` sagt nur, dass nichts mit git add hinzugefügt wurde und der commit nichts commiten kann.


# Aufgabe 2: Git-Spiel
