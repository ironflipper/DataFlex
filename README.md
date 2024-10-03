# Projekt "DataFlex"

## Projekt Beschreibung

Wir haben ein Projekt einer Kleinfirma namens "yeez1 AG" erhalten, welches ein Backupsystem mit verschiedenen Servern & Clients braucht.
Dafür haben wir ein Team erstellt und dieses Projekt kreiert.

## IPERKA Dokumentation

Für die Dokumentation haben wir uns an das IPERKA System angewandt, welches man unter folgenden Links findet:

1. [Inform](https://github.com/ironflipper/DataFlex/blob/main/Dokumentationen/iperka/01_inform.md)
2. [Planning](https://github.com/ironflipper/DataFlex/blob/main/Dokumentationen/iperka/02_planning.md)
3. [Decide](https://github.com/ironflipper/DataFlex/blob/main/Dokumentationen/iperka/03_decide.md)
4. [Realize](https://github.com/ironflipper/DataFlex/blob/main/Dokumentationen/iperka/04_realize.md)
5. [Control](https://github.com/ironflipper/DataFlex/blob/main/Dokumentationen/iperka/05_control.md)
6. [Assess](https://github.com/ironflipper/DataFlex/blob/main/Dokumentationen/iperka/06_assess.md)


Hier das Bild vom Konzept:  
![Konzept](https://github.com/ironflipper/DataFlex/blob/main/Dokumentationen/iperka/Images/Image%20(1).jpg)

## Konzept-Erklärung

Das Projekt sieht vor, dass mehrere Clients (Windows und Linux) auf einen zentralen **Windows-Server** zugreifen, der wiederum über **iSCSI** mit einem **TrueNAS**-Speichersystem verbunden ist.

- **Windows-Server**: Verwalter der zentralen **Shares**, die verschiedenen Abteilungen und Benutzern zugeordnet sind.
- **TrueNAS**: Dient als zentrale Speicher- und Backup-Lösung. Alle Daten und der Windows-Server selbst werden regelmäßig auf TrueNAS gesichert, um die Datensicherheit zu gewährleisten.

