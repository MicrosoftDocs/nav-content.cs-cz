---
title: "Nastavení webových zdrojů pro kontaktní společnosti"
description: "Můžete definovat internetové nebo webové zdroje přiřazené ke kontaktní společnosti jako pomoc pro identifikaci, informací o kontaktech, které chcete."
documentationcenter: 
author: jswymer
ms.prod: dynamics-nav-2017
ms.topic: article
ms.devlang: na
ms.tgt_pltfrm: na
ms.workload: na
ms.search.keywords: internet
ms.date: 06/06/2017
ms.author: jswymer
ms.translationtype: HT
ms.sourcegitcommit: 4fefaef7380ac10836fcac404eea006f55d8556f
ms.openlocfilehash: c744a4fb90c65b27fce8da3c37379cd93b40a8f6
ms.contentlocale: cs-cz
ms.lasthandoff: 10/16/2017

---
# <a name="how-to-set-up-web-sources-for-contact-companies"></a>Návody Nastavení webových zdrojů pro kontaktní společnosti
Můžete použít webové zdroje se svými kontaktními společnostmi například k identifikaci vyhledávačů a webových stránek na internetu, které chcete použít k vyhledání informací o kontaktech. Při přiřazování webových zdrojů určíte vyhledávač a vyhledávací slovo, které aplikace použije k vyhledání požadovaných informací.

Použití webových zdrojů v kontaktech je proces o dvou krocích. Nejprve definujete kód webových zdrojů. Pro každý webový zdroj stačí tento krok provést pouze jednou. Jakmile máte kód pro webové zdroje, můžete začít přiřazovat kód ke kontaktním osobám.

## <a name="to-define-a-web-source-code"></a>Definování kódu webového zdroje
1. Zvolte ikonu ![Vyhledat stránku nebo sestavu](media/ui-search/search_small.png "Ikona Vyhledat stránku nebo sestavu"), zadejte **webové zdroje** a vyberte související odkaz.
2. Zvolte akci **Nový**.
3. Vyplňte pole **Kód** , **Popis** a **URL** .

    Zadejte %1 v poli **URL** a vložte zástupný symbol pro hledané slovo do URL. Při spuštění webového zdroje z kontaktu je znak %1 nahrazen hledaným slovem, například názvem společnosti, kterou jste zadali do okna **Webové zdroje kontaktů**.

Opakujte tyto kroky k nastavení tolika webových zdrojů, kolik chcete.

## <a name="to-assign-web-sources-to-a-contact-company"></a>Přiřazení webových zdrojů ke kontaktní společnosti
Při přiřazování webových zdrojů určíte vyhledávač a hledané slovo, které aplikace použije k vyhledání požadovaných informací.

1. Otevřete kontakt.
2. Zvolte akci **Společnost** a poté akci **Webové zdroje**. Otevře se okno **Webové zdroje kontaktů**.
3. V poli **Kód webových zdrojů** vyberte webový zdroj, který chcete přiřadit.
4. Do pole **Hledané slovo** zadejte hledané slovo, které chcete použít k nalezení informací.

Opakujte tyto kroky, abyste přiřadili tolik webových zdrojů, kolik chcete.

Můžete také stejným postupem přiřadit webové zdroje z okna **Seznam kontaktů**.

## <a name="see-also"></a>Viz také
[Vytvoření kontaktních společností](marketing-create-contact-companies.md)  
[Práce s [!INCLUDE[d365fin](includes/d365fin_md.md)]](ui-work-product.md)

