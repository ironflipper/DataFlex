# ipeRka - Realize  <img src="https://github.com/ironflipper/DataFlex/blob/main/Dokumentationen/iperka/Images/LOGO.png" alt="DataFlex Logo" align="right" width="50"/>

### Bereitstellungskonfiguration
Hier wurde die Konfiguration für die Bereitstellung eines neuen Domänencontrollers für eine neue Domäne durchgeführt. Die Domäne wurde „yeez1.local“ genannt. Dies bedeutet, dass ein neues Active Directory erstellt und dieser Server als primärer Domänencontroller konfiguriert wird.

![Bereitstellungskonfiguration](https://github.com/ironflipper/DataFlex/blob/main/Dokumentationen/iperka/Images/Bild%20(8).png)

### Serverrollen auswählen
Im Windows Server Manager wurde der Assistent zum Hinzufügen von Rollen und Features verwendet. Es wurden Rollen wie "Active Directory-Domänendienste" und "DNS-Server" ausgewählt, um die Server als Domänencontroller zu konfigurieren.

![Serverrollen auswählen](https://github.com/ironflipper/DataFlex/blob/main/Dokumentationen/iperka/Images/Bild%20(6).png)

### Server in der Domain
Hier sieht man, dass der Server in der Domain ist.

![Server in der Domain](https://github.com/ironflipper/DataFlex/blob/main/Dokumentationen/iperka/Images/Bild%20(3).png)

### Benutzer erstellen
Danach haben wir die Benutzer erstellt, auf dem obigen Bild ist einer dieser Benutzer zu sehen.

![Benutzer erstellen](https://github.com/ironflipper/DataFlex/blob/main/Dokumentationen/iperka/Images/Bild%20(9).png)

---

### iSCSI-Tutorial  
Hier sahen wir uns ein Tutorial auf YouTube an, das erklärt, wie man **iSCSI** in **TrueNAS** und **Windows 10/11** einrichtet.

![iSCSI-Tutorial](https://github.com/ironflipper/DataFlex/blob/main/Dokumentationen/iperka/Images/Bild%20(2).png)

---

## Fullbackup erstellen

- Zunächst öffneten wir das Programm **Windows Server-Sicherung** auf unserem Windows Server.
- Danach wählten wir die **Einmalsicherung** aus.
  
  - Hier wird das Ziel festgelegt, wo die Sicherung gespeichert werden soll. In diesem Fall wurde das Volume "E:" als Sicherungsziel ausgewählt.
  - Da es sich um eine vollständige Sicherung handelt, werden alle Daten auf das ausgewählte Laufwerk gesichert.

![Windows Server-Sicherung](https://github.com/ironflipper/DataFlex/blob/main/Dokumentationen/iperka/Images/Bild%20(10).png)

![Sicherungsziel festlegen](https://github.com/ironflipper/DataFlex/blob/main/Dokumentationen/iperka/Images/Bild%20(13).png)

