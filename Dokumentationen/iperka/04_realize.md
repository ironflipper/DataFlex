## ipeRka - Realize

### Bereitstellungskonfiguration
Hier wurde die Konfiguration für die Bereitstellung eines neuen Domänencontrollers für eine neue Domäne durchgeführt. Die Domäne wurde „yeez1.local“ genannt. Dies bedeutet, dass ein neues Active Directory erstellt und dieser Server als primärer Domänencontroller konfiguriert wird.

### Serverrollen auswählen
Im Windows Server Manager wurde der Assistent zum Hinzufügen von Rollen und Features verwendet. Es wurden Rollen wie "Active Directory-Domänendienste" und "DNS-Server" ausgewählt, um die Server als Domänencontroller zu konfigurieren.

### Benutzer erstellen
Danach haben wir die Benutzer erstellt, auf dem obigen Bild ist einer dieser Benutzer zu sehen.

## Fullbackup erstellen

- Zunächst öffneten wir das Programm **Windows Server-Sicherung** auf unserem Windows Server.
- Danach wählten wir die **Einmalsicherung** aus.
- In diesem Fall wurde die einmalige Sicherung ausgewählt.
  
  - Hier wird das Ziel festgelegt, wo die Sicherung gespeichert werden soll. In diesem Fall wurde das Volume "E:" als Sicherungsziel ausgewählt.
  - Da es sich um eine vollständige Sicherung handelt, werden alle Daten auf das ausgewählte Laufwerk gesichert.
