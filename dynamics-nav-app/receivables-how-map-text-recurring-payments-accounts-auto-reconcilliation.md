---
title: "Nastavení mapování textu na účet pro opakované platby"
description: "Propojte text plateb s konkrétními účty tak, aby byly platby spojovány s účty při účtování deníku odsouhlasení plateb."
documentationcenter: 
author: SorenGP
ms.prod: dynamics-nav-2017
ms.topic: article
ms.devlang: na
ms.tgt_pltfrm: na
ms.workload: na
ms.search.keywords: account linking, direct payment posting, automatic payment processing, reconcile payment, recurring expense, recurring cash receipt
ms.date: 03/29/2017
ms.author: sgroespe
ms.translationtype: HT
ms.sourcegitcommit: 4fefaef7380ac10836fcac404eea006f55d8556f
ms.openlocfilehash: de3042d13ff280617c43075df705f86bbba7b013
ms.contentlocale: cs-cz
ms.lasthandoff: 10/16/2017

---
# <a name="how-to-map-text-on-recurring-payments-to-accounts-for-automatic-reconciliation"></a>Návod: Mapování textu periodických plateb na účtech pro automatické odsouhlasení
V okně **Textové mapování účtů**, které otevřete z okna **Deníky odsouhlasení plateb**, můžete nastavit mapování mezi textem plateb a konkrétními Dal, MD a zůstatkovými účty tak, aby tyto platby byly účtovány na určené účty, když účtujete deník odsouhlasení plateb.

> [!NOTE]  
>   Téma také platí, když používáte funkci **Mapování textu na účet** ze záznamu došlého dokladu a pomáháte při převodu elektronických dokladů přijatých z externích služeb do dokladů v [!INCLUDE[d365fin](includes/d365fin_md.md)]. Další informace naleznete v tématu [Návod: Použití funkce OCR k převedení souborů PDF a obrázkových souborů do elektronických dokladů.](across-how-use-ocr-pdf-images-files.md)   

Podobné funkce existují k tomu, aby se adekvátně sladily přebytečné částky v deníku odsouhlasení plateb na základní ad-hoc. Další informace naleznete v tématu [Návod: Odsouhlasení plateb, které nelze vyrovnat automaticky.](receivables-how-reconcile-payments-cannot-apply-auto.md)

Platby zaúčtované na základě textového mapování účtů se nevyrovnají při otevírání položek, ale kromě zaúčtování specifických účtů v doplňku k vytvoření položek knihy bankovního účtu. Podle toho je textové mapování účtů vhodné pro opakované peněžní příjmy nebo výdaje, jako jsou časté nákupy pohonných hmot nebo bankovních poplatků a úroků, které se pravidelně vyskytují na bankovním výpisu a nepotřebují související obchodní doklad. Další informace naleznete v tomto tématu v části "Příklad - Textové mapování účtů pro výdaje za palivo".

> [!NOTE]  
>   Platby na řádcích deníku odsouhlasení jsou nastaveny pouze na zaúčtování podle textového mapování účtů, pokud funkce automatické vyrovnání může poskytovat pouze spolehlivost párování **Nízká** nebo **Střední**. Pokud funkce automatické vyrovnání poskytuje spolehlivost párování vysoká, pak se platba automaticky vyrovná na jednu nebo více otevřených položek a platba se nezaúčtuje na účty zadané v okně **Textové mapování účtů**. Jinými slovy spolehlivost párování **Vysoká** zaručuje převzetí textového mapování účtů.

Na řádku deníku odsouhlasení plateb, u něhož byla platba nastavena na zaúčtování podle textového mapování účtů, pole **Spolehlivost párování** obsahuje **Vysoká - textové mapování účtů** a pole **Typ účtu** a **Číslo účtu** obsahuje mapované účty.

