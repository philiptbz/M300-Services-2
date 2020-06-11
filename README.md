# M300-Services
M300 Services von Tim Bühlmann

Ich habe jeweils diese Kriterien in der Dokumentation eingefügt, welche ich auch gelöst habe. Hier habe ich darauf geschaut, dass mindestens vier Kriterien erledigt wurden.

# Inhaltsverzeichnis
[1. Kriterium](#1-kriterium)
[2. Kriterium](#2-kriterium)
[3. Kriterium](#3-kriterium)
[4. Kriterium](#4-kriterium)


## 1. Kriterium
- [x] 1. VirtualBox
- [x] 2. Vagrant
- [x] 3. Visualstudio-Code
- [x] 4. Git-Client
- [x] 5. SSH-Key für Client erstellen

### 1. Virtualbox

Die Oracle Virtualbox habe ich bereits vor diesem Modul gebraucht. Somit hatte ich diese bereits installiert. Dies sollte der folgenden Screenshot zeigen.
  
![](https://github.com/tbztim/M300-Services/blob/master/00-Bilder/Virtualbox.png "Virtualbox")

### 2. Vagrant
Im unteren Screenshot sehen Sie, dass Vagrant korrekt installiert wurde. Dort wird auch gleich kurz die verwendete Vagrant Version angezeigt.
  
![](https://github.com/tbztim/M300-Services/blob/master/00-Bilder/Vagrant.png "Vagrant")

### 3. Visualstudio-Code

Ich habe Visualstudio Code mit den folgenden Erweiterunten installiert. Dies hat problemlos funktioniert.


- Markdown All in One (von Yu Zhang)
- Vagrant Extension (von Marco Stanzi)
- vscode-pdf Extension (von tomiko1207)

### 4. Git-Client
Im unteren Screenshot sieht man, dass der Git Client korrekt installiert wurde. Zudem wird auch die verwendete Version des Git-Clients angezeigt.

![](https://github.com/tbztim/M300-Services/blob/master/00-Bilder/git-client.png "Git-Client")

### 5. SSH-Key für Client erstellen
Im unteren Screenshot sehen Sie die Ausgabe des Befehls ```ssh -v git@github.com```. Dort ist auch gekennzeichnet, dass ich erfolgreich verbunden wurde. Dies habe ich im Screenshot auch rot markiert, sodass man dies direkt auf den ersten Blick sieht.

![](https://github.com/tbztim/M300-Services/blob/master/00-Bilder/ssh-key.png "SSH-Key")

## 2. Kriterium
- [x] 1. GitHub oder Gitlab-Account ist erstellt
- [x] 2. Git-Client wurde verwendet
- [x] 3. Dokumentation ist als Mark Down vorhanden
- [x] 4. Mark down-Editor ausgewählt und eingerichtet
- [x] 5. Mark down ist strukturiert
- [x] 6. Wichtige Lernschritte sind dokumentiert

### 1. GitHub oder Gitlab-Account ist erstellt
Der Github Account wurde erstellt. Das Profil ist unter dem folgenden Link aufrufbar: ![Github tbztim](https://github.com/tbztim)

### 2. Git-Client wurde verwendet
Der untere Screenshot zeigt, dass ich den Git Client verwendet habe. Da ich diesen Bereits in einem vorherigen Modul verwendet habe, musste ich diesen nicht nochmals installieren. Dieser war bereits auf meinem Notebook vorhanden.

![](https://github.com/tbztim/M300-Services/blob/master/00-Bilder/git-client-window.png "Git-Client-Windows")

### 3. Dokumentation ist als Mark Down vorhanden
Die Dokumentation ist als Mark Down vorhanden, wie man anhand der README.md Datei sehen kann. Es handelt sich hier um eine .md Datei also wurde hier mit Mark Down gearbeitet.

### 4. Mark down-Editor ausgewählt und eingerichtet
Als Mark Down-Editor habe ich Visual Studio Code verwendet. Hier musste ich keine konfiguration vornehmen. Das bearbeiten der README.md Datei hat ohne vorkonfiguration bereits funktioniert. Ebenfalls konnte ich die Datei aus dem Visual Studio Code auch immer "pushen".

### 5. Mark down ist strukturiert
Ich finde, dass mein Mark Down sehr gut strukturiert ist und ich dieses Kriterium erfüllt habe. Ob ein Mark Down strukturiert ist oder nicht, hängt jedoch immer vom Menschen ab. Ich finde hier eben ich habe es gut strukturiert. Andere finden zum Beispiel das meine Struktur nicht gut ist. Dies ist aber abhängig vom Menschen.

### 6. Wichtige Lernschritte sind dokumentiert
Wichtige Lernschritte habe ich jeweils im Mark Down festgehalten. Dies kann man anhand meiner Dokumentation sehen.

## 3. Kriterium
- [x] 1. Bestehende vm aus Vagrant-Cloud einrichten
- [x] 2. Kennt die Vagrant-Befehle
- [x] 3. Eingerichtete Umgebung ist dokumentiert
- [x] 4. Funktionsweise getestet inkl. Dokumentation der Testfälle
- [x] 5. andere, vorgefertigte vm auf eigenem Notebook aufgesetzt
- [x] 6. Projekt mit Git und Mark Down dokumentiert

### 1. Bestehende vm aus Vagrant-Cloud einrichten
Eine bestehende VM kann aus dem Verzeichnis, indem die VM liegt bzw. indem das Vagrant-File liegt, gestartet werden. Hierzu muss in diesem Verzeichnis die Git-Bash geöffnet werden. Danach muss der folgende Befehl eingegeben werden.

```vagrant up```

### 2. Kennt die Vagrant-Befehle
Hier sind die wichtigsten Vagrant-Befehl ausgelistet.

Befehl            | Funktion
----------------- | -------------
`vagrant up`	  | Startet vagrant Umgebung
`vagrant resume`  | Setzt eine suspendierte Maschine fort.
`vagrant reload`  | Startet die VM neu, liest das Config File neu ein
`vagrant ssh`     | Verbinden zu einer Maschine via SSH
`vagrant halt`    | Stopt die vagrant Maschine
`vagrant suspend` | suspendiert eine VM
`vagrant destroy` | Stopt und löscht die gesamte VM
`vagrant -v`      | Zeigt die vagrant Version an
`vagrant status`  | Gibt den Stataus einer VM aus.

### 3. Eingerichtete Umgebung ist dokumentiert
In der Umgebung der VM für die LB02 habe ich die folgenden Punkte eingerichetet:

- Webserver Apache installiert
- Firewall installiert und Regeln erstellt
- Reverse-Proxy konfiguriert
- Benutzer / Gruppen erstellt und konfiguriert
- LDAP installiert und konfiguriert
- HTTPS freigeschaltet

Dass diese Punkte gemacht wurden, werden Sie dann im Vagrant-File und in der Demo noch sehen.

### 4. Funktionsweise getestet inkl. Dokumentation der Testfälle
Die ausgeführten VM's haben bei mir immer sehr gut funtkioniert. Da es sich am Anfang um Beispiele gehandelt hat, haben diese immer funktioniert. Meine eigenen Scripts haben am Anfang nicht immer funktioniert. Doch nach einigen versuchen konnte ich dann auch meine eigenen Scripts zum laufen bringen. Diese haben dann auch immer funktioniert. :)

### 5. andere, vorgefertigte vm auf eigenem Notebook aufgesetzt
Ich habe noch eine weitere VM auf dem Notebook aufgesetzt. Hierbei habe ich das Vagrant-File, welches unter dem folgenden Pfad liegt ausgeführt.

![DB-Beispiel-VM](https://github.com/mc-b/M300/tree/master/vagrant/db)

Diese VM habe ich mit dem Befehl `vagrant up` gestartet. Auch hier musste ich im Verzeichnis sein, in dem das Vagrant-File vorhanden war. Dies hat ohne Probleme geklappt.

### 6. Projekt mit Git und Mark Down dokumentiert
Wie man anhand der Dokumentation hier sehen kann, habe ich alles mit Git und Mark Down schön und sauber aufgeführt.

## 4. Kriterium
- [x] 1. Firewall eingerichtet inkl. Rules
- [x] 2. Reverse-Proxy eingerichtet
- [x] 3. Benutzer- und Rechtevergabe ist eingerichtet
- [x] 4. Sicherheitsmassnahmen sind dokumentiert
- [x] 5. Projekt mit Git und Mark Down dokumentiert

### 1. Firewall eingerichtet inkl. Rules
Unter dem folgenden Screenshot wird der aktuelle Status der Firewall gezeigt. Dort ist auch ersichtlich, welche konfiguration gemacht wurde.

![](https://github.com/tbztim/M300-Services/blob/master/00-Bilder/ufw_status.png "Firewall Status")

### 2. Reverse-Proxy eingerichtet
Im folgenden Screenshot wird die Reverse Procy konfiguration angezeigt. Hier wird die KOnfigurations-Datei angezeigt, welche im Script auch definiert wurde.

![](https://github.com/tbztim/M300-Services/blob/master/00-Bilder/reverse-proxy.png "Reverse Proxy")

### 3. Benutzer- und Rechtevergabe ist eingerichtet
Im folgenden Screenshot werden die erstellten Benutzer und Gruppen angezeigt. Zudem wird auch direkt gezeigt, welcher Benutzer, welcher Gruppe zugeordnet wurde. Dies haben wir so im Vagrant-File definiert.

![](https://github.com/tbztim/M300-Services/blob/master/00-Bilder/benutzer-gruppen.png "Benutzer Gruppen")

### 4. Sicherheitsmassnahmen sind dokumentiert
Die vorgenommenen Sicherheitsmassnahmen sind einerseits im Vagrant-File kommentiert und andererseits, werde ich diese unten auch nochmals kurz aufführen.

- Firewall aktiv
- Firewall-Rules erstellt
- Proxy installiert und aktiviert
- Reverse Proxy konfiguriert

### 5. Projekt mit Git und Mark Down dokumentiert
Auch hier, finde ich, dass die einzelnen Schritte in diesem Markdown gut dokumentiert sind. Einige Dinge sind auch im Vagrant-File als Kommentar dokumentiert.