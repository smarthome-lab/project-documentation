## Gitbook Struktur

Wie oben schon erwähnt, sind die Dateien \_book.json, SUMMARY.md, README.md \_und GLOSSARY.md und deren Bedeutung durch Gitbook vorgegeben. Jede dieser Dateien hat eine spezielle Bedeutung in einem Gitbook, welche nun erläutert werden soll.

**SUMMARY.md**

Die Datei _SUMMARY.md_ hat die Funktion des Inhaltsverzeichnisses und spiegelt dieses in einer textuellen Beschreibung wieder. Darin werden die Namen der Einträge des Inhaltsverzeichnisses auf Dateien mit dem entsprechenden Inhalt abgebildet. Eine beispielsweise Datei für den Inhalt ist im folgenden Ausschnitt dargestellt. Wie alle anderen Dokumente werden die

!CAPTION Beispielhafte SUMMARY.md

```
# Summary

* [Abstract](README.md#abstract_en)
* [Abstrakt](README.md#abstract_de)

## Einleitung

  * [Hintergrund](einleitung/hintergrund.md)
  * [Projektkontext](einleitung/projektkontext.md)
  * [Relevanz und Abgrenzung](einleitung/relevanz.md)
  * [Dokumentstruktur](einleitung/struktur.md)

## Grundlagen

  * [Markdown](grundlagen/markdown.md)
  * [HTML, CSS & JavaScript](grundlagen/html_js.md)
  * [Git](grundlagen/git.md)
  * [Gitbook](grundlagen/gitbook.md)

## Kern

  * [Projektstruktur](hauptteil/projektstruktur.md)
  * [Bewertungskriterien](hauptteil/bewertungskriterien.md)
  * [Styling](hauptteil/styling.md)
  * [Theming](hauptteil/theming.md)
  * [Infrastruktur](hauptteil/infrastruktur.md)

## Fazit & Ausblick

  * [Fazit](fazit/fazit.md)
  * [Ausblick](fazit/ausblick.md)

---

* [Literaturverzeichnis](Literature.md)

## Anhang

* [Anhang 1](Anhang/a1.md)
* [Anhang 2](Anhang/a2.md)
* [Anhang 3](Anhang/a3.md)
```

Hierbei können die einzelnen Hierarchieebenen durch eine eingerückte Liste oder durch Markdown-Überschriften in Abschnitte und Kapitel unterteilt werden. Dabei entsprechen Listen unter den entsprechenden Überschriften Kapiteln der zweiten Hierarchieebene. Die Form der Menüpunkte ist dabei in Form von Links dargestellt. Das Format \`\* \[Titel\]\(Datei\)\` ist so aufgebaut, dass in den eckigen Klammern der Titel steht, welcher in dem Inhaltsverzeichnis angezeigt werden soll. Darauf kommt in den runden Klammern der relative Pfad zur Datei, in der der Inhalt zu dem entsprechenden Inhaltsverzeichnis gespeichert ist.

**README.md**

Die Datei README.md erfüllt nach Gitbook die Funktion der Kurzübersicht über den Inhalt zu geben. Daher eignet sich diese Datei besonders für Abstracts.

**GLOSSARY.md**

Die GLOSSARY.md Datei ist eine Hilfsdatei, die einen Glossar beinhaltet und die Verwendung der Glossarbegriffe in allen Inhalten verknüpft. Hierbei ist zu beachten, dass die Glossarbegriffe in einer entsprechenden Form notiert werden müssen. Die Glossarbegriffe müssen in Markdown mit einer Überschrift der zweiten Ebene beschrieben werden. Der darauf folgende Absatz ist dann die Beschreibung des Glossarbegriffs. Wie dieser Glossarbegriff dann im Text verwendet wird ist in der unten dargestellten Grafik dargestellt.



![](/img/glossar-use.png)

_**book.json**_

Dies ist die wichtigste Date in einem Gitbook, da sie alle
