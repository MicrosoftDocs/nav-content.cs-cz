---
title: "Nastavení převodu bankovních dat"
description: "Můžete nastavit bankovní účty k převodu transakcí a importu a exportu bankovních prostředků."
documentationcenter: 
author: SorenGP
ms.prod: dynamics-nav-2018
ms.topic: article
ms.devlang: na
ms.tgt_pltfrm: na
ms.workload: na
ms.search.keywords: feed, stream, data exchange, AMC, bank file import, bank file export, re-export, bank transfer, AMC, bank data conversion service, funds transfer
ms.date: 06/02/2017
ms.author: sgroespe
ms.translationtype: HT
ms.sourcegitcommit: 4fefaef7380ac10836fcac404eea006f55d8556f
ms.openlocfilehash: d0ee64e4b1426d6ce9d8b8052919e4afcae326d5
ms.contentlocale: cs-cz
ms.lasthandoff: 10/16/2017

---
# <a name="how-to-set-up-the-bank-data-conversion-service"></a>Návod: Nastavení služby převodu bankovních dat
Globální poskytovatel služeb, který převádí informace o platbách do libovolného formátu dat, který banka vyžaduje, je připojen a připraven k zapnutí v [!INCLUDE[d365fin](includes/d365fin_md.md)]. Tato služba je označována v [!INCLUDE[d365fin](includes/d365fin_md.md)] jako služba převodu bankovních dat.

Můžete exportovat platební řádky z okna **Deník plateb** do datového proudu, který pak nahrajete do své banky pro automatické zpracování, takže nemusíte provádět elektronické platby individuálně. Další informace naleznete v tématu [Návod: Export plateb do bankovního souboru](payables-how-export-payments-bank-file.md).

Můžete importovat soubory bankovních výpisů do okna  **Deník odsouhlasení plateb** pomocí služby konverze bankovních dat a převést soubor, který obdržíte od banky, do datového toku, který lze importovat [!INCLUDE[d365fin](includes/d365fin_md.md)]. Další informace naleznete v tématu  [Návod: Automatické vyrovnání plateb a odsouhlasení bankovních účtů](receivables-apply-payments-auto-reconcile-bank-accounts.md).

K importu nebo exportu bankovních souborů musíte nastavit vlastní bankovní účty a bankovní účty dodavatele.  Další informace naleznete v tématu [Návod: Nastavení bankovních účtů](bank-how-setup-bank-accounts.md).

> [!NOTE]  
>   Služba převodu bankovních dat může omezit počet řádků, které lze exportovat do jednoho souboru. Při překročení limitu se zobrazí chybová zpráva. Doporučuje se, aby soubory bankovních výpisů nepřekročily 1000 řádků, jelikož doba zpracování v bankovní službě převodu dat se může výrazně zvýšit.

## <a name="to-sign-your-company-up-for-the-bank-data-conversion-service"></a>Zaregistrování vaší společnosti na službu převodu bankovních dat
1. Zvolte ikonu ![Vyhledat stránku nebo sestavu](media/ui-search/search_small.png "Ikona Vyhledat stránku nebo sestavu"), zadejte **Nastavení služby konver. bank. dat** a pak vyberte související odkaz.  
2. Otevře se okno **Nastavení služby konver. bank. dat** se třemi políčky předem vyplněnými příslušnými adresami URL poskytovatele služby převodu bankovních dat.

    > [!NOTE]  
>   V demonstrační databázi CRONUS International Ltd. jsou pole Název uživatele a Heslo předem vyplněny přihlašovacími informacemi, které nahradíte skutečnými informacemi vaší společnosti při přihlášení k službě převod bankovní dat.
3. V poli **Přihlášení URL** vyberte tlačítko prohlížeč a otevřete přihlašovací stránku poskytovatele služby.  
4. Na přihlašovací stránce poskytovatele služby bankovních dat zadejte název uživatele a heslo pro předplatné vaší společnosti a dokončete přihlašovací proces podle pokynů poskytovatele služby.

    Vaše společnost je nyní zaregistrována pro službu konverze bankovních dat. Pokračujte v zadání jména uživatele a hesla, které jste zadali do příslušných polí v nastavení v [!INCLUDE[d365fin](includes/d365fin_md.md)].
5. V okně **Nastavení služby ****konver. bank. dat** v poli **Jméno** zadejte stejnou hodnotu, kterou jste zadali jako přihlašovací jméno na stránce poskytovatele služby v kroku 4.
6. V poli **Heslo** zadejte stejnou hodnotu, kterou jste zadali v poli **Heslo** na stránce poskytovatele služby v kroku 4.

## <a name="to-encrypt-your-login-information"></a>Šifrování přihlašovacích údajů
Doporučuje se chránit přihlašovací informace, které zadáváte v okně **Nastavení služby konver. bank. dat**. Můžete šifrovat data na serveru [!INCLUDE[d365fin](includes/d365fin_md.md)] generováním nového nebo importováním existujícího šifrovacího klíče, který povolíte na instanci serveru  [!INCLUDE[d365fin](includes/d365fin_md.md)], který je připojen k databázi.

1. V okně **Nastavení služby konver. bank. Dat** zvolte akci **Správa šifrování**.
2. V okně **Správa šifrování dat** povolte šifrování vašich dat.

## <a name="to-view-or-update-the-list-of-currently-supported-bank-data-formats"></a>Zobrazení nebo aktualizace seznamu aktuálně podporovaných formátů bankovních dat
1. Zvolte ikonu ![Vyhledat stránku nebo sestavu](media/ui-search/search_small.png "Ikona Vyhledat stránku nebo sestavu"), zadejte **Nastavení služby konver. bank. dat** a pak vyberte související odkaz.
2. V okně **Nastavení služby konver. bank. dat** zvolte akci **Název banky - Seznam převodu dat** k otevření seznamu názvů bank představujících formáty bankovních dat podporovaných službou převodu.
3. Na stránce **Název banky - Seznam převodu dat** zvolte akci **Aktualizovat seznam názvů bank**.

Seznam formátů bankovních dat, které jsou podporovány službou převodu bankovních dat je nyní aktualizován. Jedná se o seznam názvů bank, filtrovaných podle země/oblasti, kterou můžete vybrat v poli **Název Banky - Převod dat** v okně **Karta bankovního účtu**.

> [!NOTE]  
>   Aktualizace podporovaných formátů bankovních dat také nastane, když vyberete nebo zadáte hodnotu v poli **Název Banky - Převod dat** na bankovním účtu.

Nyní jste se zaregistrovali na službu převodu bankovních dat. Postupujte podle přihlašovacích informací na každém bankovním účtu, který služba použije.

## <a name="see-also"></a>Viz také
[Nastavení bankovnictví](bank-setup-banking.md)  
[Správa bankovních účtů](bank-manage-bank-accounts.md)  
[Práce s [!INCLUDE[d365fin](includes/d365fin_md.md)]](ui-work-product.md)

