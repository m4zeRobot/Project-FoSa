# Project-FoSa
Neuerstellung der Quelldateien für die Formelsammlungen von FLURUS – der Fachschaft des Studiengangs Luft- und Raumfahrttechnik an der Universität Stuttgart, Deutschland.

## Wieso existiert dieses Projekt?
Von der endgültigen Vektorisierung aller Bilder, um scharfe Ausdrucke zu ermöglichen, bis hin zur Möglichkeit, offensichtliche Fehler selbst zu korrigieren – dieses Projekt entstand mit dem Ziel der Verbesserung.
Wenn du einen Beitrag leisten möchten, schreib mir einfach, um kollaborativen Zugriff auf das Repository zu erhalten. Ansonsten können alle hier geteilten Inhalte natürlich frei verwendet werden!

### Vorteile
- Der Leerraum jedes Dokuments wurde optimiert, um das Wertvollste bei der Erstellung einer Formelsammlung zu sparen: Platz.
- Jede Grafik wurde als Vektorgrafik neu erstellt, sodass a) mögliche Fehler leichter korrigierbar sind und b) nach dem Drucken eine scharfe Darstellung gewährleistet ist, während c) jedes Bild zur leichteren Erkennung koloriert wurde.
- Jedem Dokument wurden nützliche Anmerkungen hinzugefügt, von CAS-Befehlen über einfache Seitenzahlen bis hin zu Gleichungsnummern, alles in Übereinstimmung mit der jeweiligen Vorlesung.
- Jedem wird hiermit die Möglichkeit gegeben, Fehler zu korrigieren oder eigene Formelsammlungen zu erstellen!
- Da die Originaldokumente alle auf Deutsch sind, ermöglicht dieses Projekt eine einfache Übersetzung in andere Sprachen.

## Wie die Formelsammlungen aufgebaut sind
Jedes Blatt besteht aus einer harten Unterteilung in sogenannte „Kacheln“ und einer weichen Unterteilung dieser Kacheln entweder in Spalten einer `tabularx`-Umgebung oder in mehrere `minipage`-Umgebungen.
Dadurch sieht der Code hier und da etwas unübersichtlich aus, aber die Ergebnisse sollten immer ohne Warnungen kompiliert werden können.
Die harte Unterteilung legt eine klare Struktur fest, innerhalb derer gearbeitet werden muss, während jede Form der weichen Unterteilung mehr Flexibilität ermöglicht.

## Tipps zum kompilieren der LaTeX-Dateien
Ich empfehle die Installation von [TeX-Live auf Windows](https://tug.org/texlive/windows.html) und Visual Studio Code als Editor
(PowerShell: `winget install Microsoft.VisualStudioCode`, oder manuell downloaden). Für VSCode empfehle ich die folgenden Extensions:
- [LaTeX Language Support](https://marketplace.visualstudio.com/items?itemName=torn4dom4n.latex-support) von Long Nhat Nguyen
- [LaTeX Workshop](https://marketplace.visualstudio.com/items?itemName=James-Yu.latex-workshop) von James Yu
- [LaTeX Utilities](https://marketplace.visualstudio.com/items?itemName=tecosaur.latex-utilities) von tecosaur
- Optional: [LTeX](https://marketplace.visualstudio.com/items?itemName=valentjn.vscode-ltex) von Julian Valentin (Rechtschreib-Korrektur, bei Formelsammlungen eher überflüssig)

<hr/>

## Einige weitere Anmerkungen zur verwendeten Nomenklatur
- **Indizes** werden in der Regel aufrecht geschrieben, da kursive Buchstaben für Variablen stehen. Dies gilt natürlich nicht für Indizes, die selbst Variablen sind, z. B. Zähler wie *i*, *n* usw.
- **Kennzahlen** wie bspw. die Machzahl werden ebenfalls aufrecht geschrieben, obwohl sie technisch gesehen je nach Gleichung variabel sind – das ist lediglich meine persönliche Präferenz.
- **Multiplikationen** werden im Allgemeinen verkürzt, indem einfach ein Halbraum (`\,`) zwischen den Faktoren verwendet wird, anstatt des zentralen Punktes (`\cdot`), wie man ihn vielleicht kennt. Dies dient dazu, Platz zu sparen und verwirrend lange Gleichungen zu vermeiden.

## Danksagung
Dieses Projekt wäre ohne die großartige Vorarbeit vieler vorangegangener Studierender niemals möglich gewesen.
Ich möchte den folgenden Personen explizit Dank aussprechen: R. John, F. Frank, L. Kuhn, M. Höller, P. Weig, R. Reitze, L. Habermalz.
