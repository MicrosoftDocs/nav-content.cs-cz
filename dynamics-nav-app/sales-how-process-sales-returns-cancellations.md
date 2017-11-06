---
title: "Použití Prodejních dobropisů ke zpracování prodejních vratek a zrušení"
description: "Popisuje jak vytvořit prodejní dobropis, přímo skrz objednávku prodejní vratky ke zpracování vrácení, zrušení nebo náhrady za zboží, za které jste obdrželi platby."
author: SorenGP
ms.prod: dynamics-nav-2017
ms.topic: article
ms.devlang: na
ms.tgt_pltfrm: na
ms.workload: na
ms.search.keywords: undo, credit memo, return
ms.date: 09/08/2016
ms.author: sgroespe
ms.translationtype: HT
ms.sourcegitcommit: 4fefaef7380ac10836fcac404eea006f55d8556f
ms.openlocfilehash: a6732bba66601946e3b0a6b705be233a10bafcb9
ms.contentlocale: cs-cz
ms.lasthandoff: 10/16/2017

---
# <a name="how-to-process-sales-returns-or-cancellations"></a>Návod: Proces prodejní vratky nebo zrušení
Pokud váš zákazník chce vrátit nebo získat náhradu za zboží a služby, které jste mu prodali a obdrželi jste platbu, musíte vytvořit a zaúčtovat prodejní dobropis, který specifikuje požadovanou změnu. Chcete-li zahrnout správné fakturační informace o prodeji, můžete si vytvořit prodejní dobropis ze zaúčtované prodejní faktury nebo použít vytvořit nový prodejní dobropis se skopírovanými údaji z faktury.

Pokud budete potřebovat větší kontrolu nad procesem vrácení, například dokumenty manipulace skladu nebo mít lepší přehled při přijímání vrácených položek z více prodejních dokladů, můžete vytvořit prodejní  objednávku vratky. Objednávka prodejní vraty automaticky řeší související prodejní dobropis nebo ostatní dokumenty pro vrácení, například objednávka prodejní náhrady. Pro více informací bežte do sekce „Vytváření objednávek vratky založené na jednom nebo více účtovaných prodejních dokladech“.

> [!NOTE]  
>   Pokud ještě nebyla prodejní faktura zaplacená, můžete použít funkce **Opravit** nebo **Zrušit** na účtovaných prodejních fakturách k automatickému vrácení transakce. Tato funkce funguje pouze na nezaplacených fakturách a také nepodporuje částečné vrácení nebo zrušení. Další informace naleznete v tématu [Návod: Opravit nebo zrušit nezaplacené prodejní faktury.](sales-how-correct-cancel-sales-invoice.md)

Vrácení nebo refundace se mohou týkat pouze některého zboží nebo služeb na původní prodejní faktuře. V takovém případě musíte upravit údaje na řádcích v prodejním dobropisu nebo objednávce prodejní vratky. Když zaúčtujete prodejní dobropis, objednávka prodejní vratky a prodejní doklady, které jsou touto změnou ovlivněny, jsou zrušeny a pro zákazníka může být vytvořena platba na vrácení peněz. Další informace naleznete v tématu: [Provést platby](payables-make-payments.md).  

Kromě původní účtované prodejní faktury, můžete použít prodejní dobropis na prodejní dokumenty, například na jinou účtovanou prodejní fakturu, protože zákazník také vrací položky dodané s touto fakturou.

Můžete zákazníkovi odeslat účtovaný prodejní dobropis za účelem potvrzení vrácení nebo zrušení a sdělit mu, že příslušná částka bude uhrazena. Například za zboží, které vrátil.

Účtováni dobropisu také vrátí všechny poplatky za zboží, které byly připojeny na účtovaný dokument, takže hodnota položek zboží je stejná jako předtím, než bylo zboží přiřazeno.

## <a name="inventory-costing"></a>Zásoby a ocenění
K zachování správného ocenění zásob, obvykle chcete zaskladnit zboží na skladu za jednotkové náklady za které byly zakoupeny, nikoliv za jejich současní jednotkové náklady. Toto je označováno jako přesné vrácení nákladů.

Existují dvě funkce k automatickému přiřazení přesné vrácení nákladů.   

