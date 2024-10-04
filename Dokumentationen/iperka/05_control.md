# iperKa - Control (Kontrolle)  <img src="https://github.com/ironflipper/DataFlex/blob/main/Dokumentationen/iperka/Images/LOGO.png" alt="DataFlex Logo" align="right" width="50"/>


### Fehlermeldung bei der Voraussetzung  
Während der Konfiguration der Active Directory-Domänendienste trat ein Fehler bei der Überprüfung der Voraussetzungen auf. Die Fehlermeldung deutet darauf hin, dass das **TCP/IP-Netzwerkprotokoll** ordnungsgemäss konfiguriert werden muss. Um dies zu lösen, haben wir das Internet von "Host" auf "NAT" in den VMware-Einstellungen umgestellt.

![Fehlermeldung bei der Voraussetzung](https://github.com/ironflipper/DataFlex/blob/main/Dokumentationen/iperka/Images/Bild%20(7).png)

---

### Neue HDD hinzufügen  
Um das folgende Problem zu lösen, haben wir eine neue **HDD** zur VM hinzugefügt und sie auf **NVMe** eingestellt. Nach dieser Änderung hatten wir die korrekte Auswahl für das Sicherungsziel, und wir konnten unser **Fullbackup** erfolgreich starten.

![Neue HDD hinzufügen](https://github.com/ironflipper/DataFlex/blob/main/Dokumentationen/iperka/Images/Bild%20(12).png)

---

### iSCSI Verbindungsfehler  
Dieser Screenshot zeigt den **Windows iSCSI-Initiator** und den Versuch, eine Verbindung zum iSCSI-Zielportal herzustellen. Die IP-Adresse 192.168.3.129 wurde eingegeben, jedoch trat ein Verbindungsfehler auf. Bei dem Problem handelte es sich um ein Netzwerkproblem.

![iSCSI Verbindungsfehler](https://github.com/ironflipper/DataFlex/blob/main/Dokumentationen/iperka/Images/Bild%20(1).png)



