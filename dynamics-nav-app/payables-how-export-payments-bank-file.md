---
title: "Návod: Exportování plateb do bankovního souboru"
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
ms.openlocfilehash: 09bdf56b3d5e76b12d868091e89232ce9c08e215
ms.contentlocale: cs-cz
ms.lasthandoff: 06/26/2017

---

# <a name="how-to-export-payments-to-a-bank-file"></a>Návod: Exportování plateb do bankovního souboru
Když jste připraveni provést platby dodavateli pomocí okna **Deníky plateb**, můžete exportovat soubor s informacemi o platbách na řádcích deníku. Pak můžete soubor nahrát do elektronické banky a zpracovat příslušné převody peněz.

V generické verzi služby Dynamics NAV je nastaven globální poskytovatel služeb pro převod bankovních dat do libovolného formátu souborů, který vaše banka vyžaduje.

**Poznámka**: Než budete moci exportovat z deníku plateb, musíte povolit export v související dávce deníku. Kromě toho musí být bankovní účet a bankovní účet dodavatele nastaven pro elektronickou platbu. Další informace naleznete v tématu: [Návod: Nastavení služby převodu bankovních dat](bank-how-setup-bank-data-conversion-service.md).

K zobrazení platebních souborů, které byly exportovány z deníku plateb, použijete okno **Bezhotovostní převody**. Z tohoto okna můžete také znovu exportovat platební soubory v případě technických chyb nebo změn souborů.

## <a name="to-export-payments-to-a-bank-file"></a>Exportování platby do bankovního souboru
1. V pravém horním rohu zvolte ikonu **Vyhledat stránku nebo sestavu**, zadejte **Deníky plateb** a pak vyberte související odkaz.
2. Naplňte řádky deníku plateb, například pomocí funkce **Navrhnout platby dodavateli**. Další informace naleznete v tématu: [Návod: Navrhnutí platby dodavateli](payables-how-suggest-vendor-payments.md).  
3. Po dokončení všech řádků deníku plateb zvolte **Export platby do souboru**.

    Jakékoli chybové zprávy se zobrazí v okně s fakty **Chyby platebního souboru**, kde můžete také zobrazit chybovou zprávu pro zobrazení podrobných informací. Všechny chyby musíte vyřešit dříve, než lze exportovat soubor platby.

    **Tip**: Používáte-li službu převodu bankovních dat, běžná chybová zpráva uvádí, že číslo bankovního účtu nemá délku, kterou požaduje banka. Chcete-li zabránit chybě nebo ji vyřešit, musíte hodnotu v poli **IBAN** v okně **Karta bankovního účtu** a poté v poli **Číslo bankovním účtu** zadejte číslo bankovního účtu ve formátu požadovaném vaší bankou.
4. V okně **Uložit jako** zadejte umístění, kam byl soubor exportován, a potom zvolte **Uložit**.

Bankovní platební soubor je exportován na místo, které jste zadali, a můžete ho přesunout na svůj bankovní účet a provést skutečné platby.

Poté, co obdržíte potvrzení o úspěšném zpracování plateb v bance, můžete odeslat exportované řádky deníku plateb.

## <a name="to-plan-when-to-post-exported-payments"></a>Naplánování odeslání exportované platby
Pokud nechcete uveřejnit řádek žurnálu plateb pro exportovanou platbu, například proto, že čekáte na potvrzení o tom, že transakce byla zpracována bankou, můžete pouze odstranit řádek deníku. Když později vytvoříte řádek platebního deníku a zaplatíte zbývající částku na faktuře, pole **Exportovaná částka celkem** ukazuje, kolik částky platby již bylo exportováno. Podrobné informace o exportované částce najdete také výběrem tlačítka **Položky bezhotovostního převodu** k zobrazení detailů o exportovaných platebních souborech.

Pokud se budete řídit procesem, v němž neúčtujete platby, dokud nemáte potvrzení o tom, že byly zpracovány v bance, můžete to ovládat dvěma způsoby.

* V deníku plateb s navrhovanými platebními řádky můžete třídit buď sloupec **Exportováno do souboru plateb ** nebo **Exportovaná částka celkem** a pak smazat návrhy plateb pro otevřené faktury, pro které již byly provedeny platby a nechcete za ně platit.
* V okně **Navrhnout platby dodavateli**, kde určíte platby, které chcete vložit do deníku plateb, zaškrtněte políčko **Přeskočit exportované platby**, pokud nechcete vkládat řádky deníku pro platby, které již byly exportovány.

Chcete-li zobrazit informace o exportovaných platbách, zvolte akci **Historie exportu plateb**.

## <a name="to-re-export-payments-to-a-bank-file"></a>Reexport plateb do souboru
Soubory plateb můžete znovu exportovat z okna **Bezhotovostní převody**. Před odstraněním nebo zasláním řádků deníku platby můžete také znovu exportovat platební soubor z okna **Deníky plateb** tím, že jej znovu exportujete.

Pokud jste po exportu odstranili nebo zaúčtovali řádky deníku plateb, můžete znovu exportovat stejný platební soubor z okna **Bezhotovostní převody**. Vyberte řádek dávky převodů, které chcete znovu exportovat, a poté použijte akci **Reexport plateb do souboru**.

## <a name="see-also"></a>Viz také
[Závazky](payables-manage-payables.md)  
[Správa nákupu](purchasing-manage-purchasing.md)  
[Nastavení nákupu](purchasing-setup-purchasing.md)

