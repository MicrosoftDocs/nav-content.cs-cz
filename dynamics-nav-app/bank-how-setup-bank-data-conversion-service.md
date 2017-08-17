---
title: "Návod: Nastavení služby převodu bankovních dat"
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
ms.openlocfilehash: 801e2abee52ec9804028a797e4f330b5e080549a
ms.contentlocale: cs-cz
ms.lasthandoff: 06/26/2017

---

# <a name="how-to-set-up-the-bank-data-conversion-service"></a>Návod: Nastavení služby převodu bankovních dat
Můžete exportovat platební řádky z okna **Deník plateb** do datového proudu, který pak nahrajete do své banky pro automatické zpracování, takže nemusíte provádět elektronické platby individuálně. Další informace naleznete v [Návod: Export plateb do bankovního souboru](payables-how-export-payments-bank-file.md).

Globální poskytovatel služeb, který převádí informace o platbách do libovolného formátu dat, který banka vyžaduje, je připojen a připraven k zapnutí v Dynamics NAV.

Jako alternativu k službě Envestnet Bank Data Feeds service můžete také využít službu převodu bankovních dat, abyste měli bankovní výpis, který obdržíte od své banky, převeden na datový tok, který můžete importovat do Dynamics NAV. Další informace naleznete v [Návod: Automatické vyrovnání plateb a odsouhlasení bankovních účtů](receivables-apply-payments-auto-reconcile-bank-accounts.md).

**Poznámka**: Služba převodu bankovních dat může omezit počet řádků, které lze exportovat do jednoho souboru. Při překročení limitu se zobrazí chybová zpráva. Doporučuje se, aby soubory bankovních výpisů nepřekročily 1000 řádků, jelikož doba zpracování v bankovní službě převodu dat se může výrazně zvýšit.

## <a name="to-sign-your-company-up-for-the-bank-data-conversion-service"></a>Zaregistrování vaší společnosti na službu převodu bankovních dat
1. V pravém horním rohu zvolte ikonu **Vyhledat stránku nebo sestavu**, zadejte **Konv. bankovních dat Nastavení služby** a pak vyberte související odkaz.  
2. **Konv. bankovních dat Otevře se okno Nastavení služby** se třemi políčky předem vyplněnými příslušnými adresami URL poskytovatele služby převodu bankovních dat.

    **Poznámka**: V CRONUS International Ltd. demonstrační databázi jsou pole Název uživatele a Heslo předem vyplněny přihlašovacími informacemi, které nahradíte skutečnými informacemi vaší společnosti při přihlášení k službě převod bankovní dat.
3. V poli **Přihlášení URL** vyberte tlačítko prohlížeč a otevřete přihlašovací stránku poskytovatele služby.  
4. Na přihlašovací stránce poskytovatele služby bankovních dat zadejte název uživatele a heslo pro předplatné vaší společnosti a dokončete přihlašovací proces podle pokynů poskytovatele služby.

    Vaše společnost je nyní zaregistrována pro službu konverze bankovních dat. Pokračujte v zadání názvu uživatele a hesla, které jste zadali do příslušných polí v nastavení v Dynamics NAV.
5. V **Konv. bankovních dat V okně Nastavení služby** v poli Uživatel **Název** zadejte stejnou hodnotu, kterou jste zadali jako přihlašovací jméno na stránce poskytovatele služby v kroku 4.
6. V poli **Heslo** zadejte stejnou hodnotu, kterou jste zadali v poli **Heslo** na stránce poskytovatele služby v kroku 4.

## <a name="to-encrypt-your-login-information"></a>Šifrování přihlašovacích údajů
Doporučuje se chránit přihlašovací informace, které zadáváte v **Konv. bankovních dat Okno Nastavení služeb**. Šifrování dat na serveru Dynamics NAV může vygenerovat nové nebo importovat existující šifrovací klíče, které povolíte na instanci serveru Dynamics NAV, která se připojí k databázi.

1. V **Konv. bankovních dat V okně Nastavení služeb** zvolte akci **Správa šifrování**.
2. V okně **Správa šifrování dat** povolte šifrování vašich dat.

##<a name="to-view-or-update-the-list-of-currently-supported-bank-data-formats"></a>Zobrazení nebo aktualizace seznamu aktuálně podporovaných formátů bankovních dat
1. V pravém horním rohu zvolte ikonu **Vyhledat stránku nebo sestavu**, zadejte **Konv. bankovních dat Nastavení služeb** a pak vyberte související odkaz. 
2. V **Konv. bankovních dat V okně Nastavení služeb** zvolte akci **Název banky - Seznam převodu dat** k otevření seznamu názvů bank představujících formáty bankovních dat podporovaných službou převodu.
3. Na stránce **Název banky - Seznam převodu dat** zvolte akci **Aktualizovat seznam názvů bank**.

Seznam formátů bankovních dat, které jsou podporovány službou převodu bankovních dat je nyní aktualizován. Jedná se o seznam názvů bank, filtrovaných podle země/oblasti, kterou můžete vybrat v poli **Název Banky - Převod dat** v okně **Karta bankovního účtu**.

**Poznámka**: Aktualizace podporovaných formátů bankovních dat také nastane, když vyberete nebo zadáte hodnotu v poli **Název Banky - Převod dat** na bankovním účtu.

Nyní jste se zaregistrovali na službu převodu bankovních dat. Postupujte podle přihlašovacích informací na každém bankovním účtu, který služba použije.

## <a name="to-set-up-bank-accounts-to-use-the-bank-data-conversion-service"></a>Nastavení bankovních účtů pro službu převodu bankovních dat
1. V pravém horním rohu zvolte ikonu **Vyhledat stránku nebo sestavu**, zadejte **Bankovní účty** a pak vyberte související odkaz.
2. Otevřete kartu pro bankovní účet, který budete exportovat nebo importovat pomocí služby převodů bankovních dat.
3. V záložce s náhledem **Převod** v poli **Formát exportních plateb** zvolte **Služba převodu bankovních dat -  Převod Dal** pro nastavení exportu plateb.
4. Do pole **Název banky - Převod dat** zadejte nebo vyberte název formátu bankovních dat, ke kterému jste se přihlásili v kroku 4, v části "Registrace služby převodu bankovních dat."
5. Opakujte kroky 1 až 4 pro ostatní bankovní účty, které budou používat službu převodu bankovních dat.

## <a name="see-also"></a>Viz také  
[Nastavení bankovnictví](bank-setup-banking.md)  
[Správa bankovních účtů](bank-manage-bank-accounts.md)

