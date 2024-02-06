---
title: Aufträge
description: Modul Aufträge
published: true
date: 2020-03-04T09:25:42.309Z
tags: 
editor: undefined
dateCreated: 2020-02-07T12:57:35.964Z
---


![überblick.png](/files-auftraege/überblick.png)
# Überblick
Aufträge entsprechen den vertraglich festgelegten Rahmenbedingungen der Einsätze durch den Kostenträger. Daraus folgt, dass jede Kostenübernahme einem Auftrag entspricht. 
> Bei Verlängerungen von Kassenaufträgen muss daher für jeden verlängerten Zeitraum ein neuer Auftrag angelegt werden. Dies ist einfach duch den "Kopieren"-Button in der [Navigationsleiste](/navbar) möglich, der den [neuen Auftrag im Haushalt](/auftrag-anlegen) vorausgefüllt mit den aktuellen Daten öffnet. {.is-warning}
# Kopfbereich
![kopfbereich.png](/files-auftraege/kopfbereich.png)
Der Kopfbereich des Auftragsmoduls ist in vier Abschnitte gegliedert (von links nach rechts):
* Haushalt
* Kostenträger/Kostensätze
* Auftragsdaten/Umsatzprognose
* Status
## Haushalt
![haushalt.png](/files-auftraege/haushalt.png)
In diesem Abschnitt finden sich die Adressdaten, welche aus dem [Haushalt](/haushalt) übernommen werden. **Adressdatenänderungen sollten immer im Haushalt vorgenommen werden!** Diese können dann durch das Klicken auf den ![datenübernehmen.png](/buttons/datenübernehmen.png)-Button in den Auftrag übernommen werden. 
Weiterhin sind hier Daten zum Familienstand, Betreuungsart und anfallende Tätigkeiten hinterlegt. 
## Kostenträger/Kostensätze
![kostenträger.png](/files-auftraege/kostenträger.png)
Hier finden sich Angaben zum Kostenträger, bei Amt/Kasse- und Kooperationspartner-Aufträgen kann der Kostenträger auch im Nachhinein durch das Betätigen des "Auswählen"-Buttons verändert werden. 
Im Abschnitt Kostensätze können bis zu zwei Sätze pro Auftrag vergeben werden. Dies ist bei Kostenträgern der Fall, die je nach Einsatzdauer pro Tag unterschiedliche Kostensätze ansetzen, z.B. Standardsatz 20,00€, ab der 7. Stunde 18,00€. Die Spalten WS/WT sind jeweils zur Angabe der betreffenden Wochenstunden (WS) bzw. Wochentagen (WT) gedacht. Am obigen Beispiel müsste bei einem 5x 8 Stunden Auftrag hinter Satz 1/Std. 20,00€ stehen und bei WS/WT 30 (5x 6 Stunden); hinter Satz 2/Std. 18,00€ und bei WS/WT 10 (5x die jeweils verbleibenden 2 Stunden). Diese Angaben sind wichtig für die Berechnung der Umsatzprognose.
## Auftragsdaten/Umsatzprognose
![auftragsdaten.png](/files-auftraege/auftragsdaten.png)
In dieser Spalte sind die Angaben zum zeitlichen Umfang zu finden, sowohl hinsichtlich der Einsatztage und zeiten, als auch des Gesamtzeitraums.
Die Umsatzprognose wird anhand der gemachten Angaben zu Kostensätzen und betreffenden Wochenstunden errechnet (siehe oben).
## Status
![status.png](/files-auftraege/status.png)
### Priorität/Wiedervorlage
Der Status "Priorität" legt fest, ob und auf welcher Liste (hoch oder normal) der Auftrag auf dem [Schreibtisch](/schreibtisch) angezeigt wird. Das unter "Wiedervorlage" hinterlegte Datum erscheint ebenfalls auf der jeweiligen Liste und dient der Priorisierung anfallender Tätigkeiten/[To-Dos](/todo).
### Auftragsstatus
Der Auftragsstatus gibt den aktuellen Bearbeitungsstand des Auftrags an. Folgende Status sind offiziell unterstützt:
> * **Anfrage**: Neuanfrage, Kapazitätsprüfung findet aktuell statt
> * **In Bearbeitung**: In einem, diesen Auftrag zugeordneten [Einsatz](/einsaetze) wurde eine [BP](/betreuer) zugeordnet, Kapazitäten sind vorhanden
> * **In Planung**: In einem, diesem Auftrag zugeordneten Einsatz wurde eine [Einsatzvereinbarung versendet](/ev-versenden), aber der Beginn des Auftrags liegt noch in der Zukunft
> * **Aktiv**: In einem, diesem Auftrag zugeordneten Einsatz wurde eine Einsatzvereinbarung versendet und das aktuelle Datum liegt im Betreuungszeitraum
> * **Beendet system**: Der Auftrag wurde vom System beendet
> * **Vorzeitig beendet**: Der Auftrag wurde vorzeitig beendet
> * **Nicht zustande gekommen**: Der Auftrag ist nicht zustande gekommen
> * **Storniert**: Der Auftrag ist nicht zustande gekommen, nachdem bereits eine Einsatzvereinbarung verschickt wurde 
{.is-info}

