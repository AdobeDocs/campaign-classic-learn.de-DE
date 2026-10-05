---
title: Fehlerbehebung im Control Panel
description: Im Control Panel können Sie Ihre SFTP-Speicherung nach Instanz und Zulassungslisten-IP-Adressen überwachen und verwalten.
feature: Control Panel
jira: KT-2938
doc-type: article
activity: use
team: PM
product_v2:
  - id: dfc56824-e8b9-499e-85d4-21aedb507314
    internal-label: Campaign
  - id: fd6e6e36-54e4-4f1a-96fc-1a750e400d50
    internal-label: Campaign Classic v7
feature_v2:
  - id: ae9127b0-c11d-467b-903d-a84cef43f6ed
    internal-label: Control Panel
source-git-commit: d4d4654e5b2dee85947373b8dcf139754844b316
workflow-type: tm+mt
source-wordcount: '365'
ht-degree: 81%
---

# Fehlerbehebung im [!UICONTROL Control Panel]

## Anmelden und Homepage

### Problem: Anmeldung bei Experience Cloud nicht möglich

**Vorgehensweise:**
Die Benutzerin bzw. der Benutzer muss die eigene IMS-Org-ID (xxx) suchen. Der Administrator muss den Benutzer für jede Instanz, die er verwalten möchte, dem Profil „Campaign-xxx-Admins“ hinzufügen. Wenn der Benutzer ein Administrator aller Instanzen ist, muss er sich dennoch selbst als Benutzer hinzufügen.

### Problem: Links auf der Experience Cloud-Startseite für den Zugriff auf das [!UICONTROL Control Panel] werden einem Benutzer nicht angezeigt.

**Ursache:**
Benutzer sehen die Links erst, wenn sie als Benutzer zum Produktprofil hinzugefügt werden _Campaign-xxx-Administrators/Admin_.

**Vorgehensweise:**
Die bzw. der Admin muss die Benutzerin bzw. den Benutzer für jede Instanz, die verwaltet werden soll, dem Produktprofil _Campaign-xxx-Admins_ hinzufügen. Wenn der Benutzer ein Administrator aller Instanzen ist, muss er sich selbst als Benutzer hinzufügen.

### Problem: Eine Instanz wird im [!UICONTROL Control Panel] nicht aufgeführt.

**Ursache:**
Der Benutzer muss wahrscheinlich für die fehlende Instanz dem Produktprofil „Benutzer_(Campaign-xxx-Administrators/Admin_ hinzugefügt werden.

**Vorgehensweise:**
Die bzw. der Admin muss die Benutzerin bzw. den Benutzer für jede Instanz, die verwaltet werden soll, dem Produktprofil _Campaign-xxx-Admins_ hinzufügen. Wenn der Benutzer ein Administrator aller Instanzen ist, muss er sich dennoch selbst als Benutzer hinzufügen.

### Nützliche Videos

>[!VIDEO](https://video.tv.adobe.com/v/27183?quality=12&learn=on){transcript=true}

*IMS-Organisations-ID überprüfen (00:26 Min.)*

>[!VIDEO](https://video.tv.adobe.com/v/27147?quality=12&learn=on){transcript=true}

*Hinzufügen eines Administrators zum Produktprofil-Administratoren zur Verwendung von [!UICONTROL Systemsteuerung] (01:03 Min.)*

### Nützliche Dokumentation

* [Funktionsweise des Control Panel](https://experienceleague.adobe.com/docs/control-panel/using/control-panel-home.html?lang=de)
* [Verwalten von Berechtigungen für das [!UICONTROL Control Panel]](https://experienceleague.adobe.com/docs/control-panel/using/control-panel-home.html?lang=de)

## Herstellen einer Verbindung zum SFTP-Server (Client oder API)

Für Verbindungen mit SFTP-Servern ist Folgendes erforderlich:

* [!UICONTROL Setzen auf die Zulassungsliste] der IP-Adresse, von der Sie eine Verbindung zum SFTP-Server herstellen
* Schlüsselpaar aus privatem/öffentlichem Schlüssel, das bei Adobe Campaign registriert werden muss
* Wenn Sie eine direkte Verbindung zum SFTP-Server herstellen möchten, benötigen Sie auch SFTP-Client-Software.

### Nützliche Dokumentation {#helpful-docs}

* [Anmeldung bei Ihrem SFTP-Server](https://experienceleague.adobe.com/docs/control-panel/using/control-panel-home.html?lang=de)

