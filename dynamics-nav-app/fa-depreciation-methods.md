---
title: "Metody odpisování"
description: "Informace o různých způsobech odpisování nebo snížení hodnoty dlouhodobého majetku."
documentationcenter: 
author: SorenGP
ms.prod: dynamics-nav-2018
ms.topic: article
ms.devlang: na
ms.tgt_pltfrm: na
ms.workload: na
ms.search.keywords: write down
ms.date: 06/02/2017
ms.author: sgroespe
ms.translationtype: HT
ms.sourcegitcommit: 4fefaef7380ac10836fcac404eea006f55d8556f
ms.openlocfilehash: 7d5fd80eeabb078122283748c45203356bf6f1a8
ms.contentlocale: cs-cz
ms.lasthandoff: 10/16/2017

---
# <a name="depreciation-methods"></a>Metody odpisování
K dispozici je osm metod odpisování:  

* Lineární  
* Zrychlený 1  
* Zrychlený 2  
* ZR1/SL  
* ZR2/SL  
* Uživatelem definovaný  
* Ruční  

  > [!NOTE]  
>   Tuto metodu můžete použít pro majetek, který nepodléhá odpisům například pozemky. Musíte zadat odpisy ve finančním deníku DM. Dávková úloha **Výpočet odpisů** vynechává dlouhodobý majetek, který používá metodu ručního odpisování.  
* Pololetní konvence  

  > [!NOTE]  
>    Při použití této metody se dlouhodobý majetek každoročně odpisuje o stejnou částku.  

## <a name="straight-line-depreciation"></a>Lineární odpisy
Pokud používáte lineární metodu, musíte zadat jednu z následujících možností do knihy odpisů dlouhodobého majetku:  

* Doba odpisování (roky nebo měsíce) nebo konečný termín odpisování  
* Pevné roční procento  
* Pevná roční částka  
* Odpisové období  

### <a name="depreciation-period"></a>Odpisové Období
Pokud zadáte dobu odpisování (počet odpisových let, počet odpisových měsíců nebo konečný termín odpisování), program použije pro výpočet odpisové částky následující vzorec:  

*Částka odpisů = ((Účetní hodnota - Hodnota při vyřazení) x Počet dnů odpisů) / Zbývající dny odpisů*  

Zbývající doba odpisování je vypočtena jako počet dnů odpisování mínus počet dnů mezi počátečním datem odpisování a posledním datem vložení dlouhodobého majetku.  

Účetní hodnota může být snížena o zaúčtované zhodnocení, snížení hodnoty, vlastní 1 nebo vlastní 2 částky, v závislosti na tom, zda je pole **Zahrnout do výpočtu** odpisů deaktivováno a je aktivováno pole **Část účetní hodnoty** v okně **Nastavení typu účtování DM**. Tento výpočet zajišťuje, že dlouhodobý majetek je plně odepsán v den ukončení odpisů.  

### <a name="fixed-yearly-percentage"></a>Pevná roční procentní sazba
Zadáte-li pevnou roční procentní sazbu, program vypočítá odpisovou část dle následujícího vzorce:  

Částka odpisů = (Lineární % x Odpisovatelný základ x Počet odpisových dní) / (100 x 360)  

### <a name="fixed-yearly-amount"></a>Pevná roční částka
Pokud zadáte pevnou roční částku, program použije tento vzorec pro výpočet částky odpisů:  

Částka odpisů = (pevná částka odpisů x počet dnů odepisování) / 360  

### <a name="example---straight-line-depreciation"></a>Příklad - Lineární odpisy
Dlouhodobý majetek má pořizovací cenu 100 000 LM. Odhadovaná doba života je osm let. Dávková úloha **Výpočet odpisů** se provádí dvakrát ročně.  

Příklad: Položka knihy dlouhodobého majetku vypadá takto:  

