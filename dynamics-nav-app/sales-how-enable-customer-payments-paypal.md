---
title: "Návod: Povolení zákaznických plateb pomocí PayPalu"
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
ms.openlocfilehash: a2268d8454af761c40b11d89b01778a3f92090fb
ms.contentlocale: cs-cz
ms.lasthandoff: 06/26/2017

---

# <a name="how-to-enable-customer-payments-through-paypal"></a>Návod: Povolení zákaznických plateb pomocí PayPalu
Jako alternativu k výběru plateb bankovním převodem nebo kreditními kartami můžete svým zákazníkům nabídnout, že Vám budou platit prostřednictvím účtu PayPal.

Pokud zákazník zvolí odkaz PayPal na prodejní faktuře nebo v prodejní objednávce, objeví se stránka pro služby PayPal s platebními údaji. Zákazník může zaplatit fakturu jako jakoukoli jinou PayPal platbu.

Chcete-li povolit platby zákazníkům prostřednictvím služby PayPal, musíte provést následující kroky:

1. Nastavte službu PayPal Payments Standard jako platební službu v okně **Služby pro platby**.
2. Zvolte v **Služby pro platby** PayPal Payments Standard na daném prodejním dokladu.

Služba PayPal Payments Standard bude nainstalována jako rozšíření [!INCLUDE[navnow](includes/navnow_md.md)] a bude připravena k zapnutí. Další informace naleznete v tématu: [Přizpůsobení [!INCLUDE[navnow](includes/navnow_md.md)] pomocí rozšíření](ui-extensions.md).

## <a name="to-enable-the-paypal-payments-standard-service"></a>Povolení služby PayPal Payments Standard
1. V pravém horním rohu zvolte ikonu **Vyhledat stránku nebo sestavu**, zadejte **Služby pro platby** a poté vyberte příslušný odkaz.  
2. V okně **Služby pro platby** zvolte **Nový**.
3. Vyberte **PayPal Standard** a zavřete okno.
4. V okně **Služby pro platby** zvolte **Nastavení**.
5. Vyplňte pole dle potřeby. Vyberte pole a přečtěte si krátký popis pole nebo odkaz pro další informace.

    **Poznámka**: Zaškrtněte políčko **Vždy zahrnuto v dokumentech**, pokud má být hypertextový odkaz pro platební službu PayPal vždy viditelný v prodejních dokladech, kde je povolena platba prostřednictvím služby PayPal.

6. Zavřete okno.

## <a name="to-select-paypal-payments-standard-on-a-sales-invoice"></a>Vybrání PayPal Payments Standard na prodejní faktuře
1. Na domovské stránce vyberte položku **Prodejní faktury**.
2. Otevřete prodejní fakturu, na kterou chcete povolit platby PayPal.
3. V poli **Služby pro platby** vyberte PayPal Payments Standard.

**Poznámka**: Pole **Služby pro platby** je pouze viditelné pokud je služba PayPal Payments Standard zapnutá.   

## <a name="see-also"></a>Viz také  
[Nastavení prodeje](sales-setup-sales.md)  
[Správa prodeje](sales-manage-sales.md)  
[Přizpůsobení [!INCLUDE[navnow](includes/navnow_md.md)] pomocí Extensions](ui-extensions.md)

