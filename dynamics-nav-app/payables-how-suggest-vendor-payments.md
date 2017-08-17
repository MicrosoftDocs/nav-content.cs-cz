---
title: "Návody: Navrhnout platby dodavateli"
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

# <a name="how-to-suggest-vendor-payments"></a>Návody: Navrhnout platby dodavateli
V okně **Deník plateb** můžete pomocí funkce navrhnout platební řádky podle vašich nastavení, jako jsou platby, které se brzy očekávají, nebo platby, u kterých je k dispozici platební sleva.

Chcete-li plně využít funkce Navrhnout platby dodavateli, musíte nejdříve upřednostnit dodavatele. Pro další informace viz [Návody: Určit prioritu dodavatelů](purchasing-how-prioritize-vendors.md).

Položky dodavatele, které nejsou označeny jako **Přidržené** nejsou zahrnuty do dávkové úlohy.  

**Důležité**: Chcete-li využívat slev na platby a zadáte dostupnou částku, bude částka použita pro upřednostňované položky dodavatelů nejprve v pořadí priority a pak pro položky s prodlouženým dodavatelem, které nemají prioritu, a nakonec pro položky otevřeného dodavatele, jehož nárok na slevy na platbě v pořadí podle čísla prodejce.

## <a name="to-use-the-suggest-vendor-payments-function"></a>Použití funkce Navrhnout platby dodavateli
1. V pravém horním rohu zvolte ikonu **Vyhledat stránku nebo sestavu**, zadejte **Deník plateb** a pak vyberte související odkaz.
2. Otevřete příslušný deník a poté vyberte akci **Doporučit dodavatele platby**.
3. Vyplňte pole podle potřeby. Vyberte pole a přečtěte si krátký popis pole nebo klikněte na odkaz pro další informace.
4. Vyberte tlačítko **OK**.

## <a name="to-insert-the-due-date-as-posting-date-on-payment-journal-lines"></a>Vložení data splatnosti jako data zaúčtování do řádků deníku plateb
Když použijete dávkovou úlohu **Navrhnout platby dodavateli** a vytvoříte platební řádky pro dodavatele, můžete vyplnit dvě zvláštní pole, abyste se ujistili, že generované řádky používají datum splatnosti pro výpočet data zaúčtování. Tato pole jsou **Vypočítat datum zaúčtování z data splatnosti vyrovnání dokladu** a **Posun data splatnosti vyrovnání dokladu**.

**Důležité**: Nemůžete použít pole **Vypočítat datum zaúčtování z data splatnosti vyrovnání dokladu** spolu s polem **Vyhledat skonto** nebo pole **Dodavatel na jeden řádek**. Důvodem je to, že pokud je datum zaúčtování založeno na datu splatnosti, určitá platební sleva se nemusí vypočítat správně, protože datum zaúčtování by mohlo nastat po datu slevy na platby.
Také, pokud se vypočítané datum zaúčtování vyskytne v minulosti, datum zaúčtování bude přesunuto až do data práce a zobrazí se varování.

Případně můžete také ručně vytvořit platební řádky za použití data splatnosti pro výpočet data zaúčtování. Poté, co jste použili položky seznamu prodejců, můžete použít akci **Vypočítat datum zaúčtování**. Tím se aktualizuje datum zaúčtování na řádku deníku s datem splatnosti příslušné nákupní faktury. Pro další informace viz [Návody: Vyrovnat nákupní transakce ručně](payables-how-apply-purchase-transactions-manually.md).  

**Poznámka**: Pokud je nákupní faktura splatná, datum odevzdání bude nastaveno na pracovní datum a písmo na řádku se změní na červenou barvu.

## <a name="see-also"></a>Viz také
[Spravovat závazky](payables-manage-payables.md)  
[Provést platby](payables-make-payments.md)  
[Pracovat s finančními deníky](ui-work-general-journals.md)

