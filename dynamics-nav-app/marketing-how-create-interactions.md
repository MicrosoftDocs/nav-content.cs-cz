---
title: "Vytváření interakcí s kontakty a segmenty"
description: "Popisuje jak vytvořit interakce pro komunikaci, kterou máte s vašimi kontakty a segmenty v Dynamics NAV, například: přímá pošta."
documentationcenter: 
author: jswymer
ms.prod: dynamics-nav-2017
ms.topic: article
ms.devlang: na
ms.tgt_pltfrm: na
ms.workload: na
ms.search.keywords: relationship, prospect
ms.date: 06/15/2017
ms.author: jswymer
ms.translationtype: HT
ms.sourcegitcommit: 4fefaef7380ac10836fcac404eea006f55d8556f
ms.openlocfilehash: 4ef0a5f683657f4725b04d7a231336419ea90f48
ms.contentlocale: cs-cz
ms.lasthandoff: 10/16/2017

---
# <a name="how-to-create-interactions-on-contacts-and-segments"></a>Návod: Vytváření interakcí s kontakty a segmenty
Můžete vytvořit interakce pro zaznamenání všech interakcí a komunikace, které máte s kontakty a segmenty, například přímou poštou.

Než vytvoříte interakce, musíte nastavit šablony interakcí. Další informace naleznete v tématu [Nastavení šablon interakcí](marketing-interactions.md).

## <a name="to-create-an-interaction"></a>Vytvoření interakce
1. Otevřete kontakt, dodavatele nebo položku protokolu interakce.
2. Zvolte akci **Vytvořit interakci**
3. Vyplňte pole a poté klepněte na tlačítko **OK**.

> [!NOTE]  
>   Pokud potřebujete provést jinou úlohu před dokončením interakce vybrat možnost **Storno** a dokončete interakci později. To odkládá interakci.

## <a name="to-finish-and-delete-postponed-interactions"></a>Dokončení a odstranění odložené interakce
1. Otevřete kontakt, dodavatele nebo položku protokolu interakce.
2. Zvolte **Odložit interakce**.
3. Vyberte interakci, kterou chcete dokončit, a poté vyberte akci **Pokračovat**.

## <a name="to-create-an-interaction-on-a-segment"></a>Vytvoření interakce v segmentu
1. Na domovské stránce zvolte **Aktivní segmenty**, nebo zvolte ikonu ![Vyhledat stránku nebo sestavu](media/ui-search/search_small.png " Ikona Vyhledat stránku nebo sestavu"), zadejte **Segmenty** a vyberte související odkaz.
2. V okně **Segment** v části **Interakce** vyplňte políčka a určete, kterou interakci chcete k segmentu přiřadit.

    Po přidělení interakce k segmentu můžete interakci přizpůsobit pro každý konkrétní kontakt v rámci segmentu, například výběrem jiné šablony interakcí v řádcích v okně **Segment**.  
3. Chcete-li zaznamenávat segment a interakce, zvolte akci **Protokol**. Otevře se okno **Segment protokolu**.
4. Chcete-li vytvořit nový segment se stejnými kontakty, zaškrtněte políčko **Vytvořit segment sledování**. Chcete-li vytvořit následný segment, musíte mít v okně **Nastavení marketingu** zadané číselné řady pro segmenty.

Interakce je zaznamenána pro každý kontakt v rámci segmentu v tabulce **Položka protokolu interakce** a segment je protokolován. Protokolované segmenty lze nalézt v okně **Protokolované segmenty**.

Pokud jste zaškrtli políčko **Vytvořit segment sledování**, vytvoří se nový segment, který obsahuje stejné kontakty jako segment, který jste právě protokolovali.

## <a name="see-also"></a>Viz také
[Záznam interakcí](marketing-interactions.md)  
[Správa kontaktů](marketing-contacts.md)  
[Správa prodejních příležitostí](marketing-manage-sales-opportunities.md)  
[Nastavení Správy vztahů](marketing-setup-marketing.md)  
[Práce s Dynamics NAV](ui-work-product.md)

