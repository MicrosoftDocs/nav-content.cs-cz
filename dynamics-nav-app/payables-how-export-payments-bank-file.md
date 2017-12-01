---
title: "Export plateb do elektronického platebního souboru."
description: "Chcete-li uskutečnit platby dodavatele, povolte službu převodu bankovních dat, export bankovních souborů a nahrajte soubory do vašeho elektronického bankovnictví k uskutečnění převodu peněz."
documentationcenter: 
author: SorenGP
ms.prod: dynamics-nav-2018
ms.topic: article
ms.devlang: na
ms.tgt_pltfrm: na
ms.workload: na
ms.search.keywords: bank file export, re-export, bank transfer, AMC, bank data conversion service, funds transfer
ms.date: 06/28/2017
ms.author: sgroespe
ms.translationtype: HT
ms.sourcegitcommit: 4fefaef7380ac10836fcac404eea006f55d8556f
ms.openlocfilehash: bf7a2efe0f21100676e2cfe176693c43662ea13d
ms.contentlocale: cs-cz
ms.lasthandoff: 10/16/2017

---
# <a name="how-to-export-payments-to-a-bank-file"></a>Návod: Export plateb do bankovního souboru.
Když jste připraveni provést platby dodavateli, použijte okno **Deníky plateb**, kde můžete exportovat soubor s informacemi o platbách na řádcích deníku. Pak můžete soubor nahrát do elektronické banky a zpracovat příslušné převody peněz.

V generické verzi [!INCLUDE[d365fin_long](includes/d365fin_long_md.md)] je nastaven globální poskytovatel služeb pro převod bankovních dat do libovolného formátu souborů, který vaše banka vyžaduje. V severoamerických verzích může být stejná služba použita k odesílání platebních souborů jako elektronický převod prostředků (EFT), avšak s trochu jiným procesem. Podívejte se na krok 6 v sekci „Exportování platby do bankovního souboru“    

> [!NOTE]  
>   Předtím než budete moci vyexportovat platební soubory z deníku plateb, musíte specifikovat elektronický formát pro zvolenou bankovní účet a také službu převodu bankovních dat. Další informace naleznete v tématu [Návod: Nastavení bankovních účtů](bank-how-setup-bank-accounts.md) a [Návod:  Nastavení služby převodu bankovních dat.](bank-how-setup-bank-data-conversion-service.md). Navíc musíte vybrat **Povolit export plateb** v okně **Listy finančního deníku**, Pro další informace se podívejte na [Práce s finančními deníky](ui-work-general-journals.md).  

K zobrazení platebních souborů, které byly exportovány z deníku plateb, použijete okno **Bezhotovostní převody**. Z tohoto okna můžete také znovu exportovat platební soubory v případě technických chyb nebo změn souborů. Všimněte si, že exportované soubory EFT se v tomto okně nezobrazují a nelze je znovu exportovat.  

## <a name="to-export-payments-to-a-bank-file"></a>Exportování platby do bankovního souboru
1. Zvolte ikonu ![Vyhledat stránku nebo sestavu](media/ui-search/search_small.png "Ikona Vyhledat stránku nebo sestavu"), zadejte **Deníky plateb** a vyberte související odkaz.
2. Naplňte řádky deníku plateb, například pomocí funkce **Navrhnout platby dodavateli**. Další informace naleznete v tématu [Návod: Navrhnutí plateb dodavatelů ](payables-how-suggest-vendor-payments.md).
3. Vyplňte políčka na řádku deníku plateb, jak je potřeba. [!INCLUDE[tooltip-inline-tip](includes/tooltip-inline-tip_md.md)]

> [!NOTE]  
>   Používáte-li EFT, musíte v poli **Typ platby** vybrat **Elektronickou platbu** nebo **Elektronickou platbu IAT**. Různé služby exportu souborů a jejich formáty vyžadují různé hodnoty nastavení v okně **karta bankovního účtu** a v **Karta bankovního účtu dodavatele**. Během exportu souboru budete informováni o nesprávných nebo chybějících hodnotách nastavení.

4. Po dokončení všech řádků deníku plateb zvolte **Export**.
5. V okně **Export elektronických plateb** vyplňte pole podle potřeby.

    Jakékoli chybové zprávy se zobrazí v okně s fakty **Chyby platebního souboru**, kde můžete také zobrazit chybovou zprávu pro zobrazení podrobných informací. Všechny chyby musíte vyřešit dříve, než lze exportovat soubor platby.

    > [!TIP]  
>   Používáte-li službu převodu bankovních dat, běžná chybová zpráva uvádí, že číslo bankovního účtu nemá délku, kterou požaduje banka. Chcete-li zabránit chybě nebo ji vyřešit, musíte hodnotu v poli **IBAN** v okně **Karta bankovního účtu** a poté v poli **Číslo bankovním účtu** zadejte číslo bankovního účtu ve formátu požadovaném vaší bankou.

