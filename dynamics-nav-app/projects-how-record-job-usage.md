---
title: "Návod: Využití záznamu pro projekty."
author: SorenGP
ms.custom: na
ms.date: 11/01/2016
ms.reviewer: na
ms.suite: na
ms.tgt_pltfrm: na
ms.topic: article
ms-prod: dynamics-nav-2017
ms.translationtype: Human Translation
ms.sourcegitcommit: 51adfb3588099c496f0946ff71da5c6fe518f070
ms.openlocfilehash: 86cc31ea9c117700d2905dd6b8c4bd88eb0f9854
ms.contentlocale: cs-cz
ms.lasthandoff: 06/26/2017

---

#<a name="how-to-record-usage-for-jobs"></a>Návod: Využití záznamu pro projekty.
V okně **Řádky plánování projektu** můžete prohlížet a zaznamenávat využití v různých částech vašeho projektu, které se automaticky aktualizují, když měníte a přenášíte informace mezi úlohami a deníky projektu nebo projektovými fakturami. To vyžaduje, abyste nastavili projekt tak, aby byla zapnuta možnost **Apply Usage Link** . Další informace naleznete v tématu [Návod: Nastavit Projekty](projects-how-setup-jobs.md).  

Například pro řádky plánování typu **Rozpočet** můžete zadat množství zdrojů a uvést, jaké množství se má přenést do deníku projektu. Pokud je typ řádku plánování **Fakturovatelný** , můžete zadat množství zdrojů a uvést, jaké množství se má převést na fakturu. Porovnáním množství, které bylo převedeno do deníku nebo faktury se zbývajícím množstvím, můžete rychle zkontrolovat informace o použití.

Následující postupy popisují, jak zaznamenat skutečné (fakturovatelné) nebo rozpočtové ceny a náklady projektu. Informace o odhadu rozpočtovaných hodnot během plánování naleznete v tématu [Návod: Správa rozpočtů projektu](projects-how-manage-budgets.md) .

## <a name="to-record-usage-for-a-job-planning-line-of-type-budget"></a>Záznam využití pro řádek plánování projektu typu Rozpočet

1. V pravém horním rohu zvolte ikonu **Vyhledat stránku nebo sestavu**, zadejte **Projekty** a zvolte související odkaz.  
2. Vyberte příslušnou úlohu a poté vyberte akci **Řádky plánování projektu** .
3. Vyberte řádek plánování projektu typu **Rozpočet** nebo **Rozpočet a Fakturovatelný** u kterého chcete zaznamenat využití.
4. V poli **Množ. Pro přenos do deníku** zadejte počet, který chcete přenést. Výchozí hodnota je hodnota, kterou zadáte do pole **Množství** .

    Pole **Zbývající množství** zobrazuje množství, které zbývá pro dokončení projektu a přenesení do deníku.  

5. Zvolte akci **Vytvořit řádek deníku projektu** .
6. V okně **Přesun řádku plánování do projektu** vyplňte pole podle potřeby. Vyberte pole a přečtěte si krátký popis pole nebo klikněte na odkaz pro další informace.
7. Zvolte akci **Otevřít deník projektu** .  
8. V okně **Deník projektu** vyberte relevantní řádek a pak vyberte tlačítko **Zaúčtovat**.
9. V okně **Řádky plánování projektu** zkontrolujte zaznamenané využití pozorováním polí **Množství** , **Zbývajícího množství** a **Množ. Pro přenos do deníku** .  
10. Zopakujte kroky 3 až 8, abyste zaznamenali další spotřebu.  

## <a name="to-record-usage-for-a-job-planning-line-of-type-billable"></a>Záznam spotřeby pro řádky plánování typu Fakturovatelný  
V dalším úkolu také zaznamenáváte spotřebu, ale pro řádky plánování typu **Fakturovatelný** . Obvykle v tomto případě fakturujete svou spotřebu, ale můžete ji také převést do deníku. Když to však uděláte, vytvoří se řádek plánování typu **Rozpočet** tak, aby odpovídal fakturovanému řádku. Další informace naleznete v tématu [Návod: Správa rozpočtů projektu](projects-how-manage-budgets.md) .

