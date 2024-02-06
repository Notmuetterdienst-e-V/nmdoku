---
title: Haushalt anlegen
description: Erstellen eines neuen Haushalts
published: true
date: 2020-02-10T15:33:20.454Z
tags: 
editor: undefined
dateCreated: 2020-02-07T12:57:41.287Z
---


# Übersicht
In diesem Abschnitt wird erklärt, wie ein neuer [Haushalt](/haushalt) erstellt werden kann. Dies ist im Einsatzmanagement aktuell der erste Schritt zur Aufnahme einer neuen [Anfrage](/anfrage) in der Datenbank.
Im [Haushalt](/haushalt) werden alle Informationen zum Ort hinterlegt, an dem die Unterstützung stattfinden soll. Zudem werden in diesem Modul alle [Kontakte](/kontakte), die im Haushalt leben oder extern einen wichtigen Bezug zum Haushalt haben erstellt und verknüpft.

# "+ Neu" - Dialog
Über den Button "+ Neu" entweder auf dem [Schreibtisch](/schreibtisch) hinter dem Modulnamen 
![anl_1.png](/anl_1.png) 
oder im [Modul](/modul) selbst über dem Kopfbereich 
![anl_2.png](/anl_2.png) 
wird ein Dialogfenster aufgerufen, mit dem ein neuer Haushalt angelegt werden kann.

# neuer Haushalt anlegen
![neuerhaushaltanlegendialog.png](/neuerhaushaltanlegendialog.png)
Alle mit einem * gekennzeichneten Felder sind Pflichfelder und müssen ausgefüllt werden. 

## Name
Hier bitte den Familiennamen eingeben, wenn mehrere Familiennamen im gleichen Haushalt existieren, können dieses mit einem / getrennt werden, z.B. "Müller / Schmidt". 

## Neukunde
Diese Option steht standardmäßig auf "Ja", das Feld ist relevant bei Umstellungen auf nmData, wenn bereits existierende Klient\*innen manuell in die Datenbank aufgenommen werden. 

## Adresszusatz
Hier können zusätzliche Informationen zur Adresse aufgenommen werden, wie z.B. "Hinterhaus, 4.OG".

## L / PLZ / Ort
L: Land, Standardmäßig ist DE für Deutschland ausgewählt.
PLZ: Postleitzahl
Ort: Ort, wird nach Eingabe der PLZ in der Regel automatisch ausgefüllt.

## Strasse / HsNr
In der Regel wird nach Eingabe der PLZ eine Auswahl der in diesem PLZ-Bereich verfügbaren Straßen angezeigt. Wie in allen Feldern der Datenbank mit Vorauswahloptionen kann bei zweimaligem ins Feld klicken manuell eine Straße eingegeben werden, hier wird dann allerdings die Hausnummer und nachrangig Stadtteil und Bezirk nicht mehr automatisch vom System ausgefüllt. 

## Typ 1 / Typ 2 / Schwangerschaft
Hier werden Angaben zum Familienstand und zur Schwangerschaft gemacht.

## Telefon
In dieses Feld bitte **ausschließlich die Festnetznummer** eintragen, wenn diese vorhanden ist. Handynummern werden später im Datensatz den betreffenden [Kontakten zugeordnet](/kontakte-zu-haushalt#mobil). 

## Telefax
Faxnummer, falls vorhanden. 

## kennt NMD durch
Eine der zur Verfügung stehenden Optionen auswählen, oder durch zweimaliges Klicken ins Textfeld manuell eintragen. 

## "Speichern"-Button
Beim Speichern wird geprüft, ob der Haushalt bereits existiert und wenn nein, ein neuer Datensatz mit den eingetragenen Daten erstellt. Die Dupletten-Prüfung kann auch mit dem Button "prüfen" neben dem [Namen](/haushalt-anlegen#name) manuell durchgeführt werden.


