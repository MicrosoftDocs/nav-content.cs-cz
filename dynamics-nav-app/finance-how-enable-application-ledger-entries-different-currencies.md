---
title: "Vyrovnání položek v různých měnách"
description: "Můžete vyrovnat položky v různých měnách, například pokud prodáváte v jedné měně a obdržíte platbu v jiné."
documentationcenter: 
author: edupont04
ms.prod: dynamics-nav-2017
ms.topic: article
ms.devlang: na
ms.tgt_pltfrm: na
ms.workload: na
ms.search.keywords: multiple currencies, payment, reconcile
ms.date: 06/02/2017
ms.author: edupont
ms.translationtype: HT
ms.sourcegitcommit: 4fefaef7380ac10836fcac404eea006f55d8556f
ms.openlocfilehash: f323b98472f3e2ef0f28000f8a9140b066206945
ms.contentlocale: cs-cz
ms.lasthandoff: 10/16/2017

---
# <a name="how-to-enable-application-of-ledger-entries-in-different-currencies"></a>Návod: Umožnění vyrovnání položek v různých měnách
Pokud nakoupíte od dodavatele v jedné měně a odešlete v druhé měně, můžete použít platbu k nákupu.

Když prodáte zákazníkovi v jedné měně a obdržíte platbu v druhé měně, můžete použít platbu k prodejní faktuře.

Následující procedura popisuje, jak nastavit položky dodavatele v okně **Nastavení nákupu a závazků**. Nastavení je podobné pro položky zákazníka v okně **Nastavení prodeje a pohledávek**.

## <a name="to-enable-application-of-vendor-ledger-entries-in-different-currencies"></a>Umožnění vyrovnání položek v různých měnách
1. Zvolte ikonu ![Vyhledat stránku nebo sestavu](media/ui-search/search_small.png "Ikona Vyhledat stránku nebo sestavu"), zadejte **Nastavení nákupu a závazků** a pak vyberte související odkaz.
2. V poli **Vyrovnání mezi měnami** vyberte jednu z následujících možností.

| Volba | Popis |
| --- | --- |
| Žádný |Vyrovnání mezi měnami není povoleno. |
| EMU |Vyrovnání mezi EMU měny je povoleno. |
| Všechno |Vyrovnání mezi všemi měnami je povoleno. |

## <a name="to-set-up-gl-accounts-for-currency-application-rounding-differences"></a>Nastavení finančních účtů pro rozdílné zaokrouhlení měny  
Pokud vyrovnáte položky v různých měnách, musíte nastavit finanční účty, na které chcete zaúčtovat zaokrouhlené rozdíly.  

> [!NOTE]  
>  Musíte nastavit finanční účty předtím, než dokončíte úkol. Další informace naleznete v tématu [Porozumění Hlavní knize a účetní osnově](finance-general-ledger.md).

1. Zvolte ikonu ![Vyhledat stránku nebo sestavu](media/ui-search/search_small.png "Ikona Vyhledat stránku nebo sestavu"), zadejte **Účto skupiny zákazníka** a pak vyberte související odkaz.  
2. V polích **MD účet  zaok. vyrovnání měny** a **Dal účet zaok. vyrovnání měny** zadejte příslušné finanční účty k zaúčtování zaokrouhlených rozdílů.  
3. Zvolte ikonu ![Vyhledat stránku nebo sestavu](media/ui-search/search_small.png "Ikona Vyhledat stránku nebo sestavu"), zadejte **Účto skupiny dodavatele** a pak vyberte související odkaz.  
4. V polích **MD účet zaok. vyrovnání měny** a **Dal účet zaok. vyrovnání měny** zadejte příslušné finanční účty k zaúčtování zaokrouhlených rozdílů.  

## <a name="see-also"></a>Viz také
[Správa závazků](payables-manage-payables.md)  
[Správa pohledávek](receivables-manage-receivables.md)  
[Práce s [!INCLUDE[d365fin](includes/d365fin_md.md)]](ui-work-product.md)

