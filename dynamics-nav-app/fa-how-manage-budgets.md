---
title: "Návod: Správa rozpočtů pro dlouhodobý majetek"
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
ms.openlocfilehash: 47b5e0abcae4fab92da5dd9c1bda350a37ec0358
ms.contentlocale: cs-cz
ms.lasthandoff: 06/26/2017

---

# <a name="how-to-manage-budgets-for-fixed-assets"></a>Návod: Správa rozpočtů pro dlouhodobý majetek
Můžete nastavit rozpočty pro dlouhodobý majetek. To umožňuje zahrnout veškeré očekávané pořízení a prodeje v sestavách.  

 Chcete-li připravit plánovaný výkaz zisku a ztráty, rozpočtovou rozvahu a hotovostní rozpočet, potřebujete informace o budoucích investicích, prodeji a odpisování DM. Tyto informace můžete získat ze zprávy **Dlouhodobý majetek - Očekávaná hodnota**. Než vytisknete tento přehled, musíte připravit rozpočet.  

## <a name="to-budget-the-acquisition-cost-of-a-fixed-asset"></a>Rozpočet na pořizovací cenu DM
Chcete-li připravit rozpočet, musíte v budoucnu nastavit karty DM, který chcete koupit. Rozpočet DM je stanoven jako běžný dlouhodobý majetek, ale musí být nastaven tak, aby se nezaúčtoval do hlavní knihy.

Když uveřejníte pořizovací cenu, zadejte číslo rozpočtu DM v poli **Číslo rozpočtu DM** . Zaúčtuje se pořizovací cena s opačným znaménkem pro rozpočet majetku. To znamená, že celková pořizovací cena rozpočtu majetku je rozdílem mezi rozpočtovanými a skutečnými pořizovacími náklady.

1. V pravém horním rohu zvolte ikonu **Vyhledat stránku nebo sestavu**, zadejte **Dlouhodobý majetek** a pak vyberte související odkaz.
2. Zvolte akci **Nový** pro vytvoření nové karty DM pro rozpočet DM.
3. Zaškrtněte políčko **Rozpočtový majetek**, abyste zabránili zaúčtování do hlavní knihy.
4. Vyplňte zbývající pole, přiřaďte odpisovou knihu a poté zaúčtujte první pořizovací cenu s rozpočtem DM zadaným v poli **Číslo rozpočtu DM** na řádku deníku. Další informace naleznete v [Návod: Získání DM](fa-how-acquire.md).

## <a name="to-budget-the-disposal-of-a-fixed-asset"></a>Rozpočet na vyřazení DM
Pokud máte v úmyslu prodat majetek během rozpočtového období, můžete zadat informace o prodejní ceně a dni prodeje.

1. V pravém horním rohu zvolte ikonu **Vyhledat stránku nebo sestavu**, zadejte **Dlouhodobý majetek** a pak vyberte související odkaz.
2. Vyberte dlouhodobý majetek, který chcete vyřadit a pak vyberte akci **Odpisy knih**.
3. V okně **Odpisové knihy DM** vyplňte pole **Předpokládaný den vyřazení** a **Předpokládané příjmy z vyřazení**. Vyberte pole a přečtěte si krátký popis pole nebo klikněte na odkaz pro další informace.

## <a name="to-view-projected-disposal-values"></a>Zobrazení očekávané hodnoty vyřazení
Chcete-li zobrazit hodnoty předpokládaných vyřazení a vypočítat zisk a ztráty, můžete použít zprávu **Odhadovaná hodnota DM**.

1. V pravém horním rohu zvolte ikonu **Vyhledat stránku nebo sestavu**, zadejte **Odhadovaná hodnota DM** a pak vyberte související odkaz.
2. Vyplňte pole podle potřeby.
3. Zvolte tlačítko **Tisk** nebo **Náhled**.

## <a name="to-budget-depreciation"></a>Odpis rozpočtu
Pro výpočet budoucího odpisu můžete použít výkaz **Dlouhodobý majetek - odhadovaná hodnota**. Zpráva uvádí účetní hodnotu a akumulované odpisy na začátku vybraného období, změny v daném období a účetní hodnotu a akumulované odpisy na konci vybraného období.

1. V pravém horním rohu zvolte ikonu **Vyhledat stránku nebo sestavu**, zadejte **Odhadovaná hodnota DM** a pak vyberte související odkaz.
2. Vyplňte pole podle potřeby.
3. Chcete-li zobrazit souhrnné hodnoty pro všechen majetek, zrušte zaškrtnutí políčka **Tisk dle DM**.
4. Ponechte záložku s náhledem **Dlouhodobý majetek** prázdnou, aby byl zahrnut všechen majetek. Do pole **Rozpočtový majetek** zadejte **Ne**, chcete-li vyloučit rozpočtovaný majetek nebo **Ano**, abyste viděli pouze rozpočtovaný majetek.
5. Zvolte tlačítko **Tisk** nebo **Náhled**.

## <a name="see-also"></a>Viz také
[Správa DM](fa-manage.md)  
[Nastavení DM](fa-setup.md)  
[Finance](finance-setup.md)  
[Vítejte v Dynamics NAV](across-get-started.md)

