---
title: Suchen in nmData
description: Suchbefehle und -optionen
published: true
date: 2020-02-07T13:19:51.636Z
tags: 
editor: undefined
dateCreated: 2020-02-07T12:57:59.499Z
---

# Suchen in nmData
## Überblick
![navbar.png](/navbar.png)
Alle Module haben oben in der [Navigationsleiste](/navbar) einen "Suchen"-Button, der es ermöglicht, alle Datensätze aus dem aktuellen Modul nach beliebigen Kriterien zu durchsuchen und entsprechend der Suchkriterien auszuwählen. 
### Beispiel:
#### Navigieren in das zu durchsuchende Modul
![suchenbsp1.png](/suchenbsp1.png)
Im Modul Haushalte sind aktuell 2026 vorhandene Datensätze ausgewählt (siehe gelb hinterlegte Zahl). Der Suchvorgang wird durch das Klicken auf den "Suchen"-Button gestartet. Durch das Klicken leeren sich alle Datenfelder und in den Feldern, die für die Eingabe von Suchkriterien geeignet sind, erscheint eine Lupe.
#### Eingabe der Suchkriterien
![suchenbsp2.png](/files-suchen/suchenbsp2.png)
In diesem Beispiel wurden drei Suchkriterien miteinander verknüpft. Durch das Bestätigen der Suche mit der "Enter"- oder "Return"-Taste, wird nun das Modul Haushalte nach Datensätzen durchsucht, die den Status "aktiv" haben **und** im Feld Telefon einen Wert eingetragen haben **und** Typ 3 Schwangerschaft angekreuzt haben. 
> Beachten Sie, dass Datenfelder aus allen Reitern für die Eingabe der Suchkriterien verwendet werden können. Die Reiter können auch während dem Eingeben der Suchkriterien gewechselt werden, ohne dass zuvor eingegebene Kriterien verfallen.
{.is-info}
#### Ergebnis sichten
![suchenbsp3.png](/files-suchen/suchenbsp3.png)
Insgesamt wurden vier Datensätze gefunden und ausgewählt, auf die diese Kriterien zutreffen (siehe gelb hinterlegte Zahl). Mit den Pfeilbuttons in der [Navigationsleiste](/navbar) kann durch diese vier ausgewählten Datensätze durchgeblättert werden. 
## Suchbefehle<sup>[1](/suchen#quelle)</sup>
### Suchen in Textfeldern
Suchen Sie in Textfeldern nach Text oder Textpassagen. Sofern Sie nicht nach Wortkombinationen und exakten Übereinstimmungen suchen, kann das gefundene Feld nicht nur den angegebenen Text, sondern weitere Werte in beliebiger Reihenfolge enthalten. Wenn Sie z.B. „Hotel“ in das Feld „Firma“ eingeben, findet nmData Datensätze für „Hotel“, „Wellness Hotel“ und „Hotel & Restaurant“.
#### Worte, die mit bestimmten Zeichen beginnen:
```Chris Meyer```

…findet Chris Meyer, Chris Meyerdierks und Meyer Christiane.
#### Eine exakte Phrase oder Zeichenfolge
```„Gaststätte Strohhalm“```

…findet nur „Gaststätte Strohhalm“
#### Worte mit einem unbekannten Zeichen:
```F@au```

…findet Frau und flau.
#### Ungültige Zeichen
```?``` (Fragezeichen)

…findet ungültige Zeichen, auch in einem Datums- oder Zahlenfeld
#### Mehrere unbekannte Zeichen:
```Ei*en```

…findet Eisen, eislaufen und Eisenhauer.
#### Ziffern in einem Textfeld
```#``` (für jede Ziffer)

…findet 5, aber nicht 50
#### Teile einer Phrase (eine Wort- oder Zeichenfolge):
```*“er & Schmidt“```

…findet „Meyer & Schmidt“, aber auch „Müller & Schmidt“.
#### Exakte Übereinstimmung:
```==``` (zwei Gleichheitszeichen)

```==Stefanie```
…findet Stefanie, aber nicht Stefanie Meyer.
#### Exakte Übereinstimmung mit den angegebenen ganzen Wörtern:
```=``` (ein Gleichheitszeichen)

```=Annett =Meyer```
…findet Annett Meyer oder Meyer Annett, aber nicht Annett oder Annette Meyer.
### Suchen in Zahlen- und Datumsfeldern
#### Eine Zahl in einem Zahlenfeld
```0,50```

…findet 0,50 und 50%.
#### Einen Wertebereich in einem Zahlenfeld
```8…50``` (drei Punkte zwischen den Werten)

…findet alle Werte zwischen 8 und 50.
#### Ein Datum in einem Datumsfeld
```3.3.2005```

…findet 3.3.2005, 3. März 2005 und 03-03.2005.
#### Einen Zeitraum in einem Datumsfeld
```3.3.2011…31.12.2011``` (drei Punkte zwischen den Daten)

…findet alle Datensätze mit Datum zwischen dem 3.3.2011 und dem 31.12.2011.
#### Heutiges Datum in einem Datumsfeld
```//``` (zwei Querstriche)

…findet das heutige (System) Datum
#### Datumswerte an einem bestimmten Wochentag in einem Datumsfeld
```Dienstag```

…findet alle Einträge, die auf einen Dienstag fallen
#### Alle gültigen Werte für ein Datums- oder Zeitfeld
```*``` (Stern) 

…findet alle gültigen Werte
#### Ungültige Datumsangaben
```?``` (Fragezeichen)

…findet ungültige Einträge, siehe oben

Alle genannten Suchoptionen lassen sich in Uhrzeit- oder Zeitstempfelfeldern analog zu den Datumsfeldern anwenden.

Mit den genannten Suchoptionen lassen sich nahezu alle gewünschten Suchabfragen und Selektionen erfolgreich durchführen. 
### Quelle
[1] https://gofilemaker.de/2011/03/finden-filemaker-richtig-gesucht-ist-halb-gefunden/

