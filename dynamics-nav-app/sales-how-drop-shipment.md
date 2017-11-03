---
title: "Vytvořit prodejní objednávku propojenou k nákupní objednávce pro přímou dodávku"
description: "Popisuje, jak vytvořit prodejní objednávku propojenou k nákupní objednávce k povolení dodávky přímo od dodavatele k zákazníkovi."
documentationcenter: 
author: SorenGP
ms.prod: dynamics-nav-2017
ms.topic: article
ms.devlang: na
ms.tgt_pltfrm: na
ms.workload: na
ms.search.keywords: direct shipment
ms.date: 03/29/2017
ms.author: sgroespe
ms.translationtype: HT
ms.sourcegitcommit: 4fefaef7380ac10836fcac404eea006f55d8556f
ms.openlocfilehash: 6a8210808532ff8945660c23f0bf91719e2f2963
ms.contentlocale: cs-cz
ms.lasthandoff: 10/16/2017

---
# <a name="how-to-make-drop-shipments"></a>Návod: Vytvoření přímé dodávky
Přímá dodávka je zásilka položek od jednoho z vašich dodavatelů přímo k vašemu zákazníkovi.

Je-li prodejní objednávka označena jako přímá dodávka a vy vytvoříte nákupní objednávku určující zákazníka v políčku **Prodat zákazníkovi číslo**, poté můžete propojit dva dokumenty a instruovat dodavatele, aby odeslal objednávku přímo zákazníkovi.

## <a name="to-create-a-sales-order-for-drop-shipment"></a>Vytvoření nové prodejní objednávky pro přímou dodávku.
Chcete-li připravit přímou dodávku, vytvořte prodejní objednávku zboží jako obvykle, kromě toho, že na řádku prodejní objednávky musíte uvést, že se jedná o přímou dodávku.

1. Vytvoření prodejní objednávky pro položku. Další informace naleznete v [Návod: Prodávání produktů](sales-how-sell-products.md).
2. Na řádku prodejní objednávky pro přímou dodávku zaškrtněte políčko **Přímá dodávka**. Použijte funkci **Vybrat sloupce**, pokud .není pole viditelné Další informace naleznete v tématu [Přizpůsobení uživatele](ui-user-personalization.md).

## <a name="to-create-the-purchase-order-for-drop-shipment"></a>Vytvoření nákupní objednávky pro přímou dodávku
Chcete-li vytvořit přímou dodávku pro zboží, které má být prodáváno, vytvořte prodejní objednávku jako obvykle. Jen v objednávce musíte uvést, že zásilka musí být odeslána zákazníkovi, nikoli vám.

1. Vytvořte nákupní objednávku. Nevyplňujte žádná políčka na řádcích. Další informace naleznete v [Návod: Zaznamenávání nákupů](purchasing-how-record-purchases.md).
2. V políčku **Zákazník** vyberte zákazníka, kterému chcete prodávat.
3. Vyberte tlačítko **Přímá dodávka** a tlačítko **Kopírovat prodejní objednávku**.
4. V okně **Přehled prodeje** vyberte prodejní objednávku, kterou jste nachystali v sekci „Vytvoření prodejní objednávky pro přímou dodávku“.
5. Zvolte tlačítko **OK**.

Informace o řádku z prodejní objednávky jsou vloženy na řádku (řádcích) nákupní objednávky.

Nyní můžete instruovat dodavatele, aby zboží odeslal zákazníkovi, například zasláním objednávky ve formátu PDF.     

## <a name="to-view-the-linked-purchase-order-from-the-sales-order"></a>Zobrazení propojení nákupní objednávky s prodejní objednávkou.
* Vyberte řádek přímé objednávky a zvolte tlačítko **Objednávka**, vyberte **Přímá objednávka** a vyberte tlačítko **Nákupní objednávka**.

## <a name="to-post-a-drop-shipment"></a>Účtování přímé dodávky
Potom, co dodavatel odeslal zboží, můžete zaúčtovat prodejní objednávku jako dodanou. Také můžete účtovat nákupní objednávku, ale jen s možností **Přijatá** dokud prodejní objednávka nebude vyfakturována.

1. Zvolte ikonu ![Vyhledat stránku nebo sestavu](media/ui-search/search_small.png "Ikona Vyhledat stránku nebo sestavu"), zadejte **Prodejní objednávky** a poté vyberte příslušný odkaz.
2. Otevřete prodejní objednávku, kterou jste vytvořili v sekci „Vytvoření prodejní objednávky pro přímou dodávku“.
3. V políčku **Množství k odeslání** specifikujte počet jednotek z objednaného zboží k odeslání, buď celé nebo částečné množství.
4. Vyberte tlačítko **Účtovat** nebo **Účtovat a odeslat**.
5. Zvolte buď volbu **Odeslat** pro pozdější fakturaci, nebo volbu **Odeslat a fakturovat** okamžitě fakturovat.

## <a name="see-also"></a>Viz také
[Návody: Vytvořit zvláštní objednávky](sales-how-to-create-special-orders.md)|  
[Návod: Prodávání produktu](sales-how-sell-products.md)  
[Návod: Zaznamenávání nákupu](purchasing-how-record-purchases.md)  
[Prodej](sales-manage-sales.md)  
[Sklady](inventory-manage-inventory.md)  
[Práce s [!INCLUDE[d365fin](includes/d365fin_md.md)]](ui-work-product.md)

