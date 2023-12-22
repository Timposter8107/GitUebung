# Backup-Konzept für Ihr Notebook/PC erstellen

## Backup mit RoboCopy

Robocopy (Robust File Copy) ist ein Windows-Kommandozeilen-Tool von Microsoft zum Kopieren und Synchronisieren von Verzeichnissen. Damit kann man einfach in einem anderen Verzeichnis eine Kopie der Dateien erstellen und das Originale Verzeichniss damit synchronisieren.

### Vorteile

* Wie der Name schon sagt, ist Robocopy darauf ausgelegt, robust und zuverlässig zu sein. Es kann große Mengen von Dateien und Verzeichnissen effizient kopieren.

* Robocopy kann große Dateien problemlos handhaben und ist daher gut für die Sicherung großer Datenmengen geeignet.

* Falls die Kopieroperation unterbrochen wird (aufgrund von Netzwerkproblemen oder anderen Fehlern), kann Robocopy die Übertragung fortsetzen, ohne bereits kopierte Dateien erneut zu kopieren.

* Robocopy bietet eine Vielzahl von Schaltern und Optionen, mit denen Sie das Kopierverhalten anpassen können. Dies ermöglicht eine feine Kontrolle über den Kopiervorgang.

* Robocopy kann mehrere Dateien gleichzeitig kopieren, was zu einer verbesserten Leistung führen kann, insbesondere bei der Arbeit mit großen Datenmengen.

### Nachteile

* Robocopy ist spezifisch für Windows und steht nicht auf anderen Betriebssystemen zur Verfügung. Wenn Sie plattformübergreifende Anforderungen haben, müssen Sie möglicherweise auf andere Lösungen zurückgreifen.

* Robocopy ist ein Befehlszeilentool, was bedeutet, dass es keine grafische Benutzeroberfläche hat. Einige Benutzer könnten Schwierigkeiten haben, es zu verwenden, wenn sie nicht mit der Befehlszeile vertraut sind.

* Robocopy bietet keine integrierte Versionsverwaltung für Dateien. Wenn Sie eine detaillierte Versionskontrolle benötigen, müssen Sie möglicherweise auf andere Werkzeuge zurückgreifen.

* Obwohl Robocopy für den Einsatz in Netzwerken konzipiert ist, kann es bei der Arbeit mit einigen Netzwerkfreigaben Probleme geben, insbesondere wenn die Berechtigungen nicht korrekt konfiguriert sind.

* Robocopy ist nicht für Echtzeitsynchronisation konzipiert. Es muss manuell oder durch Skripte gestartet werden, um Dateien zu kopieren.

[Empfehlung für Robocopy](https://www.tecchannel.de/a/robocopy-daten-schnell-und-einfach-unter-windows-sichern,2033515,2)

### Vorgang

Der grundlegende Syntax des Robocopy-Befehls lautet:

1. Öffnen sie die Kommando-Zeile
2. 
3. Schreiben sie ``` robocopy Quellpfad Zielort [Dateien] [Optionen] ```

* Quellpfad: Der Pfad zum Quellverzeichnis, das kopiert werden soll.

* Zielort: Der Pfad zum Zielverzeichnis, wohin die Dateien kopiert werden sollen.

* [Dateien]: Optional können Sie Dateinamen oder Muster angeben, um nur bestimmte Dateien zu kopieren.

* [Optionen]: Hier können Sie verschiedene Schalter und Optionen verwenden, um das Kopierverhalten anzupassen.
