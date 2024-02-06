---
title: Datev Belegtransfer
description: In diesem Abschnitt sind alle Themen rund um das Programm Belegtransfer beschrieben
published: true
date: 2020-07-28T07:24:23.569Z
tags: 
editor: undefined
dateCreated: 2020-06-02T11:11:04.345Z
---

# Überblick
In folgendem Abschnitt werden alle Themen hinsichtlich des Datev Belegtransfer-Programms beschrieben.
> Für alle Aktionen in diesem Abschnitt benötigen Sie eine Datev mIdenty-SmartCard! {.is-warning}
# Erstmalige Einrichtung
## Starten des Programms
Das Programm Datev Belegtransfer können Sie über die Suchfunktion in der Taskleiste starten. Sobald Sie dort "beleg" eingeben, sollte Ihnen das Programm angezeigt werden:
![appstarten.png](/files-belegtransfer/appstarten.png)
> Sollte dies nicht der Fall sein, wenden Sie sich bitte an die zuständige Geschäftsstellenleitung, das Programm muss dann höchstwahrscheinlich erst bei Ihnen freigeschaltet werden.
{.is-info}

## Verzeichnisse hinzufügen
Nach dem erstmaligen Starten sind noch keine Verzeichnisse zu sehen:
![belegtransfer.png](/files-belegtransfer/belegtransfer.png)
Um Verzeichnisse hinzufügen zu können, klicken Sie bitte auf den ![btn_verzeichnishinzufügen.png](/files-belegtransfer/btn_verzeichnishinzufügen.png) Button. Sie sollten daraufhin folgendes Fenster sehen:
![verzeichnishinzufügen.png](/files-belegtransfer/verzeichnishinzufügen.png)
Geben Sie nun die Beraternummer "1173" und die Mandantennummer entsprechend der Nummer Ihrer Geschäftsstelle in die entsprechenden Felder ein und klicken Sie auf den ![btn_belegtypenanzeigen.png](/files-belegtransfer/btn_belegtypenanzeigen.png) Button. Das Fenster sollte nun in etwa wie folgt aussehen:
![verzeichnisse.png](/files-belegtransfer/verzeichnisse.png)
Klicken Sie nun auf den "Alle abwählen"-Button und setzen lediglich bei dem Belegtyp "Ohne Belegtyp" ein Häkchen, die anderen Ordner werden für den XML-Upload nicht benötigt.
> Bitte achten Sie unbedingt darauf, dass hier das Häkchen gesetzt ist:
> ![xmlaktivieren.png](/files-belegtransfer/xmlaktivieren.png) {.is-warning}

Klicken Sie nun auf den "Übernehmen"-Button.
In der Hauptansicht können Sie nun alle Verzeichnisse, bis auf "Ohne Belegtyp", abwählen:
![verzeichnisseabwählen.png](/files-belegtransfer/verzeichnisseabwählen.png)
Das Belegtransfer-Programm ist nun für den Import zu Unternehmen Online eingerichtet. 

# Upload zu Unternehmen Online
## Belegtransfer
Kopieren Sie die von nmData beim [Export](/verwaltung/export/export-aus-nmdata) erstellte .zip-Datei in den Ordner Dokumente/Belegtransfer/1173-15490/ohne Belegtyp:
![ohnebelegtypordner.png](/files-belegtransfer/ohnebelegtypordner.png)
Anschließend klicken Sie  Belegtransfer auf den ![btn_datensenden.png](/files-belegtransfer/btn_datensenden.png) Button, damit sollte der Upload starten. 
> Unternehmen Online akzeptiert den selben Dateinamen nicht mehrmals hintereinander, benennen Sie daher die Dateien entsprechend um, wenn Sie mehrere Uploads gleichzeitig oder hintereinander durchführen. {.is-warning}
## Uploadprotokoll überprüfen
Nach dem Upload bitte immer das Importprotokoll auf Unternehmen Online auf Fehler überprüfen. Melden Sie sich dazu auf Unternehmen Online an und gehen auf die "Belege" Seite. 
![startseitebelege.png](/files-belegtransfer/startseitebelege.png)
Klicken Sie dann auf das ![symbol_protokoll.png](/files-belegtransfer/symbol_protokoll.png) Symbol auf der Leiste Rechts im Fenster. Daraufhin sollte sich das Protokolle-Fenster öffnen:
![protokollfenster.png](/files-belegtransfer/protokollfenster.png)
Hier zunächst auf Import und dann den Button "Importprotokoll anzeigen" klicken:
![importprotokollanzeigen.png](/files-belegtransfer/importprotokollanzeigen.png)
Im folgenden Dialog können Sie den gewünschten Datenbereich angeben, standardmäßig ist hier das aktuelle Datum eingetragen, durch einen Klick auf den "Anzeigen"-Button werden Ihnen die aktuelle Protokolleintragungen angezeigt:
![importprotokoll.png](/files-belegtransfer/importprotokoll.png)
Wenn hier etwas anderes, als das ![symbol_ok.png](/files-belegtransfer/symbol_ok.png) in der Spalte "Status Import" angezeigt wird, können Sie das Protokoll mit einem Klick auf das ![btn_protokollanzeigen.png](/files-belegtransfer/btn_protokollanzeigen.png) Symbol einsehen. Achten Sie bei der Protokolldurchsicht auf Ausrufezeichen in der Spalte ganz links, exemplarisch hier ein Eintrag, der zu einer Fehlermeldung geführt hat:
![importprotokolleintrag.png](/files-belegtransfer/importprotokolleintrag.png)
Die Zahl im Dateinamen steht hier übrigens für die entsprechende ER- bzw. AR-Nummer.
