---
title: "Přecenění dlouhodobého majetku"
description: "Zjistěte, jak upravit hodnotu dlouhodobého majetku, zaznamenat nové částky jako snížení hodnoty nebo zhodnocení a zaúčtovat další pořizovací náklady."
documentationcenter: 
author: SorenGP
ms.prod: dynamics-nav-2017
ms.topic: article
ms.devlang: na
ms.tgt_pltfrm: na
ms.workload: na
ms.date: 06/02/2017
ms.author: sgroespe
ms.translationtype: HT
ms.sourcegitcommit: 4fefaef7380ac10836fcac404eea006f55d8556f
ms.openlocfilehash: 09c3babe38e1ec20f5d695f97df37104a9cc4d35
ms.contentlocale: cs-cz
ms.lasthandoff: 10/16/2017

---
# <a name="how-to-revalue-fixed-assets"></a>Návod: Přecenění dlouhodobého majetku
Přecenění DM může zahrnovat zhodnocení, znehodnocení nebo úpravy obecné hodnoty.

Když se hodnota DM zvýšila, zaúčtujete řádky deníku s vyšší hodnotou (zhodnocení) do odpisové knihy. Nová částka je zaznamenána jako zhodnocení podle nastavení zaúčtování DM.

Pokud se hodnota DM sníží, zaúčtujete řádky deníku s nižší hodnotou (znehodnocení) do odpisové knihy. Nová částka se zaznamená jako snížení hodnoty podle nastavení zaúčtování DM.

Indexace se používá k úpravě více hodnot DM například na základě změn obecné ceny. Dávková úloha **Indexovat DM** může být použita ke změně různých částek například snížení hodnoty a zhodnocení.

## <a name="to-post-an-appreciation-from-the-fixed-asset-gl-journal"></a>Zaúčtování zhodnocení z finančního deníku DM
1. Zvolte ikonu ![Vyhledat stránku nebo sestavu](media/ui-search/search_small.png "Ikona Vyhledat stránku nebo sestavu"), zadejte **Finanční deník DM** a pak vyberte související odkaz.  
2. Vytvořte počáteční řádek deníku a vyplňte pole podle potřeby.
3. Do pole **Typ účtování DM** vyberte **Zhodnocení**.
4. Zvolte možnost **Vložit protiúčet DM**. Druhý řádek deníku je vytvořen pro vyrovnávací účet, který je nastaven pro zhodnocení zaúčtování.

    > [!NOTE]  
>   Krok 4 funguje pouze v případě, že jste nastavili následující: V okně **Karta účto skupiny DM** pro zaúčtování skupin DM, pole **Účet zhodnocení** obsahuje hlavní knihu účtu MD a pole **Protiúčet zhodnocení **obsahuje účet hlavní knihy, na který chcete zaúčtovat zůstatkové položky pro zhodnocení. Další informace naleznete v tématu "Nastavení skupin zaúčtování DM“ [Návod: Nastavení informací o obecném dlouhodobém majetku](fa-how-setup-general.md).  
5. Zvolte akci **Zaúčtovat**.

## <a name="to-post-a-write-down-from-the-fixed-asset-gl-journal"></a>Zaúčtování snížení hodnoty z finančního deníku DM
1. Zvolte ikonu ![Vyhledat stránku nebo sestavu](media/ui-search/search_small.png "Ikona Vyhledat stránku nebo sestavu"), zadejte **Finanční deník DM** a pak vyberte související odkaz.  
2. Vytvořte počáteční řádek deníku a vyplňte pole podle potřeby.
3. Do pole **Typ účtování DM** vyberte **Znehodnocení**.
4. Zvolte možnost **Vložit protiúčet DM**. Druhý řádek deníku je vytvořen pro vyrovnávací účet, který je nastaven pro zaúčtování snížení hodnoty.

    > [!NOTE]  
>   Krok 4 funguje pouze v případě, že jste nastavili následující: V okně **Karta účto skupiny DM** pro zaúčtování skupin DM, pole **Účet znehodnocení** obsahuje hlavní knihu účtu Dal a pole **Účet nákladů znehodnocení** obsahuje hlavní knihu účtu MD, na který chcete zaúčtovat zůstatkové položky pro snížení hodnoty. Další informace naleznete v tématu "Nastavení skupin zaúčtování DM“ [Návod: Nastavení informací o obecném dlouhodobém majetku](fa-how-setup-general.md).
5. Zvolte akci **Zaúčtovat**.

## <a name="to-perform-general-revaluation-of-fixed-assets"></a>Provádění obecného přecenění DM
Indexace se používá k úpravě více hodnot DM, například na základě změn obecné ceny. Dávková úloha **Indexovat DM** může být použita ke změně různých částek například snížení hodnoty a zhodnocení. Musí být vybráno zaškrtávací políčko **Povolit indexaci** v okně **Knihy odpisů**.

1. Zvolte ikonu ![Vyhledat stránku nebo sestavu](media/ui-search/search_small.png "Ikona Vyhledat stránku nebo sestavu"), zadejte **Indexovat DM** a pak vyberte související odkaz.  
2. Vyplňte pole dle potřeby.
3. Zvolte tlačítko **OK**.

    Řádky přecenění jsou vytvořeny podle nastavení v kroku 2. Řádky jsou vytvářeny buď v deníku DM nebo ve finančním deníku DM v závislosti na vaší šabloně a nastavení dávky v okně **Nastavení deníku DM**. Další informace naleznete v tématu [Návod: Nastavení informací o obecném dlouhodobém majetku](fa-how-setup-general.md).
