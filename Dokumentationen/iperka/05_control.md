# iperKa - Control (Kontrolle)

![Fehlermeldung bei der Voraussetzung](Dokumentationen/iperka/Images/Bild%20(7).png)
Fehlermeldung bei der Voraussetzung  
Während der Konfiguration der Active Directory-Domänendienste trat ein Fehler bei der Überprüfung der Voraussetzungen auf. Die Fehlermeldung deutet darauf hin, dass das TCP/IP-Netzwerkprotokoll ordnungsgemäß konfiguriert werden muss. Was wir dagegen gemacht haben, ist, dass wir das Internet von "Host" auf "NAT" umgestellt haben in den VMware-Einstellungen.

![Neue HDD hinzufügen](Dokumentationen/iperka/Images/Bild%20(12).png)  
Um dieses Problem zu lösen, haben wir eine neue HDD zur VM hinzugefügt und sie auf NVMe eingestellt. Nach dieser Einstellung hatte man nun die korrekte Auswahl für das Sicherungsziel, und wir konnten unser Fullbackup erfolgreich starten.

![iSCSI Verbindungsfehler](Dokumentationen/iperka/Images/Bild%20(1).png)  
Dieser Screenshot zeigt den Windows iSCSI-Initiator und den Versuch, eine Verbindung zum iSCSI-Zielportal herzustellen. Die IP-Adresse 192.168.3.129 wurde eingegeben, jedoch trat ein Verbindungsfehler auf. Möglicherweise liegt ein Netzwerkproblem vor.

![iSCSI-Tutorial](Dokumentationen/iperka/Images/Bild%20(2).png)  
Hier sahen wir uns ein Tutorial auf YouTube an, das erklärt, wie man iSCSI in TrueNAS und Windows 10/11 einrichtet.

