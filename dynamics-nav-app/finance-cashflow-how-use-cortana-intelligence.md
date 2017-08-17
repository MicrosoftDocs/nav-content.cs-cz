---
title: "Návody: Předvídat prognózu cashflow"
author: bholtorf
ms.custom: na
ms.date: 09/16/2016
ms.reviewer: na
ms.suite: na
ms.tgt_pltfrm: na
ms.topic: article
ms.prod: dynamics-nav-2017
ms.translationtype: Human Translation
ms.sourcegitcommit: 51adfb3588099c496f0946ff71da5c6fe518f070
ms.openlocfilehash: f657509fc2195674db81f47bc5ae31b7ba1aa40e
ms.contentlocale: cs-cz
ms.lasthandoff: 06/26/2017

---

# <a name="how-to-make-predictive-cash-flow-forecasts"></a>Návody: Předvídat prognózu cashflow
Předpovědi cashflow pomáhají zajistit, aby vaše firma měla dostatek hotovosti na finanční povinnosti a užitečné identifikační úpravy. Například pokud máte přebytek hotovosti, můžete splatit nějaké dluhy a oceníte brzké varování, když bude zbývat málo času. 

Cortana Intelligence používá službu Azure Machine Learning k zabezpečení spolehlivé předpovědi. Například předpověď z Cortana Intelligence může pomoci předpovědět a vyhnout se nedostatku hotovosti. Služba kombinuje historické informace s aktuálním zaúčtováním závazků a pohledávek včetně zaúčtování s nadcházejícími termíny splnění. Tyto zahrnují:
* Nákupní objednávky
* Prodejní objednávky
* Zaúčtovaní prodeje a nákupní faktury
* Dobropisy

## <a name="before-you-start"></a>Než začnete  
Je pár věcí ke splnění než budete moci použít Cortana Intelligence pro prognózu cashflow. 
* Pokud ještě nepoužíváte prognózu cashflow, budete muset nastavit:
    * Ještě jedno nastavení v **Nastavení cashflow**. 
    * Účty pro závazky, pohledávky, prodejní objednávky a nákupní objednávky. Cortana Intelligence používá zaúčtování v těchto účtech.
    * Jeden nebo více prognóz cashflow v **Prognóza cashflow**. Ujistěte se, že zahrnujete nákupní objednávky, prodejní objednávky, pohledávky a závazky jako zdroje.  
    Pro další informace hledejte _Prognóza cashflow_ v systému Nápovědy. 
* Je potřeba znát API URL a klíč rozhraní API pro webovou službu předpovědi pro použití.  
    Můžete použít Azure Machine Learning nebo jinou službu. Alternantivně veřejný model pojmenovaný _Model prognózování pro Microsoft Dynamics NAV_ Pro použití modelu postupujte následově:

    1. V prohlížeči, jděte na [Cortana Intelligence Gallery](https://go.microsoft.com/fwlink/?linkid=828352)
    2. Hledejte _Model prognózování pro Microsoft Dynamics NAV_ a pak otevřete model v Azure Machine Learning Studio.
    3. Použijte svůj Microsoft účet k přihlášení do pracovní prostoru a pak zkopírujte model.
    4. Spusťte model a publikovat.
    5. Zapsat poznámku o API URL a klíči rozhraní API. Použijete tyto přihlašovací údaje, když nastavíte Cortana Intelligence v Microsoft Dynamics NAV.  

* Zvažte, jak často počítat prognózu. Služba Azure Machine Learning má limity dle použití. Například pokud máte hodně zboží, bude lepší počítat méně často. 
* Buďte přiřazený k Centru rolí účetního. 

## <a name="set-up-cortana-intelligence"></a>Nastavit Cortana Intelligence
Můžete použít asistovaného průvodce instalace k nastavení prognózy cashflow. Průvodce pomáhá určit věci, např. jak často aktualizovat prognózu, účty, na kterých to založit, informace, kdy platit daně, a zda požít Cortana Intelligence.  

Pokud již prognózu cashflow využíváte a jen chcete zapnout Cortana Intelligence, můžete také využít manuální proces. Jakmile se přihlásíte, zobrazí se notifikace v modrém pruhu nahoře pracovního prostoru. K nastavení Cortana Intelligence rovnou, vyberte **Ano, prosím**. Zpráva se zobrazí pouze jednou. Pokud to zavřete, použijte mauální proces k nastavení Cortana Intelligence.  

**Tip:** Zvažte délku období, které bude služba využívat ve výpočtech. Čím více dat poskytnete, tím přesnější prognózy budou. Také dejte pozor na velké odchylky v období. Také ovlivní předpovědi. Pokud Cortana Intelligence nenajde dostatek dat, nebo se budou data hodně lišit, služba nevytvoří předpověď. 

Použít asistovaného průvodce nastavením.
1. V centru rolí Účetní pod přehledem **Prognóza cashflow**, zvolte akci **Otevřít asistované nastavení**.
2. Vyplňte pole podle potřeby v každém kroku průvodce.

Použít manuální proces:
1. Hledejte **Nastavení cashflow** a zvolte související odkaz.
2. Rozbalte záložku s náhledem **Cortana Intelligence** a pak vyplňte pole podle potřeby.

## <a name="turn-on-cortana-intelligence-for-cash-flow-forecasts"></a>Zapnout Cortana Intelligence pro prognózu cashflow.
1. Hledejte **Prognóza cashflow**, pak zvolte související odkaz.
2. Zvolte akci **List cashflow**.
3. Na stránce **List cashflow** zvolte akci **Navrhnout řádky listu**.  
4. Pod **Typy zdrojů k zahrnutí** zvolte zaškrtávací políčko **Předpověď Cortana Intelligence**.

## <a name="investigate-a-cash-flow-forecast"></a>Zjistit prognózu cashflow
Chcete-li se dobře podívat na data za prognózou včetně odchylky, vyberte sloupec **Cortana Intelligence**. První řádek v tabulce zobrazuje odchylku. Ostatní řádky jsou uspořádány podle zdrojového dokumentu.  

Například můžete vidět, jak si předpověď:    
* Poradí s potvrzenými prodeji a nákupy. 
* Odečítá závazky a přičítá pohledávky.
* Přeskakuje duplikované prodejní a nákupní objednávky

## <a name="see-also"></a>Viz také  
[Pracujte s Dynamics NAV](ui-work-product.md)
