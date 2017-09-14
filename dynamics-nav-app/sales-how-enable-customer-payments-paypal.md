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
ms.sourcegitcommit: 6b60b1344a1e18ad91863046110df880f75f7c04
ms.openlocfilehash: 15f30a03c3e7ccc865ef527a707794c2c6428b2f
ms.contentlocale: cs-cz
ms.lasthandoff: 07/19/2017

---

# <a name="how-to-enable-customer-payments-through-paypal"></a><span data-ttu-id="9adad-102">Návod: Povolení zákaznických plateb pomocí PayPalu</span><span class="sxs-lookup"><span data-stu-id="9adad-102">How to: Enable Customer Payments Through PayPal#</span></span>
<span data-ttu-id="9adad-103">Jako alternativu k výběru plateb bankovním převodem nebo kreditními kartami můžete svým zákazníkům nabídnout, že Vám budou platit prostřednictvím účtu PayPal.</span><span class="sxs-lookup"><span data-stu-id="9adad-103">As an alternative to collecting payments through bank transfer or credit cards, you can offer your customers to pay you through their PayPal account.</span></span>

<span data-ttu-id="9adad-104">Pokud zákazník zvolí odkaz PayPal na prodejní faktuře nebo v prodejní objednávce, objeví se stránka pro služby PayPal s platebními údaji.</span><span class="sxs-lookup"><span data-stu-id="9adad-104">When a customer chooses the PayPal link on a sales invoice or sales order document, the service page for their PayPal account appears showing the payment details for the sale.</span></span> <span data-ttu-id="9adad-105">Zákazník může zaplatit fakturu jako jakoukoli jinou PayPal platbu.</span><span class="sxs-lookup"><span data-stu-id="9adad-105">The customer can then pay the invoice as any other PayPal payment.</span></span>

<span data-ttu-id="9adad-106">Chcete-li povolit platby zákazníkům prostřednictvím služby PayPal, musíte provést následující kroky:</span><span class="sxs-lookup"><span data-stu-id="9adad-106">To enable customer payments through PayPal, you must do the following:</span></span>

1. <span data-ttu-id="9adad-107">Nastavte službu PayPal Payments Standard jako platební službu v okně **Služby pro platby**.</span><span class="sxs-lookup"><span data-stu-id="9adad-107">Set up PayPal Payments Standard as a payment service in the **Payments Services** window.</span></span>
2. <span data-ttu-id="9adad-108">Zvolte v **Služby pro platby** PayPal Payments Standard na daném prodejním dokladu.</span><span class="sxs-lookup"><span data-stu-id="9adad-108">Select PayPal Payments Standard in the **Payment Service** field on the sales document in question.</span></span>

<span data-ttu-id="9adad-109">Služba PayPal Payments Standard bude nainstalována jako rozšíření [!INCLUDE[navnow](includes/navnow_md.md)] a bude připravena k zapnutí.</span><span class="sxs-lookup"><span data-stu-id="9adad-109">The PayPal Payments Standard service is installed as an extension to Dynamics NAV and ready to enabled.</span></span> <span data-ttu-id="9adad-110">Další informace naleznete v tématu: [Přizpůsobení [!INCLUDE[navnow](includes/navnow_md.md)] pomocí rozšíření](ui-extensions.md).</span><span class="sxs-lookup"><span data-stu-id="9adad-110">For more information, see [Customizing Dynamics NAV Using Extensions ](ui-extensions.md).</span></span>

