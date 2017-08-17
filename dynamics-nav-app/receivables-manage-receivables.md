---
title: "Správa pohledávek"
author: SorenGP
ms.custom: na
ms.date: 09/22/2016
ms.reviewer: na
ms.suite: na
ms.tgt_pltfrm: na
ms.topic: article
ms.prod: dynamics-nav-2017
ms.translationtype: Human Translation
ms.sourcegitcommit: 51adfb3588099c496f0946ff71da5c6fe518f070
ms.openlocfilehash: 3f2be627dfda9720e9f31fd227164d1c27116d2c
ms.contentlocale: cs-cz
ms.lasthandoff: 06/26/2017

---

# <a name="manage-receivables"></a>Správa pohledávek#
Centrálním úkolem ve Správě pohledávek je uplatňovat příchozí platby na související položky zákazníků nebo prodejců, a tím uzavřít související prodejní faktury nebo nákupní dobropisy jako zaplacené. Po uplatnění všech plateb můžete odsouhlasit bankovní účet.  

Tuto úlohu můžete provést v okně **Deník vyrovnávání plateb** importováním  bankovního výpisu nebo dávku, abyste mohli rychle zapsat platby v Dynamics NAV. Funkce automatických vyrovnání platby na jejich související položky pro otevřené položky zákazníka nebo dodavatele založené na datových shodách mezi textem platby a informacemi o vstupu. Před zveřejněním deníku můžete zkontrolovat a měnit automatické vyrovnání. Můžete zvolit uzavření jakékoli otevřené položky bankovního účtu související s vyrovnanými položkami hlavní knihy, když se účtujete deník. To znamená, že bankovní účet je automaticky odsouhlasený při vyrovnání všech plateb.

**Poznámka**:  Můžete odsouhlasit bankovní účty jako samostatný úkol v okně **Odsouhlasení bankovního účtu**, které taktéž podporuje kontrolu položek hlavní knihy.  Další informace naleznete v tématu [Jak na: Odsouhlasení Bankovních účtů samostatně](bank-how-reconcile-bank-accounts-separately.md).

Případně můžete platby zapsat v okně **Registrace Plateb**pomocí ruční kontroly plateb přijatých jako hotovost, šek nebo bankovní transakce na základě generovaného seznamu neplacených prodejních dokladů. Tato funkce je k dispozici pouze pro prodejní doklady.

Jako další manuální odsouhlasení plateb můžete zaúčtovat každý příjem do příslušné účetní knihy, zákazníka nebo jiného účtu zadáním platebního řádku do okna **Deník přijaté hotovosti**  V takovém případě můžete před vystavením deníku o přebírání peněz aplikovat potvrzení o vrácení peněz na jednu nebo více otevřených položek, nebo můžete vyrovnat vytvořené položky zákazníka.

Dalším úkolem při správě pohledávek je vybírat nesplacené zůstatky, včetně správy poplatků za sestavení financí a vydávání upomínek.

Následující tabulka popisuje postup úkolů s odkazy na témata, která je popisují.

|Viz |také |
|---|----|
|Vyrovnat platby otevřených položek zákazníků nebo dodavatelů založených na importovaných bankovních výpisech a odsouhlasení bankovního účtu, pokud jsou všechny platby vyrovnány.|[Vyrovnejte platby automaticky a odsouhlaste bankovní účty](receivables-apply-payments-auto-reconcile-bank-accounts.md)|
|Vyrovnejte platby otevřených položek pro zákazníky založené na ručním zadání v seznamu neplacených prodejních dokladů. | [Návody Odsouhlasit platby zákazníka manuálně z seznamu Nezaplacených prodejních dokumentů.](receivables-how-reconcile-customer-payments-list-unpaid-sales-documents.md)|
|Zaúčtovat hotovostní příjmový doklad nebo refundovat zákazníkům v deníků přijaté hotovosti a vyrovnat položky zákazníka, kterýmkoli z deníků nebo z účtovaných položek. | [Návody Odsouhlasit platby zákazníků ručně](receivables-how-apply-sales-transactions-manually.md) |
|Připomenout zákazníkům částky po splatnosti, vypočítat poplatky za úroky a financování a spravovat pohledávky. | [Návody Vyzvednout zbývající zůstatky](receivables-collect-outstanding-balances.md) |

## <a name="see-also"></a>Viz také
[Správa prodeje](sales-manage-sales.md)  
[Správa závazků](payables-manage-payables.md)  
[Práce s Dynamics NAV](ui-work-product.md)  
[Napříč obchodními oblastmi](ui-across-business-areas.md)

