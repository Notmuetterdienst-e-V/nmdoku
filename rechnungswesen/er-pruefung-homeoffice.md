---
title: Eingangsrechnungsprüfung Homeoffice
description: 
published: true
date: 2021-07-19T08:09:38.129Z
tags: 
editor: undefined
dateCreated: 2021-07-16T11:47:30.393Z
---

# Prozessbeschreibung
Im Folgenden wird der Prozess zur Erfassung, Prüfung und Bezahlung von Eingangsrechnungen beschrieben. Dabei liegt der Fokus auf einem möglichst digitalen Prozess, der zumindest nach der Erfassung der Rechnungen auch aus der Ferne bearbeitet werden kann. 
## Rechnungserfassung
**Michaela**
Eingangsrechnungen werden mit der Tagespost erfasst und entsprechende Datensätze in der Datenbank erstellt. Als Bearbeiter muss beim Erstellen der Datensätze die Person ausgewählt werden, die die Rechnungen später prüfen soll. Nach erfolgreicher Erstellung des Datensatzes werden die Amt/Kasse-Rechnungen von der Einsatzdokumentation getrennt und jeweils fortlaufend nach der ER-Nummer abgelegt. Die entsprechenden Rechnungsdeckblätter werden ebenfalls aufwärts nach ER-Nummer sortiert in einem Ordner abgelegt. Eingangsrechnungen von privaten Einsätzen werden zusammen mit der Einsatzdokumentation separat abgelegt, da diese von Dilay geprüft werden.
## Rechnungsprüfung Amt/Kasse
**Sofie**
Rechnungen werden über den Datensatz in nmData unter Berücksichtigung des angehängen PDFs und ggfs. des Verlaufs auf rechnerische und sachliche Richtigkeit geprüft und über den entsprechenden Button in der Datenbank zum Export vorgemerkt. Zudem speichert die Bearbeiter\*in das PDF im Ordner Zentrale Daten\GS Berlin\Buchhaltung\Rechnungsprüfung\\{JAHR}\ unter der ER-Nummer als Dateiname ab und signiert die rechnerische und sachliche Richtigkeit digital im PDF. Korrekturen werden vor Ort vorgenommen, entweder direkt im PDF oder per Ausdrucken und erneut einscannen.
## Überweisung
**Oli**
Nach dem Export der Buchungsdaten zu Datev können die Rechnungen dort angewiesen werden. Die Beträge werden mit den PDFs abgeglichen und ebenfalls nach erfolgreicher Überweisung mit einem Datumsstempel digital signiert und in einen neuen Unterordner ..\\{ÜBERWEISUNGSDATUM} verschoben.
## Aktualisierung des Datensatzes
**Irena**
Der Datensatz in mData wird auf "bezahlt" mit dem jeweiligen Bezahldatum umgestellt. Die digital signierten PDFs bleiben auf dem Server gespeichert und sind durch den ER-Nummernnamen einfach zu finden.
## Lieferantenrechnungen
Provisionsrechnungen aus den Regionalbüros werden von Irena geprüft und abgezeichnet, anschließend werden diese mit der Signatur erneut gescannt und in Unternehmen Online hochgeladen, entweder per Webanwendung oder per Email. 
CNAD-Rechnungen werden von Sebastian direkt geprüft, abgezeichnet und in Unternehmen Online hochgeladen.
Alle anderen Lieferantenrechnungen werden direkt zu Unternehmen Online hochgeladen und vor der Überweisung von Oli geprüft. 
