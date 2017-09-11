---
title: "Použití automatických plateb a odsouhlasení bankovních účtů"
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
ms.openlocfilehash: 11df387c16e19421090531fd03c209103b9989d9
ms.contentlocale: cs-cz
ms.lasthandoff: 06/26/2017

---

# <a name="apply-payments-automatically-and-reconcile-bank-accounts"></a>Použití automatických plateb a odsouhlasení bankovních účtů
Musíte pravidelně sladit své účty s bankami, pohledávkami a závazky v Dynamics NAV uhrazením plateb zaznamenaných v bance na jejich souvisejících nezaplacených fakturách a dobropisech nebo jiných otevřených položkách v Dynamics NAV.

Tuto úlohu můžete provést v okně **Deník odsouhlasení plateb** importováním souboru  bankovního výpisu, abyste mohli rychle zapsat platby v Dynamics NAV. Funkce automatických aplikací uplatňuje platby k jejich souvisejícím otevřeným položkám zákazníka nebo dodavatele založených na datových shodách mezi textem platby a zadaných informací. Před zaúčtováním deníku můžete zkontrolovat a měnit automatické aplikace. Při účtování deníku můžete uzavřít všechny otevřené položky bankovního účtu, které se vztahují k zaplaceným položkám. To znamená, že bankovní účet je automaticky odsouhlasen při zaplacení všech plateb.

Chcete-li povolit import bankovních výpisů jako bankovního zdroje, musíte nejprve nastavit a aktivovat službu Envestnet Yodlee Bank Feed a poté propojit své bankovní účty se souvisejícími online bankovními účty. Další informace naleznete v tématu [Návod: Nastavení služby Envestnet Yodlee Bank Feed](bank-how-setup-bank-statement-service.md).

**Poznámka**: Služba Envestnet Yodlee Bank Feeds nebo jiná služba bankovního poskytovatele nemusí být ve vašem systému k dispozici. Obraťte se na svého partnera Microsoft, chcete-li pro import bankovních výpisů použít bankovní službu.

Případně můžete použít službu převodu bankovních dat, abyste měli bankovní výpis v jakémkoli formátu převedený na datový proud, který můžete importovat do Dynamics NAV. Další infromace naleznete v tématu [Návod: Nastavení služby převodu bankovních dat](bank-how-setup-bank-data-conversion-service.md).

Následující tabulka popisuje sekvenci úkolů s odkazy na téma, která je popisují.

|Popis |Odkaz |
|---|----|
|Uhradit platby k otevřeným položkám zákazníka nebo dodavatele importem bankovního výpisu a odsouhlasit bankovní účet při uhrazení všech plateb. | [Návod: Odsouhlasení plateb pomocí automatické aplikace](receivables-how-reconcile-payments-auto-application.md) |
|Ručně uhradit platby zobrazením podrobných informací o shodných datech a návrzích pro kandidátské otevřené položky, které mají být uhrazeny. | [Návody: Přezkoumání nebo uhrazení plateb po automatické aplikaci](receivables-how-review-apply-payments-auto-application.md)
|Vyřešíte platby, které nelze automaticky vyrovnat na jejich související otevřené položky například proto, že se částky liší nebo protože související věcná položka neexistuje. | [Návod: Odsouhlasení plateb, které nelze uplatnit automaticky](receivables-how-reconcile-payments-cannot-apply-auto.md)
|Odkazovat text na platbách na konkrétního zákazníka, dodavatele nebo účet hlavní knihy, aby došlo vždy po zaúčtování periodických pokladních příjmů nebo výdajů na tyto účty, pokud neexistují žádné doklady pro vyrovnání.| [Návod: Mapovat text periodických plateb na účtech pro automatické odsouhlasení](receivables-how-map-text-recurring-payments-accounts-auto-reconcilliation.md)|

## <a name="see-also"></a>Viz také
[Správa pohledávek](receivables-manage-receivables.md)  
[Správa prodeje](sales-manage-sales.md)

