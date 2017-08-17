---
title: "Návody Vytvořit Přímé dodávky"
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
ms.openlocfilehash: f636de789dc6b006a449ec59c390fab85e62b443
ms.contentlocale: cs-cz
ms.lasthandoff: 06/26/2017

---

# <a name="how-to-make-drop-shipments"></a>Návody Vytvořit Přímé dodávky
Přímá dodávka je zásilka položek od jednoho z Vašich dodavatelů přímo k Vašemu zákazníkovi.

Je-li prodejní objednávka označena jako přímá dodávka a vy vytvoříte nákupní objednávku určující zákazníka v políčku **Prodat zákazníkovi číslo**, Poté můžete propojit dva dokumenty a instruovat dodavatele, aby odeslal objednávku přímo zákazníkovi.

## <a name="to-create-a-sales-order-for-drop-shipment"></a>Vytvořit novou prodejní objednávku pro přímou dodávku.
Chcete-li připravit přímou dodávku, vytvořte prodejní objednávku zboží jako obvykle, kromě toho, že na řádku prodejní objednávky musíte uvést, že se vyžaduje přímá dodávka.

1. Vytvořit prodejní objednávku pro položku. Další informace naleznete v tématu [Jak na: Prodejní produkty](sales-how-sell-products.md)
2. Na řádku prodejní objednávky pro přímou dodávku zaškrtněte políčko **Přímá dodávka**.

## <a name="to-create-the-purchase-order-for-drop-shipment"></a>Vytvořit nákupní objednávku pro přímou dodávku.
Chcete-li vytvořit přímou dodávku pro zboží, které má být prodání vytvořte prodejní obejdnávku jako obvykle, kromě toho, že v objednávce musíte uvedeno, že zásilka musí být odeslána zákazníkovi, nikoli Vám.

1. Vytvořit nákupní objednávku. Nevyplňujte žádná políčka na řádcích. Další informace naleznete v tématu [Jak na: Záznam nákupů](purchasing-how-record-purchases.md)
2. V políčku **Zákazník** Vyberte zákazníka, kterému chcete prodávat.
3. Vyberte tlačítko **Přímá dodávka** a vyberte tlačítko **Získat prodejní objednávku**.
4. V okně **Seznamu prodeje** vyberte prodejní objednávku, kterou jste nachystali v sekci „Vytvořit prodejní objednávku pro přímou dodávku“.
5. Zvolte tlačítko **OK**.

Informace o řádku z prodejní objednávky jsou vloženy na řádku (řádcích) nákupní objednávky.

Nyní můžete instruovat dodavatele, aby zboží odeslal zákazníkovi, například zasláním objednávky ve formátu PDF.     

## <a name="to-view-the-linked-purchase-order-from-the-sales-order"></a>Zobrazit propojení nákupní objednávky s nákupní objednávkou.
1. Vyberte řádek přímé objednávky a zvolte tlačítko **Objednávka**, vyberte **Přímá objednávka** a vyberte tlačítko **Nákupní objednávka**.

Propojená nákupní objednávka se otevře.

## <a name="to-post-a-drop-shipment"></a>Účtovat přímou dodávku.
Když dodavatel odeslal zboží, můžete zaúčtovat prodejní objednávku jako dodaná. Také můžete účtovat nákupní objednávku, ale jen s možností **Přijatá** dokud prodejní objednávka nebude vyfakturována.
1. V pravém horním rohu zvolte ikonu **Vyhledat stránku nebo sestavu**, zadejte **Prodejní objednávky** a poté vyberte příslušný odkaz.
2. Otevřete prodejní objednávku, kterou jste vytvořili v sekci „Vytvořte prodejní objednávku pro přímou dodávku“.
3. V políčku **Množství k odeslání** specifikujte počet jednotek z objednaného zboží k odeslání, buď celé nebo částečné množství.
3. Vyberte tlačítko **Účtovat** nebo **Účtovat a odeslat**.
4. Zvolte buď volbu **Odeslat** pro pozdější fakturaci, nebo volbu **Odeslat a fakturovat**okamžitě fakturovat.

## <a name="see-also"></a>Viz také
[Návody Prodejní produkty](sales-how-sell-products.md)    
[Návody Záznam nákupů](purchasing-how-record-purchases.md)  
[Správa prodeje](sales-manage-sales.md)  
[Správa skladů](inventory-manage-inventory.md)      
[Práce s Dynamics NAV](ui-work-product.md)

