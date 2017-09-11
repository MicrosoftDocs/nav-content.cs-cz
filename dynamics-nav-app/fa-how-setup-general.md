---
title: "Návod: Nastavení informací o obecném dlouhodobém majetku"
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
ms.openlocfilehash: 8c0e33a78d47ccfbe39a78f81e31b69f61fd4f80
ms.contentlocale: cs-cz
ms.lasthandoff: 06/26/2017

---

# <a name="how-to-set-up-general-fixed-assets-information"></a>Návod: Nastavení informací o obecném dlouhodobém majetku
Než budete moci spravovat dlouhodobý majetek, musíte nastavit výchozí finanční účty, alokační klíče, šablony deníků a dávky pro zaúčtování DM a reklasifikaci a klasifikovat dlouhodobý majetek v třídách, jako je Hmotný a Nehmotný.

## <a name="to-set-up-general-default-values-for-fixed-assets"></a>Nastavení obecných výchozích hodnot pro dlouhodobý majetek
Definujte obecné chování nebo funkčnost DM a nastavte řadu čísel dokumentu v okně **Nastavení DM**.

1. V pravém horním rohu zvolte ikonu **Vyhledat stránku nebo sestavu**, zadejte **Nastavení DM** a pak vyberte související odkaz.  
2. Vyplňte pole podle potřeby. Vyberte pole a přečtěte si krátký popis pole nebo klikněte na odkaz pro další informace.

## <a name="to-set-up-fixed-asset-posting-groups"></a>Nastavení účtovacích skupin DM  
Pomocí účtovacích skupin můžete definovat skupiny DM. Položky pro tyto účtovací skupiny jsou zaúčtovány na stejných účtech hlavní knihy.  
1. V pravém horním rohu zvolte ikonu **Vyhledat stránku nebo sestavu**, zadejte **Účto skupiny DM** a pak vyberte související odkaz.  
2. Zvolte akci **Nový**.
3. V okně **Karta účto skupiny DM** vyplňte pole podle potřeby.

    **Poznámka**: Chcete-li se ujistit, že vyrovnávací účty pro různý zaúčtovaný dlouhodobý majetek jsou automaticky vloženy, zvolte akci **Vložit protiúčet DM** na řádcích deníku a postupujte podle dalšího kroku založeného na zhodnocení zaúčtování.
4. V záložce s náhledem **Vyrovnávací účet** pole **Protiúčet zhodnocení** obsahuje účet hlavní knihy, na který chcete zaúčtovat zůstatkové položky pro zhodnocení.

Další informace o použití akce **Vložit protiúčet DM** na řádcích finančního deníku DM, viz například [Návod: Přecenění DM](fa-how-revalue.md).

## <a name="to-set-up-fixed-asset-allocation-keys"></a>Nastavení přidělovacích klíčů DM  
Transakce mohou být přiděleny různým oddělením nebo projektům podle uživatelsky definovaných přidělovacích klíčů. Například byste mohli nastavit přidělovací klíč pro přidělení nákladů na odpisy vozidel s 35% administrativnímu oddělení a 65% prodejnímu oddělení. Další informace naleznete v tématu [Návod: Použití přidělovacího klíče v obecných denících](ui-how-use-allocation-keys-general-journals.md).

Přidělovací klíče platí pro třídy DM, nikoli pro jednotlivý majetek.  
1. V pravém horním rohu zvolte ikonu **Vyhledat stránku nebo sestavu**, zadejte **Účto skupiny DM** a pak vyberte související odkaz.  
2. V okně **Účto skupiny DM** vyberte akci **Rozdělení** a poté vyberte typ účtování.
3. V okně **Rozdělení DM** vyplňte pole podle potřeby.
4. Opakujte kroky 2 a 3 pro každý typ účtování, pro který chcete definovat přidělovací klíče.

## <a name="to-set-up-fixed-asset-journal-templates"></a>Nastavení šablon deníku DM  
Šablona je předdefinované rozložení pro deník. Šablona obsahuje informace o sledovacích kódech, výkazech a číselných řadách. Další informace naleznete v tématu [Práce s Finančním deníkem](ui-work-general-journals.md).

Dynamics NAV automaticky vytvoří šablonu deníku DM při prvním otevření okna **Deník DM**, ale můžete nastavit další šablony deníku.  
1. V pravém horním rohu zvolte ikonu **Vyhledat stránku nebo sestavu**, zadejte **Šablony deníku DM** a pak vyberte související odkaz.  
2. Vyplňte pole podle potřeby.

## <a name="to-set-up-fixed-asset-journal-batches"></a>Nastavení dávek deníku DM
Můžete nastavit více dávek deníku, což jsou jednotlivé deníky pro každou šablonu deníku. Zaměstnanci mohou například mít vlastní dávku deníku, která používá iniciály zaměstnanců jako název šablony deníku. Další informace naleznete v tématu [Práce s Finančním deníkem](ui-work-general-journals.md).  
1. V pravém horním rohu zvolte ikonu **Vyhledat stránku nebo sestavu**, zadejte **Šablony deníku DM** a pak vyberte související odkaz.  
2. Vyberte příslušnou šablonu deníku a pak zvolte akci **Dávky**.
3. V okně **Dávky deníku DM** vyplňte pole podle potřeby.

