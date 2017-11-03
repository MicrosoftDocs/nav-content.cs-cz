---
title: "Použití rozdílu přenosu na funkční účet k odsouhlasení plateb"
description: "Popisuje, jak proces plateb, který nemůže být vyrovnán na doklad, např. když směnný kurz způsobuje rozdílné částky."
author: SorenGP
ms.prod: dynamics-nav-2017
ms.topic: article
ms.devlang: na
ms.tgt_pltfrm: na
ms.workload: na
ms.search.keywords: payment process, cash receipts
ms.date: 09/08/2017
ms.author: sgroespe
ms.translationtype: HT
ms.sourcegitcommit: 4fefaef7380ac10836fcac404eea006f55d8556f
ms.openlocfilehash: 14728fea5d8661004c23f65920ca835e1d29ac55
ms.contentlocale: cs-cz
ms.lasthandoff: 10/16/2017

---
# <a name="how-to-reconcile-payments-that-cannot-be-applied-automatically"></a>Návod: Odsouhlasení plateb, které nelze vyrovnat automaticky
Někdy budete muset zpracovávat platby na váš bankovní účet, které nelze vyrovnat na souvisejícího otevřeného zákazníka, dodavatele nebo položku knihy bankovního učtu. Důvodem může být skutečnost, že v [!INCLUDE[d365fin](includes/d365fin_md.md)] neexistuje žádný doklad, který by umožňoval vyrovnat platbu nebo žádný související dokument v [!INCLUDE[d365fin](includes/d365fin_md.md)] nemá jinou částku než částku transakce například kvůli kurzu měny. V okně **Deník odsouhlasení plateb** se všechny transakce částek za platby, které nejsou vyrovnány, objeví v poli **Rozdíl** včetně částek, které nelze vyrovnat z důvodů, které jsou uvedené výše.

Platby, které nelze vyrovnat se mohou objevit na řádcích deníku odsouhlasení plateb následujícími různými způsoby:

* Hodnota v poli **Rozdíl** se rovná hodnotě v poli **Částka transakce**, což znamená, že žádnou část platby nelze vyrovnat na souvisejícího otevřeného zákazníka, dodavatele nebo položku knihy bankovního účtu.
* Hodnota v poli **Rozdíl** je nižší než hodnota v poli **Částka transakce**, což znamená, že část platby může být vyrovnána na souvisejícího otevřeného zákazníka, dodavatele nebo položku knihy bankovního účtu. Zbývající část platby nemůže být vyrovnána a musí být odsouhlasena ručně nebo zaúčtována přímo na účet.

Chcete-li odsouhlasit takové platby, můžete zvolit tlačítko **Převést rozdíl na účet** a poté určit, na který účet bude částka v poli **Rozdíl** zaúčtována, když zaúčtujete deník odsouhlasení plateb.

> [!TIP]  
>   Podobné funkce existují pro nastavení automatického odsouhlasení opakujících se plateb, které nelze vyrovnat na souvisejícího otevřeného zákazníka, dodavatele nebo položku knihy bankovního účtu. Další informace naleznete v tématu [Návod: Namapovaný text o opakovaných platbách na účtech pro automatické odsouhlasení](receivables-how-map-text-recurring-payments-accounts-auto-reconcilliation.md).

## <a name="to-reconcile-payments-that-cannot-be-applied"></a>Odsouhlasení plateb, které nelze vyrovnat
1. Zvolte ikonu ![Vyhledat stránku nebo sestavu](media/ui-search/search_small.png "Ikona Vyhledat stránku nebo sestavu"), zadejte **Deníky odsouhlasení plateb** a poté vyberte příslušný odkaz.
2. Otevřete deník odsouhlasení plateb. Další informace naleznete v tématu [Návod: Odsouhlasení plateb pomocí automatické aplikace](receivables-how-reconcile-payments-auto-application.md).
3. Zvolte **Převést rozdíl na účet**. Otevře se okno **Převést rozdíl na účet**.
4. Pole **Typ účtu** určuje typ účtu, kde částka platby bude vyrovnána.
5. Pole **Číslo účtu** určuje typ účtu, kde částka platby bude vyrovnána.
6. Pole **Popis** určuje text, který popisuje toto přímé zaúčtování platby. Ve výchozím nastavení je vložen text v poli **Text transakce** na řádku deníku odsouhlasení plateb.
7. Zvolte tlačítko **OK**.

Pokud byla hodnota v poli **Rozdíl** rovna hodnotě v poli **Částka transakce** při zaúčtování deníku odsouhlasení plateb, bude celá platba na řádku deníku zaúčtována přímo pro specifický vyrovnávací účet.

Pokud by hodnota v poli **Rozdíl** byla nižší než hodnota v poli **Částka transakce**, vytvoří se další řádek deníku se stejným textem a datem a s rozdílem vloženým do pole **Částka transakce**. Na původním řádku deníku bude rozdíl odečten od hodnoty v poli **Částka transakce** a platba zůstane vyrovnána na příslušného zákazníka, dodavatele nebo položku knihy bankovního účtu. Při zaúčtování deníku odsouhlasení plateb bude jedna část platby zaúčtována jako vyrovnaná platba. Druhá část platby bude zaúčtována přímo na uvedený účet.

## <a name="see-also"></a>Viz také
[Správa pohledávek](receivables-manage-receivables.md)  
[Prodej](sales-manage-sales.md)  
[Práce s [!INCLUDE[d365fin](includes/d365fin_md.md)]](ui-work-product.md)