|Funkce|Popis|  
|------------------|---------------------------------------|  
|Funkce **Získat účt. řádky pro stornování** v okně **Prodejní objednávka vratky**|Kopíruje řádky jednoho nebo více účtovaných dokumentů, které mají být vráceny pomocí objednávky prodejní vratky Pro více informací běžte do sekce „Vytváření prodejních objednávek vratky založené a příslušného prodejního dobropisu zaleženého na jedné nebo více účtovaných prodejních fakturách“.|  
|Funkce **Kopírovat doklad** v oknech **Objednávka prodejní vratky** a **Prodejní dobropis**.|Kopie obou hlaviček a řádků z jednoho účtovaného dokumentu, který má být vrácen.<br /><br /> Vyžaduje, že check box **Nutné vrác.přesn.nákladů** v okně **Prodej a závazky**.|

Pro ruční přiřazení přesné reverzace nákladů musíte zvolit políčko **Vyrovnat položkou zboží** na jakémkoli řádku dokumentu pro vrácení a vybrat číslo originální prodejní položky. Toto propojí prodejní dobropis nebo objednávku vratky k původní prodejní položce a zajistí, že zboží je hodnoceno původními náklady.

Další informace naleznete v tématu [Návrh detailů Zásoby a ocenění](design-details-inventory-costing.md)

## <a name="to-create-a-sales-credit-memo-from-a-posted-sales-invoice"></a>Vytvoření prodejního dobropisu z účtované prodejní faktury
1. Zvolte ikonu ![Vyhledat stránku nebo sestavu](media/ui-search/search_small.png "Ikona Vyhledat stránku nebo sestavu"), zadejte **Účtované prodejní faktury** a vyberte související odkaz.  
2. V okně **Účtované prodejní faktury** vyberte účtovanou fakturu, kterou chcete vrátit, a vyberte tlačítko **Vytvořit opravný dobropis**.

    Hlavička prodejního dobropisu bude obsahuje údaje z účetované prodejní faktury. Toto můžete editovat, například nové informace reflektující na vrácení.  
3. Upravte informace na řádcích vzhledem k dohodě, jako je počet položek vráceného zboží nebo částku, jaká má být vrácena.
4. Zvolte akci **Vyrovnat položky**.
5. V okně **Vyrovnat položky zákazníka** vyberte řádky s účtovanými dokumenty, které chcete použít na prodejní dobropis a poté zvolte **ID vyrovnání**.

    Indetifikátor prodejního dobropisu je vložen do políčka **ID vyrovnání**.
6. V poli **Částka k vyrovnání** vložte částku, kterou chce vyrovnat pokud je menší než původní částka.  

    V dolní části okna **Vyrovnat položky zákazníka** můžete vidět celkový součet k částky k vyrovnání všech položek, jmenovitě, pokud políčko **Zůstatek** je nulové.
7. Zvolte tlačítko **OK**. Pokud účtujete prodejní dobropis, bude se vztahovat na účtované prodejní dokumenty.

    Po vytvoření nebo upravě potřebných řádků prodejního dobropisu a jsou určena jednoduchá nebo násobná vyrovnání, můžete pokračovat v procesu účtování prodejního dobropisu.   
8. Vyberte tlačítko **Účtovat a Odeslat**.  

Zobrazí se dialogové okno **Potvrzení účtování a odeslání** s uvedením preferovaného způsobu odeslání zákazníkovi. Způsob odesílání můžete změnit výběrem vyhledávacího tlačítka pro pole **Odeslat dokument do**. Další informace naleznete v tématu [Návod: Nastavení profilů odesílaného dokladu.](sales-how-setup-document-send-profiles.md)  

Účtované prodejní dokumenty, na které jste vytvořili prodejní dobropis, jsou nyní stornovány a platba vrácení peněz může být vytvořena. Prodejní dobropis je smazán a nahrazen novým dokumentem v seznamu účtovaných prodejních dobropisů.

