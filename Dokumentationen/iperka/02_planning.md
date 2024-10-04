# iPerka - Planning  <img src="https://github.com/ironflipper/DataFlex/blob/main/Dokumentationen/iperka/Images/LOGO.png" alt="DataFlex Logo" align="right" width="50"/>

Schon in der ersten Woche haben wir konkrete Ziele für den Ablauf des Projekts festgelegt. Wir haben beschlossen, alle notwendigen ISO-Dateien und VMs direkt am ersten Tag auf Lionels Laptop zu installieren. Ausserdem haben wir gemeinsam besprochen, was wir in den nächsten zwei Wochen erreichen möchten.

Dabei haben wir uns realistisch Gedanken gemacht und nicht erwartet, dass wir in der zweiten Woche bereits alles fertigstellen. Stattdessen ist unser Ziel, bis zur zweiten Woche eine Basis zu schaffen und in der dritten Woche alle Details fertig haben.

## Infrastrukturplan

- **TrueNAS** wird als zentrale Speicherlösung genutzt, um eine einheitliche NAS-Lösung für den Zugriff aller Clients bereitzustellen.
- Ein **Windows-Server** wird als Vermittler für die Clients fungieren und mit dem NAS verbunden.
- Es werden zwei Arten von Clients verwendet:
  - **Windows-Client**.
  - **Linux-Client**.

## Backup-Planung: 3-2-1-Strategie

Die **3-2-1-Backup-Strategie** wird für maximale Datensicherheit implementiert:

1. **3 Kopien der Daten**:
   - Eine Kopie auf **TrueNAS**.
   - Eine Kopie auf **Rewans Laptop**.
   - Eine Kopie auf **Lionels externe Festplatte**.
   
2. **2 verschiedene Speicherarten**:
   - **TrueNAS** als zentraler Speicher.
   - **Externe Festplatte** zur Sicherung der Daten.

3. **1 Kopie an einem externen Ort**:
   - Ein Backup wird auf **Lionels externer Festplatte** gespeichert, um sicherzustellen, dass ein Backup außerhalb des primären Systems gesichert ist.

## Konzept-Erklärung

Das Projekt sieht vor, dass zwei Clients (Windows und Linux) auf einen zentralen **Windows-Server** zugreifen, der wiederum mit einem **TrueNAS**-Speichersystem verbunden ist.

- **Windows-Server**: Verwalter der zentralen **Shares**, die verschiedenen Benutzern zugeordnet sind.
- **TrueNAS**: Dient als zentrale Speicher- und Backup-Lösung. Alle Daten und der Windows-Server selbst werden regelmäßig auf TrueNAS gesichert, um die Datensicherheit zu gewährleisten.
![Konzept](https://github.com/ironflipper/DataFlex/blob/main/Dokumentationen/iperka/Images/Image%20(1).jpg)
