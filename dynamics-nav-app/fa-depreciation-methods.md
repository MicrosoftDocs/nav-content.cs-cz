---
title: "Metody odpisování"
author: SorenGP
ms.custom: na
ms.date: 09/22/2016
ms.reviewer: na
ms.suite: na
ms.tgt_pltfrm: na
ms.topic: article
ms-prod: dynamics-nav-2017
ms.translationtype: Human Translation
ms.sourcegitcommit: 51adfb3588099c496f0946ff71da5c6fe518f070
ms.openlocfilehash: 71773d69e6e98e7917f5e937f04cfa29197da7b8
ms.contentlocale: cs-cz
ms.lasthandoff: 06/26/2017

---

# <a name="depreciation-methods"></a>Metody odpisování
K dispozici je osm metod odpisování:  
- Přímá  
- Declining-Balance 1  
- Declining-Balance 2  
- DB1/SL  
- DB2/SL  
- Definované uživatelem  
- Manuální  

    Pokud používáte manuální metodu, je nutné ručně zadat odpis dlouhodobého majetku ve finančním deníku. Dávková úloha **Výpočet odpisů** vynechává dlouhodobý majetek, který používá metodu ručního odpisování. Tuto metodu můžete použít pro majetek, který nepodléhá odpisům, například pozemky.  
- Pololetní úmluva  

    Při použití této metody se dlouhodobý majetek každoročně odpisuje o stejnou částku.  

## <a name="straight-line-depreciation"></a>Přímé odpisy
Pokud používáte přímou metodu, musíte zadat jednu z následujících možností do knihy odpisů dlouhodobého majetku:
- Doba odpisování (roky nebo měsíce) nebo konečný termín odpisování  
- Pevné roční procento  
- Pevná roční částka  
- Odpisové období  

### <a name="depreciation-period"></a>Odpisové Období  
 Pokud zadáte dobu odpisování (počet odpisových let, počet odpisových měsíců nebo konečný termín odepisování), program použije pro výpočet odpisové částky následující vzorec:  

*Částka odpisů = ((Účetní hodnota - hodnota záchrany) x Počet dnů odpisů) / Zbývající dny odpisů*  

Zbývající doba odpisování je vypočtena jako počet dnů odpisování mínus počet dnů mezi počátečním datem odpisování a posledním datem vložení dlouhodobého majetku.  

Účetní hodnota může být snížena o zaúčtované zhodnocení, snížení hodnoty, vlastní 1 nebo vlastní 2 částky, v závislosti na tom, zda je v **Include in Depr. Pole Výpočet** je deaktivováno a je aktivováno pole **Část účetní hodnoty** v okně **Nastavení typu účtování DM**.  

Tento výpočet zajišťuje, že dlouhodobý majetek je plně odepsán v den ukončení odpisů.    
### <a name="fixed-yearly-percentage"></a>Pevná roční procentní sazba  
Zadáte-li pevnou roční procentní sazbu, program vypočítá odpisovou část dle následujícího vzorce:  

Částka odpisů = (Přímá % x Odpisovatelný základ x Počet odpisových dní) / (100 x 360)  

### <a name="fixed-yearly-amount"></a>Pevná roční částka  
Pokud zadáte pevnou roční částku, program použije tento vzorec pro výpočet částky odpisů:  

Částka odpisů = (pevná částka odpisů x počet dnů odepisování) / 360  

### <a name="example---straight-line-depreciation"></a>Příklad - Přímé Odpisy
Dlouhodobý majetek má pořizovací cenu 100 000 LM. Odhadovaná doba života je osm let.  

 Dávková úloha **Výpočet odpisů** se provádí dvakrát ročně. Položka knihy dlouhodobého majetku vypadá takto:  

