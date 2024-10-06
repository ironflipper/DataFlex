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

### iSCSI-Tutorial  
Hier sahen wir uns ein Tutorial auf YouTube an, welches erklärt, wie man **iSCSI** in **TrueNAS** und **Windows 10/11** einrichtet.

![iSCSI-Tutorial](https://github.com/ironflipper/DataFlex/blob/main/Dokumentationen/iperka/Images/Bild%20(2).png)




# TrueNAS – Einrichten eines Files unter einem Pool

![TrueNAS Screenshot](https://github.com/ironflipper/DataFlex/blob/main/Dokumentationen/iperka/Images/true.png)

In der *TrueNAS*-Benutzeroberfläche wird ein File unter einem Pool eingerichtet. Der Pfad des Verzeichnisses ist /mnt/Backup/Geschäftsleitung. Der Benutzer *root* und die Gruppe *Geschäftsleitung* haben erweiterte Berechtigungen. Die Konfiguration zeigt, dass die Gruppe *Geschäftsleitung* Zugriff auf das Verzeichnis hat, und grundlegende sowie erweiterte Berechtigungen (Lesen, Schreiben, Anhängen von Daten) erteilt wurden. Der Zugriffstyp ist auf „Erlauben“ gestellt.

---

# Yeez1 FullBackup

![Yeez1 FullBackup Screenshot](https://github.com/ironflipper/DataFlex/blob/main/Dokumentationen/iperka/Images/backu2.png)

Die Benutzeroberfläche von *Duplicati* zeigt die Sicherung *Yeez1 FullBackup*, die für morgen um 13:00 Uhr geplant ist. Bisher wurde keine erfolgreiche Sicherung durchgeführt, aber es gibt die Option, die Sicherung sofort zu starten („Jetzt sichern“).

---

# Sicherung hinzufügen und Zeitplan konfigurieren

![Sicherung hinzufügen und Zeitplan Screenshot](https://github.com/ironflipper/DataFlex/blob/main/Dokumentationen/iperka/Images/basckip.png)

Hier wird die Konfiguration der automatischen Sicherungen in *Duplicati* dargestellt. Die Sicherung ist so eingestellt, dass sie automatisch ausgeführt wird, wenn ein geplanter Zeitpunkt verpasst wurde. Der nächste geplante Zeitpunkt ist der *07.10.2024 um 13:00 Uhr*, mit täglicher Wiederholung. Alle Wochentage sind für die Ausführung der Sicherung ausgewählt.
