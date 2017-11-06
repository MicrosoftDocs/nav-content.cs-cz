---
title: "Nastavení průmyslové skupiny pro kontaktní společnosti"
description: "Popisuje jak definovat průmyslové skupiny a přiřadit je ke společnosti, například maloobchodní průmysl nebo automobilový průmysl."
documentationcenter: 
author: jswymer
ms.prod: dynamics-nav-2017
ms.topic: article
ms.devlang: na
ms.tgt_pltfrm: na
ms.workload: na
ms.search.keywords: relationship, prospect
ms.date: 06/06/2017
ms.author: jswymer
ms.translationtype: HT
ms.sourcegitcommit: 4fefaef7380ac10836fcac404eea006f55d8556f
ms.openlocfilehash: 62d946155cb65a3e976771bc5029878893bd4797
ms.contentlocale: cs-cz
ms.lasthandoff: 10/16/2017

---
# <a name="how-to-set-up-industry-groups-for-contact-companies"></a>Návod: Nastavení průmyslové skupiny pro kontaktní společnosti
Používáte průmyslové skupiny k označení typu průmyslu, ke kterému patří vaše kontakty, například maloobchod nebo automobilový průmysl.

Použití průmyslových skupin v kontaktech je proces o dvou krocích. Nejprve definujete kód průmyslové skupiny. Pro každou průmyslovou skupinu stačí tento krok provést pouze jednou. Jakmile máte průmyslovou skupinu, můžete začít přiřazovat kódy ke kontaktním společnostem.

> [!NOTE]  
>   Pokud máte v úmyslu synchronizovat své kontakty s dodavateli, zákazníky nebo bankovními účty v jiných částech aplikace, můžete si pro ně nastavit obchodní vztah.

## <a name="to-define-an-industry-group-code"></a>Definování kódu průmyslové skupiny
Kód průmyslové skupiny definuje typ nebo kategorii skupiny, např. REKLAMA pro reklamu nebo TISK pro televizní a rozhlasové vysílání. Můžete mít několik kódů průmyslových skupin. Chcete-li definovat průmyslové skupiny, použijete okno **Průmyslové skupiny**.

1. Zvolte ikonu ![Vyhledat stránku nebo sestavu](media/ui-search/search_small.png "Ikona Vyhledat stránku nebo sestavu"), zadejte **Průmyslové skupiny** a vyberte související odkaz.
2. Vyberte tlačítko **Nový** a vyplňte kód a popis. Kód může mít maximálně 11 znaků a může obsahovat jakékoli kombinace čísel a písmen.

## <a name="AssignIndustryGroupContact"></a> Přiřazení průmyslových skupin ke kontaktu
Nemůžete přiřadit průmyslové skupiny ke kontaktním osobám - pouze společnosti.

1. Otevřete kontakt.
2. Zvolte akci **Společnost** a poté akci **Průmyslové skupiny**. Otevře se okno **Průmyslové skupiny kontaktu**.
3. V poli **Kód průmyslových skupiny** vyberte průmyslové skupiny, které chcete přiřadit.

Opakujte tyto kroky, abyste přiřadili tolik průmyslových skupin, kolik chcete. Průmyslové skupiny můžete také přiřadit stejným postupem ze seznamu kontaktů.

Počet průmyslových skupin, které jste přidali ke kontaktu, se zobrazuje v poli **Počet průmyslových skupin** v sekci **Segmentace** v okně **Kontaktu**.

Po přidělení průmyslových skupin k vašim kontaktům můžete pomocí těchto informací vybrat kontakty pro vaše segmenty. Další informace naleznete v tématu [Návod: Přidání kontaktů do segmentů.](marketing-add-contact-segment.md).

## <a name="see-also"></a>Viz také
[Vytvoření kontaktních společností](marketing-create-contact-companies.md)  
[Práce s [!INCLUDE[d365fin](includes/d365fin_md.md)]](ui-work-product.md)