1. V pravém horním rohu zvolte ikonu **Vyhledat stránku nebo sestavu**, zadejte **Projekty** a zvolte související odkaz.
2. Vyberte příslušnou úlohu a poté vyberte akci **Řádky plánování projektu** .  
3. Vyberte řádek plánování projektu typu **Fakturovatelný** pro který chcete zaznamenat spotřebu.
4. V poli **Množ. Pro přenos na fakturu** zadejte počet, který chcete přenést. Výchozí hodnota je hodnota, kterou zadáte do pole **Množství** .

    Pole **Množství k fakturaci** zobrazuje množství, které zbývá pro dokončení úlohy a bude fakturováno.  

5. Zvolte akci **Vytvořit prodejní fakturu**
6. V okně **Transfer projektu na prodejní fakturu** vyplňte pole podle potřeby a poté klepněte na tlačítko **OK** .
7. V okně **Řádky plánování projektu** vyberte příslušný řádek a poté zvolte akci **Zaúčtovat** .
8. Zkontrolujte zaznamenané využití sledováním polí **Množství** , **Množství k fakturaci** , **Množ. Pro přenos na fakturu** , a pokud je prodejní faktura zaúčtována, pole **Fakturované množství** .
9. Zopakujte kroky 3 až 8, abyste zaznamenali další spotřebu.  
10. Chcete-li zkontrolovat související zaúčtovanou prodejní fakturu, zvolte akci **Prodejní faktury / Dobropisy** .  
11. V okně **Faktury projektu** vyberte příslušnou fakturu a poté zvolte akci **Otevřít prodejní fakturu / Dobropis** .         

## <a name="to-create-job-journal-lines-from-job-planning-lines"></a>Vytvoření řádků deníku projektu z řádku plánování projektu  
Pokud jste připraveni zaúčtovat finanční informace pro projekty, musíte vytvořit řádky deníku projektu, které můžete zaúčtovat.

1. V pravém horním rohu zvolte ikonu **Vyhledat stránku nebo sestavu**, zadejte **Projekty** a zvolte související odkaz.  
2. Vyberte příslušný otevřený projekt a poté vyberte akci **Řádky plánování projektu** .  
3. V okně **Řádky plánování projektu** na příslušném řádku plánování projektu v poli **Množs. Pro přenos do deníku** , zadejte množství, které chcete převést do deníku projektu.  
4. Zvolte akci **Vytvořit řádky deníku projektu** .
5. V okně **Přesun řádku plánování do projektu** vyplňte pole podle potřeby.  
6. Zvolte tlačítko **OK**. Řádky deníku projektu jsou vytvořeny.
7. Chcete-li ověřit přenos, otevřete příslušný list deníku projektu a zkontrolujte položky.  
8. Po dokončení řádků deníku projektu zvolte akci **Zaúčtovat**.  

## <a name="to-create-job-journal-lines-manually"></a>Tvorba řádku deníku projektu ručně  

1. V pravém horním rohu zvolte ikonu **Vyhledat stránku nebo sestavu**, zadejte **Deníky projektu** a poté vyberte související odkaz.  
2. V poli **Název listu** vyberte příslušný list deníku projektu.  
3. Na novém řádku zadejte číslo dokladu, číslo projektu, číslo činnosti, typ a množství typu spotřeby.  
4. Po dokončení řádků deníku projektů zvolte akci **Zaúčtovat**.  

## <a name="to-review-planning-lines-for-a-job-ledger-entry"></a>Kontrola řádků plánování pro věcné položky projektu  
Po zaúčtování řádků deníku projektu můžete zobrazit řádky plánování, které jsou přiřazeny k položkám deníku projektu, které byly zaúčtovány.

**Poznámka**: To vyžaduje zaškrtnutí políčka **Apply Usage Link** pro projekty nebo nastavení jako výchozí volba pro všechny projekty ve vaší organizaci. Další informace naleznete v tématu [Návod: Nastavení projektů](projects-how-setup-jobs.md).  

1. V pravém horním rohu zvolte ikonu **Vyhledat stránku nebo sestavu**, zadejte **Deníky projektu** a poté vyberte související odkaz.  
2. Vyberte příslušný deník projektu a potom vyberte akci **Věcné položky**.  
3. V okně **Položky projektu** vyberte akci **Zobrazit řádky plánování projektu** .

## <a name="see-also"></a>Viz také
[Správa projektů](projects-manage-projects.md)  
[Finance](finance-setup.md)  
[Správa nákupu](purchasing-manage-purchasing.md)         
[Spravovat prodej](sales-manage-sales.md)      
[Pracujte s Dynamics NAV](ui-work-product.md)  

