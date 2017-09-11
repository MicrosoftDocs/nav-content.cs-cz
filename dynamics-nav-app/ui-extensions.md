---
title: "Přizpůsobení Dynamics NAV pomocí Rozšíření"
author: edupont04
ms.custom: na
ms.date: 09/23/2016
ms.reviewer: na
ms.suite: na
ms.tgt_pltfrm: na
ms.topic: article
ms.prod: dynamics-nav-2017
ms.translationtype: Human Translation
ms.sourcegitcommit: 6b60b1344a1e18ad91863046110df880f75f7c04
ms.openlocfilehash: cc832772a255c7c801a7b956c74da827caca3765
ms.contentlocale: cs-cz
ms.lasthandoff: 07/19/2017

---

# <a name="customizing-dynamics-nav-using-extensions"></a><span data-ttu-id="2a635-102">Přizpůsobení Dynamics NAV pomocí Rozšíření</span><span class="sxs-lookup"><span data-stu-id="2a635-102">Customizing Dynamics NAV Using Extensions</span></span>
<span data-ttu-id="2a635-103">Dynamics NAV můžete změnit instalací rozšíření, které přidávají funkce, mění chování nebo například umožňují přístup k novým online službám.</span><span class="sxs-lookup"><span data-stu-id="2a635-103">You can change Dynamics NAV by installing extensions that add functionality, change behavior, or give you access to new online services, for example.</span></span>
<span data-ttu-id="2a635-104">Při prvním spuštění služby Dynamics NAV jsou pro vás některá rozšíření již nainstalována.</span><span class="sxs-lookup"><span data-stu-id="2a635-104">When you first launch Dynamics NAV, some extensions are already installed for you.</span></span> <span data-ttu-id="2a635-105">Postupem času mohou být k dispozici další rozšíření a poté můžete zvolit, zda chcete rozšíření použít, nebo ne.</span><span class="sxs-lookup"><span data-stu-id="2a635-105">Over time, more extensions can be made available to you, and you can then choose if you want to use the extension or not.</span></span>

<span data-ttu-id="2a635-106">Například společnost Microsoft poskytuje rozšíření, které umožňuje integraci s platebním standardem PayPal.</span><span class="sxs-lookup"><span data-stu-id="2a635-106">For example, Microsoft provides an extension that provides integration with PayPal Payments Standard.</span></span> <span data-ttu-id="2a635-107">Toto rozšíření je standardně nainstalováno.</span><span class="sxs-lookup"><span data-stu-id="2a635-107">This extension is installed by default.</span></span>
<span data-ttu-id="2a635-108">Pokud je dispozici další rozšíření, které nabízí integraci s jinou platební službou, můžete nainstalovat nové rozšíření a vybrat, kterou z těchto dvou služeb použijete.</span><span class="sxs-lookup"><span data-stu-id="2a635-108">But if another extension is made available that offers integration with another payment service, you can install the new extension and then choose which of the two services to use.</span></span>  

<span data-ttu-id="2a635-109">Spravujete rozšíření v okně **Správa rozšíření**.</span><span class="sxs-lookup"><span data-stu-id="2a635-109">You manage the extensions in the **Extension Management** window.</span></span> <span data-ttu-id="2a635-110">K tomuto oknu můžete přistupovat z domovské stránky.</span><span class="sxs-lookup"><span data-stu-id="2a635-110">You can access this window from Home.</span></span> <span data-ttu-id="2a635-111">Alternativně, v pravém horním rohu zvolte ikonu **Vyhledat stránku nebo sestavu**, zadejte **Rrozšíření** a poté vyberte příslušný odkaz.</span><span class="sxs-lookup"><span data-stu-id="2a635-111">Alternatively, choose the **Search for Page or Report** icon in the top right corner, enter **Extension**, and then choose the related link.</span></span>   