## <a name="to-create-a-sales-credit-memo-by-copying-a-posted-sales-invoice"></a>Vytvoření prodejního dobropisu z kopírováním účtované prodejní faktury
1. Zvolte ikonu ![Vyhledat stránku nebo sestavu](media/ui-search/search_small.png "Ikona Vyhledat stránku nebo sestavu"), zadejte **Prodejní dobropisy** a vyberte související odkaz.
2. Zvolte tlačíko **Nový** k otevření prázdného prodejního dobropisu.
3. V políčku **Zákazník** napište jméno existujícího zákazníka.
4. Vyberte tlačítko **Kopírovat doklad**.
5. V okně **Kopie prodejního dokladu** v poli **Typ dokladu** vyberte **Účtované faktury**.
6. Vyberte políčko **Číslo dokladu** k otevření **Účtované prodejní faktury** a potom vyberte zaúčtovanou prodejní fakturu, která obsahuje řádky, které chcete vrátit zpět.
7. Zaškrtněte políčko **Přepočítat řádky** pokud chcete, aby řádky účtované prodejní faktury byly aktualizovány s jakoukoli změnou ceny položky a jednotkovými náklady od účtování faktury.
8. Zvolte tlačítko **OK**. Zkopírované řádky faktury jsou vloženy do prodejního dobropisu.
9. Dokončete dobropis, tak jak je vysvětleno v „Vytvoření prodejního dobropisu z účtované prodejní faktury“.

## <a name="to-create-a-sales-return-order-based-on-one-or-more-a-posted-sales-documents"></a>Vytvoření Prodejní objednávky vratky založené na jednom nebo více účtovaných dokladech
1. Zvolte ikonu ![Vyhledat stránku nebo sestavu](media/ui-search/search_small.png "Ikona Vyhledat stránku nebo sestavu"), zadejte **Objednávky prodejní vratky** a vyberte související odkaz.
2. Vyberte akci **Nový**.  
3. Vyplňte políčka na v záložce **Obecné** jak je potřeba.
4. Na záložce **Řádky** vyplňte řádky ručně nebo nakopírujte automaticky do řádků z ostatních dokumentů.

    - Použijte funkci **Získat účt. řádky pro stornování** ke kopírování jednoho nebo více účtovaných řádků z jednoho nebo několika účtovaných dokladů. Tato funkce vždy přesně vrátí náklady z účtováného řádku. Tato funkce je popsána v následujících krocích.    
    - Použijte funkci **Kopírovat doklad** ke zkopírování existujícího dokladu k vrácení objednávky. Tuto funkci použijte ke zkopírování celého dokladu. Může být to být také účtovaný doklad nebo nezaúčtovaný. Tato funkce pouze povoluje přesné vracení nákladů pokud je pole **Nutné vrác.přesn.nákladů** je zatrhnuté v okně **Nastavení prodeje a pohledávek**.  

5. Zvolte akci **Získat účt. řádky pro stornování**.
6. V horní části okna **Účtované řádky prodejního dokladu** vyberte zaškrtávací políčko **Zobrazit pouze vratné řádky** k zobrazení řádků obsahující množství, které ještě nebylo vráceno. Například, pokud bylo množství z účtované prodejní faktury již vráceno, tak pravděpodobně právě toto množství nebudete chtít zahrnou do nového dokumentu k vrácení.

    > [!NOTE]  
    >  Toto pole funguje pouze pro účtované dodávky a účtované řádky faktur, nikoli pro vratky nebo účtované prodejní dobropisy.

    Na levé straně okna, jsou zobrazeny různé typy dokladů a čísla v závorkách zobrazují počet dostupných dokladů pro každý typ dokladu.

7. V poli **Filtr typů dokladů** vyberte typ účtovaného řádku dokladu, který chcete použít.  
8. Vyberte řádky které chcete kopírovat do nového dokadu.  

    > [!NOTE]  
    >  Pokud použijete Ctrl + A k výběru řádku, budou zkopírovány všechny řádky, ale filtr **Zobrazit pouze zbývající množství** bude ignorován. Například, předpokládejme, že jste filtrovali řádky na určité číslo dokumentu s dvěma řádky, z nichž jeden byl již vrácen. Pokud je dokonce vybráno pole **Zobrazit pouze zbývající množství** a když zmáčknete Ctrl+A ke kopírování řádků, oba řádky budou zkopírovány místo jednoho, který nebyl vrácen.  

