# Schlanke Electron App mit Karusell Kiosk Funktion für Raspberry PI

## Voraussetzungen
- Electron
- npm und Node.js müssen installiert sein
- nodejs mindest version 20.x

## Was kann das Script
- So viele URLs im Karusell Modus anzeigen wie du willst
- Sekunden definieren, wie lange ein Webseite angezeigt werden soll.
- Es können zusätzlich Start und Endzeit angegeben werden, falls eine URL nur zwischen einer definierten Uhrzeit angezeigt werden soll.
- Es lädt die Webseiten **OHNE** IFRAME. Immer mit reload.
    - Dadurch bleibt die Applikation schlank. Es öffnet nur eine Instanz.

## Ansible
- im Ansible Ordner findest du die Scripts für:
    - Kiosk App hochladen (Der Ordner für zum kopieren, muss auf dem Ansible Server im /home/username/ liegen, oder du änderst das Script auf ein Webrepo).
    - Start Kiosk (reboot host).
    - Stop Kiosk (falls du auf den Dekstop musst)

