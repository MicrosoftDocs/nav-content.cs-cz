---
title: "Uložené nastavení sestav"
author: jswymer
ms.custom: na
ms.date: 09/26/2016
ms.reviewer: na
ms.suite: na
ms.tgt_pltfrm: na
ms.topic: article
ms.prod: dynamics-nav-2017
ms.translationtype: Human Translation
ms.sourcegitcommit: 51adfb3588099c496f0946ff71da5c6fe518f070
ms.openlocfilehash: 0f11d862315c8ecd160cd18afb0a72a2d684b9b2
ms.contentlocale: cs-cz
ms.lasthandoff: 06/26/2017

---
# <a name="saved-settings-on-reports"></a>Uložené nastavení sestav
V závislosti na spuštěné sestavě vám může být zobrazena stránka, která vám umožní nastavit určité možnosti a filtry pro změnu dat, která jsou součástí generované sestavy. Tato stránka je známá jako stránka požadavku o sestavu. Sestava může obsahovat jedno nebo více *Uložených nastavení*, které můžete použít na sestavu ze stránky požadavku. *Uložená nastavení* jsou  v podstatě předdefinované možnosti a filtry. Použití uložených nastavení je rychlý a spolehlivý způsob, jak důsledně vytvářet sestavy, které obsahují správná data.

Můžete si zobrazit uložená nastavení, která jsou Vám k dispozici pro sestavu v sekci **Uložená nastavení** na stránce požadavku o sestavu.

## <a name="to-apply-saved-settings-to-a-report"></a>Použití uložených nastavení pro sestavu
1.  Otevřete sestavu.

    Zobrazí se stránka požadavku o sestavu.    
2.  Na stránce v sekci **Uložené nastavení**, nastavte políčko **Název** k uložení nastavení, které chcete použít.

    Sekce **Uložené nastavení** se zobrazí pouze, pokud byla sestava spuštěná již dříve, nebo pokud existují uložené položky nastavení. Uložená položka nastavení s názvem **Naposledy použité možnosti a filtry** je vždy k dispozici. Tato nastavení jsou volby a hodnoty filtru, které byly použity při posledním spuštění sestavy.

## <a name="administer-saved-report-settings-for-users"></a>Správa uložených nastavení sestav pro uživatele
Máte-li správná oprávnění, můžete pro všechny uživatele ve společnosti zobrazit, vytvořit a upravit uložená nastavení pro všechny sestavy. Můžete přiřadit uložená nastavení sestav jednotlivým uživatelům nebo všem uživatelům ve společnosti.

Spravujte uložená nastavení na stránce 1506 **Nastavení sestav**. Pro otevření stránky musíte v pravém horním rohu vybrat ikonu **Vyhledat stránku nebo sestavu**, zadejte **Nastavení sestav** a vyberte příslušný odkaz. 

Ze stránky **Nastavení sestav** můžete vytvořit nové nastavení od začátku nebo vytvořit jako kopii a následně modifikovat existující nastavení. Chcete-li upravit nastavení a filtry pro nastavení, zvolte **Upravit**.

**Poznámky**:
-    Funkce uložených nastavení sestav je relevantní pouze tehdy, když je vlastnost SaveValues ​​na stránce požadavku nastavena na Ano. Vlastnost SaveValues ​je nastavena ve vývojovém prostředí.
-    Pokud vytvoříte uloženou položku nastavení pro všechny uživatele a má stejný název jako existující uložené nastavení pro určitého uživatele, nebude tento uživatel moci použít uložená nastavení, která je přiřazena všem.  V poli Uložená nastavení na stránce požadavku o sestavu uživatel uvidí dvě možnosti uloženého nastavení se stejným názvem. Nicméně, bez ohledu na to, kterou volbu zvolí, budou použity uložená nastavení pro uživatele.

## <a name="see-also"></a>Viz také
[Plánované spuštění sestavy](ui-schedule-report.md)

