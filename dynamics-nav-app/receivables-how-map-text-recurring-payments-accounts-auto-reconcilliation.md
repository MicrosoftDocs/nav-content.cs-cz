---
title: "Návod: Mapování textu periodických plateb na účtech pro automatické odsouhlasení"
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
ms.openlocfilehash: 7f9bf8b0550f7da1cced995234e15ad7aab484ba
ms.contentlocale: cs-cz
ms.lasthandoff: 06/26/2017

---

# <a name="how-to-map-text-on-recurring-payments-to-accounts-for-automatic-reconciliation"></a>Návod: Mapování textu periodických plateb na účtech pro automatické odsouhlasení
V okně **Textové mapování účtů**, které otevřete z okna **Deníky odsouhlasení plateb**, můžete nastavit mapování mezi textem plateb a konkrétními Dal, MD a zůstatkovými účty tak, aby tyto platby byly účtovány na určené účty, když účtujete deník odsouhlasení plateb.

**Poznámka**: Téma také platí, když používáte funkci **Mapování textu na účet** ze záznamu došlého dokladu a pomáháte při převodu elektronických dokladů přijatých z externích služeb do dokladů v [!INCLUDE[navnow](includes/navnow_md.md)]. Další informace naleznete v tématu [Návod: Použití funkce OCR k převedení souborů PDF a obrázkových souborů do elektronických dokladů](across-how-use-ocr-pdf-images-files.md).   

Podobné funkce existují k tomu, aby se adekvátně sladily přebytečné částky v deníku odsouhlasení plateb na základní ad-hoc. Další informace naleznete v tématu [Návod: Odsouhlasení plateb, které nelze vyrovnat automaticky](receivables-how-reconcile-payments-cannot-apply-auto.md).

Platby zaúčtované na základě textového mapování účtů se nevyrovnají při otevírání položek, ale kromě zaúčtování specifických účtů v doplňku k vytvoření položek knihy bankovního účtu. Podle toho je textové mapování účtů vhodné pro opakované peněžní příjmy nebo výdaje, jako jsou časté nákupy pohonných hmot nebo bankovních poplatků a úroků, které se pravidelně vyskytují na bankovním výpisu a nepotřebují související obchodní doklad. Další informace naleznete v tomto tématu v části "Příklad - Textové mapování účtů pro výdaje za palivo".

**Poznámka**: Platby na řádcích deníku odsouhlasení jsou nastaveny pouze na zaúčtování podle textového mapování účtů, pokud funkce automatické vyrovnání může poskytovat pouze spolehlivost párování **Nízká** nebo **Střední**. Pokud funkce automatické vyrovnání poskytuje spolehlivost párování vysoká, pak se platba automaticky vyrovná na jednu nebo více otevřených položek a platba se nezaúčtuje na účty zadané v okně **Textové mapování účtů**. Jinými slovy spolehlivost párování **Vysoká** zaručuje převzetí textového mapování účtů.

Na řádku deníku odsouhlasení plateb, u něhož byla platba nastavena na zaúčtování podle textového mapování účtů, pole **Spolehlivost párování** obsahuje **Vysoká - textové mapování účtů** a pole **Typ účtu** a **Číslo účtu** obsahuje mapované účty.

## <a name="to-map-text-on-recurring-payments-to-accounts-for-automatic-reconciliation"></a>Mapování textu periodických plateb na účtech pro automatické odsouhlasení
1. V pravém horním rohu zvolte ikonu **Vyhledat stránku nebo sestavu**, zadejte **Deníky odsouhlasení plateb** a pak vyberte související odkaz.
2. Otevřete deník odsouhlasení plateb. Další informace naleznete v tématu [Návod: Odsouhlasení plateb pomocí automatického vyrovnání](receivables-how-reconcile-payments-auto-application.md).
3. Zvolte akci **Mapovat text na účet**. Otevře se okno **Textové mapování účtů**.
4. Do pole **Mapovaný text** zadejte libovolný text, který se vyskytuje u plateb, které chcete zaúčtovat na určené účty bez použití otevřeného záznamu. Můžete zadat až 50 znaků.

    **Poznámka**: Pokud neexistují žádné jiné platby nebo došlé doklady s mapovaným textem, pak textové mapování účtů se objeví, i když pouze část textu v platbě nebo došlého dokladu existuje jako mapovaný text.
5. V poli **Číslo Dodavatele** zadejte dodavatele, pro kterého budou vytvořeny došlé doklady obsahující namapovaný text nebo platby budou zaúčtovány. Další informace naleznete v tématu [Návod: Použití funkce OCR k převedení souborů PDF a obrázkových souborů do elektronických dokladů](across-how-use-ocr-pdf-images-files.md).      
6. V poli **Číslo účtu MD** zadejte účet, kde platby obsahující mapovaný text budou zaúčtovány, pokud se jedná o příchozí platby. U příchozích plateb je znaménko hodnoty v poli **Částka výkazu** kladné.
7. V poli **Číslo účtu Dal** zadejte účet, kde platby obsahující mapovaný text budou zaúčtovány, pokud se jedná o odchozí platby. U odchozích plateb je hodnoty v poli **Částka výpisu** záporná.
8. V poli **Typ zdroje protiúčtu** zadejte, zda bude platba zaúčtována na účet hlavní knihy nebo na zákazníka nebo dodavatele.
9. V poli **Číslo zdroje protiúčtu účet,** na který bude platba zaúčtována v závislosti na vašem výběru v poli **Typ zdroje protiúčtu**.
10. Opakujte kroky 4 až 8 pro všechny texty o platbách, které chcete mapovat na účty pro přímé účtování bez vyrovnání.

Příště, jakmile importujete soubor s výpisem z banky nebo zvolíte akci **Automatické vyrovnání** v okně **Deník odsouhlasení plateb**, budou řádky deníku pro platby, které obsahují zadaný mapovaný text s mapovanými účty v poli **Typ účtu** a **Číslo účtu**. Pole **Spolehlivost párování** bude obsahovat **Vysoká - textové mapování účtů**. To je za předpokladu, že funkce automatické vyrovnání může poskytnout pouze spolehlivost párování **Nízká** nebo **Střední**.

##<a name="example-text-to-account-mapping-for-fuel-expense"></a>Příklad: Textové mapování účtů pro výdaje za pohonné hmoty

Chcete-li vždy zaúčtovat výdaje za pohonné hmoty vzniklé u čerpacích stanic společnosti Shell do účtu hlavní knihy pro benzin (účet 8510), vyplňte následující řádek v okně **Textové mapování účtů**.

|Mapování textu |MD účet Číslo |Dal účet Číslo |Typ zdroje protiúčtu |Číslo zdroje protiúčtu |
|-------------|---------------|----------------|-----------------|----------------|
|Shell |PRÁZDNÝ |8510 |Finanční účet|PRÁZDNÝ|

**Tip**: Další informace o práci s poli a sloupci naleznete v tématu [Práce s programem [!INCLUDE[navnow](includes/navnow_md.md)]](ui-work-product.md). Další informace o hledání konkrétních stránek naleznete v tématu [Hledat](ui-search.md) .

## <a name="see-also"></a>Viz také
[Správa pohledávek](receivables-manage-receivables.md)  
[Správa prodeje](sales-manage-sales.md)  
[Návod: Nastavení služby Envestnet Yodlee Bank Feeds](bank-how-setup-bank-statement-service.md)  
[Přizpůsobení [!INCLUDE[navnow](includes/navnow_md.md)] pomocí rozšíření](ui-extensions.md)