4. Zvolte ikonu ![Vyhledat stránku nebo sestavu](media/ui-search/search_small.png "Ikona Vyhledat stránku nebo sestavu"), zadejte **Finanční deník DM** a pak vyberte související odkaz.  
5. Vyberte deník s dlouhodobým majetkem, který chcete přehodnotit a poté vyberte akci **Položky**.  
6. Zkontrolujte vytvořené položky a potom vyberte akci **Účtovat** k zaúčtování deníku.

    > [!TIP]  
>   Pokud jsou indexy pouze pro simulační účely, můžete vytvořit speciální odpisovou knihu, která je uloží. Pak tyto položky neovlivní žádné z ostatních odpisových knih.

   ## <a name="to-post-additional-acquisition-costs"></a>Zaúčtování doplňující pořizovací ceny
   Zaúčtování doplňující pořizovací ceny pro dlouhodobý majetek je stejné jako zaúčtování původní pořizovací ceny z nákupní faktury nebo z deníku DM. Další informace naleznete v tématu [Návod: Pořízení DM](fa-how-acquire.md).  

Pokud již byl odpis vypočítán pro dlouhodobý majetek, vyberte zaškrtávací políčko **Odpis nákladů pořízení** k tomu, aby byla doplňující pořizovací cena snížena o odpis hodnoty při vyřazení v poměru k částce, o kterou již dříve získané dlouhodobé aktivum bylo odpisováno. To zajišťuje, že doba odpisování se nezmění.  

Procentní odpis je vypočten jako:  

*P = (celkové odpisy x 100) / odpisovatelný základ*

*Odpisová částka = (P/100) x (zvláštní pořizovací cena - hodnota při vyřazení)*  

Nezapomeňte vybrat zaškrtávací políčko **Odpisy od zúčt.data DM** na faktuře, finančního deníku DM nebo řádku deníku DM, aby se zajistilo, že odpisy budou vypočítány od posledního data zaúčtování DM do data zaúčtování doplňující pořizovací ceny.

### <a name="example---posting-additional-acquisition-costs"></a>Příklad - Zaúčtování doplňující pořizovací ceny
Stroj je zakoupen 1. srpna 2000. Pořizovací cena je 4.800. Metoda odpisování je lineární po dobu čtyř let.

Dávková úloha **Výpočet odpisů** je spuštěna 31. srpna 2000. Odpisy se vypočítají jako:

*účetní hodnota x počet dnů odpisování / celkový počet dnů odpisování = 4800 x 30/1440 = 100*  

Dne 15. září 2000 byla zaúčtována faktura pro malování stroje. Částka faktury je 480.

Pokud jste vybrali zaškrtávací políčko **Odpisy od zúčt.data DM** na faktuře před zaúčtováním, provede se následující výpočet:  

15 dní odpisování (od 09/01/00 do 09/15/00) se vypočte jako:

*účetní hodnota x počet dnů odepisování / zbývající počet dnů odpisování = (4800 - 100) x 15/1410 = 50*

Pokud jste vybrali zaškrtávací políčko **Odpis nákladů pořízení** na faktuře před zaúčtováním, tak se provede následující výpočet:  

*Doplňující pořizovací náklady jsou odepisovány ((150 x 100) / 4800) / 100 x 480 = 15*

Odpisovatelný základ je nyní *5280 = (4800 + 480)* a akumulované odpisy jsou *165 = (100 + 50 + 15)*, což odpovídá 45 dnům odpisů z celkové pořizovací ceny. To znamená, že majetek bude zcela odepsán během předpokládané životnosti čtyř let.  

Když je dávková úloha **Výpočet odpisů** spuštěna dne 09/30/00, provede se následující výpočet:  

*Zbývající doba odpisování je 3 roky, 10 měsíců a 15 dní = 1395 dní*  

*Účetní hodnota je (5280 - 165) = 5115*  

*Částka odpisů za září 2000: 5115 x 15 / 1395 = 55,00*  

*Celkové odpisy = 165 + 55 = 220*  

Pokud jste nevybrali zaškrtávací políčko **Odpisy od zúčt.data DM**, majetek by ztratil 15 dní odpisování, protože dávková úloha **Výpočet odpisů** je spuštěna dne 09/30/00 a vypočítá odpis od 09/15/00 do 09/30/00. To znamená, že když je spuštěna dávková úloha **Výpočet odpisů** dne 09/30/00, výpočet je následující:  

*Zbývající doba života je 3 roky, 10 měsíců a 15 dní = 1395 dní*  

*Účetní hodnota je (4800 + 480 - 100 - 15) = 5165*

*Částka odpisů za září 2000: 5165 x 15 / 1395 = 55,54*  

*Celkové odpisy = 100 + 15 + 55,54 = 170,54*

## <a name="see-also"></a>Viz také
[Dlouhodobý majetek](fa-manage.md)  
[Nastavení DM](fa-setup.md)  
[Finance](finance.md)  
[Vítejte v [!INCLUDE[d365fin_long](includes/d365fin_long_md.md)]](index.md)  
[Práce s [!INCLUDE[d365fin](includes/d365fin_md.md)]](ui-work-product.md)