9. Zvolte tlačítko **OK** ke zkopírování řádků do nového dokumentu.  

    Dochází k následujícím procesům:  

    -   Pro účtované řádky dokladů typu **Zboží** je vytvořen nový řádek, který je zkopírován z účtovaného dokladu s množstvím, které ještě nebylo vráceno. V poli **Vyrovnat položkou zboží** je vyplněno odpovídajícím číslem položky zboží z účtovaného řádku dokladu.  

    -   Pro účtované řádky, které nejsou typu **Zboží**, jako jsou poplatky se nový řádek dokladu vytvoří jako kopie původního účtovaného řádku dokladu.  

    -   Výpočet pole **Pořizovací cena**na novém řádku z nákladů na příslušné položky hlavní knihy.  

    -   Pokud je kopírovaným dokladem účtovaná dodávka, účtovaná příjemka, účtovaná výdejka, nebo účtovaná vratka dodávky, jednotková cena se automaticky vypočítává z karty zboží.  

    -   Pokud je kopírovaný doklad účtovaná faktura nebo dobropis, pořizovací cena, fakturační slevy a řádková sleva je také zkopírována.  

    -   Jestliže účtovaný dokument obsahuje řádky se sledováním zboží, pole **Vyrovnat položkou zboží** je na řádku sledování zboží vyplněno na příslušnou položkou zboží a číslem z řádků sledování zboží.  

     Při kopírování z účtované faktury nebo účtovaného dobropisu, program zkopíruje relevantní fakturační slevy a řádkové slevy jako platné k datu zaúčtování, tak že je řádek účtovaného dokladu překopírován do nového dokumentu. Dávejte pozor,** pokud možnost Výpočet fakturační slevy** aktivovaný v okně **Nastavení Prodeje a pohledávek**, potom bude fakturační sleva nově vypočítaná, pokud zaúčtujete nový řádek dokladu. Částka na řádku může být odlišná pro nový řádek z účtovaného dokladu, záleží na novém výpočtu fakturační slevy.  

     > [!NOTE]  
     >  Pokud byla část množství na řádku již vrácena, prodána nebo spotřebována, řádek je vytvořen pouze pouze pro množství zbývajícího množství zásob nebo které bylo vráceno. Pokud je jíž celé množství na řádku účtovaném dokumentu vráceno, nový dokument se nevytvoří.  
     >   
     >  Pokud je tok zboží v účtovaném dokladu stejný jako tok zboží v novém dokladu, vytvoří se v novém dokladu kopie původního řádku účtovaného dokladu. Pole **Vyrovnat položkou zboží** není vyplněno v případě, kdy přesné vrácení nákladu není možné. Například, pokud použijete funkci **Získat účt. řádky pro stornování** k získání řádků účtovaných prodejních dobropisů pro nové dobropisy. Původní řádky dobropisu jsou zkopírovány do nového dobropisu.  

10. V okně **Objednávka prodejní vratky** v poli **Kód příčiny vratky** na každém řádku vyberte důvod vratky.
11. Zvolte akci **Zaúčtovat**.

## <a name="to-create-a-replacement-sales-order-from-a-sales-return-order"></a>Vytvoření náhrady prodejní objednávky z prodejní objednávky vratky
Možná se rozhodnete kompenzovat zákazníkovi za zboží které jste mu prodali jiným zbožím Můžete udělat nahrazení stejným nebo jiným zbožím. Tato situace může nastat špatným odesláním zboží k jinému zákazníkovi.  

1. Pro aktivní proces vratky v okně **Objednávka prodejní vratky** udělejte negativní položky na výměnu vložením záporného počtu v poli **Množství**.  
2. Vyberte tlačítko **Přesunout záporné řádky**.
3. V okně **Přesun záporných prod.řádků** vyplňte pole podle potřeby.
4. Zvolte tlačítko **OK**. Záporné řádky za nahrazení zboží jsou vymazány z objednávek prodejní vratky a místo toho jsou vloženy do okna **Prodejní objednávky**. Další informace naleznete v tématu [Návod: Prodávání produktů](sales-how-sell-products.md)