|Datum|Typ zaúčtování DM|Dny|Částka|Účetní hodnota|  
|----------|---------------------|----------|------------|----------------|  
|01/01/10|Pořizovací cena|*|100 000,00|100 000,00|  
|06/30/10|Odpisy|180|-6 250,00|93 750,00|  
|12/31/10|Odpisy|180|-6 250,00|87 500,00|  
|06/30/11|Odpisy|180|-6 250,00|81 250,00|  
|12/31/11|Odpisy|180|-6 250,00|75 000,00|  
|06/30/17|Odpisy|180|-6 250,00|6 250,00|  
|12/31/17|Odpisy|180|-6 250,00|0|  

* Datum zahájení odpisování  

## <a name="declining-balance-1-depreciation"></a>Declining-Balance 1 Odpis
Jedná se o zrychlenou metodu odpisování, která přiděluje největší část nákladů na majetek v prvních letech své životnosti. Používáte-li tuto metodu, musíte zadat pevný roční procentní podíl.  

Program používá pro výpočet odpisů následující vzorec:  

*Částka odpisů = (Declining-Bal. % x počet odpisových dní x Depr. Basis) / (100 x 360)*  

Odpisovatelný základ se vypočítá jako účetní hodnota snížená o zaúčtované odpisy od počátku běžného fiskálního roku.  

Zaúčtovaná částka odpisů může obsahovat položky s různými druhy zaúčtování (odpis, vlastní1 a vlastní2), které byly zveřejněny od data zahájení současného fiskálního roku. Tyto typy zaúčtování jsou zahrnuty v částce zaúčtovaného odpisu, pokud jsou zaškrtnuty značky v poli **Typ odpisování** a v poli **Část účetní hodnoty** v okně **Nastavení typu účtování DM**.  

### <a name="example---declining-balance-1-depreciation"></a>Příklad - Declining-Balance 1 Odpisy
Dlouhodobý majetek má pořizovací cenu 100 000 LM. V poli **Declining-Balance %** je hodnota 25. Dávková úloha  **Výpočet odpisů** se provádí dvakrát ročně. Položky knihy dlouhodobého majetku vypadají takto:  

|Datum|Typ zaúčtování DM|Dny|Částka|Účetní hodnota|  
|----------|---------------------|----------|------------|----------------|  
|01/01/10|Pořizovací cena|*|100 000,00|100 000,00|  
|06/30/10|Odpisy|180|-12 500,00|87 500,00|  
|12/31/10|Odpisy|180|-12 500,00|75 000,00|  
|06/30/11|Odpisy|180|-9 375,00|65 625,00|  
|12/31/11|Odpisy|180|-9 375,00|56 250,00|  
|06/30/12|Odpisy|180|-7 031,25|49 218,75|  
|12/31/12|Odpisy|180|-7 031,25|42 187,50|  
|06/30/13|Odpisy|180|-5 273,44|36 914,06|  
|12/31/13|Odpisy|180|-5 273,44|31 640,62|  
|06/30/14|Odpisy|180|-3 955,08|27 685,54|  
|12/31/14|Odpisy|180|-3 955,08|23 730,46|  

* Datum zahájení odpisování  

 Metoda výpočtu:  

*1. rok: 25% z 100,000 = 25,000 = 12,500 + 12,500*

*2. rok: 25% z 75,000 = 18,750 = 9,375 + 9,375*

*3. rok: 25% z 56,250 = 14,062.50 = 7,031.25 + 7,031.25*

Výpočet pokračuje, dokud účetní hodnota neodpovídá konečnému počtu zaokrouhlení částky nebo hodnotě, kterou zadáte.   

## <a name="declining-balance-2-depreciation"></a>Declining-Balance 2 Odpisy
Declining-Balance 1 metoda a Declining-Balance 2 metoda vypočítá stejnou celkovou částku odpisů za každý rok. Pokud však spustíte dávkovou úlohu **Výpočet odpisů** vícekrát za rok, metoda DB 1 bude mít za následek stejné částky odpisů pro každé období odpisování. Metoda DB 2 na druhé straně bude mít za následek částky odpisů, které klesnou za každé období.  