## <a name="installing-an-extension"></a><span data-ttu-id="2a635-112">Instalace rozšíření</span><span class="sxs-lookup"><span data-stu-id="2a635-112">Installing an Extension</span></span>
<span data-ttu-id="2a635-113">Pokud jsou k dispozici nové rozšíření, jelikož byly zveřejněny na vašem serveru, zobrazí se v okně **Správa rozšíření**.</span><span class="sxs-lookup"><span data-stu-id="2a635-113">If new extensions are made available to you because they have been published to your server, they will be shown in the **Extension Management** window.</span></span> <span data-ttu-id="2a635-114">Odtud můžete instalovat a odinstalovat rozšíření.</span><span class="sxs-lookup"><span data-stu-id="2a635-114">From here, you can choose to install and uninstall extensions.</span></span>  

<span data-ttu-id="2a635-115">Pokud vyberete rozšíření, můžete si přečíst co rozšíření dělá, dále získat přístup k nápovědě pro rozšíření, kde se dozvíte více.</span><span class="sxs-lookup"><span data-stu-id="2a635-115">If you choose an extension, you can read about what the extension does, and you can access Help for the extension to learn more.</span></span> <span data-ttu-id="2a635-116">Pokud se rozhodnete pro rozšíření, musíte souhlasit s podmínkami používání.</span><span class="sxs-lookup"><span data-stu-id="2a635-116">When you choose to get an extension, you must agree to the terms of use.</span></span>  

<span data-ttu-id="2a635-117">Při instalaci rozšíření budete možná muset zadat nastavení, například zadat účet pro použití s **Rozšíření platební standard PayPal pro Dynamics NAV**.</span><span class="sxs-lookup"><span data-stu-id="2a635-117">When you install an extension, you might have to set it up, such as specifying an account for use with the **PayPal Payments Standard for Dynamics NAV** extension.</span></span>
<span data-ttu-id="2a635-118">Ostatní rozšíření jednoduše přidávají pole na existující stránku nebo přidávají například novou stránku.</span><span class="sxs-lookup"><span data-stu-id="2a635-118">Other extensions simply add fields to an existing page, or they add a new page, for example.</span></span>   

<span data-ttu-id="2a635-119">Pokud se rozhodnete odinstalovat rozšíření a poté se rozhodnete, že ho opět chcete, stačí ho znovu nainstalovat.</span><span class="sxs-lookup"><span data-stu-id="2a635-119">If you uninstall an extension, and you then change your mind, you can install it again.</span></span> <span data-ttu-id="2a635-120">Když odinstalujete rozšíření, které jste použili, data jsou zachována, takže pokud znovu nainstalujete rozšíření, jsou vaše data stále k dispozici.</span><span class="sxs-lookup"><span data-stu-id="2a635-120">When you uninstall an extension that you have been using, the data is preserved so that if you install the extension again, your data is still available.</span></span>  

<span data-ttu-id="2a635-121">Společnost Microsoft poskytuje následující rozšíření:</span><span class="sxs-lookup"><span data-stu-id="2a635-121">Microsoft provides the following extensions:</span></span>  
- [<span data-ttu-id="2a635-122">Platební standard PayPal</span><span class="sxs-lookup"><span data-stu-id="2a635-122">PayPal Payments Standard</span></span>](ui-extensions-paypal-payments-standard.md)  
- [<span data-ttu-id="2a635-123">Prognóza prodeje a zásob</span><span class="sxs-lookup"><span data-stu-id="2a635-123">Sales and Inventory Forecast</span></span>](ui-extensions-sales-forecast.md)  

<span data-ttu-id="2a635-124">Ostatní rozšíření jsou také k dispozici ve výchozím nastavení v závislosti na vaší zemi/oblasti.</span><span class="sxs-lookup"><span data-stu-id="2a635-124">Other extensions are also available by default, depending on your country/region.</span></span>

## <a name="see-also"></a><span data-ttu-id="2a635-125">Viz také</span><span class="sxs-lookup"><span data-stu-id="2a635-125">See Also</span></span>  
[<span data-ttu-id="2a635-126">Návod: Povolení plateb zákazníka pomocí PayPalu</span><span class="sxs-lookup"><span data-stu-id="2a635-126">How to: Enable Customer Payment Through PayPal</span></span>](sales-how-enable-customer-payments-paypal.md)  
[<span data-ttu-id="2a635-127">Vítejte v aplikaci Dynamics NAV</span><span class="sxs-lookup"><span data-stu-id="2a635-127">Welcome to Dynamics NAV</span></span>](across-get-started.md)  