## <a name="to-enable-the-paypal-payments-standard-service"></a><span data-ttu-id="9adad-111">Povolení služby PayPal Payments Standard</span><span class="sxs-lookup"><span data-stu-id="9adad-111">To enable the PayPal Payments Standard service</span></span>
1. <span data-ttu-id="9adad-112">V pravém horním rohu zvolte ikonu **Vyhledat stránku nebo sestavu**, zadejte **Služby pro platby** a poté vyberte příslušný odkaz.</span><span class="sxs-lookup"><span data-stu-id="9adad-112">In the top right corner, choose the **Search for Page or Report** icon, **Payment Services**, and then choose the related link.</span></span>  
2. <span data-ttu-id="9adad-113">V okně **Služby pro platby** zvolte **Nový**.</span><span class="sxs-lookup"><span data-stu-id="9adad-113">In the **Payment Services** window, choose the **New** action.</span></span>
3. <span data-ttu-id="9adad-114">Vyberte **PayPal Standard** a zavřete okno.</span><span class="sxs-lookup"><span data-stu-id="9adad-114">Select **PayPal Standard**, and then close the window.</span></span>
4. <span data-ttu-id="9adad-115">V okně **Služby pro platby** zvolte **Nastavení**.</span><span class="sxs-lookup"><span data-stu-id="9adad-115">In the **Payment Services** window, choose the **Setup** action.</span></span>
5. <span data-ttu-id="9adad-116">Vyplňte pole dle potřeby.</span><span class="sxs-lookup"><span data-stu-id="9adad-116">Fill in the fields as necessary.</span></span> <span data-ttu-id="9adad-117">Vyberte pole a přečtěte si krátký popis pole nebo odkaz pro další informace.</span><span class="sxs-lookup"><span data-stu-id="9adad-117">Choose a field to read a short description of the field or link to more information.</span></span>

    <span data-ttu-id="9adad-118">**Poznámka**: Zaškrtněte políčko **Vždy zahrnuto v dokumentech**, pokud má být hypertextový odkaz pro platební službu PayPal vždy viditelný v prodejních dokladech, kde je povolena platba prostřednictvím služby PayPal.</span><span class="sxs-lookup"><span data-stu-id="9adad-118">**Note**: Select the **Always Include on Documents** check box if the hyperlink for the PayPal payment service should always be visible on sales documents where payment through PayPal is enabled.</span></span>

6. <span data-ttu-id="9adad-119">Zavřete okno.</span><span class="sxs-lookup"><span data-stu-id="9adad-119">Close the window.</span></span>

## <a name="to-select-paypal-payments-standard-on-a-sales-invoice"></a><span data-ttu-id="9adad-120">Vybrání PayPal Payments Standard na prodejní faktuře</span><span class="sxs-lookup"><span data-stu-id="9adad-120">To select PayPal Payments Standard on a sales invoice</span></span>
1. <span data-ttu-id="9adad-121">Na domovské stránce vyberte položku **Prodejní faktury**.</span><span class="sxs-lookup"><span data-stu-id="9adad-121">On the Home page, choose **Sales Invoices**.</span></span>
2. <span data-ttu-id="9adad-122">Otevřete prodejní fakturu, na kterou chcete povolit platby PayPal.</span><span class="sxs-lookup"><span data-stu-id="9adad-122">Open the sales invoice that you want to enable PayPal payments for.</span></span>
3. <span data-ttu-id="9adad-123">V poli **Služby pro platby** vyberte PayPal Payments Standard.</span><span class="sxs-lookup"><span data-stu-id="9adad-123">In the **Payment Service** field, choose PayPal Payments Standard.</span></span>

<span data-ttu-id="9adad-124">**Poznámka**: Pole **Služby pro platby** je pouze viditelné pokud je služba PayPal Payments Standard zapnutá.</span><span class="sxs-lookup"><span data-stu-id="9adad-124">**Note**: The **Payment Service** field is only visible if the PayPal Payments Standard service is enabled.</span></span>   

## <a name="see-also"></a><span data-ttu-id="9adad-125">Viz také</span><span class="sxs-lookup"><span data-stu-id="9adad-125">See Also</span></span>  
[<span data-ttu-id="9adad-126">Nastavení prodeje</span><span class="sxs-lookup"><span data-stu-id="9adad-126">Set Up Sales</span></span>](sales-setup-sales.md)  
[<span data-ttu-id="9adad-127">Správa prodeje</span><span class="sxs-lookup"><span data-stu-id="9adad-127">Manage Sales</span></span>](sales-manage-sales.md)  
<span data-ttu-id="9adad-128">[Přizpůsobení [!INCLUDE[navnow](includes/navnow_md.md)] pomocí Extensions](ui-extensions.md)</span><span class="sxs-lookup"><span data-stu-id="9adad-128">[Customizing Dynamics NAV Using Extensions](ui-extensions.md)</span></span>