| Datum | Typ zaúčtování DM | Dny | Částka | Účetní hodnota |
| --- | --- | --- | --- | --- |
| 01/01/10 |Pořizovací cena |* |100 000,00 |100 000,00 |
| 06/30/10 |Odpisy |180 |-6 250,00 |93 750,00 |
| 12/31/10 |Odpisy |180 |-6 250,00 |87 500,00 |
| 06/30/11 |Odpisy |180 |-6 250,00 |81 250,00 |
| 12/31/11 |Odpisy |180 |-6 250,00 |75 000,00 |
| 06/30/17 |Odpisy |180 |-6 250,00 |6 250,00 |
| 12/31/17 |Odpisy |180 |-6 250,00 |0 |

* Počáteční datum odpisování  

## <a name="declining-balance-1-depreciation"></a>Zrychlený odpis 1
Jedná se o zrychlenou metodu odpisování, která přiděluje největší část nákladů na majetek v prvních letech své životnosti. Používáte-li tuto metodu, musíte zadat pevný roční procentní podíl.  

Následující vzorec počítá odpisy:  

*Částka odpisů = (Zrychlený % x počet odpisových dní x Odpisový základ) / (100 x 360)*  

Odpisový základ se vypočítá jako účetní hodnota snížená o zaúčtované odpisy od počátku běžného fiskálního roku.  

Zaúčtovaná částka odpisů může obsahovat položky s různými druhy zaúčtování (odpis, vlastní1 a vlastní2), které byly zveřejněny od data zahájení současného fiskálního roku. Tyto typy zaúčtování jsou zahrnuty v částce zaúčtovaného odpisu, pokud jsou zaškrtnuty značky v poli **Typ odpisování** a v poli **Část účetní hodnoty** v okně **Nastavení typu účtování DM**.  

### <a name="example---declining-balance-1-depreciation"></a>Příklad - Zrychlený odpis 1
Dlouhodobý majetek má pořizovací cenu 100 000 LM. V poli **Zrychlený %** je hodnota 25. Dávková úloha  **Výpočet odpisů** se provádí dvakrát ročně.  

Následující tabulka ukazuje, jak vypadají položky DM.  

| Datum | Typ zaúčtování DM | Dny | Částka | Účetní hodnota |
| --- | --- | --- | --- | --- |
| 01/01/10 |Pořizovací cena |* |100 000,00 |100 000,00 |
| 06/30/10 |Odpisy |180 |-12 500,00 |87 500,00 |
| 12/31/10 |Odpisy |180 |-12 500,00 |75 000,00 |
| 06/30/11 |Odpisy |180 |-9 375,00 |65 625,00 |
| 12/31/11 |Odpisy |180 |-9 375,00 |56 250,00 |
| 06/30/12 |Odpisy |180 |-7 031,25 |49 218,75 |
| 12/31/12 |Odpisy |180 |-7 031,25 |42 187,50 |
| 06/30/13 |Odpisy |180 |-5 273,44 |36 914,06 |
| 12/31/13 |Odpisy |180 |-5 273,44 |31 640,62 |
| 06/30/14 |Odpisy |180 |-3 955,08 |27 685,54 |
| 12/31/14 |Odpisy |180 |-3 955,08 |23 730,46 |

* Počáteční datum odpisování  

    Metoda výpočtu:  

    *1. rok: 25% z 100,000 = 25,000 = 12,500 + 12,500*

    *2. rok: 25% z 75 000 = 18 750 = 9 375 + 9 375*

    *3. rok: 25% z 56 250 = 14 062,50 = 7 031,25 + 7 031,25*

    Výpočet pokračuje, dokud účetní hodnota neodpovídá konečnému počtu zaokrouhlení částky nebo hodnotě, kterou zadáte.   

## <a name="declining-balance-2-depreciation"></a>Zrychlený odpis 2
Metoda Zrychlený 1 a Zrychlený 2 vypočítá stejnou celkovou částku odpisů za každý rok. Pokud však spustíte dávkovou úlohu **Výpočet odpisů** vícekrát za rok, metoda Zrychlený 1 bude mít za následek stejné částky odpisů pro každé období odpisování. Metoda Zrychlený 2 na druhé straně bude mít za následek částky odpisů, které klesnou za každé období.  