## <a name="to-map-text-on-recurring-payments-to-accounts-for-automatic-reconciliation"></a>Mapování textu periodických plateb na účtech pro automatické odsouhlasení
1. Zvolte ikonu ![Vyhledat stránku nebo sestavu](media/ui-search/search_small.png "Ikona Vyhledat stránku nebo sestavu"), zadejte **Deníky odsouhlasení plateb** a vyberte související odkaz.
2. Otevřete deník odsouhlasení plateb. Další informace naleznete v tématu [Návod: Odsouhlasení plateb pomocí automatického vyrovnání.](receivables-how-reconcile-payments-auto-application.md)
3. Zvolte akci **Mapovat text na účet**. Otevře se okno **Textové mapování účtů**.
4. Do pole **Mapovaný text** zadejte libovolný text, který se vyskytuje u plateb, které chcete zaúčtovat na určené účty bez použití otevřeného záznamu. Můžete zadat až 50 znaků.

    > [!NOTE]  
>   Pokud neexistují žádné jiné platby nebo došlé doklady s mapovaným textem, pak textové mapování účtů se objeví, i když pouze část textu v platbě nebo došlého dokladu existuje jako mapovaný text.
5. V poli **Číslo Dodavatele** zadejte dodavatele, pro kterého budou vytvořeny došlé doklady obsahující namapovaný text nebo platby budou zaúčtovány. Další informace naleznete v tématu [Návod: Použití funkce OCR k převedení souborů PDF a obrázkových souborů do elektronických dokladů.](across-how-use-ocr-pdf-images-files.md)      
6. V poli **Číslo účtu MD** zadejte účet, kde platby obsahující mapovaný text budou zaúčtovány, pokud se jedná o příchozí platby. U příchozích plateb je znaménko hodnoty v poli **Částka výkazu** kladné.
7. V poli **Číslo účtu DAL** zadejte účet, kde platby obsahující mapovaný text budou zaúčtovány, pokud se jedná o příchozí platby. U odchozích plateb je hodnoty v poli **Částka výpisu** záporná.
8. V poli **Číslo zdroje protiúčtu **zdroje protiúčtu zadejte, zda bude platba zaúčtována na účet hlavní knihy nebo na zákazníka nebo dodavatele.
9. V poli **Číslo zdroje protiúčtu **na který bude platba zaúčtována v závislosti na vašem výběru v poli** Typ zdroje protiúčtu.**
10. Opakujte kroky 4 až 8 pro všechny texty o platbách, které chcete mapovat na účty pro přímé účtování bez vyrovnání.

Příště, jakmile importujete soubor s výpisem z banky nebo zvolíte akci **Automatické vyrovnání** v okně **Deník odsouhlasení plateb**, budou řádky deníku pro platby, které obsahují zadaný mapovaný text s mapovanými účty v polích **Typ účtu** a **Číslo účtu**. Pole **Spolehlivost párování** bude obsahovat **Vysoká - textové mapování účtů**. To je za předpokladu, že funkce automatické vyrovnání může poskytnout pouze spolehlivost párování **Nízká** nebo **Střední**.

## <a name="example-text-to-account-mapping-for-fuel-expense"></a>Příklad: Textové mapování účtů pro výdaje za pohonné hmoty
Chcete-li vždy zaúčtovat výdaje za pohonné hmoty vzniklé u čerpacích stanic společnosti Shell do účtu hlavní knihy pro benzin (účet 8510), vyplňte následující řádek v okně **Textové mapování účtů**.

| Mapování textu | Číslo účtu MD | Číslo účtu DAL | Typ zdroje protiúčtu | Číslo zdroje protiúčtu |
| --- | --- | --- | --- | --- |
| Shell |PRÁZDNÝ |8510 |Finanční účet |PRÁZDNÝ |

> [!TIP]  
>   Další informace o práci s poli a sloupci naleznete v tématu [Práce s programem [!INCLUDE[d365fin](includes/d365fin_long_md.md)]](ui-work-product.md). Další informace o hledání konkrétních stránek naleznete v tématu [Hledat](ui-search.md) .

## <a name="see-also"></a>Viz také
[Správa pohledávek](receivables-manage-receivables.md)  
[Prodej](sales-manage-sales.md)  
[Návod: Nastavení služby převodu bankovních dat](bank-how-setup-bank-data-conversion-service.md)    
[Přizpůsobení [!INCLUDE[d365fin](includes/d365fin_md.md)] Pomocí rozšíření](ui-extensions.md)  
[Práce s [!INCLUDE[d365fin](includes/d365fin_md.md)]](ui-work-product.md)

