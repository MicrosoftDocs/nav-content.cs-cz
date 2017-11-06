---
title: "Přiřazení úrovně priority dodavateli"
description: "Můžete přidělit čísla vašim dodavatelům, abyste je upřednostnili a usnadnili návrhy na platby v Dynamics NAV."
documentationcenter: 
author: SorenGP
ms.prod: dynamics-nav-2017
ms.topic: article
ms.devlang: na
ms.tgt_pltfrm: na
ms.workload: na
ms.search.keywords: supplier, payment priority
ms.date: 03/29/2017
ms.author: sgroespe
ms.translationtype: HT
ms.sourcegitcommit: 4fefaef7380ac10836fcac404eea006f55d8556f
ms.openlocfilehash: 79458c1372c9f696a8331f2e7c83179dd42fb905
ms.contentlocale: cs-cz
ms.lasthandoff: 10/16/2017

---
# <a name="how-to-prioritize-vendors"></a>Návod: Prioritizace dodavatelů
[!INCLUDE[d365fin](includes/d365fin_md.md)] může navrhnout různé platby dodavatelům například platby, které budou brzy splatné nebo platby, u kterých je skonto k dispozici. Další informace naleznete v tématu [Návod: Navrhnutí plateb dodavatelů ](payables-how-suggest-vendor-payments.md).

Nejprve musíte upřednostnit dodavatele přiřazením čísel.

## <a name="to-prioritize-vendors"></a>Prioritizace dodavatelů
1. Zvolte ikonu ![Vyhledat stránku nebo sestavu](media/ui-search/search_small.png "Ikona Vyhledat stránku nebo sestavu"), zadejte **Dodavatelé** a vyberte související odkaz.
2. Vyberte příslušného dodavatele a poté zvolte **Úpravy**.
3. Do pole **Priorita** zadejte číslo.

[!INCLUDE[d365fin](includes/d365fin_md.md)] považuje nejnižší hodnotu, s výjimkou 0, za nejvyšší prioritu. Takže například pokud používáte 1, 2 a 3, pak bude mít 1 nejvyšší prioritu.

Pokud nechcete upřednostnit dodavatele, ponechte pole **Priorita** prázdné. Poté, pokud použijete funkci návrhu platby, dodavatel bude uveden po všech dodavatelích, kteří mají číslo priority. Můžete zadat tolik prioritních úrovní, kolik potřebujete.

## <a name="see-also"></a>Viz také
[Nastavení nákupu](purchasing-setup-purchasing.md)  
[Správa závazků](payables-manage-payables.md)  
[Práce s [!INCLUDE[d365fin](includes/d365fin_md.md)]](ui-work-product.md)