### <a name="example---declining-balance-2-depreciation"></a>Příklad -  Declining-Balance 2 Odpisy
Dlouhodobý majetek má pořizovací cenu 100 000 LM. V poli **Declining-Balance %** je hodnota 25. Dávková úloha **Výpočet odpisů** se provádí dvakrát ročně. Položky knihy dlouhodobého majetku vypadají takto:  

|Datum|Typ zaúčtování DM|Dny|Částka|Účetní hodnota|  
|----------|---------------------|----------|------------|----------------|  
|01/01/10|Pořizovací cena|*|100 000,00|100 000,00|  
|06/30/10|Odpisy|180|-13 397,46|86 602,54|  
|12/31/10|Odpisy|180|-11 602,54|75 000,00|  
|06/30/11|Odpisy|180|-10 048,09|64 951,91|  
|12/31/11|Odpisy|180|-8 701,91|56 250,00|  

* Datum zahájení odpisování  

Metoda výpočtu:
- BV = účetní hodnota  
- ND = počet dnů odpisování  
- DBP = Declining-balance percent  
- P = DBP/100  
- D = ND/360  

Vzorec pro výpočet odpisových částek je:  

*DA = BV x (1 – (1 –P)<sup>D<sup>*  

Hodnoty odpisování jsou:  

|Datum|Výpočet|  
|----------|-----------------|  
|06/30/10|DA = 100,000.00 x (1 -(1 - 0.25)<sup>0.5<sup>) = 13,397.46|  
|12/31/10|DA = 86,602.54 x (1 - (1 - 0.25)<sup>0.5<sup>) = 11,602.54|  
|06/30/11|DA = 75,000.00 x (1 - (1 - 0.25)<sup>0.5<sup>) = 10,048.09|  
|12/31/11|DA = 64,951.91 x (1 - (1 - 0.25)<sup>0.5<sup>) = 8,701.91|  

## <a name="db1sl-depreciation"></a>DB1/SL Odpis
Výpočet pokračuje, dokud účetní hodnota neodpovídá konečnému počtu zaokrouhlení částky nebo hodnotě, kterou zadáte.

DB1/SL je zkrácená kombinace Declining-Balance 1 a Přímé.  

Dávková úloha **Výpočet odpisů** vypočítá přímou částku a klesající částku zůstatku, ale pouze část větší z obou částek je převedena do deníku.  

Program dokáže zpracovat výpočet klesajícího zůstatku pomocí různých procent.  

Používáte-li tuto metodu, musíte zadat odhadovanou životnost a klesající procentuální zůstatek v okně **Odpisové knihy DM**.  

### <a name="example---db1-sl-depreciation"></a>Například - DB1-SL Odpisy
Dlouhodobý majetek má pořizovací cenu 100 000 LM. V okně **Odpisové knihy DM** pole **Declining-Balance %** obsahuje hodnotu 25 a pole **No. of Depreciation Years** obsahuje hodnotu 8. Dávková úloha **Výpočet odpisů** se provádí dvakrát ročně.  

Položky knihy dlouhodobého majetku vypadají takto:  

|Datum|Typ zaúčtování DM|Dny|Částka|Účetní hodnota|  
|----------|---------------------|----------|------------|----------------|  
|01/01/10|Pořizovací cena|*|100 000,00|100 000,00|  
|06/30/10|Odpisy|180|-12 500,00|87 500,00|  
|12/31/10|Odpisy|180|-12 500,00|75 000,00|  
|06/30/11|Odpisy|180|-9 375,00|65 625,00|  
|12/31/11|Odpisy|180|-9 375,00|56 250,00|  
|06/30/12|Odpisy|180|-7 031,25|49 218,75|  
|12/31/12|Odpisy|180|-7 031,25|42 187,50|  
|06/30/13|Odpisy|180|-5 273,44|36 914,06|  
|12/31/13|Odpisy|180|-5 273,44|31 640,62|  
|06/30/14|Odpisy|180|-3 955,08|27 685,54|  
|12/31/14|Odpisy|180|-3 955,08|23 730,46|  
|06/30/15|Odpisy|180|-3 955,08|19,775.38 SL|  
|12/31/15|Odpisy|180|-3 955,08|15,820.30 SL|  
|06/30/16|Odpisy|180|-3 955,08|11,865.22 SL|  
|12/31/16|Odpisy|180|-3 955,07|7,910.15 SL|  
|06/30/17|Odpisy|180|-3 955,08|3,955.07 SL|  
|12/31/17|Odpisy|180|-3 955,07|0.00 SL|  

* Datum zahájení odpisování  

"SL" po účetní hodnotě znamená, že byla použita přímá metoda.  

Způsob výpočtu:  

1. rok:

*Klesající zůstatková částka: 25% z 100,000 = 25,000 = 12,500 + 12,500*  

*Přímá částka = 100,000 / 8 = 12,500 = 6,250 + 6,250*  

Klesající částka se používá, protože je to větší částka.  

6. rok (2015):  

*Klesající zůstatková částka: 25% z 23,730.46 = 4,943.85= 2,471.92 + 2,471.92*  

*Přímá částka = 23,730.46/3 = 7,910.15 = 3,995.07 + 3,995.08*  

Přímá částka se používá, protože je to větší částka.  

## <a name="user-defined-depreciation"></a>Odpisy definované uživatelem
Program má zařízení, které umožňuje nastavit uživatelem definované metody odpisování.  

Metodu definovanou uživatelem můžete použít v okně **Tabulky odpisů**, kde musíte pro každé období (měsíc, čtvrtletí, rok nebo účetní období) zadat procento odpisů.  

Vzorec pro výpočet odpisových částek je:  

Částka odpisů = (Odpisy % x Počet dnů odpisů x Depr. Basis) / (100 x 360)

### <a name="depreciation-based-on-number-of-units"></a>Odpisy založené na počtu jednotek  
 Tato uživatelsky definovaná metoda může být také použita k odpisování na základě počtu jednotek, například v případě výrobních strojů se stanovenou životností. V okně **Tabulky odpisů** můžete zadat počet jednotek, které lze vytvořit v každém období (měsíc, čtvrtletí, rok nebo účetní období).  

### <a name="to-set-up-user-defined-depreciation-methods"></a>Nastavení uživatelských metod odpisování
V okně **Tabulky odpisů** můžete nastavit uživatelem definované metody odpisování. Například můžete nastavit odpis podle počtu jednotek.  

1. V pravém horním rohu zvolte ikonu **Vyhledat stránku nebo sestavu**, zadejte **Tabulky odpisů** a pak vyberte související odkaz.
2. V okně **Přehled tabulek odpisů** zvolte akci **Nový**.
3. V okně **Karta tabulky odpisů** vyplňte pole podle potřeby. Vyberte pole a přečtěte si krátký popis pole nebo klikněte na odkaz pro další informace.

### <a name="example---user-defined-depreciation"></a>Příklad - Uživatelem definované odpisy
Používáte metodu odpisování, která vám umožňuje rychleji odpisovat majetek pro účely daně z příjmů.  

Pro dlouhodobý majetek s tříletou životností pro daňové účely byste použili následující odpisové sazby:  

1. rok: 25%  

2. rok: 38%  

3. rok: 37%  

Pořizovací cena činí 100 000 LM a odpisovatelná životnost je pět let. Odpisy se vypočítají ročně.  

|Datum|Typ zaúčtování DM|Dny|Částka|Účetní hodnota|  
|----------|---------------------|----------|------------|----------------|  
|01/01/10|Pořizovací cena|*|100 000,00|100 000,00|  
|12/31/10|Odpisy|360|-25 000,00|75 000,00|  
|12/31/11|Odpisy|360|-38 000,00|37 000,00|  
|12/31/12|Odpisy|360|-37 000,00|0|  
|12/31/13|Odpisy|Žádný|Žádný|0|  
|12/31/14|Odpisy|Žádný|Žádný|0|  

* Datum zahájení odpisování  

Používáte-li metodu definovanou uživatelem **First User-Defined Depr. Pole Datum** a **Datum zahájení odpisování** musí být vyplněno v okně **Odpisové knihy DM**. **First User-Defined Depr. Pole Datum** a pole **Délka období** v okně **Tabulky odpisů** se používají k určení časových intervalů, které mají být použity pro výpočty odpisů. Tím je zajištěno, že program začne používat určený procentní podíl ve stejný den pro všechny aktiva. Pole **Datum zahájení odpisování** se používá pro výpočet počtu dnů odpisování.  

V předchozím příkladě v obou **First User-Defined Depr. Pole Datum** a **Datum zahájení odpisování** obsahuje 01/01/01. Pokud ovšem **First User-Defined Depr. Pole Datum** obsahuje 01/01/10 a pole **Datum zahájení odpisování** obsahuje 04/01/11, výsledek bude:  

|Datum|Typ zaúčtování DM|Dny|Částka|Účetní hodnota|  
|----------|---------------------|----------|------------|----------------|  
|01/01/10|Pořizovací cena|*|100 000,00|100 000,00|  
|12/31/10|Odpisy|270|-18 750,00|81 250,00|  
|12/31/11|Odpisy|360|-38 000,00|42 250,00|  
|12/31/12|Odpisy|360|-37 000,00|6 250,00|  
|12/31/13|Odpisy|90|-6 250,00|0|  
|12/31/14|Odpisy|Žádný|Žádný|0|  

* Datum zahájení odpisování

## <a name="half-year-convention-depreciation"></a>Pololetní konverze odpisů   
Metoda Pololetní konverze bude použita pouze tehdy, pokud do políčka **Use Half-Year Convention** umístíte zaškrtávací políčko v okně **Odpisová kniha DM**.  

Tuto metodu odpisování lze použít v souvislosti s následujícími metodami odpisování v programu:  
- Přímá
- Declining-Balance 1
- DB1/SL  

Pokud se použije pololetní konvence, bude mít dlouhodobý majetek v prvním finančním roce šestiměsíční odpisy bez ohledu na obsah pole **Datum zahájení odpisování**.  

**Poznámka**. Odhadovaná životnost dlouhodobého majetku, která zůstane po prvním fiskálním roce, bude vždy obsahovat půl roku s použitím metody pololetní smlouvy. Proto, aby byla metoda půlroční konvence aplikována správně, musí pole **Datum ukončení odpisů** v okně **Odpisová kniha DM** vždy obsahovat datum, které je přesně šest měsíců před konečným datem fiskálního roku, ve kterém se stávající dlouhodobý majetek stane Plně odepsán.  

### <a name="example---half-year-convention-depreciation"></a>Příklad - pololetní konvence odpisů
Dlouhodobý majetek má pořizovací cenu 100 000 LM. **Datum zahájení odpisování** je 03/01/10. Odhadovaná životnost je pět let, takže **Datum ukončení odpisů** musí být 06/30/15. Dávková úloha **Výpočet odpisů** se provádí ročně. Tento příklad je založen na kalendářním fiskálním roce.  

 Položky knihy dlouhodobého majetku vypadají takto:  

|Datum|Typ zaúčtování DM|Dny|Částka|Účetní hodnota|  
|----------|---------------------|----------|------------|----------------|  
|03/01/10|Pořizovací cena|*|100 000,00|100 000,00|  
|12/31/10|Odpisy|270|-10 000,00|90 000,00|  
|12/31/11|Odpisy|360|-20 000,00|70 000,00|  
|12/31/12|Odpisy|360|-20 000,00|50 000,00|  
|12/31/13|Odpisy|360|-20 000,00|30 000,00|  
|12/31/14|Odpisy|360|-20 000,00|10 000,00|  
|12/31/15|Odpisy|180|-10 000,00|0,00|  

* Datum zahájení odpisování  

## <a name="example---db1sl-depreciation-using-half-year-convention"></a>Příklad - Odpisy DB1/SL pomocí pololetní smlouvy  
Dlouhodobý majetek má pořizovací cenu 100 000 LM. **Datum zahájení odpisování** je 11/01/10. Odhadovaná životnost je pět let, takže **Datum ukončení odpisů** musí být 06/30/15. V okně **Odpisové knihy DM** pole **Declining-Balance %** obsahuje 40. Dávková úloha **Výpočet odpisů** se provádí ročně. Tento příklad je založen na kalendářním fiskálním roce.  

Položky knihy dlouhodobého majetku vypadají takto:  

|Datum|Typ zaúčtování DM|Dny|Částka|Účetní hodnota|  
|----------|---------------------|----------|------------|----------------|  
|11/01/10|Pořizovací cena|*|100 000,00|100 000,00|  
|12/31/10|Odpisy|60|-20 000,00|80 000,00|  
|12/31/11|Odpisy|360|-32 000,00|48 000,00|  
|12/31/12|Odpisy|360|-19 200,00|28 800,00|  
|12/31/13|Odpisy|360|-11 520,00|17 280,00|  
|12/31/14|Odpisy|360|-11 520,00|5,760.00 SL|  
|12/31/15|Odpisy|180|-5 760,00|0.00 SL|  

 * Datum zahájení odpisování  

"SL" po účetní hodnotě znamená, že byla použita přímá metoda.  

Způsob výpočtu:  

1. rok:  

*Snížená částka = celková roční částka = 40% ze 100 000 = 40 000. Tedy za půl roku 40 000/2 = 20 000*  

*Přímá částka = celková roční částka = 100 000/5 = 20 000. Tedy za půl roku = 20 000/2 = 10 000*  

Klesající částka se používá, protože je to větší částka.  

5. Rok (2004):  

*Klesající částka = 40% z 17 280 000 = 6 912,00*  

*Přímá částka = 28,800 / 1.5 = 11,520.00*  

Použije se přímá částka, protože se jedná o větší částku.

## <a name="duplicating-entries-to-more-depreciation-books"></a>Kopírování položek do dalších odpisových knih
Pokud máte tři odpisové knihy B1, B2 a B3 a chcete duplikovat položky z B1 na B2 a B3, můžete zaškrtnout políčko **Část seznamu duplikací** na kartách odpisů pro B2 a B3. To může být užitečné, pokud je odpisová kniha B1 integrována s hlavní knihou a používá finanční deník dlouhodobého majetku a odpisové knihy B2 a B3, které nejsou integrovány do hlavní knihy a používají deník dlouhodobého majetku.  

Při zadání položky v B1 ve finančním deníku dlouhodobého majetku a zaškrtnutí do pole **Použití seznamu duplikací** program duplikuje záznam v knize B2 a B3 v deníku dlouhodobého majetku, když je záznam zaúčtován.  

**Poznámka**: Není možné duplikovat ve stejném deníku a dávku deníku, jakou jste zkopírovali. Pokud zaúčtujete položky dlouhodobého majetku ve finančním deníku, můžete je duplikovat v deníku dlouhodobého majetku nebo ve finančním deníku dlouhodobého majetku pomocí jiné dávky.  

**Poznámka**: Stejné číselné řady nelze použít ve finančním deníku dlouhodobého majetku a deníku dlouhodobého majetku. Při zaúčtování položek do finančního deníku dlouhodobého majetku musíte nechat pole **Číslo dokumentu** prázdné . Zadáte-li číslo do pole, program duplikuje číslo do deníku dlouhodobého majetku a nemůžete zaúčtovat deník, pokud ručně nezměníte číslo dokumentu.     

## <a name="see-also"></a>Viz také
[Správa dlouhodobého majetku](fa-manage.md)  
[Nastavení dlouhodobého majetku](fa-setup.md)  
[Finance](finance-setup.md)  
[Vítejte v Dynamics NAV](across-get-started.md)