## <a name="to-set-up-fixed-asset-reclassification-journal-templates"></a>Nastavení šablon deníku pro reklasifikaci DM  
Používáte-li vyhrazené přeřazení deníků, když potřebujete převést, rozdělit nebo kombinovat dlouhodobý majetek. Dynamics NAV automaticky vytvoří šablonu deníku pro reklasifikaci DM při prvním otevření okna **Deník přeřazení DM**, ale můžete nastavit další reklasifikaci šablony deníku. Další informace naleznete v tématu [Práce s Finančním deníkem](ui-work-general-journals.md).  
1. V pravém horním rohu zvolte ikonu **Vyhledat stránku nebo sestavu**, zadejte **Šablony deníku přeřazení DM** a pak vyberte související odkaz.  
2. Vyplňte pole podle potřeby.

## <a name="to-set-up-fixed-asset-reclassification-journal-batches"></a>Nastavení dávky deníku pro reklasifikaci DM  
Můžete nastavit více dávek deníku, což jsou jednotlivé deníky pro každou reklasifikaci šablony deníku. Zaměstnanci mohou mít například vlastní reklasifikaci dávky deníku, který používá iniciály zaměstnanců jako název reklasifikaci dávky deníku. Další informace naleznete v tématu [Práce s Finančním deníkem](ui-work-general-journals.md).
1. V pravém horním rohu zvolte ikonu **Vyhledat stránku nebo sestavu**, zadejte **Šablony deníku ** přeřazení DM** a pak vyberte související odkaz.  
2. Vyberte příslušnou šablonu deníku a pak zvolte akci **Dávky**.
3. V okně **Listy deníku přeřazení DM** vyplňte pole podle potřeby.

## <a name="to-set-up-fixed-asset-class-codes"></a>Nastavení kódů tříd DM  
Kódy tříd DM můžou být použity k seskupení DM, například do hmotného a nehmotného majetku.
1. V pravém horním rohu zvolte ikonu **Vyhledat stránku nebo sestavu**, zadejte **Třidy DM** a pak vyberte související odkaz.
2. Zadejte kódy a názvy pro třídy, které chcete vytvořit.

## <a name="to-set-up-fixed-asset-subclass-codes"></a>Nastavení podtřídových kódů DM
Používáte-li podtřídové kódy DM k seskupení svého DM do kategorií jako jsou budovy, vozidla, nábytek nebo strojní zařízení.  
1. V pravém horním rohu zvolte ikonu **Vyhledat stránku nebo sestavu**, zadejte **Podtřídy DM** a pak vyberte související odkaz.
2. Zadejte kódy a názvy pro třídy, které chcete vytvořit.

## <a name="to-set-up-fixed-asset-location-codes"></a>Nastavení kódů místa DM
Použijete kódy místa DM k registraci umístění DM, např. oddělení prodeje, příjem, správa, výroba nebo sklad. Tyto informace jsou užitečné pro účely pojištění a inventáře.
1. V pravém horním rohu zvolte ikonu **Vyhledat stránku nebo sestavu**, zadejte **Umístění DM** a pak vyberte související odkaz.
2. Zadejte kódy a názvy pro umístění DM, který chcete vytvořit.

## <a name="to-register-opening-entries"></a>Zaregistrování otevíracích položek  
Pokud používáte dlouhodobý majetek v Dynamics NAV poprvé, musíte nastavit oblast aplikace hlavní knihy před nastavením DM. Jak to uděláte, závisí na tom, zda je dlouhodobý majetek integrován do hlavní knihy.  

 Následující postup se používá, pokud mají být transakce DM zaúčtovány do hlavní knihy.  

1. Ujistěte se, že jste dokončili základní nastavení procedury pro dlouhodobý majetek.  
2. Vytvořte kartu DM pro každý existující majetek.  
3. Nastavení odpisových knih DM.  
4. Povolte integraci hlavní knihy podle následujících kroků.
5. Do pole **Hledat** zadejte **Knihy odpisů** a poté vyberte příslušný odkaz.  
6. Vyberte příslušnou knihu odpisů. Na kartě **Domů** ve skupině **Správa** vyberte možnost **Upravit** a otevřete okno **Karta knihy odpisů**.
7. V záložce s náhledem **Integrace** se ujistěte, že všechna pole jsou prázdná odstraněním všech značek zaškrtnutí. Pokud máte více než jednu odpisovou knihu, zapněte integraci hlavní knihy pro každý z nich.  
8. V deníku DM zadejte následující řádky pro každý majetek:
    - Řádek s pořizovací cenou.
    - Řádek s akumulovaným odpisem do konce předchozího fiskálního roku.
    - Řádek s akumulovaným odpisem od začátku běžného fiskálního roku do data, kdy je Dynamics NAV nastaven tak, aby začal vypočítávat odpisy.

Máte-li další počáteční zůstatky, můžete je nyní také zadat, například napsat\-dolů a zhodnocení.  

Pokud není dlouhodobý majetek integrován do hlavní knihy, přeskočte kroky 4 až 7.

## <a name="see-also"></a>Viz také
[Nastavení DM](fa-setup.md)  
[Správa DM](fa-manage.md)  
[Finance](finance-setup.md)  
[Vítejte v Dynamics NAV](across-get-started.md)

