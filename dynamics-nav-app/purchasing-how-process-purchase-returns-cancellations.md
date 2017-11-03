---
title: "Použití nákupního dobropisu k procesu vrácení nebo zrušení"
description: "Téma vystvětlu jak vytvořit a účtovat nákupní dobropis, když chcete vrátit zboží dodavateli a zrušit nákupní proces."
documentationcenter: 
author: SorenGP
ms.prod: dynamics-nav-2017
ms.topic: article
ms.devlang: na
ms.tgt_pltfrm: na
ms.workload: na
ms.search.keywords: cancel, undo, correct
ms.date: 08/03/2017
ms.author: sgroespe
ms.translationtype: HT
ms.sourcegitcommit: 4fefaef7380ac10836fcac404eea006f55d8556f
ms.openlocfilehash: 3f0c187e2cd2520854fe69f3896f6d7311cdc2da
ms.contentlocale: cs-cz
ms.lasthandoff: 10/16/2017

---
# <a name="how-to-process-purchase-returns-or-cancellations"></a>Návod: Zpracování vratek nebo zrušení nákupů
Pokud chcete vrátit položky dodavateli nebo zrušit zakoupené služby, můžete vytvořit a zaúčtovat nákupní dobropis, který specifikuje požadovanou změnu ve vztahu k původní nákupní faktuře. Chcete-li zahrnout správné fakturační informace o nákupu, můžete si vytvořit nákupní dobropis ze zaúčtované nákupní faktury nebo použít vytvořit nový nákupní dobropis se skopírovanými údaji z faktury.

Pokud budete potřebovat větší kontrolu nad procesem vrácení, například dokumenty manipulace skladu nebo mít lepší přehled při přijímání vrácených položek z více nákupních dokladů, můžete vytvořit nákupní objednávku vratky. Nákupní objednávka vratky automaticky řeší vystavuje příslušný nákupní dobropis. Pro více informací bežte do sekce „Vytváření objednávek vratky založené na jednom nebo více účtovaných prodejních dokladech“.

> [!NOTE]  
>   Pokud ještě nebyla nákupní faktura zaplacená, můžete použít funkce **Opravit** nebo **Zrušit** na účtovaných nákupních fakturách k automatickému vrácení dané transakce.  Tato funkce funguje pouze na nezaplacených fakturách a také nepodporuje částečné vrácení nebo zrušení. Další informace naleznete v tématu [Návod: Opravit nebo zrušit nezaplacené nákupní faktury](purchasing-how-correct-cancel-unpaid-purchase-invoices.md)

Obvykle vytvoříte nákupní dobropis nebo objednávku vratky v reakci na dobropis, který vám byl zaslán dodavatelem. Funkce nákupního dobropisu nebo objednávky vratkyje jako interní dokumentace pro vaše účetní účely nebo pro kontrolu přepravy zainteresovaných položek.

Změna se může týkat všech produktů na původní nákupní faktuře nebo pouze některých produktů. V důsledku toho můžete částečně vrátit přijaté položky nebo požadovat částečnou úhradu přijatých služeb. V tomto případě, musítě upravit inforace na nákupním dobropisu nebo nákupní objednávce vratky.

Kromě původní zaúčtované nákupní faktury můžete vyrovnat nákupní dobropis nebo objednávku vratky na jiné nákupní doklady například další zaúčtovanou nákupní fakturu, protože také vracíte položky dodané s touto fakturou.

Účtováni dobropisu také vrátí všechny poplatky za zboží, které byly připojeny na účtovaný dokument, takže hodnota položek zboží je stejná jako předtím, než bylo zboží přiřazeno.

## <a name="inventory-costing"></a>Zásoby a ocenění
K zachování správného ocenění zásob, obvykle chcete vyskladnit zboží ze skladu za jednotkové náklady za které byly zakoupeny, nikoliv za jejich současní jednotkové náklady. Toto je označováno jako přesné vrácení nákladů.

Existují dvě funkce k automatickému přiřazení přesné vrácení nákladů.  

