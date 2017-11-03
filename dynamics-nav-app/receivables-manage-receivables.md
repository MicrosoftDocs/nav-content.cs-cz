---
title: "Přehled úloh pro správu pohledávek"
description: "Úlohy osnovy ke správě pohledávek a vyrovnání plateb položek zákazníka nebo dodavatele."
documentationcenter: 
author: SorenGP
ms.prod: dynamics-nav-2017
ms.topic: article
ms.devlang: na
ms.tgt_pltfrm: na
ms.workload: na
ms.search.keywords: customer payment, debtor, balance due, AR
ms.date: 08/10/2017
ms.author: sgroespe
ms.translationtype: HT
ms.sourcegitcommit: b9b1f062ee6009f34698ea2cf33bc25bdd5b11e4
ms.openlocfilehash: b9a486d099a6a52bec6ac6b23c21a3c341c20b14
ms.contentlocale: cs-cz
ms.lasthandoff: 10/23/2017

---
# <a name="managing-receivables"></a>Správa pohledávek
Běžný krok v jakémkoli finančním rytmu je odsouhlasení bankovních účtů, které vyžadují, abyste vyrovnali platby položek zákazníka nebo dodavatele k uzavření faktur a nákupních dobropisů.  

V [!INCLUDE[d365fin](includes/d365fin_md.md)] jeden z nejrychlejších způsobů k registraci plateb z okna **Deník odsouhlasení plateb** importem souboru bankovního výpisu nebo podáním. Platby jsou vyrovnány pro otevřené položky zákazníka nebo dodavatele založených na datových shodách mezi textem platby a informacemi o vstupu. Můžete zkontrolovat a změnit shody předtím, než zaúčtujete deník a zavřít položky bankovního účtu pro položky při účtování do deníku. Bankovní účet je odsouhlasený při vyrovnání všech plateb.

Existují však jiné užitečné místa k vyrovnání a odsouhlasení bankovních účtů:  

* Okno **Odsouhlasení bankovního účtu** vás také nechá zkontrolovat položky. Další informace naleznete v [Návod: Odsouhlasení Bankovních účtů samostatně](bank-how-reconcile-bank-accounts-separately.md).  
* Okno **Registrace Plateb** pomocí ruční kontroly plateb přijatých jako hotovost, šek nebo bankovní transakce na základě generovaného seznamu neplacených prodejních dokladů. Tato funkce je k dispozici pouze pro prodejní doklady.  
* Okno **Deník příjmu hotovosti**, kde můžete ručně uložit příjmy do příslušné účetní knihy, zákazníka nebo jiného účtu zadáním platebního řádku. Můžete před vystavením deníku o přebírání peněz aplikovat potvrzení o vrácení peněz na jednu nebo více otevřených položek, nebo položky zákazníka.  

Další částí správy pohledávek je vybírat nesplacené zůstatky, včetně finančních poplatků a vydávání upomínek. [!INCLUDE[d365fin](includes/d365fin_md.md)] nabízí způsoby k vykonání takových věcí také. Další informace naleznete v [Návod: Shromáždění zbývajících zůstatků](receivables-collect-outstanding-balances.md).  

Následující tabulka popisuje sekvekci úloh s odkazy na témata, která je popisují.  

| Popis | Odkaz |
| --- | --- |
| Vyrovnání plateb otevřených položek zákazníků nebo dodavatelů založených na importovaných bankovních výpisech a odsouhlasení bankovního účtu, pokud jsou všechny platby vyrovnány. |[Automatické vyrovnání plateb a odsouhlasení bankovních účtů](receivables-apply-payments-auto-reconcile-bank-accounts.md) |
| Vyrovnání plateb otevřených položek pro zákazníky založené na ručním zadání v seznamu neplacených prodejních dokladů. |[Návod: Manuální odsouhlasení plateb zákazníka z seznamu nezaplacených prodejních dokumentů](receivables-how-reconcile-customer-payments-list-unpaid-sales-documents.md) |
| Účtování hotovostních příjmových dokladů nebo refundace zákazníkům v deníků přijaté hotovosti a vyrovnaní položek zákazníka, kterýmkoli z deníků nebo z účtovaných položek. |[Návod: Ruční odsouhlasení plateb zákazníkům](receivables-how-apply-sales-transactions-manually.md) |
| Připomenutí zákaznických částek po splatnosti, vypočítání poplatků za úroky a financování a správa pohledávek. |[Návod: Shromáždění zbývajících zůstatků](receivables-collect-outstanding-balances.md) |
|Ujistěte se, že znáte náklady na zaslané zásilky přidělením dodatečných nákladů, jako je náklad, fyzická manipulace, pojištění a doprava, které vzniknou po prodeji.|[Návod: Použití Náklady na zboží k účtu pro dodatečné obchodní náklady](payables-how-assign-item-charges.md)|
|Nastavte toleranci, díky níž systém zavírá fakturu, i když platba, včetně případné slevy, zcela nezahrnuje částku na faktuře.|[Návod: Práce s tolerancemi plateb a platebními slevami](finance-payment-tolerance-and-payment-discount-tolerance.md)|
## <a name="see-also"></a>Viz také
[Prodej](sales-manage-sales.md)  
[Správa závazků](payables-manage-payables.md)  
[Práce s [!INCLUDE[d365fin](includes/d365fin_md.md)]](ui-work-product.md)  
[Obecné obchodní funkce](ui-across-business-areas.md)