Hinter dem Statusfeld befindet sich noch ein Datumsfeld, welches nur im Fall eines vorzeitig beendeten Auftrags mit dem Datum befüllt werden muss, **an dem der Auftrag vorzeitig zuende ging**.
### Grund Auftragsstatus
Hier sollte in den Fällen "vorzeitig beendet", "nicht zustande gekommen" und "storniert" ein entsprechende Grund ausgewählt werden. Wenn keiner der vorausgewählten Gründe passt, kann wie überall in der Datenbank zweimal in das Textfeld geklickt werden und manuell etwas eingegeben werden. 
### Status Kostenübernahme
Muss manuell ausgewählt werden, der Status "Schriftlich" ist nur erlaubt, wenn ein Kostenübernahme-Dokument im Auftrag hinterlegt ist. 
### Status Betreuer
Wird automatisch vom System ausgefüllt, sobald eine Betreuungsperson in einem [Einsatz](/eisaetze) zugeordnet wurde. 
### Abrechnungsstatus 
Wird teilweise automatisch vom System ausgefüllt, sobald Ausgangsrechnungen im Auftrag erstellt wurden. Gibt an, ob bereits teilweise oder vollständig abgerechnet wurde.
### To-do / Wer
Ermöglicht das Setzen von Aufgaben, mehr dazu unter [To-Dos](/todo).
### Bearbeiter
Die Mitarbeiter\*in, welche für den Auftrag im Einsatzmanagement zuständig ist. 
# Reiter
![reiter.png](/files-auftraege/reiter.png)
## Personen
![personen.png](/files-auftraege/personen.png)
### Personen, die im Haushalt leben
Hier werden die Personen angezeigt, die im [Haushaltsmodul](/haushalt) eingetragen sind. Wenn neue Haushaltsmitglieder dort nachträglich hinzugefügt wurden, können diese mit dem "Kontakt auswählen"-Button auch zu einem späteren Zeitpunkt im Auftrag hinzugefügt werden. 
### Externe Kontaktpersonen zum Haushalt
Analog zum Haushaltsmodul tauchen hier externe Personen mit wichtigem Bezug zum Haushalt auf. Hier können auch weitere Kontakte hinzugefügt werden, die dann nur **spezifisch für diesen Auftrag sind**. Kontakte, die auf der Auftragsebene hinzugefügt werden, tauchen **nicht** auf der Haushaltsebene auf. Dies ist z.B. bei Sozialdiensten relevant, die ggf. nur zu Beginn des Auftrags eine Rolle spielen und nach der Entlassung aus den Krankenhäusern nicht mehr zuständig sind. 
> Kontakte können, anders als im [Haushalt](/haushalt), hier nicht neu erstellt werden. Nur bereits bestehende Kontakte können auf der Auftragsebene hinzugefügt werden. Sollte z.B. der Kontakt eines Sozialdienstes noch nicht in der Datenbank hinterlegt sein, muss dieser zuerst im [Unternehmensmodul](/unternehmen) unter dem entsprechenden Sozialdienst erstellt werden und dann dem Auftrag hinzugefügt werden.
{.is-warning}
### Wichtige Datenfelder bei Kontakten
> Dies betrifft sowohl im Haushalt lebende Personen, als auch externe Kontakte. 
{.is-info}
#### Leistungsempfänger: 
bei einer Person muss diese Rolle durch Klicken auf das Datenfeld ausgewählt werden. Bei Kassenaufträgen ist dies in der Regel der/die Versicherte.
![leistungsempfänger.png](/files-auftraege/leistungsempfänger.png) 
#### EV
Alle Personen, die später auf der **[Einsatzvereinbarung](/einsaetze#einsatzvereinbarung)** angezeigt werden sollen, müssen hier bei "**EV**" ein Kreuz gesetzt haben.
![evhaken.png](/files-auftraege/evhaken.png)
#### Unterschrift
Die Person, die später auf der **[Einsatzdokumentation](/auftragsunterlagen#einsatzdokumentation)** unterschreiben darf, muss mit einem Haken unter **"Unterschrift"** kenntlich gemacht werden.
![unterschrift.png](/files-auftraege/unterschrift.png)
#### Kostenträger
Die Person, die bei privaten Aufträgen als **Kostenträger** auf der [Ausgangsrechnung](/ausgangsrechnung) erscheinen soll, muss mit einem Haken unter **"Kostenträger"** kenntlich gemacht werden. Sie erscheint später bei der Ausgangsrechnung im Briefkopf als Adressat\*in der Rechnung.
![person_kostenträger.png](/files-auftraege/person_kostenträger.png)
#### Rechnungsempfänger
Die Person, die die [Ausgangsrechnung](/ausgangsrechnung) **erhalten** soll, muss als "Rechnungsempfänger" kenntlich gemacht werden. Dies ist zum Beispiel dann wichtig, wenn ein Privatvertrag auf die Leistungsempfänger\*in läuft, aber deren Kinder sich um die Bezahlung kümmern. Oder wenn ein Privatvertrag mit einer Abtretungserklärung des Vertragspartners mit einem dritten Kostenträger abgerechnet wird (z.B. Verhinderungspflege). Dies ermöglicht später bei der Rechnungsstellung die Erstellung eines Deckblattes mit einer gesonderten Adresse.
![rechnungsempfänger.png](/files-auftraege/rechnungsempfänger.png)
## Tätigkeiten
![tätigkeiten.png](/files-auftraege/tätigkeiten.png)
Hier kann unter den Rubriken **Haushaltstätigkeiten**, **Kinderbetreuung**, **Seniorenbetreuung** und **Grundpflege Senioren** genauer angegeben werden, was im Auftrag an Tätigkeiten anfällt. Die angekreuzten Tätigkeiten werden später bei der [Einsatzausschreibung](/einsaetze#ausschreibung) angegeben.
### Anmerkungen
Hier kann etwas ausführlicher über die Situation bei den Klient\*innen berichtet werden. Auch dieser Text wird in die [Einsatzausschreibung](/einsaetze#ausschreibung) übernommen.
> **Datenschutz**: Hier bitte keine personenbezogenen Daten zu den Aufträgen eintragen, da diese Informationen an Betreuungspersonen weiter gegeben werden!
{.is-warning}
## Einsätze
![einsätze.png](/files-auftraege/einsätze.png)
Der Reiter Einsätze zeigt alle dem Auftrag zugeordneten Einsätze an. Dabei gibt es zwei unterschiedliche Ansichtsarten:
- Liste
- Verlauf
### Listenansicht
Wie der Name suggeriert, werden Einsätze hier als Liste angezeigt (siehe Bild oben). Aktive Einsätze sind weiß hinterlegt, inaktive grau. Aus dieser Ansicht heraus können neue Einsätze über den ![neuereinsatz.png](/buttons/neuereinsatz.png)-Button erstellt werden.
> Stornierte und nicht zustande gekommene Aufträge werden standardmäßig ausgeblendet und müssen über das Setzen eines Häkchens im entsprechenden Feld explizit eingeblendet werden. {.is-warning}
### Verlaufsansicht
![verlauf.png](/files-auftraege/verlauf.png)
Im Verlauf können die von den [Betreuungspersonen](/betreuer) eingereichten Einsatzdokumentationen übertragen werden. So kann innerhalb der Datenbank nachvollzogen werden, wann wieviel gearbeitet wurde. Dies ist insbesondere bei Aufträgen sinnvoll, in denen mehrere Betreuungspersonen tätig sind, gegebenenfalls auch am selben Tag. Durch das Übertragen der geleisteten Stunden entsteht eine Übersicht, inwieweit die maximal zu leistende Stundenanzahl pro Tag/pro Woche/pro Monat erreicht wurde. 