### <a name="example---declining-balance-2-depreciation"></a>Příklad - Zrychlený odpis 2
Dlouhodobý majetek má pořizovací cenu 100 000 LM. V poli **Zrychlený %** je hodnota 25. Dávková úloha  **Výpočet odpisů** se provádí dvakrát ročně. Položky knihy dlouhodobého majetku vypadají takto:  

| Datum | Typ zaúčtování DM | Dny | Částka | Účetní hodnota |
| --- | --- | --- | --- | --- |
| 01/01/10 |Pořizovací cena |* |100 000,00 |100 000,00 |
| 06/30/10 |Odpisy |180 |-13 397,46 |86 602,54 |
| 12/31/10 |Odpisy |180 |-11 602,54 |75 000,00 |
| 06/30/11 |Odpisy |180 |-10 048,09 |64 951,91 |
| 12/31/11 |Odpisy |180 |-8 701,91 |56 250,00 |

* Počáteční datum odpisování  

Metoda výpočtu:  

* BV = účetní hodnota  
* ND = počet dnů odpisování  
* ZRP = Zrychlený procenta  
* P = ZRP/100  
* D = ND/360  

Vzorec pro výpočet odpisových částek je:  

*DA = BV x (1 – (1 –P)<sup>D<sup>*  

Hodnoty odpisování jsou:  

| Datum | Výpočet |
| --- | --- |
| 06/30/10 |DA = 100,000.00 x (1 -(1 - 0.25)<sup>0.5<sup>) = 13,397.46 |
| 12/31/10 |DA = 86,602.54 x (1 - (1 - 0.25)<sup>0.5<sup>) = 11,602.54 |
| 06/30/11 |DA = 75,000.00 x (1 - (1 - 0.25)<sup>0.5<sup>) = 10,048.09 |
| 12/31/11 |DA = 64,951.91 x (1 - (1 - 0.25)<sup>0.5<sup>) = 8,701.91 |

## <a name="db1sl-depreciation"></a>ZR1/SL odpis
ZR1/SL je zkrácená kombinace Zrychlený 1 a Lineární. Výpočet pokračuje, dokud účetní hodnota neodpovídá konečnému počtu zaokrouhlení částky nebo hodnotě, kterou zadáte.  

Dávková úloha **Výpočet odpisů** vypočítá Lineární částku a klesající částku zůstatku, ale pouze část větší z obou částek je převedena do deníku.  

Pro výpočet klesajícího zůstatku můžete použít různé procentní podíly.  

Používáte-li tuto metodu, musíte zadat odhadovanou životnost a klesající procentuální zůstatek v okně **Knihy odpisů DM**.  

### <a name="example---db1-sl-depreciation"></a>Například - ZR1-SL Odpisy
Dlouhodobý majetek má pořizovací cenu 100 000 LM. V okně **Knihy odpisů DM** pole **Zrychlený %** obsahuje hodnotu 25 a pole **Počet roků odpisování** obsahuje hodnotu 8. Dávková úloha  **Výpočet odpisů** se provádí dvakrát ročně.  

Položky knihy dlouhodobého majetku vypadají takto:  

| Datum | Typ zaúčtování DM | Dny | Částka | Účetní hodnota |
| --- | --- | --- | --- | --- |
| 01/01/10 |Pořizovací cena |* |100 000,00 |100 000,00 |
| 06/30/10 |Odpisy |180 |-12 500,00 |87 500,00 |
| 12/31/10 |Odpisy |180 |-12 500,00 |75 000,00 |
| 06/30/11 |Odpisy |180 |-9 375,00 |65 625,00 |
| 12/31/11 |Odpisy |180 |-9 375,00 |56 250,00 |
| 06/30/12 |Odpisy |180 |-7 031,25 |49 218,75 |
| 12/31/12 |Odpisy |180 |-7 031,25 |42 187,50 |
| 06/30/13 |Odpisy |180 |-5 273,44 |36 914,06 |
| 12/31/13 |Odpisy |180 |-5 273,44 |31 640,62 |
| 06/30/14 |Odpisy |180 |-3 955,08 |27 685,54 |
| 12/31/14 |Odpisy |180 |-3 955,08 |23 730,46 |
| 06/30/15 |Odpisy |180 |-3 955,08 |19,775.38 SL |
| 12/31/15 |Odpisy |180 |-3 955,08 |15,820.30 SL |
| 06/30/16 |Odpisy |180 |-3 955,08 |11,865.22 SL |
| 12/31/16 |Odpisy |180 |-3 955,07 |7,910.15 SL |
| 06/30/17 |Odpisy |180 |-3 955,08 |3,955.07 SL |
| 12/31/17 |Odpisy |180 |-3 955,07 |0.00 SL |

* Počáteční datum odpisování  

"SL" po účetní hodnotě znamená, že byla použita lineární metoda.  

Způsob výpočtu:  

1. rok:  

*Zrychlená částka: 25% z 100,000 = 25,000 = 12,500 + 12,500*  

*Lineární částka = 100,000 / 8 = 12,500 = 6,250 + 6,250*  

Klesající částka se používá, protože je to větší částka.  

6. rok (2015):  

*Zrychlená částka: 25% z 23,730.46 = 4,943.85= 2,471.92 + 2,471.92*  

*Lineární částka = 23,730.46/3 = 7,910.15 = 3,995.07 + 3,995.08*  

Lineární částka se používá, protože je to větší částka.  

## <a name="user-defined-depreciation"></a>Uživatelem definovaný odpis
Program má zařízení, které umožňuje nastavit uživatelem definované metody odpisování.  

Metodu uživatelem definovanou můžete použít v okně **Tabulky odpisů**, kde musíte pro každé období (měsíc, čtvrtletí, rok nebo účetní období) zadat procento odpisů.  

Vzorec pro výpočet odpisových částek je:  

Částka odpisů = (Odpisy % x Počet dnů odpisů x Odpisový základ) / (100 x 360)  

### <a name="depreciation-based-on-number-of-units"></a>Odpisy založené na počtu jednotek
Tato uživatelem definovaná metoda může být také použita k odpisování na základě počtu jednotek, například v případě výrobních strojů se stanovenou životností. V okně **Tabulky odpisů** můžete zadat počet jednotek, které lze vytvořit v každém období (měsíc, čtvrtletí nebo účetní období).  

### <a name="to-set-up-user-defined-depreciation-methods"></a>Nastavení uživatelem definovaných metod odpisování
V okně **Tabulky odpisů** můžete nastavit uživatelem definované metody odpisování. Například můžete nastavit odpis podle počtu jednotek.  

1. Zvolte ikonu ![Vyhledat stránku nebo sestavu](media/ui-search/search_small.png "Ikona Vyhledat stránku nebo sestavu"), zadejte **Tabulky odpisů** a pak vyberte související odkaz.  
2. V okně **Přehled tabulek odpisů** zvolte akci **Nový**.  
3. V okně **Karta tabulky odpisů** vyplňte pole podle potřeby. [!INCLUDE[tooltip-inline-tip](includes/tooltip-inline-tip_md.md)]  

### <a name="example---user-defined-depreciation"></a>Příklad - Uživatelem definované odpisy
Používáte metodu odpisování, která vám umožňuje rychleji odpisovat majetek pro účely daně z příjmů.  

Pro dlouhodobý majetek s tříletou životností pro daňové účely byste použili následující odpisové sazby:  

* 1. rok: 25%  
* 2. rok: 38%  
* 3. rok: 37%  

Pořizovací cena činí 100 000 LM a odpisovatelná životnost je pět let. Odpisy se vypočítají ročně.  

| Datum | Typ zaúčtování DM | Dny | Částka | Účetní hodnota |
| --- | --- | --- | --- | --- |
| 01/01/10 |Pořizovací cena |* |100 000,00 |100 000,00 |
| 12/31/10 |Odpisy |360 |-25 000,00 |75 000,00 |
| 12/31/11 |Odpisy |360 |-38 000,00 |37 000,00 |
| 12/31/12 |Odpisy |360 |-37 000,00 |0 |
| 12/31/13 |Odpisy |Žádný |Žádný |0 |
| 12/31/14 |Odpisy |Žádný |Žádný |0 |

* Počáteční datum odpisování  

Používáte-li metodu uživatelem definovanou pole **První uživ. definované datum **a **Počáteční datum odpisování** musí být vyplněno v okně **Knihy odpisů DM**. Pole **První uživ. definované datum** a pole **Délka období** v okně **Tabulky odpisů** se používají k určení časových intervalů, které mají být použity pro výpočty odpisů. Tím je zajištěno, že program začne používat určený procentní podíl ve stejný den pro všechny aktiva. Pole **Počáteční datum odpisování** se používá pro výpočet počtu dnů odpisování.  

V předchozím příkladu v obou polích **První uživ. definované datum **a **Počáteční datum odpisování** obsahuje 01/01/01. Pokud ovšem pole **První uživ. definované datum **obsahuje 01/01/10 a pole **Počáteční datum odpisování** obsahuje 04/01/11, výsledek bude:  

| Datum | Typ zaúčtování DM | Dny | Částka | Účetní hodnota |
| --- | --- | --- | --- | --- |
| 01/01/10 |Pořizovací cena |* |100 000,00 |100 000,00 |
| 12/31/10 |Odpisy |270 |-18 750,00 |81 250,00 |
| 12/31/11 |Odpisy |360 |-38 000,00 |42 250,00 |
| 12/31/12 |Odpisy |360 |-37 000,00 |6 250,00 |
| 12/31/13 |Odpisy |90 |-6 250,00 |0 |
| 12/31/14 |Odpisy |Žádný |Žádný |0 |

* Počáteční datum odpisování  

## <a name="half-year-convention-depreciation"></a>Pololetní konvence odpisů
Metoda Pololetní konvence bude použita pouze tehdy, pokud do pole **Použít pololetní konvenci** umístíte zaškrtávací políčko v okně **Kniha odpisů DM**.  

Tuto metodu odpisování lze použít v souvislosti s následujícími metodami odpisování v programu:  

* Lineární  
* Zrychlený 1  
* ZR1/SL  

Pokud se použije pololetní konvence, bude mít dlouhodobý majetek v prvním finančním roce šestiměsíční odpisy bez ohledu na obsah pole **Počáteční datum odpisování**.  

> [!NOTE]  
>   Odhadovaná životnost dlouhodobého majetku, která zůstane po prvním fiskálním roce, bude vždy obsahovat půl roku s použitím metody pololetní konvence. Proto, aby byla metoda pololetní konvence aplikována správně, musí pole **Poslední datum odpisování** v okně **Kniha odpisů DM** vždy obsahovat datum, které je přesně šest měsíců před konečným datem fiskálního roku, ve kterém se stávající dlouhodobý majetek stane plně odepsán.  

### <a name="example---half-year-convention-depreciation"></a>Příklad - pololetní konvence odpisů
Dlouhodobý majetek má pořizovací cenu 100 000 LM. **Počáteční datum odpisování** je 03/01/10. Odhadovaná životnost je pět let, takže **Poslední datum odpisování** musí být 06/30/15. Dávková úloha **Výpočet odpisů** se provádí ročně. Tento příklad je založen na kalendářním fiskálním roce.  

Položky knihy dlouhodobého majetku vypadají takto:  

| Datum | Typ zaúčtování DM | Dny | Částka | Účetní hodnota |
| --- | --- | --- | --- | --- |
| 03/01/10 |Pořizovací cena |* |100 000,00 |100 000,00 |
| 12/31/10 |Odpisy |270 |-10 000,00 |90 000,00 |
| 12/31/11 |Odpisy |360 |-20 000,00 |70 000,00 |
| 12/31/12 |Odpisy |360 |-20 000,00 |50 000,00 |
| 12/31/13 |Odpisy |360 |-20 000,00 |30 000,00 |
| 12/31/14 |Odpisy |360 |-20 000,00 |10 000,00 |
| 12/31/15 |Odpisy |180 |-10 000,00 |0,00 |

* Počáteční datum odpisování  

## <a name="example---db1sl-depreciation-using-half-year-convention"></a>Příklad - Odpisy ZR1/SL pomocí pololetní konvence
Dlouhodobý majetek má pořizovací cenu 100 000 LM. **Počáteční datum odpisování** je 11/01/10. Odhadovaná životnost je pět let, takže **Poslední datum odpisování** musí být 06/30/15. V okně **Knihy odpisů DM** pole **Zrychlený %** obsahuje 40. Dávková úloha **Výpočet odpisů** se provádí ročně. Tento příklad je založen na kalendářním fiskálním roce.  

Položky knihy dlouhodobého majetku vypadají takto:  

| Datum | Typ zaúčtování DM | Dny | Částka | Účetní hodnota |
| --- | --- | --- | --- | --- |
| 11/01/10 |Pořizovací cena |* |100 000,00 |100 000,00 |
| 12/31/10 |Odpisy |60 |-20 000,00 |80 000,00 |
| 12/31/11 |Odpisy |360 |-32 000,00 |48 000,00 |
| 12/31/12 |Odpisy |360 |-19 200,00 |28 800,00 |
| 12/31/13 |Odpisy |360 |-11 520,00 |17 280,00 |
| 12/31/14 |Odpisy |360 |-11 520,00 |5,760.00 SL |
| 12/31/15 |Odpisy |180 |-5 760,00 |0.00 SL |

* Počáteční datum odpisování  

"SL" po účetní hodnotě znamená, že byla použita lineární metoda.  

Způsob výpočtu:  

1. rok:  

*Snížená částka = celková roční částka = 40% ze 100 000 = 40 000. Tedy za půl roku 40 000/2 = 20 000*  

*Lineární částka = celková roční částka = 100 000/5 = 20 000. Tedy za půl roku = 20 000/2 = 10 000*  

Klesající částka se používá, protože je to větší částka.  

5. Rok (2004):  

*Klesající částka = 40% z 17 280 000 = 6 912,00*  

*Lineární částka = 28,800 / 1.5 = 11,520.00*  

Lineární částka se používá, protože je to větší částka.  

## <a name="duplicating-entries-to-more-depreciation-books"></a>Kopírování položek do dalších odpisových knih
Pokud máte tři knihy odpisů B1, B2 a B3 a chcete duplikovat položky z B1 na B2 a B3, můžete zaškrtnout políčko **Část seznamu duplikací** na kartách odpisů pro B2 a B3. To může být užitečné, pokud je odpisová kniha B1 integrována s hlavní knihou a používá finanční deník dlouhodobého majetku a Knihy odpisů B2 a B3, které nejsou integrovány do hlavní knihy a používají deník dlouhodobého majetku.  

Při zadání položky v B1 ve finančním deníku dlouhodobého majetku a zaškrtnutí do pole **Použití seznamu duplikací** program duplikuje záznam v knize B2 a B3 v deníku dlouhodobého majetku, když je záznam zaúčtován.  

> [!NOTE]  
>   Není možné duplikovat ve stejném deníku a dávku deníku, jakou jste zkopírovali. Pokud zaúčtujete položky dlouhodobého majetku ve finančním deníku, můžete je duplikovat v deníku dlouhodobého majetku nebo ve finančním deníku dlouhodobého majetku pomocí jiné dávky.  

> [!NOTE]  
>   Stejné číselné řady nelze použít ve finančním deníku dlouhodobého majetku a deníku dlouhodobého majetku. Při zaúčtování položek DM do finančního deníku musíte nechat pole **Číslo dokumentu** prázdné. Zadáte-li číslo do pole, číslo bude duplikováno v deníku DM. Budete muset ručně změnit číslo dokumentu, abyste mohli zaúčtovat deník.  

## <a name="see-also"></a>Viz také
[Dlouhodobý majetek](fa-manage.md)  
[Nastavení dlouhodobého majetku](fa-setup.md)  
[Finance](finance.md)  
[Vítejte v [!INCLUDE[d365fin_long](includes/d365fin_long_md.md)]](index.md)  
[Práce s [!INCLUDE[d365fin](includes/d365fin_md.md)]](ui-work-product.md)

