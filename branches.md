# Branches

## Was ist ein Branch?

Ein Branch in Git ist im Wesentlichen ein Zeiger auf einen Commit. Standardmäßig beginnt jedes Git-Repository mit einem Haupt-Branch, oft als master bezeichnet. Wenn du einen neuen Branch erstellst, erbst du alle Commits des aktuellen Branches und kannst dann neue Commits auf dem neuen Branch hinzufügen, ohne den Haupt-Branch zu beeinflussen.

## Umgang mit Branches

### Branch erstellen
Um einen neuen Branch zu erstellen und zu diesem zu wechseln, verwenden Sie den Befehl ``` git checkout -b neuer-branch ```.

Dies erstellt einen neuen Branch mit dem Namen "neuer-branch" und wechselt sofort zu diesem Branch.

### Branch wechseln
Um zwischen Branches zu wechseln, verwenden Sie den Befehl ``` git checkout anderer-branch ```.

### Branch auflisten

Um alle branches aufzulisten, verwenden Sie den Befehl ``` git branch ```.

### Änderungen committen

Nachdem Sie Änderungen in einem Branch vorgenommen haben, können Sie diese mit den üblichen ``` git add ``` und ```git commit ``` Befehlen committen.

### Branch mergen

Um die Änderungen aus einem Branch in einen anderen zu integrieren, verwenden Sie die Befehle

``` git checkout ziel-branch ```

``` git merge quell-branch ```

### Branch löschen

Um einen Branch zu löschen, wenn Sie damit fertig sind, benutzen Sie den Befehl ``` git branch -d zu-loeschender-branch ```.

Hier ist noch ein YouTube Video, das ich gefunden habe, das alles ein bisschen besser erklären wird:

##### Git & GitHub Tutorial for Beginners #8 - Branches

[![Git & GitHub Tutorial for Beginners #8 - Branches](https://i3.ytimg.com/vi/QV0kVNvkMxc/maxresdefault.jpg)](https://www.youtube.com/watch?v=QV0kVNvkMxc)