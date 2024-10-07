# Iperka - Inform <img src="https://github.com/ironflipper/DataFlex/blob/main/Dokumentationen/iperka/Images/LOGO.png" alt="DataFlex Logo" align="right" width="50"/>

Wir arbeiten in der Firma "Redundant Data Corporation" und haben eine Aufgabe von einer Kleinfirma namens "yeez1 AG" bekommen.  
Unser Chef will den Auftrag bekommen und hat uns die Aufgabe zugeteilt und mitgeteilt, wir sollen ein Team machen.  
Nun haben wir ein Team erstellt: "Dataflex" und unser Projekt "Dataflex Project".  
Dieser Teamname steht für die *Flexibilität im Umgang mit Daten*, was ein starkes, zukunftsorientiertes Bild für unser Team schafft.

## Server und CLients

Windows 10 Enterprise
- **IP-Adresse:** 192.168.1.60

Ubuntu 22.04.1
- **IP-Adresse:** 192.168.1.61

TrueNAS
- **IP-Adresse:** 192.168.1.128

Windows Server 2019
- **IP-Adresse:** 192.168.1.100

## Berechtigungsmatrix und Organigramm der Infrastruktur Yeez1 AG

| Sharename            | Geschäftsleitung | Design_Publishing | Marketing_Sales | IT-Administration | Abwicklung   |
|:---------------------|:-----------------|:------------------|:----------------|:------------------|:-------------|
| GL                   | Vollzugriff      | Read              | Read            | 0                 | Read         |
| Design_Publishing     | Read             | Vollzugriff       | Read            | 0                 | Read         |
| Marketing_Sales       | Read             | Read              | Vollzugriff     | 0                 | Read         |
| IT-Administration     | 0                | 0                 | 0               | Vollzugriff       | 0            |
| Abwicklung           | Read             | Read              | Read            | 0                 | Vollzugriff  |

<img src="https://github.com/ironflipper/DataFlex/blob/main/Dokumentationen/iperka/Images/organigramm.png"

## Ressourcen, die wir verwendet haben

[**TrueNAS Backup & Recovery Tutorial** - Lawrence Systems](https://www.youtube.com/watch?v=XIj0iHtZvOg)

[**TrueNAS iSCSI und Windows-Integration** - Raid Owl](https://www.youtube.com/watch?v=TBFB6F--Nvk)

[**TrueNAS NFS Setup for XCP-ng** - Tech Tutorials (David McKone)](https://www.youtube.com/watch?v=ySMitWnNxp4&t=551s&ab_channel=TechTutorials-DavidMcKone)

[**How to Backup & Restore Windows** - NETVN82](https://www.youtube.com/watch?v=juMz3WcZB4U&ab_channel=NETVN82)

[**Install DHCP on Windows Server** - IT King](https://www.youtube.com/watch?v=r4mx_Iu0lr4)

[**How to Install Hyper-V on Windows Server** - IT King](https://www.youtube.com/watch?v=vsQX08u6YNA&ab_channel=ITKing)

[**How to Install Windows Server** - IT King](https://www.youtube.com/watch?v=Rg9-YDDHkyk&t=151s&ab_channel=ITKing)

[**Install Active Directory on Windows Server** - IT King](https://www.youtube.com/watch?v=Mww5THo5zf8&ab_channel=ITKing)

