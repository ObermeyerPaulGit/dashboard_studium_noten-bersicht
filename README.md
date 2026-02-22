Installationsanleitung für dashboard_prototyp.zip 
1. GitHub-Link: 
https://github.com/ObermeyerPaulGit/dashboard_studium_noten-bersicht 
2. Voraussetzungen 
Python 3.11 oder neuer ist installiert und in der PowerShell verfügbar (python 
oder  py) 
Das Projekt wurde aus GitHub heruntergeladen oder als ZIP entpackt 
getestet unter Windows 10 und demententsprechend empfohlen. Windows 11 
wird ebenfalls empfohlen 
theoretisch ist das Programm plattformneutral, konnte jedoch unter Linux oder
MacOS getestet werden 
3. Projekt herunterladen  
1. Repository auf GitHub über den GitHub Link am Anfang des Dokuments öffnen 
2. Unter „Code“ auf GitHub auf „Download ZIP“ herunterladen 
3. ZIP-Datei entpacken 
4. In den Projektordner wechseln (PowerShell) 
Beispiel: 
PowerShell 
cd C:\Users\Name\Downloads\dashboard_prototyp 
Der Dateipfad des Ordners kann wie folgt eingesehen werden: 
1. Rechtsklick auf den Ordner dashboard_prototyp 
2. Auf „Eigenschaften“ klicken  
Unter „Ort:“ ist der Dateipfad zu finden 
5. Installation, nachdem der Dateipfad ausgewählt wurde 
Start Windows:  
python main.py in die PowerShell eingeben  
oder 
py main.py in die PowerShell eingeben 
Start Linux/MacOS 
python3 main.py in die PowerShell eingeben 
6. Bedienung:  
Nach dem Start erscheint ein Konsolenmenü mit den folgenden Optionen: 
Was möchtest du tun? 
1) Dashboard anzeigen 
2) Prüfungsleistung zu Modul hinzufügen/ändern 
3) Semester hinzufügen 
4) Modul hinzufügen 
5) Einstellungen (Studiengang/Zielsemester/aktuelles 
Semester/Monatsziel/momentanes Modul) 
6) Löschen (Semester/Modul/Prüfungsleistung) 
7) Speichern 
8) Alles zurücksetzen 
9) Beenden 
Auswahl (1-9): 
Geben Sie die Zahl (1-9) für die gewünschte Funktion ein.  
7. Datenhaltung 
Die Daten werden lokal auf Ihrem Gerät in einer JSON-Datei (Standard: 
studiengang.json) im Projektordner gespeichert. Nach dem Speichern wird im 
Dashboard die letzte Aktualisierung (Zeitpunkt der letzten Speicherung) angezeigt. Die 
Datei studiengang.json kann manuell gesichert oder kopiert werden um Backups 
anzulegen.  
