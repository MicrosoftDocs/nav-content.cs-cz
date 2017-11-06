---
title: "Použití funkce dávkové úlohy Návrh platby dodavateli"
description: "Můžete zadat nastavení plateb dodavatelů získat podněty a návrhy na platby, které jsou splatné dříve nebo pokud je k dispozici sleva"
documentationcenter: 
author: SorenGP
ms.prod: dynamics-nav-2017
ms.topic: article
ms.devlang: na
ms.tgt_pltfrm: na
ms.workload: na
ms.search.keywords: vendor payment, creditor, debt, balance due, AP
ms.date: 06/06/2017
ms.author: sgroespe
ms.translationtype: HT
ms.sourcegitcommit: 4fefaef7380ac10836fcac404eea006f55d8556f
ms.openlocfilehash: 99bec4a5cc06209d4e7cfc0e7d2736bfc6fe9e1e
ms.contentlocale: cs-cz
ms.lasthandoff: 10/16/2017

---
# <a name="how-to-suggest-vendor-payments"></a>Návod: Navrhnutí plateb dodavatele
V okně **Deník plateb**, můžete použít dávkové úlohy **Navrhnout platby dodavateli**k návrhu řádků deníku. Na základě vašich nastavení jsou navrženy řádky pro platby, které jsou brzy splatné, nebo platby, u kterých je k dispozici sleva.

Chcete-li plně využít funkce na navrhnutí řádku, musíte nejdříve upřednostnit dodavatele. Další informace naleznete v tématu [Návod: Určení priority dodavatelů.](purchasing-how-prioritize-vendors.md)  

Položky dodavatele, které nejsou označeny jako **Vyčkat** nejsou zahrnuty.  

> [!IMPORTANT]  
>   Chcete-li využít platební slevy a zadali dostupné množství, bude částka použita pro:  

* Na základě priority objednávky, budou prioritní položky dodavatele po splatnosti.  
* Položky dodavatelů, které nemají nastavenou prioritu.  
* Otevřené položky dodavatele, které splňují podmínky pro platební slevy, uspořádané podle počtu dodavatelů.  

## <a name="to-use-the-suggest-vendor-payments-function"></a>Použití funkce Návrh platby dodavateli
1. Zvolte ikonu ![Vyhledat stránku nebo sestavu](media/ui-search/search_small.png "Ikona Vyhledat stránku nebo sestavu"), zadejte **Deníky plateb** a vyberte související odkaz.  
2. Otevřete příslušný deník a poté vyberte akci **Navrhnout platby dodavateli**.  
3. Vyplňte pole dle potřeby. [!INCLUDE[tooltip-inline-tip](includes/tooltip-inline-tip_md.md)]  
4. Zvolte tlačítko **OK**.  

## <a name="to-insert-the-due-date-as-posting-date-on-payment-journal-lines"></a>Vložení data splatnosti jako data zaúčtování do řádků deníku plateb
Když použijete dávkovou úlohu **Navrhnout platby dodavateli** pro vytvoření platebních řádků pro dodavatele, můžete vyplnit dvě zvláštní pole, abyste se ujistili, že generované řádky používají datum splatnosti pro výpočet data zaúčtování. Tato pole jsou **Vypočítat zúčtovací datum z datumu splatnosti vyrovnání dokladu** a **Posun datumu splatnosti vyrovnání dokladu.**.  

> [!IMPORTANT]  
>   Nemůžete použít pole **Vypočítat zúčtovací datum z data splatnosti vyrovnání dokladu** spolu s polem **Vyhledat skonto** nebo s polem **Dodavatel na jeden řádek**. Důvodem je to, že pokud je datum zaúčtování založeno na datu splatnosti, určitá sleva se nemusí vypočítat správně, protože datum zaúčtování by mohlo nastat po datu slevy.  

Také, pokud se vypočítané datum zaúčtování vyskytne v minulosti, datum zaúčtování je změněno na pracovní datum a zobrazí se varování.  

Případně můžete ručně vytvořit platební řádky za použití data splatnosti pro výpočet data zaúčtování. Poté co vyrovnáte položky dodavateli, můžete použít tlačítko **Výpočet zúčtovaího data** k aktualizaci zúčtovacího data na řádku deníku s datem splatnosti na příslušné nákupní faktuře. Další informace naleznete v tématu [Návod: Vyrovnání nákupní transakce ručně.](payables-how-apply-purchase-transactions-manually.md)  

> [!NOTE]  
>   Pokud je nákupní faktura po splatnosti, zúčtovací datum bude nastaveno na pracovní datum a font písma na řádku se změní na červenou .  

## <a name="see-also"></a>Viz také
[Správa závazků](payables-manage-payables.md)  
[Provedení plateb](payables-make-payments.md)  
[Práce s finančními deníky](ui-work-general-journals.md)  
[Práce s [!INCLUDE[d365fin](includes/d365fin_md.md)]](ui-work-product.md)  

