---
title: "Nastavení návrhů hodnot polí"
description: "Chcete-li rychle a přesně zabránit manuálním výpočtům a dokončení úloh, můžete nastavit automatické zadávání dat tak, aby Dynamics NAV vyplňoval vybraná pole."
documentationcenter: 
author: SorenGP
ms.prod: dynamics-nav-2018
ms.topic: article
ms.devlang: na
ms.tgt_pltfrm: na
ms.workload: na
ms.date: 08/15/2017
ms.author: sgroespe
ms.translationtype: HT
ms.sourcegitcommit: 4fefaef7380ac10836fcac404eea006f55d8556f
ms.openlocfilehash: 7c68019ff32d6fbe700975b0897dff9474da7bc1
ms.contentlocale: cs-cz
ms.lasthandoff: 10/16/2017

---
# <a name="letting-included365finincludesd365finmdmd-suggest-values"></a>Nechání [!INCLUDE[d365fin](includes/d365fin_md.md)] navrhovat pole
[!INCLUDE[d365fin](includes/d365fin_md.md)] vám pomůže dokončit úkoly rychleji a správněji tím, že předvyplní pole nebo doplní řádky daty, které byste jinak museli spočítat a zadat. Přestože je tato automatická zadání vždy správná, pokud chcete, můžete ji později změnit.

Funkce, která pro vás zadává hodnoty do polí, je typicky nabízena pro úkoly, kde zadáváte velké objemy transakčních dat a chcete se vyhnout chybám a zároveň šetřit čas. Toto téma obsahuje výběr takových funkcí. Další sekce budou přidány v následujících aktualizacích [!INCLUDE[d365fin](includes/d365fin_md.md)].

## <a name="the-suggest-balancing-amount-check-box-in-the-general-journal-batches-window"></a>Zaškrtávací políčko **Navrhovat vyrovnávací částku** v okně **Listy finančního deníku**
Pokud například zadáváte řádky finančního deníku pro více výdajů, které musí být všechny zaslány na stejný bankovní účet, pak pokaždé, když pro výdaj zadáte nový řádek deníku, můžete mít pole **Částka** na řádku bankovního účtu automaticky aktualizováno na částku, která vyrovnává výdaje. Další informace o práci s finančními deníky naleznete v části [Práce s finančními deníky](ui-work-general-journals.md).

### <a name="to-have-the-amount-field-on-balancing-general-journal-lines-filled-automatically"></a>Chcete-li mít pole **Částka** na vyrovnávacích řádcích finančního deníku automaticky vyplněná.
1. Zvolte ikonu ![Vyhledat stránku nebo sestavu](media/ui-search/search_small.png "Ikona Vyhledat stránku nebo sestavu"), zadejte **Finanční deník** a pak vyberte související odkaz.
2. Na řádku pro vámi preferovanou dávku finančního deníku vyberte zaškrtávací políčko **Navrhovat vyrovnávací částku**.
3. Otevřete finanční deník a pokračujte k zaznamenání a účtování transakcí pomocí popsané funkce pro automatické zadání hodnoty pole.       

Další informace o tom, jak nastavit osobní dávku finančního deníku, například jak zpracovat výdaje, nalezte v části [Práce s finančními deníky](ui-work-general-journals.md).

## <a name="the-automatically-fill-date-received-field-in-the-payment-registration-window"></a>Pole **Automaticky vyplnit datum přijetí** v okně **Registrace plateb**
Okno **Registrace plateb** zobrazuje neuhrazené příchozí platby jako řádky, které představují prodejní doklady, u nichž je částka splatná. Další informace o použití zákaznických plateb naleznete v[Návod: Ruční odsouhlasení zákaznických plateb ze seznamu neuhrazených prodejních dokladů](receivables-how-reconcile-customer-payments-list-unpaid-sales-documents.md).

Vaší hlavní akcí je zaškrtnout v okně políčko **Platba provedena** a vyplnit pole **Datum přijetí**. Váš [!INCLUDE[d365fin](includes/d365fin_md.md)] můžete nastavit tak, aby když zaškrtnete políčko **Platba provedena**, automaticky vložil pracovní datum do pole **Datum přijetí**.

### <a name="to-have-the-date-received-field-in-the-payment-registration-window-filled-automatically"></a>Automatické vyplnění pole **Datum přijetí** v okně **Registrace plateb**
1. Zvolte ikonu ![Vyhledat stránku nebo sestavu](media/ui-search/search_small.png "Ikona Vyhledat stránku nebo sestavu"), zadejte **Nastavení registrace plateb** a poté vyberte příslušný odkaz.
2. Zaškrtněte políčko **Automaticky vyplnit datum přijetí**.
3. Otevřete okno **Registrace plateb** a pokračujte v procesu zpracování příchozích plateb zákazníků pomocí popsané funkce pro automatické zadání hodnoty pole.

## <a name="see-also"></a>Viz také
[Práce s [!INCLUDE[d365fin](includes/d365fin_md.md)]](ui-work-product.md)  
[Finance](finance.md)

