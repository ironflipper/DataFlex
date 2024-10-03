# iPerka - Planning

Schon in der ersten Woche haben wir konkrete Ziele für den Ablauf des Projekts festgelegt. Wir haben beschlossen, alle notwendigen ISO-Dateien und VMs direkt am ersten Tag auf Lionels Laptop zu installieren. Ausserdem haben wir gemeinsam besprochen, was wir in den nächsten zwei Wochen erreichen möchten.

Dabei haben wir uns realistisch Gedanken gemacht und nicht erwartet, dass wir in der zweiten Woche bereits alles fertigstellen. Stattdessen ist unser Ziel, bis zur zweiten Woche eine Basis zu schaffen und in der dritten Woche alle Details fertig haben.



## Konzept-Erklärung

Das Projekt sieht vor, dass mehrere Clients (Windows und Linux) auf einen zentralen **Windows-Server** zugreifen, der wiederum über **iSCSI** mit einem **TrueNAS**-Speichersystem verbunden ist.

- **Windows-Server**: Verwalter der zentralen **Shares**, die verschiedenen Abteilungen und Benutzern zugeordnet sind.
- **TrueNAS**: Dient als zentrale Speicher- und Backup-Lösung. Alle Daten und der Windows-Server selbst werden regelmäßig auf TrueNAS gesichert, um die Datensicherheit zu gewährleisten.
![Konzept](https://github.com/ironflipper/DataFlex/blob/main/Dokumentationen/iperka/Images/Image%20(1).jpg)