|Funkce|Popis|  
|------------------|---------------------------------------|  
|Funkce **Získat účt. řádky pro stornování** v okně **Nákupní objednávka vratky**|Kopíruje řádky jednoho nebo více účtovaných dokumentů, které mají být vráceny pomocí objednávky prodejní vratky Pro více informací běžte do sekce „Vytváření objednávek vratky založené a příslušného dobropisu zaležených na jedné nebo více účtovaných nákupních fakturách“.|  
|Funkce **Kopírovat doklad** v oknech **Objednávka nákupní vratky** a **Nákupní dobropis**.|Kopie obou hlaviček a řádků z jednoho účtovaného dokumentu, který má být vrácen.<br /><br /> Vyžaduje, že check box **Nutné vrác.přesn.nákladů** v okně **Nákupy a závazky**.|

Pro ruční přiřazení přesné reverzace nákladů musíte zvolit políčko **Vyrovnat položkou zboží** na jakémkoli řádku dokumentu pro vrácení a vybrat číslo originální nákupní položky. Toto propojí nákupní dobropis nebo objednávku vratky k původnímu nákupní položce nákupu prodeje a zajistí, že zboží je hodnoceno původními náklady.

Další informace naleznete v tématu [Návrh detailů Zásoby a ocenění](design-details-inventory-costing.md)

## <a name="to-create-a-purchase-credit-memo-from-a-posted-purchase-invoice"></a>Vytvoření nákupního dobropis ze zaúčtované nákupní faktury
1. Zvolte ikonu ![Vyhledat stránku nebo sestavu](media/ui-search/search_small.png "Ikona Vyhledat stránku nebo sestavu"), zadejte **Účtované nákupní faktury** a vyberte související odkaz.  
2. V okně **Zaúčtované nákupní faktury** vyberte fakturu za nákup, kterou chcete vrátit zpět a poté vyberte akci **Vytvořit opravný dobropis**.

    Většina polí v záhlaví nákupního dobropisu je vyplněna informacemi ze zaúčtované nákupní faktury. Můžete upravit všechna pole například s novými informacemi, které odrážejí dohodu o vrácení.
3. Upravte informace o řádcích podle dohody například počet vrácených položek nebo částku, která má být vrácena.
4. Zvolte akci **Vyrovnat položky**.
5. V okně **Vyrovnat položky dodavatele** vyberte řádek se zaúčtovaným nákupním dokladem, na který chcete vyrovnat nákupní dobropis a poté vyberte akci **ID vyrovnání**. Číslo nákupního dobropisu se vloží do pole **ID vyrovnání**.
6. Do pole **Částka k vyrovnání** zadejte částku, kterou chcete vyrovnat, pokud je menší než původní částka.

    V dolní části okna **Vyrovnat položky dodavatele** můžete vidět celkovou částku, která má být použita k převedení všech zahrnutých položek a to v případě, že hodnota v poli **Zůstatek** je nula.
7. Zvolte tlačítko **OK**. Když zaúčtujete nákupní dobropis, bude vyrovnán na určené zaúčtované nákupní dokumenty.

    Když jste vytvořili nebo upravili řádky potřebného nákupního dobropisu a jsou specifikovány jednotlivé nebo více aplikací, můžete pokračovat v zaúčtování nákupního dobropisu.
8. Zvolte akci **Zaúčtovat**.

Zaúčtované nákupní faktury, na které vyrovnáte dobropis, jsou nyní zrušeny. Pokud jste již zaplatili původní fakturu, dodavatel by vám nyní měl vrátit platbu. Pokud je dobropis pouze pro část produktu na původní faktuře, můžete zaplatit zbývající částku pouze v původní nákupní faktuře.

Nákupní dobropis je odstraněn a nahrazen novým dokladem v seznamu zaúčtovaných dobropisů.

## <a name="to-create-a-purchase-credit-memo-by-copying-a-posted-purchase-invoice"></a>Vytvoření nákupního dobropisu kopírováním ze zaúčtované nákupní faktury
1. Zvolte ikonu ![Vyhledat stránku nebo sestavu](media/ui-search/search_small.png "Ikona Vyhledat stránku nebo sestavu"), zadejte **Nákupní dobropisy** a vyberte související odkaz.
2. Chcete-li otevřít nový prázdný nákupní dobropis, zvolte akci **Nový**.
3. Do pole **Dodavatel** zadejte název existujícího dodavatele.
4. Zvolte akci **Kopírovat doklad**.
5. V okně **Kopírovat nákupní doklad** v poli **Typ dokumentu** vyberte **Účtovaná faktura**.
6.  Vyberte políčko **Číslo dokladu** k otevření **Účtované nákupní faktury** a potom vyberte zaúčtovanou nákupní fakturu, která obsahuje řádky, které chcete vrátit zpět.
7. Zaškrtněte políčko **Přepočítat řádky**, pokud chcete, aby byly kopírované řádky zaúčtované nákupní faktury aktualizovány s jakýmikoliv změnami v ceně zboží a jednotkových cenách od zaúčtované faktury.
8. Zvolte tlačítko **OK**. Zkopírované řádky faktur jsou vloženy do nákupního dobropisu.
9. Dokončete nákupní dobropis, jak je vysvětleno v části "Vytvoření nákupního dobropisu ze zaúčtované nákupní faktury" v tomto tématu.

