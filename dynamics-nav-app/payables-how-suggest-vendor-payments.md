---
title: "Návod: Návrh platby dodavatele"
author: SorenGP
ms.custom: na
ms.date: 09/22/2016
ms.reviewer: na
ms.suite: na
ms.tgt_pltfrm: na
ms.topic: article
ms.prod: dynamics-nav-2017
ms.translationtype: Human Translation
ms.sourcegitcommit: 51adfb3588099c496f0946ff71da5c6fe518f070
ms.openlocfilehash: 11bfba9f279f6bd84c5d169f6f97fd48759bc6df
ms.contentlocale: cs-cz
ms.lasthandoff: 06/26/2017

---

# <a name="how-to-suggest-vendor-payments"></a>Návod: Návrh platby dodavatele
V okně **Deníky plateb** můžete pomocí funkce navrhnout platební řádky podle vašich nastavení, jako jsou platby, které jsou brzy splatné, nebo platby, u kterých je k dispozici skonto sleva.

Chcete-li plně využít funkce Navrhnout platby dodavateli, musíte nejdříve upřednostnit dodavatele. Pro další informace viz [Návod: Určení priority dodavatelů](purchasing-how-prioritize-vendors.md).

Položky dodavatele, které nejsou označeny jako **Vyčkat** nejsou zahrnuty do dávkové úlohy.  

**Důležité**: Chcete-li využívat skonto slev a zadáte dostupnou částku, bude částka použita nejprve pro položky po splatnosti prioritních dodavatelů v pořadí priority, pak pro položky po splatnosti dodavatelů, kteří nemají prioritu, a nakonec pro otevřeného položky dodavatelů, kde je nárok na skonto slevy v pořadí podle čísla dodavatele.

## <a name="to-use-the-suggest-vendor-payments-function"></a>Použití funkce Návrh platby dodavateli
1. V pravém horním rohu zvolte ikonu **Vyhledat stránku nebo sestavu**, zadejte **Deníky plateb** a pak vyberte související odkaz.
2. Otevřete příslušný deník a poté vyberte akci **Navrhnout platby dodavateli**.
3. Vyplňte pole dle potřeby. Vyberte pole a přečtěte si krátký popis pole nebo zvolte odkaz pro další informace.
4. Zvolte tlačítko **OK**.

## <a name="to-insert-the-due-date-as-posting-date-on-payment-journal-lines"></a>Vložení data splatnosti jako data zaúčtování do řádků deníku plateb
Když použijete dávkovou úlohu **Navrhnout platby dodavateli** pro vytvoření platebních řádků pro dodavatele, můžete vyplnit dvě zvláštní pole, abyste se ujistili, že generované řádky používají datum splatnosti pro výpočet data zaúčtování. Tato pole jsou **Vypočítat zúčtovací datum z datumu splatnosti vyrovnání dokladu** a **Posun datumu splatnosti vyrovnání dokladu.**.

**Důležité**: Nemůžete použít pole **Vypočítat zúčtovací datum z data splatnosti vyrovnání dokladu** spolu s polem **Vyhledat skonto** nebo s polem **Dodavatel na jeden řádek**. Důvodem je to, že pokud je datum zaúčtování založeno na datu splatnosti, určitá skonto sleva se nemusí vypočítat správně, protože datum zaúčtování by mohlo nastat po datu skonto slevy.
Také, pokud se vypočítané datum zaúčtování vyskytne v minulosti, datum zaúčtování bude změněno na pracovní datum a zobrazí se varování.

Případně můžete také ručně vytvořit platební řádky za použití data splatnosti pro výpočet data zaúčtování. Poté, co jste vyrovnali položky dodavatelů, můžete použít akci **Vypočítat zúčtovací datum**. Tím se aktualizuje datum zaúčtování na řádku deníku s datem splatnosti příslušné nákupní faktury. Další informace naleznete v tématu: [Návod: Vyrovnání nákupní transakce ručně](payables-how-apply-purchase-transactions-manually.md).  

**Poznámka**: Pokud je nákupní faktura po splatnosti, zúčtovací datum bude nastaveno na pracovní datum a font písma na řádku se změní na červenou barvu.

## <a name="see-also"></a>Viz také
[Správa závazků](payables-manage-payables.md)  
[Provedení plateb](payables-make-payments.md)  
[Práce s finančními deníky](ui-work-general-journals.md)

