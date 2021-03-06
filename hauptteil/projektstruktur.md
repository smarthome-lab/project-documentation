# Projektstruktur

Wie vorhin schon beschrieben ist ein Unterschied, dass ein Gitbook eine spezifische Struktur besitzt, welche über mehrere Dateien aufgeteilt ist. Wie diese Struktur aufgebaut ist, wird im Folgenden beschrieben und noch erweitert.

Die Projektstruktur baut auf der standardmäßigen Struktur von Gitbook auf. Dabei sind relevante Dateien und Ordner die Dateien _book.json_, _SUMMARY.md_, _README.md_ und _GLOSSARY.md_ {{ "Gitbook2018b" | cite }}. Diese geben die Grundstruktur vor, welche durch die Ordner Einleitung, Grundlagen, Hauptteil und Fazit ergänzt wird. Der Zweck davon ist, dass sie einen organisatorischen und logischen Zweck erfüllen, um eine bessere Übersichtlichkeit über den Inhalt der Kapitel zu schaffen. Eine Übersicht über die Dateistruktur wird im folgenden Quellcodeabschnitt aufgezeigt. Weiter soll in den folgenden Unterkapiteln auf die Bedeutung der einzelnen Strukturkomponenten eingegangen werden.

!CAPTION Übersicht über die Projektstruktur

```
$ tree -L 1 .                                                                                                                                                                     ‹2.5.0›  09:15:45
.
├── GLOSSARY.md
├── Literature.md
├── Notes.md
├── README.md
├── SUMMARY.md
├── _assets
├── _book
├── _layouts
├── book.json
├── einleitung
├── fazit
├── grundlagen
├── hauptteil
├── literature.bib
└── node_modules

8 directories, 7 files
```



