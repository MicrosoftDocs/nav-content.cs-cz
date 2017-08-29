---
title: "Vytváření číselných řad"
author: SusanneWindfeldPedersen
ms.custom: na
ms.date: 09/22/2016
ms.reviewer: na
ms.suite: na
ms.tgt_pltfrm: na
ms.topic: article
ms.prod: dynamics-nav-2017
ms.translationtype: Human Translation
ms.sourcegitcommit: 51adfb3588099c496f0946ff71da5c6fe518f070
ms.openlocfilehash: 22b3bcf71c99e106527d6bfa35478045d29b9629
ms.contentlocale: cs-cz
ms.lasthandoff: 06/26/2017

---

# <a name="create-number-series"></a>Vytváření číselných řad

Pro každou společnost, kterou jste založili, musíte přiřadit jedinečné identifikační kódy věcem, jako jsou účty hlavní knihy, účty zákazníků a dodavatelů, faktury a dokumenty. Číslování je důležité nejen pro identifikaci, dobře navržený systém číslování také usnadňuje správu a snadnou analýzu společnosti a může snížit počet chyb, ke kterým dochází při zadávání dat.

Můžete nastavit kompletní číslovací systém s neomezeným počtem číselných řad. Číselné řady můžete používat pro všechny typy dokumentů a deníků, stejně jako pro hlavní údaje, jako jsou zákazníci, položky a projekty.

Můžete kombinovat použití číselných řad s manuálním číslováním.

Systém číslování vytvoříte nastavením jednoho nebo více kódů pro každý typ hlavních dat nebo dokumentu. Například můžete nastavit jeden kód pro číslování zákazníků, jiný kód pro číslování prodejních faktur a další kód pro číslování dokumentů ve všeobecných denících.

Pokud nastavíte kód, musíte nastavit alespoň jednu číselnou řadu. Řádek číselné řady obsahuje informace jako první a poslední číslo v sérii a počáteční datum. Můžete nastavit více než jednu číselnou řadu pro každý kód číselné řady s jiným počátečním datem pro každý řádek. Řady budou použity postupně počínaje každou sérií v příslušném počátečním datu.

Chcete-li pro jeden typ hlavních dat použít více než jeden kód číselné řady - například chcete-li použít různé číselné řady pro různé kategorie zboží - můžete použít vztahy číselných řad.

Vedle čísel, které přiřadíte ručně nebo pomocí systému číslování, jsou všechny transakce (záznamy v knihách) automaticky přiděleny po sobě jdoucím číslům. Tyto čísla můžete vidět v políčku **Číslo položky** v okně souvisejících položek. Nemůžete editovat nebo mazat tyto čísla.

## <a name="to-create-relationships-between-number-series"></a>Vytváření vztahů mezi číselnými řadami
Pokud jste nastavili více než jednu číselnou řadu pro stejný druh informací nebo transakcí, můžete vytvářet vztahy mezi kódy. Tato funkce vám pomůže  při rozhodování mezi kódy pokud používáte čísla.

1. V pravém horním rohu zvolte ikonu **Vyhledat stránku nebo sestavu**, zadejte **Číselná řada** a poté vyberte příslušný odkaz.
2. Vyberte řádek s číselnou řadou, pro kterou chcete vytvořit vztahy, a poté zvolte **Vztah**.
3. V poli **Kód řady** vložte kód číselné řady, kterou chcete spojit s řadou, kterou jste vybrali v kroku 2.
4. Přidejte řádek pro každý kód, který chcete spojit s vybranou číselnou řadou.
5. Zavřete okno.

Nyní, když nastavíte něco, co vyžaduje číslo, můžete použít vztahy, které jste vytvořili k výběru mezi souvisejícími číselnými řadami.

## <a name="see-also"></a>Viz také
[Práce s Dynamics NAV](ui-work-product.md)

