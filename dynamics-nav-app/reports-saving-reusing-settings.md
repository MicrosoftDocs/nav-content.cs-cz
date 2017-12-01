---
title: "Použití a úprava uloženého nastavení v přehledech"
description: "Popisuje použití předdefinovaných možností a filtrů pro přizpůsobení sestavy a generování správných dat."
author: jswymer
ms.prod: dynamics-nav-2018
ms.topic: article
ms.devlang: na
ms.tgt_pltfrm: na
ms.workload: na
ms.search.keywords: customization, personalization
ms.date: 09/08/2017
ms.author: jswymer
ms.translationtype: HT
ms.sourcegitcommit: 4fefaef7380ac10836fcac404eea006f55d8556f
ms.openlocfilehash: c63b5585f724a60007e836ab06333798bce65129
ms.contentlocale: cs-cz
ms.lasthandoff: 10/16/2017

---
# <a name="managing-saved-settings-on-reports"></a>Správa uloženého nastavení sestav
V závislosti na spuštěné sestavě vám může být zobrazena stránka, která vám umožní nastavit určité možnosti a filtry pro změnu dat, která jsou součástí generované sestavy. Tato stránka je známá jako stránka požadavku o sestavu. Sestava může obsahovat jedno nebo více *Uložených nastavení*, které můžete použít na sestavu ze stránky požadavku. *Uložená nastavení* jsou  v podstatě předdefinované možnosti a filtry. Použití uložených nastavení je rychlý a spolehlivý způsob, jak důsledně vytvářet sestavy, které obsahují správná data.

Můžete si zobrazit uložená nastavení, která jsou Vám k dispozici pro sestavu v sekci **Uložená nastavení** na stránce požadavku o sestavu.  

## <a name="to-apply-saved-settings-to-a-report"></a>Použití uložených nastavení pro sestavu
1. Otevřete sestavu.

   Zobrazí se stránka požadavku o sestavu.    
2. Na stránce v sekci **Uložené nastavení**, nastavte políčko **Název** k uložení nastavení, které chcete použít.

   Sekce **Uložené nastavení** se zobrazí pouze, pokud byla sestava spuštěná již dříve, nebo pokud existují uložené položky nastavení. Uložená položka nastavení s názvem **Naposledy použité možnosti a filtry** je vždy k dispozici. Tato nastavení jsou volby a hodnoty filtru, které byly použity při posledním spuštění sestavy.

## <a name="administer-saved-report-settings-for-users"></a>Správa uložených nastavení sestav pro uživatele
Máte-li správná oprávnění, můžete pro všechny uživatele ve společnosti zobrazit, vytvořit a upravit uložená nastavení pro všechny sestavy. Můžete přiřadit uložená nastavení sestav jednotlivým uživatelům nebo všem uživatelům ve společnosti.

Spravujte uložená nastavení na stránce 1506 **Nastavení sestav**. Pro otevření stránky zvolte ikonu ![Vyhledat stránku nebo sestavu](media/ui-search/search_small.png "Ikona Vyhledat stránku nebo sestavu"), zadejte **Nastavení sestav** a vyberte příslušný odkaz.

Ze stránky **Nastavení sestav** můžete vytvořit nové nastavení od začátku nebo vytvořit jako kopii a následně modifikovat existující nastavení. Chcete-li upravit nastavení a filtry pro nastavení, zvolte **Upravit**.

> [!NOTE]
> Funkce uložených nastavení sestav je relevantní pouze tehdy, když je vlastnost SaveValues ​​na stránce požadavku nastavena na Ano. Vlastnost SaveValues ​je nastavena ve vývojovém prostředí.  

> [!Important]
> Pokud vytvoříte uloženou položku nastavení pro všechny uživatele a má stejný název jako existující uložené nastavení pro určitého uživatele, nebude tento uživatel moci použít uložená nastavení, která je přiřazena všem.  V poli Uložená nastavení na stránce požadavku o sestavu uživatel uvidí dvě možnosti uloženého nastavení se stejným názvem. Nicméně, bez ohledu na to, kterou volbu zvolí, budou použity uložená nastavení pro uživatele.

## <a name="see-also"></a>Viz také
[Práce se sestavami](ui-work-report.md)  

