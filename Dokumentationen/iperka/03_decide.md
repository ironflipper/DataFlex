# ipErka - Decide (Entscheiden)  <img src="https://github.com/ironflipper/DataFlex/blob/main/Dokumentationen/iperka/Images/LOGO.png" alt="DataFlex Logo" align="right" width="50"/>

Wir haben uns von Anfang an entschieden, alles gemeinsam zu machen und uns gegenseitig zu unterstützen, insbesondere bei Schwierigkeiten. Unsere getroffenen Entscheidungen sind unten aufgeführt, und für schnell entschiedene Punkte haben wir eine Excel-Tabelle erstellt.

1. **Teamname:** Es war schwierig, einen passenden Teamnamen zu finden, und wir hatten mehrere Ideen, wie z. B. "yeez1 Migration". Da es sich jedoch nicht um eine Migration handelt, haben wir uns für "DataFlex" entschieden, da der Name Flexibilität im Umgang mit Daten vermittelt und unserer Meinung nach gut zum Thema passt.

2. **Projektname:** Nachdem wir einen Teamnamen gefunden hatten, war es nicht schwierig, einen Projektnamen auszuwählen. Wir haben uns für "Projekt DataFlex" entschieden, da dieses Team speziell für dieses Projekt zusammengestellt wurde.

3. **Hardware:** Wir haben die Prozessoren unserer Laptops verglichen, um festzustellen, wer den besten Laptop hat, da diese Person die VMs erstellen soll. Es stellte sich heraus, dass Lionel den besten Laptop besitzt.

4. **VM-Erstellung:** Da Lionel das leistungsfähigste Gerät hat, wird er die VMs auf seinem Laptop erstellen, und Samuele wird ihn dabei unterstützen.

5. **Dokumentation:** Rewan wird die Dokumentation erstellen, unterstützt von Aakib.

6. **Passwortwahl:** Wir haben zusammen ein passendes Windows-Administrator-Passwort gefunden, das leicht zu merken ist. Dafür haben wir die Anfangsbuchstaben unserer Namen verwendet, ergänzt durch drei Zahlen.

7. **GitHub:** Wir haben beschlossen, alles über GitHub zu verwalten, da dies unserer Meinung nach die beste Plattform für unsere Zusammenarbeit ist.

8. **VM-Software:** Wir haben uns für VMware Pro entschieden, da es mehr Funktionen bietet, z. B. Snapshots, und daher besser für unsere Anforderungen geeignet ist als VirtualBox.

Zudem haben wir entschieden, einen Windows-Server 2019 als zentrales Verwaltungssystem für die Clients zu implementieren.

TrueNAS fungiert als zentrales Speichersystem.
Der Windows-Server fungiert zur Verwaltung und für die Verbindungen zu den Clients (Windows und Linux).
Verwendung der 3-2-1-Backup-Strategie, um die Datensicherheit zu gewährleisten.

---

### Windows-Setup und Disk-Setup 

![Windows Setup](https://github.com/ironflipper/DataFlex/blob/main/Dokumentationen/iperka/Images/Bild.png)  
Wir haben den Windows Setup für unseren Server durchgeführt. Dabei entschieden wir uns für den Windows Server 2019.

![RAID-Z Pool](https://github.com/ironflipper/DataFlex/blob/main/Dokumentationen/iperka/Images/Bild%20(5).png)  
Anfangs hatten wir für jede Abteilung eine separate Disk eingerichtet. Später haben wir dies jedoch geändert und die drei Disks in einem Pool zusammengefasst, der mit RAID-Z konfiguriert ist. Innerhalb dieses Pools sind die Abteilungen nun strukturiert unterteilt.


## Fullbackup 

- Anfangs hatten wir die Idee, den Fullbackup auf dem Windows-Server per Win-Tools zu machen, 
jedoch hatten wir uns dann für Duplicati entschieden, um das Backup auf dem NAS zu machen 

![Sicherungsziel festlegen](https://github.com/ironflipper/DataFlex/blob/main/Dokumentationen/iperka/Images/Bild%20(13).png)