## <a name="to-create-return-related-documents-from-a-sales-return-order"></a>Vytvoření vratky souvisejících dokladů z prodejní objednávky vratky
Můžete mít náhradu prodejní objednávky, objednávku prodejní vratky a náhradu nákupní objednávky vytvořenou automaticky v procesu prodejní vratky. Toto je užitečné, například v situaci, kdy potřebujete manipulovat se zbožím se zárukou poskytované dodavatelem.

1. V okně **Objednávka prodejní vratky** pro aktivní proces vrácení, zvolte akci **Přesun záporných prod.řádků**.
2. V poli **Číslo Dodavatele** vložte číslo dodavatele, pokud se nedoplní automaticky
3. Pokud vracíte zboží, musíte ho vrátit dodavateli, zvolte** Check box Vytvořit nák.obj.vratky**.
4. Pokud vracíte zboží, musíte ho vrátit dodavateli, zvolte **Vytvořit nákupní objednávku**.
5. Pokud prodejní objednávka nahrazení je vytvořena, zvolte check box **Vytvořit prodejní objednávku**.

## <a name="to-create-a-restock-charge"></a>Vytvoření poplatku zaskladnění
Můžete účtovat poplatek vašemu zákazníkovi za zasekladnění k pokrytí manipulace při vracení zboží. K tomu může dojít, pokud zákazník nesprávně objednal nesprávný předmět nebo změnil názor po obdržení položky, kterou jste prodali.

Můžete zaúčtovat tuto zvýšenou platbu jako poplatek za zboží na nákupním dobropisu a spojit ho s účtovanou dodávkou. Následující popis je o Objednávce prodejní vratky, současně můžete aplikovat tyto kroky na prodejní dobropisy.

1. Otevřete okno **Objednávky prodejní vratky** pro aktivaci procesu vrácení.
2. Na řádku v poli **Typ** vyberte **Poplatek**.  
3. Vyplňte pole pro každý řádek poplatku zboží. Další informace naleznete v tématu [Návod: Použití poplatku za položku pro účtování dodatečných obchodních nákladů.](payables-how-assign-item-charges.md)  

Když chcete účtovat objednávku prodejní vratky, poplatek připojen k odpovídající částce položky. Tímto způsobem můžete zachovat přesné ocenění zásob.  

## <a name="to-create-a-sales-allowance"></a>Vytvoření příspěvku na Prodej
Můžete poslat zákazníkovi dobropis se sníženou cenou, pokud zákazník obdržel poničené zboží, nebo ho dostal pozdě.  
Můžete zaúčtovat tuto sníženou cenu jako poplatek za zboží na  dobropisu a spojit ho s účtovanou dodávkou. Následující popis je o prodejním dobropisu, současně můžete aplikovat tyto kroky na objednávce prodejní vratky.

1. Zvolte ikonu ![Vyhledat stránku nebo sestavu](media/ui-search/search_small.png "Ikona Vyhledat stránku nebo sestavu"), zadejte **Prodejní dobropisy** a vyberte související odkaz.
2. Zvolte tlačítko **Nový** k otevření prázdného prodejního dobropisu.
3. Vyplňte hlavičku dobropisu se souvisejícími informacemi o zákazníkovi, kterému chcete dát příspěvek na prodej.  
4. Na záložce **Řádky** v poli **Typ** vyberte **Poplatek**.  
5.  Do pole **Číslo** Vyberte příslušný poplatek za zboží.  
     Pokud budete chtít můžete vytvořit speciální číslo poplatku za zboží k pokrytí příspěvku na prodej.  
6.  Do pole **Množství** zadejte **1**.  
7.  Do pole **Jednotková cena** vložte částku příspěvku na prodej.  
8.  Připsání příspěvku na prodej jako poplatek za zboží k položce v účtované dodávce. Další informace naleznete v tématu [Návod: Použití poplatku za položku pro účtování dodatečných obchodních nákladů.](payables-how-assign-item-charges.md) Pokud jste přiřadili příspěvek, vraťte se na okno **Prodejní dobropis**.  

Když chcete účtovat objednávku prodejní vratky, příspěvek na prodej je připojen k odpovídající částce položky. Tímto způsobem můžete zachovat přesné ocenění zásob.

