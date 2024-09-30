# iperKa - Control (Kontrolle)


### Fehlermeldung bei der Voraussetzung  
Während der Konfiguration der Active Directory-Domänendienste trat ein Fehler bei der Überprüfung der Voraussetzungen auf. Die Fehlermeldung deutet darauf hin, dass das **TCP/IP-Netzwerkprotokoll** ordnungsgemäß konfiguriert werden muss. Was wir gemacht haben, ist, das Internet von "Host" auf "NAT" umzustellen in den VMware-Einstellungen.

![Fehlermeldung bei der Voraussetzung](https://github.com/ironflipper/DataFlex/blob/main/Dokumentationen/iperka/Images/Bild%20(7).png)

---

### Neue HDD hinzufügen  
Um das vorherige Problem zu lösen, haben wir eine neue **HDD** zur VM hinzugefügt und sie auf **NVMe** eingestellt. Nach dieser Änderung hatten wir die korrekte Auswahl für das Sicherungsziel, und wir konnten unser **Fullbackup** erfolgreich starten.

![Neue HDD hinzufügen](https://github.com/ironflipper/DataFlex/blob/main/Dokumentationen/iperka/Images/Bild%20(12).png)

---

### iSCSI Verbindungsfehler  
Dieser Screenshot zeigt den **Windows iSCSI-Initiator** und den Versuch, eine Verbindung zum iSCSI-Zielportal herzustellen. Die IP-Adresse 192.168.3.129 wurde eingegeben, jedoch trat ein Verbindungsfehler auf. Möglicherweise liegt ein Netzwerkproblem vor.

![iSCSI Verbindungsfehler](https://github.com/ironflipper/DataFlex/blob/main/Dokumentationen/iperka/Images/Bild%20(1).png)

---

### iSCSI-Tutorial  
Hier sahen wir uns ein Tutorial auf YouTube an, das erklärt, wie man **iSCSI** in **TrueNAS** und **Windows 10/11** einrichtet.

![iSCSI-Tutorial](https://github.com/ironflipper/DataFlex/blob/main/Dokumentationen/iperka/Images/Bild%20(2).png)


