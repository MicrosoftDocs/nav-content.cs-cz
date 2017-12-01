---
title: "Vytvoření záznamů došlých dokladů"
description: "Můžete vytvořit záznam došlého dokladu jako například elektronické faktury a řízení úkolů OCR, eCommerce a výměny dokumentů."
documentationcenter: 
author: SorenGP
ms.prod: dynamics-nav-2018
ms.topic: article
ms.devlang: na
ms.tgt_pltfrm: na
ms.workload: na
ms.search.keywords: electronic document, e-invoice, incoming document, OCR, ecommerce, document exchange, import invoice
ms.date: 06/02/2017
ms.author: sgroespe
ms.translationtype: HT
ms.sourcegitcommit: 4fefaef7380ac10836fcac404eea006f55d8556f
ms.openlocfilehash: f7b90a92fe0f0efac4c79881501732267cec2497
ms.contentlocale: cs-cz
ms.lasthandoff: 10/16/2017

---
# <a name="how-to-create-incoming-document-records"></a>Návod: Vytvoření záznamu došlého dokladu
V okně **Došlé doklady** můžete použít různé funkce pro kontrolu výdajů, správu OCR úkolů a převod došlých dokladů ručně nebo automaticky na příslušné doklady nebo řádky deníku. Externí doklady lze připojit v libovolné fázi procesu, včetně zaúčtovaných dokladů a výsledků dodavatelů, zákazníků a položek hlavní knihy.

K záznamu externího dokladu v [!INCLUDE[d365fin](includes/d365fin_md.md)], musíte nejprve vytvořit nebo dokončit záznam došlého dokladu. Můžete to provést ručně nebo můžete pořídit fotografii externího dokladu a pak vytvořit záznam došlého dokladu s připojeným obrazovým souborem.

Předtím než můžete použít funkce Došlého dokladu, musíte provést požadované nastavení. Další informace naleznete v tématu [Návod: Nastavení došlých dokladů](across-how-setup-income-documents.md).

## <a name="to-approve-or-reject-an-incoming-document"></a>Schválení nebo odmítnutí došlého dokladu
Pokud chcete povolit uživatelům vytvářet faktury nebo řádky finančního deníku ze záznamů došlého dokladu, dokud nejsou schváleny, můžete nastavit toho, kdo musí schválit záznamy předtím, než budou zpracovány.

1. Zvolte ikonu ![Vyhledat stránku nebo sestavu](media/ui-search/search_small.png "Ikona Vyhledat stránku nebo sestavu"), zadejte **Došlé doklady** a pak vyberte související odkaz.
2. Vyberte řádek dokladu, který chcete vydat nebo odmítnout a pak zvolte akci **Vydat** nebo **Odmítnout**.

Pokud vydáte záznam došlého dokladu, je vybráno zaškrtávací políčko **Uvolnit** v řádku došlého dokladu. Uživatel, který je pověřen tvorbou například nákupních faktur, může zpracovat záznam.

## <a name="to-create-an-incoming-document-record-by-taking-a-photo"></a>Vytvoření záznamu došlého dokladu pořízením fotografie
> [!NOTE]  
>   Následující postup platí pouze [!INCLUDE[d365fin](includes/d365fin_md.md)] pro klienty tabletu a telefonu.

1. Na panelu aplikace zvolte dlaždici **Vytvořit došlý doklad z fotoaparátu** a pak pokračujte na krok 4.
2. Alternativně na panelu aplikace zvolte tlačítko možnosti, vyberte **Došlé doklady** a pak zvolte **Vše**.
3. V okně **Došlé doklady** zvolte tlačítko tři tečky a pak zvolte **Vytvořit z fotoaparátu**. Kamera v tabletu nebo telefonu se aktivuje.
4. Udělejte fotku dokladu například nákupního dokladu, který chcete zpracovat jako došlý doklad a potom klepněte na tlačítko **OK**.

    Nový záznam došlého dokladu je vytvořen s připojením obrázku.

## <a name="to-attach-an-image-to-an-incoming-document-record-by-taking-a-photo"></a>Připojení obrázku k záznamu došlého dokladu pomocí fotografie
> [!NOTE]  
>   Následující postup platí pouze [!INCLUDE[d365fin](includes/d365fin_md.md)] pro klienty tabletu a telefonu.

1. Na panelu aplikace zvolte tlačítko možnosti, zvolte **Došlé doklady** a pak zvolte **Vše**.
2. Otevře se karta pro existující záznam došlého dokladu.
3. V okně **Došlé doklady** zvolte tlačítko tři tečky a pak zvolte **Připojit obrázek z fotoaparátu**. Kamera v tabletu nebo telefonu se aktivuje.
4. Udělejte fotku dokladu například nákupního dokladu, který chcete zpracovat jako došlý doklad a potom klepněte na tlačítko **OK**.

    Obrázek je připojen k záznamu došlého dokladu.

## <a name="to-create-an-incoming-document-record-manually"></a>Vytvoření záznamu došlého dokladu manuálně
1. Zvolte ikonu ![Vyhledat stránku nebo sestavu](media/ui-search/search_small.png "Ikona Vyhledat stránku nebo sestavu"), zadejte **Došlé doklady** a pak vyberte související odkaz.
2. Zvolte akci **Vytvořit ze souboru**.  
3. V okně **Vložit soubor** vyberte soubor a pak zvolte **Otevřít**. Soubor je automaticky připojen.
4. Alternativně zvolte akci **Nový**.
5. Pro připojení souboru zvolte akci **Připojit soubor**.
6. V okně **Vložit soubor** vyberte soubor, který reprezentuje došlý doklad a pak zvolte tlačítko **Otevřít**.
7. V okně **Došlý doklad** vyplňte pole podle potřeby. [!INCLUDE[tooltip-inline-tip](includes/tooltip-inline-tip_md.md)]

## <a name="see-also"></a>Viz také
[Proces došlých dokladů](across-process-income-documents.md)  
[Došlé doklady](across-income-documents.md)  
[Nákup](purchasing-manage-purchasing.md)  
[Práce s [!INCLUDE[d365fin](includes/d365fin_md.md)]](ui-work-product.md)

