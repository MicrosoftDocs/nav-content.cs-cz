---
title: "Návod: Priorita dodavatelů"
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
ms.openlocfilehash: 3b89bf07e1e9d1839b6c86a01111e936fb62c9f3
ms.contentlocale: cs-cz
ms.lasthandoff: 06/26/2017

---

# <a name="how-to-prioritize-vendors"></a>Návod: Priorita dodavatelů
Dynamics NAV může navrhnout různé platby dodavatelům například platby, které budou brzy splatné nebo platby, u kterých je skonto k dispozici. Další informace naleznete v tématu [Návod: Navrhnutí plateb dodavatelů](payables-how-suggest-vendor-payments.md) .

Nejprve musíte upřednostnit dodavatele přiřazením čísel.

## <a name="to-prioritize-vendors"></a>Prioritizace dodavatelů
1. V pravém horním rohu zvolte ikonu **Vyhledat stránku nebo sestavu**, zadejte **Dodavatelé** a zvolte související odkaz.
2. Vyberte příslušného dodavatele a poté zvolte **Úpravy**.
3. Do pole **Priorita** zadejte číslo.

Dynamics NAV považuje nejnižší hodnotu, s výjimkou 0, za nejvyšší prioritu. Takže například pokud používáte 1, 2 a 3, pak bude mít 1 nejvyšší prioritu.

Pokud nechcete upřednostnit dodavatele, ponechte pole **Priorita** prázdné. Poté, pokud použijete funkci návrhu platby, dodavatel bude uveden po všech dodavatelích, kteří mají číslo priority. Můžete zadat tolik prioritních úrovní, kolik potřebujete.

## <a name="see-also"></a>Viz také
[Nastavení nákupu](purchasing-setup-purchasing.md)  
[Správa závazků](payables-manage-payables.md)