## <a name="to-combine-return-receipts"></a>Kombinování příjemek vratek
Můžete kombinovat prodejní vratku pokud zákazník vrátí několik položek, které jsou pokryty různými objednávkami.  

Když obdržíte zboží do vašeho skladu, zaúčtujete související objednávky jako obdržené. Tento krok vytvoří účtovanou příjemku vratky  

Když jste připraveni fakturovat tohoto zákazníka, namísto jednotlivé fakturace jednotlivých objednávek prodejních vratek, můžete prodejní dobropisy automaticky zkopírovat účtované řádky příjemku vratky do tohoto dokladu. Potom můžete účtovat prodejní dobropisy a výhodně fakturovat všechny otevřené objednávky prodejních vratek ve stejný čas.  

Pro kombinování příjemek vratek musí být zatržené políčko **Kombinovat dodávky** v okně **karta zákazníka**.  

### <a name="to-manually-combine-return-receipts"></a>Manuální kombinování příjemek vratek  

1. Zvolte ikonu ![Vyhledat stránku nebo sestavu](media/ui-search/search_small.png "Ikona Vyhledat stránku nebo sestavu"), zadejte **Prodejní dobropisy** a vyberte související odkaz.  
2. Vyberte akci **Nový**.
3. Na záložce s náhledem **Obecné** vyplňte pole podle potřeby.  
4. Zvolte akci **Kopie řádků příjemky vratky**.  
5. Vyberte několik řádků dodávky vratky, které chcete zahrnou do dobropisu.  

    -   K vložení všech řádku, vyberte všechny řádky a zvolte tlačítko **OK**.  

    -   K vložení specifických řádků, vybrte řádky a klikněte na **OK**.  

6.  Pokud jste vybrali špatný řádek prodejní vratky nebo chcete začít znovu, můžete jednoduše smazat řádek na prodejním dobropisu a potom použít znovu **Kopie řádků příjemky vratky**.  
7.  Zaúčtujte fakturu  

### <a name="to-automatically-combine-return-receipts"></a>Tím se automaticky kombinuje příjemka vratky.  
Můžete automaticky kombinovat příjemky vratek a mít možnost automatického účtování dobropisů pomocí funkce **Kombinace příjemek vratky**.  

1.  Zvolte ikonu ![Vyhledat stránku nebo sestavu](media/ui-search/search_small.png "Ikona Vyhledat stránku nebo sestavu"), zadejte **Kombinace příjemek vratky** a vyberte související odkaz.
2. V okně **Kombinace příjemek vratky** vyplňte políčka k souvisejícím příjemkám vratky.
3. Zvolte check box **Účtovat dobropis**. Pokud ne, budete muset zaúčtovat manuálně udělat manuálně
4.  Zvolte tlačítko **OK**.  

### <a name="to-remove-a-received-and-invoiced-return-order"></a>Odebrání přijaté a účtované příjemky vratky  
Když zaúčtujete příjemku vratky tímto způsobem, vratka, z které byly zaúčtovány přijemky vratky a stále existuje, můžete ji plně přijmout a smazat.   

Pokud jsou vratky kombinovány na dobropisu a jsou účtovány, tak účtované Prodej dobropisy jsou vytvořeny z těchto řádků Pole **Fakturované množství** na původní objednávce prodejní vratky je aktualizováno na základě faktorovaného množství.   
1.  Zvolte ikonu ![Vyhledat stránku nebo sestavu](media/ui-search/search_small.png "Ikona Vyhledat stránku nebo sestavu"), zadejte **Odstranit fakt. obj. prod. vratky...** a vyberte související odkaz.  
2.  Specifikujte v poli **Číslo** , z které má být smazána.  
3.  Zvolte tlačítko **OK**.  

Případně můžete ručně vymazat jednotlivé objednávky prodejní vratky.   

## <a name="see-also"></a>Viz také
[Prodej](sales-manage-sales.md)  
[Nastavení prodeje](sales-setup-sales.md)  
[Návod: Odesílání dokladů e-mailem](ui-how-send-documents-email.md)  
[Práce s [!INCLUDE[d365fin](includes/d365fin_md.md)]](ui-work-product.md)