## <a name="to-create-a-purchase-return-order-based-on-one-or-more-a-posted-purchase-documents"></a>Vytvoření nákupní objednávky vratky založené na jednom nebo více účtovaných dokumentech
1. Zvolte ikonu ![Vyhledat stránku nebo sestavu](media/ui-search/search_small.png "Ikona Vyhledat stránku nebo sestavu"), zadejte **Nákupní objednávky vratky** a vyberte související odkaz.  
2. Vyberte akci **Nový**.  
3. Vyplňte políčka na v záložce **Obecné** jak je potřeba.
4. Na záložce **Řádky** vyplňte řádky ručně nebo nakopírujte automaticky do řádků z ostatních dokumentů.

    - Použijte funkci **Získat účt. řádky pro stornování** ke kopírování jednoho nebo více účtovaných řádků z jednoho nebo několika účtovaných dokladů. Tato funkce vždy přesně vrátí náklady z účtováného řádku. Tato funkce je popsána v následujících krocích.    
    - Použijte funkci **Kopírovat doklad** ke zkopírování existujícího dokladu k vrácení objednávky. Tuto funkci použijte ke zkopírování celého dokladu. Může být to být také účtovaný doklad nebo nezaúčtovaný. Tato funkce pouze povoluje přesné vracení nákladů pokud je pole **Nutné vrác.přesn.nákladů** je zatrhnuté v okně **Nastavení prodeje a pohledávek**.  

4. Zvolte akci **Získat účt. řádky pro stornování**.
5. V horní části okna **Účtované řádky nákupního dokladu** vyberte zaškrtávací políčko **Zobrazit pouze vratné řádky** k zobrazení řádků obsahující množství, které ještě nebylo vráceno. Například, pokud bylo množství z účtované nákupní faktury již vráceno, tak pravděpodobně právě toto množství nebudete chtít zahrnou do nového dokumentu k vrácení.

    > [!NOTE]  
    >  Toto pole funguje pouze pro účtované příjemky a účtované řádky faktur, nikoli pro vratky nebo účtované prodejní dobropisy.  

    Na levé straně okna, jsou zobrazeny různé typy dokladů a čísla v závorkách zobrazují počet dostupných dokladů pro každý typ dokladu.

6. V poli **Filtr typů dokladů** vyberte typ účtovaného řádku dokladu, který chcete použít.  
7. Vyberte řádky které chcete kopírovat do nového dokadu.  

    > [!NOTE]  
    >  Pokud použijete Ctrl + A k výběru řádku, budou zkopírovány všechny řádky, ale filtr **Zobrazit pouze zbývající množství** bude ignorován. Například, předpokládejme, že jste filtrovali řádky na určité číslo dokumentu s dvěma řádky, z nichž jeden byl již vrácen. Pokud je dokonce vybráno pole **Zobrazit pouze zbývající množství** a když zmáčknete Ctrl+A ke kopírování řádků, oba řádky budou zkopírovány místo jednoho, který nebyl vrácen.  

