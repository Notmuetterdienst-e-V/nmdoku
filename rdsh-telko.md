---
title: Audio- und Videowiedergabe in der RDP Umgebung
description: Beschreibung, um die Audio- und Videowiedergabe und Aufzeichnung innerhalb der RDP Umgebung zu aktivieren
published: true
date: 2020-03-31T09:55:40.132Z
tags: 
editor: undefined
dateCreated: 2020-03-31T09:31:11.639Z
---

# Übersicht
Im Folgenden wird beschrieben, wie die Audio- und Videoaufzeichnung für Videotelefonkonferenzen innerhalb der RDP-Umgebung aktiviert wird. 
# 1. Schritt: Aufrufen des Bearbeiten-Dialogs
**Bevor** man sich auf der RDP-Umgebung anmeldet, kann man über einen Rechtsklick auf die .rdp-Datei den Bearbeiten-Dialog auswählen:
![rklickbearbeiten.png](/files-rdsh-telko/rklickbearbeiten.png)
Nach dem Rechtsklick auf den im Bild Gelb hinterlegten Bearbeiten-Menupunkt klicken.
# 2. Schritt: Im Dialog den Reiter "Lokale Ressourcen" auswählen
![bearbeitenmenu.png](/files-rdsh-telko/bearbeitenmenu.png)
# 3. Schritt: Lokale Geräte dauerhaft hinzufügen
Im Reiter "Lokale Ressourcen" im Bereich "Lokale Geräte und Ressourcen" den Button "Weitere" klicken:
![lokaleressourcen.png](/files-rdsh-telko/lokaleressourcen.png)
Dann sicherstellen, dass bei "Videoaufnahmegeräte" ein Häkchen gesetzt ist. Dieser Punkt sollte aufklappbar sein, hier kann nochmal gecheckt werden, ob alle Geräte ausgewählt sind:
![kamera.png](/files-rdsh-telko/kamera.png)
> Dieser Schritt muss nur einmalig durchgeführt werden! {.is-info}
# 4. Schritt: Audioaufzeichnung aktivieren
> Dieser Schritt muss **jedesmal** vor dem Anmelden erneut durchgeführt werden, wenn ein Mikrofon nötig ist. {.is-warning}

Im Reiter "Lokale Ressourcen" im Bereich "Remoteaudio" den "Einstellungen" Button betätigen (siehe erstes Bild unter Schritt 3).
Im folgenden Dialog sicherstellen, dass unter "Remoteaudioaufzeichnung" "von diesem Computer aufzeichnen" ausgewählt ist:
![audioaufnahme.png](/files-rdsh-telko/audioaufnahme.png)
