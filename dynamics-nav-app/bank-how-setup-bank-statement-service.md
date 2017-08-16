---
title: "Návod: Nastavení Envestnet Yodlee Bank Feeds Service"
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
ms.openlocfilehash: 270568214afd2ca8af15f0fa7640337c77ec2f1e
ms.contentlocale: cs-cz
ms.lasthandoff: 06/26/2017

---

# <a name="how-to-set-up-the-envestnet-yodlee-bank-feeds-service"></a>Návod: Nastavení Envestnet Yodlee Bank Feeds Service
Můžete importovat elektronické bankovní výpisy z vaší banky pro rychlé naplnění v okně **Deník odsouhlasení plateb**, abyste mohli zaplatit a odsouhlasit bankovní účet. Další informace naleznete v části [Použití plateb automaticky a odsouhlasení bankovních účtů](receivables-apply-payments-auto-reconcile-bank-accounts.md).

**Poznámka**: The Envestnet Yodlee Bank Feeds service nebo jiný poskytovatel bankovních služeb nemusí být ve vašem systému k dispozici. Obraťte se na svého partnera Microsoft, chcete-li pro import bankovních výpisů použít bankovní službu.

Pokud jste povolili bankovní službu, musíte propojit příslušný bankovní účet s bankovním účtem online, ze kterého pochází zdroj. Bankovní účty propojíte s online bankovními účty v různých scénářích:

- Bankovní účet neexistuje v Dynamics NAV pro váš online bankovní účet. Proto vytvoříte bankovní účet tím, že ho propojíte s online bankovním účtem.
- V Dynamics NAV existuje bankovní účet, který chcete propojit s online bankovním účtem.
- Propojený bankovní účet musí být odpojen, protože chcete přestat používat bankovní službu pro daný účet.
- Online bankovní účty se změnily a chcete aktualizovat informace o bankovních účtech v Dynamics NAV.

Když je bankovní služba aktivována, můžete nastavit bankovní účet, aby automaticky importoval nové bankovní výpisy do okna **Deník odsouhlasení plateb** každé dvě hodiny. Transakce plateb, které již byly zveřejněny jako zaúčtované a/nebo odsouhlasené v okně **Deník odsouhlasení plateb** nebudou importovány. Další informace naleznete v části “Povolit automatický import bankovních výpisů.“

**Poznámka**: Používáte-li instalaci s asistencí nastavení společnosti, pak se některé kroky v následujících postupech automaticky provedou, když se dostanete k nastavení bankovního účtu společnosti. Další informace naleznete v části [Vítejte v Dynamics NAV](across-get-started.md).

## <a name="to-enable-the-bank-feed-service"></a>Povolení bankovní služby 
1. V pravém horním rohu zvolte ikonu **Vyhledat stránku nebo sestavu**, zadejte **Bankovní účty** a pak vyberte související odkaz.
2. Otevřete bankovní účet, který použijete pro bankovní službu.
3. V okně **Bankovní účty** v poli **Formát importu bankovního výpisu** vyberte YODLEEBANKFEED.  

Bankovní služba bude aktivována, když propojíte bankovní účet s jeho souvisejícím online bankovním účtem. Viz další postup.  

## <a name="to-create-a-new-linked-bank-account"></a>Vytvoření nového propojeného bankovního účtu
1. V pravém horním rohu zvolte ikonu **Vyhledat stránku nebo sestavu**, zadejte **Bankovní účty** a pak vyberte související odkaz.
2. Vyberte relevantní bankovní účet a pak zvolte **Vytvořit nový propojený bankovní účet**. Po několika okamžicích se otevře okno **Propojení bankovního účtu**.

    **Poznámka**: Toto okno zobrazuje aktuální webovou stránku služby Envestnet Yodlee Bank Feeds. Terminologie a funkčnost v okně nemusí odpovídat instrukcím uvedeným v tomto tématu.  
3. V okně **Propojení online bankovního účtu** v podokně **Propojit účet** použijte funkci Hledat a vyhledejte banku, kde máte jeden nebo více online bankovních účtů.
4. Vyberte název banky. Otevře se podokno **Přihlášení**.
5. Zadejte uživatelské jméno a heslo, které používáte pro přihlášení do online banky a poté zvolte tlačítko **Další**.  
6. Bankovní služba se připravuje k propojení prvního online bankovního účtu na určené bance s novým bankovním účtem v Dynamics NAV.

    **Poznámka**: Máte-li v bance více online bankovních účtů, musíte pro tyto další online bankovní účty vytvořit v účtu Dynamics NAV další bankovní účty. Viz kroky 8 až 10.

    Po úspěšném dokončení procesu se název banky zobrazí v podokně **Mé účty** na kartě **Propojené**. Číslo v závorce udává, kolik online bankovních účtů bylo spojeno.
7. Zvolte tlačítko **OK**.

    Pokud je propojen pouze jeden online bankovní účet, otevře se okno **Karta bankovního účtu** pro nový bankovní účet, který je předem vyplněn názvem online bankovního účtu. V tomto případě je dokončena úloha propojení bankovního účtu. Zbývá jen nastavení bankovního účtu. Další informace naleznete v [Návod: Nastavení bankovních účtů](bank-how-setup-bank-accounts.md).

    Pokud bylo propojeno více online bankovních účtů, otevře se okno **Propojení bankovních účtů** s uvedenými dalšími online bankovními účty, které ještě nejsou propojeny s bankovními účty v Dynamics NAV. V tomto případě, následujte další krok.  
