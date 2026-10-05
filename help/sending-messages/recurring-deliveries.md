---
title: Konfigurieren wiederkehrender und kontinuierlicher E-Mail-Kampagnen
description: Erfahren Sie, wie Sie einen wiederkehrenden und einen fortlaufenden Versand einrichten und worin sich die beiden Ansätze unterscheiden.
feature: Workflows, Campaigns
jira: KT-1560
doc-type: feature video
activity: use
team: TM
role: User
level: Beginner
exl-id: 42f2a7e6-7d88-473b-b913-fe09b7016b28
TQID: 'https://experienceleague.adobe.com/JPcr0Ub8i7-L-v9MsR0BKIg0Umc6JuGIX0iBcCAc610'
product_v2:
  - id: dfc56824-e8b9-499e-85d4-21aedb507314
    internal-label: Campaign
  - id: fd6e6e36-54e4-4f1a-96fc-1a750e400d50
    internal-label: Campaign Classic v7
feature_v2:
  - id: a075b2c1-7748-4328-b7f6-343aa314616a
    internal-label: Campaigns
  - id: a658c786-869b-4194-a780-2594d663adda
    internal-label: Data management
subfeature_v2:
  - id: fcb46c0f-76e1-48bc-9dd0-fcf9d97526cf
    internal-label: Workflows
role_v2:
  - id: b69b2659-1057-424e-8fc5-ed9e016dc554
    internal-label: User
level_v2:
  - id: e8ccd51f-da0d-4e3b-939b-e30d5ebb1ea5
    internal-label: Beginner
source-git-commit: d4d4654e5b2dee85947373b8dcf139754844b316
workflow-type: tm+mt
source-wordcount: '240'
ht-degree: 100%
---
# Konfigurieren wiederkehrender und kontinuierlicher E-Mail-Kampagnen

In diesem Tutorial erfahren Sie, wie Sie einen wiederkehrenden und einen fortlaufenden Versand einrichten und worin sich die beiden Ansätze unterscheiden.

## Tracking des wiederkehrenden und des fortlaufenden Versands {#recurring-and-continuous-delivery-tracking}

Der wiederkehrende und der fortlaufende Versand unterscheiden sich bezüglich der Verwaltung von Kontaktdaten:

* Beim **fortlaufenden Versand** können Sie einem bestehenden Versand neue Empfänger hinzufügen, sodass Sie nicht jedes Mal einen neuen Versand erstellen müssen, wenn ein neuer Empfänger hinzugefügt wird. Sie können die kreativen Inhalte direkt im Kampagnen-Workflow aktualisieren, wodurch die Vorlage im Ressourcen-Ordner für Versandvorlagen aktualisiert wird.

  Bei einem fortlaufenden Versand wird EIN Versand erstellt. Versandlogs (Broadlog) und Trackinglogs, die auf diesen Versand verweisen, werden bei jeder Ausführung hinzugefügt.

  ![Versand (fortlaufend)](/help/assets/delivery_continuous.jpg)

* Ein **wiederkehrender Versand** erstellt bei jeder Ausführung eine neue Versandinstanz. Wenn der Workflow beispielsweise einmal pro Woche ausgeführt werden soll, führt dies nach einem Jahr zu 52 Sendungen. Dies bedeutet auch, dass das Broadlog und die Trackinglogs je Versandinstanz getrennt sind.

  ![Wiederkehrender Versand](/help/assets/delivery_recurring.jpg)

## Einrichten eines wiederkehrenden Versands {#how-to-set-up-a-recurring-delivery}

In diesem Video wird das Konfigurieren eines wiederkehrenden Versands und einer Planungsaktivität erläutert.

>[!VIDEO](https://video.tv.adobe.com/v/25040?quality=12&learn=on){transcript=true}

## Einrichten eines Versands (fortlaufend) {#how-to-set-up-a-continuous-delivery}

In diesem Video wird gezeigt, wie Sie einen fortlaufenden Versand mit einer inkrementellen Abfrage konfigurieren.

>[!VIDEO](https://video.tv.adobe.com/v/25039?quality=12&learn=on){transcript=true}
