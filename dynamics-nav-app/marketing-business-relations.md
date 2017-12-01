---
title: "Definujte kódy obchodních vztahů v kontaktech"
description: "Použijte obchodní vztahy v Dynamics NAV, abyste pomohli s marketingem a označili obchodní vztah, který máte s vašimi klienty a zákazníky, například s bankou nebo poskytovatelem služeb."
documentationcenter: 
author: jswymer
ms.prod: dynamics-nav-2018
ms.topic: article
ms.devlang: na
ms.tgt_pltfrm: na
ms.workload: na
ms.search.keywords: marketing, prospect, contact, client, customer
ms.date: 06/06/2017
ms.author: jswymer
ms.translationtype: HT
ms.sourcegitcommit: 4fefaef7380ac10836fcac404eea006f55d8556f
ms.openlocfilehash: 36e77c794e7aa92d5d323d93a7703359018efd39
ms.contentlocale: cs-cz
ms.lasthandoff: 10/16/2017

---
# <a name="setting-up-business-relations-on-contact-companies"></a>Nastavení obchodních vztahů ke kontaktním společnostem
Pomocí obchodních vztahů můžete označit obchodní vztah, který máte s vašimi kontakty, například potencionálním zákazníkem, bankou, konzultantem, dodavatelem služeb atd.

Použití obchodních vztahů na kontaktech je proces o dvou krocích. Nejprve definujete kód obchodních vztahů. Pro každý obchodní vztah stačí tento krok provést pouze jednou. Jakmile máte kód pro obchodní vztahy, můžete jej přiřadit ke kontaktním společnostem.

> [!NOTE]  
>   Pokud máte v úmyslu synchronizovat své kontakty s dodavateli, zákazníky nebo bankovními účty v jiných částech aplikace, můžete si pro ně nastavit obchodní vztah.

## <a name="to-define-a-business-relation-code"></a>Definování kódu obchodních vztahů
Kód obchodních vztahů definuje kategorii nebo typ obchodního vztahu, jako je například BANKA nebo PRÁVO. Můžete mít několik kódů obchodních vztahů. Chcete-li definovat obchodní vztah, použijete okno **Obchodní vztahy**.

1. Zvolte ikonu ![Vyhledat stránku nebo sestavu](media/ui-search/search_small.png "Ikona Vyhledat stránku nebo sestavu"), zadejte **Obchodní vztahy** a pak vyberte související odkaz.
2. Vyberte tlačítko **Nový** a vyplňte kód a popis. Kód může mít maximálně 11 znaků a může obsahovat jakékoli kombinace čísel a písmen.

## <a name="AssignBusRelContact"></a> Přiřazení obchodních vztahů ke kontaktu
Nemůžete přiřadit obchodní vztahy ke kontaktním osobám - pouze společnosti.

1. Otevřete kontakt.
2. Zvolte akci **Společnost** a poté akci **Obchodní vztahy**.

    Otevře se okno **Obchodní vztahy kontaktu**.
3. V poli **Kód obchodních vztahů** vyberte obchodní vztah, který chcete přiřadit.

Opakujte tyto kroky, abyste přiřadili tolik obchodních vztahů, kolik chcete. Obchodní vztahy můžete také přidělit stejným postupem ze seznamu kontaktů.

Počet obchodních vztahů, které jste přidali ke kontaktu, se zobrazuje v poli **Počet obchodních vztahů** v sekci **Segmentace** v okně **Kontakt**.

Po přidělení obchodních vztahů k vašim kontaktům můžete pomocí těchto informací vybrat kontakty pro vaše segmenty. Další informace naleznete v tématu [Návod: Přidání kontaktů do segmentů](marketing-add-contact-segment.md).

## <a name="see-also"></a>Viz také
[Vytvoření kontaktních společností](marketing-create-contact-companies.md)  
[Práce s [!INCLUDE[d365fin](includes/d365fin_md.md)]](ui-work-product.md)

