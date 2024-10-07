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
Danach haben wir die Benutzer erstellt. Im folgenden Bild ist einer dieser Benutzer zu sehen.

![Benutzer erstellen](https://github.com/ironflipper/DataFlex/blob/main/Dokumentationen/iperka/Images/Bild%20(9).png)

---
### iSCSI Einrichten in TrueNAS

![iSCSI TrueNAS Screenshot](https://github.com/ironflipper/DataFlex/blob/main/Dokumentationen/iperka/Images/iscsi%20truernas.png)

Hier wird die Konfiguration von iSCSI in TrueNAS gezeigt. Ein neues Block-Gerät mit dem Namen iscsi-design-publisher wird erstellt und der Pfad im Pool /Backup/Design_Publishing gewählt. 

### TrueNAS – Berechtigungen von Ordnern

![TrueNAS Screenshot](https://github.com/ironflipper/DataFlex/blob/main/Dokumentationen/iperka/Images/true.png)

In diesem Abschnitt wurden die Berechtigungen für den Ordner Geschäftsleitung in TrueNAS angepasst. 

### Pools auf dem TrueNas

![TrueNAS Pools](https://github.com/ironflipper/DataFlex/blob/main/Dokumentationen/iperka/Images/truenaspools.png)

Auf dieser Abbildung sieht man die konfigurierten Pools.

---
Linux NFS-Setup

Commands, um bei uns den NFS-Share einzurichten

sudo apt update

sudo apt install nfs-common

sudo mkdir /mnt/it-administration

sudo mount 192.168.1.80:/IT-Administration /mnt/it-administration

 ---

### Yeez1 FullBackup

![Yeez1 FullBackup Screenshot](https://github.com/ironflipper/DataFlex/blob/main/Dokumentationen/iperka/Images/backu2.png)

Die Benutzeroberfläche von Duplicati zeigt die Sicherung *Yeez1 FullBackup*, die für morgen um 13:00 Uhr geplant ist. 

---

### Sicherung hinzufügen und Zeitplan konfigurieren

![Sicherung hinzufügen und Zeitplan Screenshot](https://github.com/ironflipper/DataFlex/blob/main/Dokumentationen/iperka/Images/basckip.png)

Hier wird die Konfiguration der  Sicherungen in Duplicati dargestellt. Die Sicherung ist so eingestellt, dass sie automatisch ausgeführt wird. Der nächste geplante Zeitpunkt ist der 07.10.2024 um 13:00 Uhr, mit täglicher Wiederholung.