8. V okně **Propojení bankovního účtu** vyberte řádek pro online bankovní účet a poté zvolte akci **Odkaz na nový bankovní účet**.

    V okně **Karta bankovního účtu** se otevře nový bankovní účet, který je předem vyplněn názvem online bankovního účtu.

    Pokud v Dynamics NAV již existuje bankovní účet, ke kterému chcete připojit další bankovní účet, postupujte podle následujícího kroku.  
9. V okně **Připojení bankovního účtu** vyberte řádek pro online bankovní účet a poté zvolte akci **Propojit na existující bankovní účet**.
10. V okně **Seznam bankovních účtů** vyberte bankovní účet, ke kterému ho chcete propojit a potom klepněte na tlačítko **OK**.

## <a name="to-link-a-bank-account-to-an-online-bank-account"></a>Propojení bankovního účtu s bankovním účtem online
1. V pravém horním rohu zvolte ikonu **Vyhledat stránku nebo sestavu**, zadejte **Bankovní účty** a pak vyberte související odkaz.
2. Vyberte řádek pro bankovní účet, který není propojen s bankovním účtem online, a poté vyberte akci **Propojit s bankovním účtem online**. Otevře se okno **Propojení online bankovního účtu** s názvem banky, která je vyplněna v podokně **Propojení účtu**.
3. Vyberte název banky. Otevře se podokno **Přihlášení**.
4. Zadejte uživatelské jméno a heslo, které používáte pro přihlášení do online banky a poté zvolte tlačítko **Další**.

    Bankovní služba se připravuje na propojení vašeho bankovního účtu v Dynamics NAV s příslušným online bankovním účtem.

    Po úspěšném dokončení procesu se název banky zobrazí v podokně **Mé účty** na kartě **Propojené**. Pokud má banka více než jeden bankovní účet, je propojen pouze bankovní účet, který jste vybrali v kroku 2.
5. Zvolte tlačítko **OK**.

V okně **Seznam bankovních účtů** je zaškrtnuto políčko **Propojené**.

## <a name="to-unlink-a-bank-account"></a>Zrušení propojení bankovního účtu
1. V pravém horním rohu zvolte ikonu **Vyhledat stránku nebo sestavu**, zadejte **Bankovní účty** a pak vyberte související odkaz.  
2. Vyberte řádek pro propojený bankovní účet, který chcete odpojit od souvisejícího online bankovního účtu a vyberte akci **Odpojit online bankovní účet**.

**Poznámka**: Pokud v dialogovém okně pro potvrzení zvolíte možnost **Ano**, odstraní se odkaz na online bankovní účet a údaje o přihlašování se vymažou. Chcete-li bankovní účet znovu propojit s bankovním účtem online, musíte se znovu přihlásit. Další informace naleznete v části "Propojení bankovního účtu s online bankovním účtem".

## <a name="to-update-bank-account-linking"></a>Aktualizace propojení bankovního účtu
1. V pravém horním rohu zvolte ikonu **Vyhledat stránku nebo sestavu**, zadejte **Bankovní účty** a pak vyberte související odkaz.
2. Vyberte příslušný bankovní účet a poté vyberte akci **Aktualizovat propojení bankovního účtu**.

Pokud existují problémy pro kterýkoliv z propojených bankovních účtů v okně **Seznam bankovních účtů** otevře se okno **Propojení bankovního účtu**, které specifikuje bankovní účty s problémy. Problémy lze nejlépe vyřešit zrušením propojení online bankovního účtu a následným znovu vytvořením odkazu. Další informace naleznete v části "Propojení bankovního účtu s online bankovním účtem."

## <a name="to-enable-automatic-import-of-bank-statements"></a>Povolení automatického importu bankovních výpisů
1. V pravém horním rohu zvolte ikonu **Vyhledat stránku nebo sestavu**, zadejte **Bankovní účty** a pak vyberte související odkaz.
2. Vyberte řádek propojeného bankovního účtu a poté zvolte akci **Automatický import výpisu z bankovního účtu**.
3. V okně **Automatické nastavení importu bankovních výpisů**, pole **Zahrnutých počet dnů** určuje, jak daleko zpět v čase lze získat nové bankovní transakce.

    **Poznámka**: Doporučujeme nastavit tuto hodnotu na 7 nebo více dní.
4. Zaškrtněte políčko **Povolit**.  
Každou hodinu bude nyní okno **Deník odsouhlasení plateb** naplněno novými platbami provedenými na online bankovním účtu.

**Poznámka**: Transakce plateb, které již byly zveřejněny jako zaúčtované a/nebo odsouhlasené v okně **Deník odsouhlasení plateb** nebudou importovány.

## <a name="see-also"></a>Viz také  
[Nastavení bankovnictví](bank-setup-banking.md)  
[Správa bankovních účtů](bank-manage-bank-accounts.md)  
[Použití automatických plateb a odsouhlasení bankovních účtů](receivables-apply-payments-auto-reconcile-bank-accounts.md)  
[Přizpůsobení Dynamics NAV pomocí rozšíření ](ui-extensions.md)