8. Zvolte tlačítko **OK** ke zkopírování řádků do nového dokumentu.  

    Dochází k následujícím procesům:  

    -   Pro účtované řádky dokladů typu **Zboží** je vytvořen nový řádek, který je zkopírován z účtovaného dokladu s množstvím, které ještě nebylo vráceno. V poli **Vyrovnat položkou zboží** je vyplněno odpovídajícím číslem položky zboží z účtovaného řádku dokladu.  

    -   Pro účtované řádky, které nejsou typu **Zboží**, jako jsou poplatky se nový řádek dokladu vytvoří jako kopie původního účtovaného řádku dokladu.  

    -   Výpočet pole **Pořizovací cena**na novém řádku z nákladů na příslušné položky hlavní knihy.  

    -   Pokud je kopírovaným dokladem účtovaná dodávka, účtovaná příjemka, účtovaná výdejka, nebo účtovaná vratka dodávky, jednotková cena se automaticky vypočítává z karty zboží.  

    -   Pokud je kopírovaný doklad účtovaná faktura nebo dobropis, pořizovací cena, fakturační slevy a řádková sleva je také zkopírována.  

    -   Jestliže účtovaný dokument obsahuje řádky se sledováním zboží, pole **Vyrovnat položkou zboží** je na řádku sledování zboží vyplněno na příslušnou položkou zboží a číslem z řádků sledování zboží.  

     Při kopírování z účtované faktury nebo účtovaného dobropisu, program zkopíruje relevantní fakturační slevy a řádkové slevy jako platné k datu zaúčtování, tak že je řádek účtovaného dokladu překopírován do nového dokumentu. Dávejte pozor,** pokud možnost Výpočet fakturační slevy** aktivovaný v okně **Nastavení nákupu a závazků**, potom bude fakturační sleva nově vypočítaná, pokud zaúčtujete nový řádek dokladu. Částka na řádku může být odlišná pro nový řádek z účtovaného dokladu, záleží na novém výpočtu fakturační slevy.  

    > [!NOTE]  
    >  Pokud byla část množství na řádku již vrácena, prodána nebo spotřebována, řádek je vytvořen pouze pouze pro množství zbývajícího množství zásob nebo které bylo vráceno. Pokud je jíž celé množství na řádku účtovaném dokumentu vráceno, nový dokument se nevytvoří.  
    >   
    >  Pokud je tok zboží v účtovaném dokladu stejný jako tok zboží v novém dokladu, vytvoří se v novém dokladu kopie původního řádku účtovaného dokladu. Pole **Vyrovnat položkou zboží** není vyplněno v případě, kdy přesné vrácení nákladu není možné. Například, pokud použijete funkci **Získat účt. řádky pro stornování** k získání řádků účtovaných nákupních dobropisů pro nové dobropisy. Původní řádky dobropisu jsou zkopírovány do nového dobropisu.  

8. V okně **Objednávka nákupní vratky** v poli **Kód příčiny vratky** na každém řádku vyberte důvod vratky.
9. Zvolte akci **Zaúčtovat**.

## <a name="to-create-a-replacement-purchase-order-from-a-purchase-return-order"></a>Vytvoření náhrady nákupní objednávky z nákupní objednávky vratky
Můžete souhlasit s vaším dodavatelem, který chce kompenzovat vámi koupenou položku. Vyměňované zboží může být stejné nebo může být jiné. Tato situace by mohla způsobit, že dodavatel náhodou odešle špatné zboží.  
1.  Pro aktivní proces vratky v okně **Nákupní objednávka vratky** udělejte negativní položky na výměnu vložením záporného počtu v poli **Množství**.  
2. Vyberte tlačítko **Přesunout záporné řádky**.  
3. V okně **Nákup Nákupčí** vyplňte pole podle potřeby.
4. Zvolte tlačítko **OK**. Záporný řádek je smazán z objednávky nákupní vratky a nová nákupní objednávka je vytvořena. Další informace naleznete v tématu [Návod: Zaznamenávání nákupů.](purchasing-how-record-purchases.md).  

## <a name="to-create-a-purchase-allowance"></a>Vytvoření příspěvku na nákup  
Pokud obdržíte zboží od dodavatele, které jste nechtěli, například, pokud je poškozené nebo špatné barvy, případně špatná velikost - dodavatel vám pravděpodobně navrhne příspěvek na nákup.  

Můžete zaúčtovat tuto sníženou platbu jako poplatek za zboží na nákupním dobropisu a spojit ho s účtovanou příjemkou. Následující popis je o Objednávce nákupní vratky, současně můžete aplikovat tyto kroky na nákupní dobropisy.

