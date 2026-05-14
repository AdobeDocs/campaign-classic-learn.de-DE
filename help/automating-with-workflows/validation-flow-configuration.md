---
title: Konfigurieren von Validierungs-Workflows in Adobe Campaign Classic
description: Erfahren Sie, wie Sie verschiedene Validierungs-Workflows konfigurieren.
feature: Workflows, Approvals
jira: KT-1566
doc-type: feature video
activity: setup
team: TM
role: User
level: Experienced
exl-id: 34fbb91d-ae99-497c-872e-55ce2e6ea2aa
TQID: https://experienceleague.adobe.com/KhR76gfI2ZAMjDZDHCm7tOqQcJ5atG23hAwssYh3kcc
product_v2: id: dfc56824-e8b9-499e-85d4-21aedb507314
feature_v2: id: a075b2c1-7748-4328-b7f6-343aa314616a
role_v2: id: b69b2659-1057-424e-8fc5-ed9e016dc554
source-git-commit: ccbe1ae144ce2079b11103b9b8a9344fed56cbd2
workflow-type: tm+mt
source-wordcount: 274
ht-degree: 96%

---

# Erstellen von Validierungs-Workflows

Adobe Campaign bietet Marketing-Experten verschiedene Möglichkeiten, Versandinhalte, Kampagnenziele, Datenextraktion und Budgetgenehmigungen zu überprüfen und bereitzustellen.

In diesem Tutorial wird erläutert, wie verschiedene Validierungs-Workflows für Genehmigungen konfiguriert werden.

## Voraussetzung {#prerequisite}

Vor der Aktivierung von Genehmigungsschritten muss das Marketing-Team die einzelnen Validierungsverantwortlichen definieren:

* Die Adobe Campaign-Rolle eines Validierungsverantwortlichen innerhalb einer Genehmigungsaktivität kann entweder ein einzelner Validierungsverantwortlicher (Benutzer) oder eine Gruppe von Validierungsverantwortlichen (Benutzerrolle) sein.
* Damit Kampagnenentwickler die Validierungsverantwortlichen als Genehmiger in einer Kampagne oder einem Versand auswählen können, müssen diese von einem Administrator in Adobe Campaign konfiguriert werden.

## Konfigurieren von Genehmigungen für Kampagnen  {#configuring-approvals-for-campaigns}

Wenn Sie in Ihrem Kampagnen-Workflow für alle Sendungen dieselben Validierungsverantwortlichen haben, wenden Sie die Genehmigungsfunktion der Kampagne an, indem Sie Genehmigungen und Validierungsverantwortliche auf Kampagnenebene einrichten. Die Genehmigungsaufgaben und Validierungsverantwortlichen werden nach der Ausführung des Workflows in jede Versandaktivität Ihres Workflows übertragen.

>[!VIDEO](https://video.tv.adobe.com/v/25175?quality=12&learn=on){transcript=true}

## Konfigurieren von Genehmigungen auf Versandebene  {#configuring-approvals-for-deliveries}

Sie können Genehmigungen auch auf Versandebene einrichten. Wenn sich die Genehmigungsschritte und Validierungsverantwortlichen für den Versand von denen für Kampagnen unterscheiden, wird die Kampagnenkonfiguration durch die Versandeinstellungen außer Kraft gesetzt.

>[!VIDEO](https://video.tv.adobe.com/v/25176?quality=12&learn=on){transcript=true}

## Konfigurieren von Genehmigungsaktivitäten  {#configuring-an-approval-activity}

Im Gegensatz zu Versand- oder Kampagnengenehmigungen ermöglicht die Genehmigungsaktivität die Erstellung eines Genehmigungsprozesses innerhalb eines Workflows. Auf diese Weise kann die Auswahllogik der Zielgruppenbestimmung vor Beginn des Versands validiert werden. Bei Bedarf sind Genehmigungen auch auf mehreren Ebenen innerhalb des Workflows zulässig.

>[!VIDEO](https://video.tv.adobe.com/v/25174?quality=12&learn=on){transcript=true}

Weitere Informationen finden Sie in der [Dokumentation zu Genehmigungen](https://experienceleague.adobe.com/docs/campaign-classic/using/automating-with-workflows/flow-control-activities/approval.html?lang=de).
