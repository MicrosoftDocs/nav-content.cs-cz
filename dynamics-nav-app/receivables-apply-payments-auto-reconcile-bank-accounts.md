---
title: "Úkoly k vyrovnání bankovních účtů a vyrovnání plateb souvisejícich položek"
description: "Představuje úkoly, jako jsou vyrovnání banky, pohledávek a závazných účtů, účtované příjmy nebo výdaje a vyrovnání plateb."
documentationcenter: 
author: SorenGP
ms.prod: dynamics-nav-2018
ms.topic: article
ms.devlang: na
ms.tgt_pltfrm: na
ms.workload: na
ms.search.keywords: payment process, direct payment posting, reconcile payment, expenses, cash receipts
ms.date: 03/29/2017
ms.author: sgroespe
ms.translationtype: HT
ms.sourcegitcommit: b9b1f062ee6009f34698ea2cf33bc25bdd5b11e4
ms.openlocfilehash: 33c0661a2ebf9b8d9b817c026a8c9abf0f0eff91
ms.contentlocale: cs-cz
ms.lasthandoff: 10/23/2017

---
# <a name="applying-payments-automatically-and-reconciling-bank-accounts"></a>Automatikcé vyrovnání plateb a odsouhlasení bankovních účtů
Musíte pravidelně sladit své účty s bankami, pohledávkami a závazky uhrazením plateb zaznamenaných v bance na jejich souvisejících nezaplacených fakturách a dobropisech nebo jiných otevřených položkách v [!INCLUDE[d365fin](includes/d365fin_long_md.md)].  

Tuto úlohu můžete provést v okně **Deník vyrovnávání plateb** importováním bankovního výpisu nebo dávky, abyste mohli rychle registrovat platby. Platby jsou vyrovnány k otevřeným věcným položkám zákazníka nebo dodavatele, založené na shodě mezi textem platby a informací položky. Před zveřejněním deníku můžete zkontrolovat a měnit automatické vyrovnání. Můžete zvolit uzavření jakékoli otevřené položky bankovního účtu související s vyrovnanými položkami hlavní knihy, když se účtujete deník. Bankovní účet je automaticky odsouhlasený při vyrovnání všech plateb.  

Pro import bankovních výpisů je nejdříve nastavit a povolit službu bankovní konverze dat. Další informace naleznete v tématu [Návod: Nastavení služby převodu bankovních dat.](bank-how-setup-bank-data-conversion-service.md).  

Následující tabulka popisuje sekvenci úkolů s odkazy na téma, která je popisují.  

| Viz | také |
| --- | --- |
| Uhradit platby k otevřeným položkám zákazníka nebo dodavatele importem bankovního výpisu a odsouhlasit bankovní účet při uhrazení všech plateb. |[Návod:: Odsouhlasení plateb pomocí automatického vyrovnání](receivables-how-reconcile-payments-auto-application.md) |
| Ručně uhradit platby zobrazením podrobných informací o shodných datech a návrzích pro kandidátské otevřené položky, které mají být uhrazeny. |[Návod:: Přezkoumání nebo uhrazení plateb po automatické aplikaci](receivables-how-review-apply-payments-auto-application.md) |
| Vyřešte platby, které nelze automaticky vyrovnat na jejich související otevřené položky. Například se částky liší nebo proto, že související položka neexistuje. |[Návod:: Odsouhlasení plateb, které nelze vyrovnat automaticky](receivables-how-reconcile-payments-cannot-apply-auto.md) |
| Odkazovat text na platbách na konkrétního zákazníka, dodavatele nebo účet hlavní knihy, aby došlo vždy po zaúčtování periodických pokladních příjmů nebo výdajů na tyto účty, pokud neexistují žádné doklady pro vyrovnání. |[Návod:: Mapování textu periodických plateb na účtech pro automatické odsouhlasení](receivables-how-map-text-recurring-payments-accounts-auto-reconcilliation.md) |

## <a name="see-also"></a>Viz také
[Správa pohledávek](receivables-manage-receivables.md)  
[Prodej](sales-manage-sales.md)  
[Práce s [!INCLUDE[d365fin](includes/d365fin_md.md)]](ui-work-product.md)