1. Zvolte ikonu ![Vyhledat stránku nebo sestavu](media/ui-search/search_small.png "Ikona Vyhledat stránku nebo sestavu"), zadejte **Nákupní dobropisy** a vyberte související odkaz.
2. Chcete-li otevřít nový prázdný nákupní dobropis, zvolte akci **Nový**.  
3.  Vyplňte hlavičku dobropisu s informacemi o dodavateli, který vám chce poslat příspěvek na nákup.  
4. Na záložce **Řádky** v poli **Typ** vyberte **Poplatek**.  
5.  Do pole **Číslo** Vyberte příslušný poplatek za zboží.  

    Pokud budete chtít můžete vytvořit speciální číslo poplatku za zboží k pokrytí příspěvku na nákup.   
6.  Do pole **Množství** zadejte **1**.  
7.  Do pole **Nákupní cena** vložte částku příspěvku na nákup.  
8.  Připsání příspěvku na nákup jako poplatek za zboží k položce v účtované přijemce.  Další informace naleznete v tématu [Návod: Použití poplatku za položku pro účtování dodatečných obchodních nákladů.](payables-how-assign-item-charges.md) Pokud jste přiřadili příspěvek, vraťte se na okno **Nákupní dobropis**.

Když chcete účtovat objednávku nákupní vratky, příspěvek na nákup je připojen k odpovídající částce položky. Tímto způsobem můžete zachovat přesné ocenění zásob.  

## <a name="to-combine-return-shipments"></a>Kombinování dodávek vratky  
Pokud chcete vrátit zboží pokryté různými objednávkami nákupních vratek stejnému dodavateli, můžete použít funkci **Kombinování dodávek vratky**  

Pokud odesíláte zboží, účtuhete příslušnou objednávku nákupní vratky jako dodanou, a to vytvoří účtovanou dodávku nákupní vratky.  

Když jste připraveni fakturovat toto zboží, namísto jednotlivé fakturace jednotlivých objednávek nákupních vratek, můžete nákupní dobropisy automaticky zkopírovat účtované řádky dodávek vratky do tohoto dokladu. Potom můžete účtovat nákupní dobropisy a výhodně fakturovat všechny otevřené objednávky nákupních vratek ve stejný čas.  

Pokud jsou vratky kombinovány na dobropisu a jsou účtovány, tak účtované nákupní dobropisy jsou vytvořeny z těchto řádků Pole **Fakturované množství** na původní objednávce nákupní vratky je aktualizováno na základě faktorovaného množství. Tato původní objednávka nákupní vratky však není smazána, a to ani v případě, že byla plně přijata a fakturována, a proto musíte doklad smazat ručně.

> [!NOTE]  
> Následující procedura předpokládá, že pro dodavatele existuje několik objednávek nákupních vratek a že byly účtované.     

1.  Zvolte ikonu ![Vyhledat stránku nebo sestavu](media/ui-search/search_small.png "Ikona Vyhledat stránku nebo sestavu"), zadejte **Nákupní dobropisy** a vyberte související odkaz.  
2.  Vyberte akci **Nový**.  
3. Na záložce s náhledem **Obecné** vyplňte pole podle potřeby.  
4. Zvolte akci **Získat řádky dodávky vratky**.  
5.  Vyberte několik řádků dodávky vratky, které chcete zahrnou to faktury  

    Pokud jste vybrali špatný řádek vratky nebo chcete začít znovu, můžete jednoduše smazat řádek na nákupním dobropisu a potom použít znovu **Získat řádky dodávky vratky**.  
6.  Zvolte akci **Zaúčtovat**.  

### <a name="to-remove-open-purchase-return-orders-after-combined-return-shipment-posting"></a>Odstranění otevřených objednávek nákupní vratek po kombinovaném účtovaném odeslání.  

1.  Zvolte ikonu ![Vyhledat stránku nebo sestavu](media/ui-search/search_small.png "Ikona Vyhledat stránku nebo sestavu"), zadejte **Smazat účtované nákupní objednávky vratky** a vyberte související odkaz.  
2.  Vyplňte pole a poté klepněte na tlačítko **OK**.  
3.  Případně můžete ručně vymazat jednotlivé nákupní objednávky vratky.

## <a name="see-also"></a>Viz také
[Nákup](purchasing-manage-purchasing.md)  
[Návod: Zaznamenávání nákupu](purchasing-how-record-purchases.md)  
[Návod: Návod: Opravit nebo zrušit nezaplacené nákupní faktury](purchasing-how-correct-cancel-unpaid-purchase-invoices.md)  
[Práce s [!INCLUDE[d365fin](includes/d365fin_md.md)]](ui-work-product.md)