6. V okně **Uložit jako** zadejte umístění, kam byl soubor exportován, a potom zvolte **Uložit**.

    > [!NOTE]  
>   Používáte-li EFT, uložíte výsledný formulář výplatce dodavatele jako dokument aplikace Word nebo vyberte, chcete-li jej odeslat e-mailem přímo dodavateli. Platby se nyní přidávají do okna **Generovat soubor EFT**, ze kterého můžete společně vygenerovat více platebních příkazů, abyste ušetřili náklady na přenos. Pro více informací sledujte následující kroky
7. V okně **Deník plateb** zvolte **Generovat EFT soubor**.

    V okně** Generovat EFT soubor** všechny platby jsou nastavené pro EFT, které jste exportovali z deníku plateb pro určený bankovní účet, ale dosud nebyly vygenerovány. Tyto platby jsou uvedeny v záložce **Řádky**.
8. Zvolte **Generovat EFT soubor** pro export jednoho jednoho nebo všech EFT plateb
9. V okně **Uložit jako** zadejte umístění, kam byl soubor exportován, a potom zvolte **Uložit**.

Bankovní platební soubor je exportován na místo, které jste zadali, a můžete ho přesunout na svůj bankovní účet a provést skutečné platby. Potom můžete účtovat exportované řádky deníku plateb.

## <a name="to-export-payments-that-represent-customer-refunds"></a>Exportování plateb, které představují náhrady zákazníkům
Následující text popisuje práci pro export plateb elektronické refundace.

> [!CAUTION]  
>   Výsledné řádky deníku plateb nelze odeslat, odstranit nebo zrušit.
1. Nastavení zákazníka jako dodavatele Pojmenujte ho jako například: „Zákazník X pro refundaci“. Další informace naleznete v tématu [Návod: Registrace nového dodavatele.](purchasing-how-register-new-vendors.md)
2. Na řádku deníku plateb zákazníka nastavte **Typ účtu** na **Zákazník** a **Typ dokumentu** na **Refundace**.
3. Proveďte běžné kroky pro export platby, jak je popsáno v sekci „Export plateb do bankovního souboru.“

## <a name="to-plan-when-to-post-exported-payments"></a>Naplánování odeslání exportované platby
Pokud nechcete uveřejnit řádek žurnálu plateb pro exportovanou platbu, například proto, že čekáte na potvrzení o tom, že transakce byla zpracována bankou, můžete pouze odstranit řádek deníku. Když později vytvoříte řádek platebního deníku a zaplatíte zbývající částku na faktuře, pole **Exportovaná částka celkem** ukazuje, kolik částky platby již bylo exportováno. Podrobné informace o exportované částce najdete také výběrem tlačítka **Položky bezhotovostního převodu** k zobrazení detailů o exportovaných platebních souborech.

Pokud se budete řídit procesem, v němž neúčtujete platby, dokud nemáte potvrzení o tom, že byly zpracovány v bance, můžete to ovládat dvěma způsoby.

* V deníku plateb s navrhovanými platebními řádky můžete třídit buď sloupec **Exportováno do souboru plateb** nebo **Exportovaná částka celkem** a pak smazat návrhy plateb pro otevřené faktury, pro které již byly provedeny platby a nechcete za ně platit.
* V okně **Navrhnout platby dodavateli**, kde určíte platby, které chcete vložit do deníku plateb, zaškrtněte políčko **Přeskočit exportované platby**, pokud nechcete vkládat řádky deníku pro platby, které již byly exportovány.

Chcete-li zobrazit informace o exportovaných platbách, zvolte akci **Historie exportu plateb**.

## <a name="to-re-export-payments-to-a-bank-file"></a>Reexport plateb do souboru
Soubory plateb můžete znovu exportovat z okna **Bezhotovostní převody**. Před odstraněním nebo zasláním řádků deníku platby můžete také znovu exportovat platební soubor z okna **Deníky plateb** tím, že jej znovu exportujete. Pokud jste po exportu odstranili nebo zaúčtovali řádky deníku plateb, můžete znovu exportovat stejný platební soubor z okna **Bezhotovostní převody**. Vyberte řádek dávky převodů, které chcete znovu exportovat, a poté použijte akci **Reexport plateb do souboru**.

> [!NOTE]  
>   Exportované soubory EFT se nezobrazují v okně **Bezhotovostní převody** a nelze je znovu exportovat.

1. Zvolte ikonu ![Vyhledat stránku nebo sestavu](media/ui-search/search_small.png "Ikona Vyhledat stránku nebo sestavu"), zadejte **Bezhotovostní převody** a vyberte související odkaz.
2. Vyberte platbu pro export, kterou chcete znovu exportovat, a poté zvolte akci **Reexport plateb do souboru**.

## <a name="see-also"></a>Viz také
[Závazky](payables-manage-payables.md)  
[Nastavení nákupu](purchasing-setup-purchasing.md)  
[Práce s [!INCLUDE[d365fin](includes/d365fin_md.md)]](ui-work-product.md)

## 

