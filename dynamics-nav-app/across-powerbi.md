---
title: "Použití balíčku obsahu Dynamics NAV pro Power BI"
author: edupont04
ms.custom: na
ms.date: 09/22/2016
ms.reviewer: na
ms.suite: na
ms.tgt_pltfrm: na
ms.topic: article
ms.prod: dynamics-nav-2017
ms.translationtype: HT
ms.sourcegitcommit: 6b60b1344a1e18ad91863046110df880f75f7c04
ms.openlocfilehash: ad9519b8ce9c244480308ccc99c05e78e4926b06
ms.contentlocale: cs-cz
ms.lasthandoff: 10/16/2017

---

# <a name="using-the-dynamics-nav-content-pack-for-power-bi"></a><span data-ttu-id="cae9b-102">Použití balíčku obsahu Dynamics NAV pro Power BI</span><span class="sxs-lookup"><span data-stu-id="cae9b-102">Using the Dynamics NAV Content Pack for Power BI</span></span>
<span data-ttu-id="cae9b-103">Získejte přehled o vašich datech v Dynamics NAV pomocí funkce Power BI a balíčku obsahu Dynamics NAV.</span><span class="sxs-lookup"><span data-stu-id="cae9b-103">Getting insights into your Dynamics NAV data is easy with Power BI and the Dynamics NAV content pack.</span></span> <span data-ttu-id="cae9b-104">Power BI načítá vaše data a poté sestaví řídící panel a přehledy vycházející z těchto dat.</span><span class="sxs-lookup"><span data-stu-id="cae9b-104">Power BI retrieves your data and then builds an out-of-the-box dashboard and reports based on that data.</span></span>  

<span data-ttu-id="cae9b-105">Balíček obsahu je překonfigurován pro práci s prodejními a finančními daty od demonstrační společnosti, které získáte při registraci k Dynamics NAV.</span><span class="sxs-lookup"><span data-stu-id="cae9b-105">The content pack is preconfigured to work with sales data and financial data from the demonstration company that you get when you sign up for the Dynamics NAV preview.</span></span>  

- <span data-ttu-id="cae9b-106">Vyberte si jakýkoli vizuál na řídícím panelu, abyste získali jednu ze sedmi podkladových zpráv.</span><span class="sxs-lookup"><span data-stu-id="cae9b-106">Choose any visual on the dashboard to bring up one of seven underlying reports.</span></span>  
- <span data-ttu-id="cae9b-107">Filtrování sestavy nebo přidání polí, které chcete sledovat.</span><span class="sxs-lookup"><span data-stu-id="cae9b-107">Filter the report or add fields that you want to monitor.</span></span>  
- <span data-ttu-id="cae9b-108">Připojte toto přizpůsobené zobrazení k řídicímu panelu a pokračujte ve sledování.</span><span class="sxs-lookup"><span data-stu-id="cae9b-108">Pin this customized view to the dashboard to continue tracking.</span></span>  
<span data-ttu-id="cae9b-109">Řídicí panel a podkladové zprávy se denně aktualizují.</span><span class="sxs-lookup"><span data-stu-id="cae9b-109">The dashboard and underlying reports refresh daily.</span></span> <span data-ttu-id="cae9b-110">Můžete upravit plán obnovení a upravit frekvenci v datovém souboru.</span><span class="sxs-lookup"><span data-stu-id="cae9b-110">You can control the refresh schedule and modify the frequency on the dataset.</span></span>  

## <a name="accessing-dynamics-nav-in-power-bi"></a><span data-ttu-id="cae9b-111">Přístup k Dynamics NAV v Power BI</span><span class="sxs-lookup"><span data-stu-id="cae9b-111">Accessing Dynamics NAV in Power BI</span></span>
<span data-ttu-id="cae9b-112">Chcete-li zobrazit údaje Dynamics NAV v Power BI, musíte mít následující:</span><span class="sxs-lookup"><span data-stu-id="cae9b-112">To see your Dynamics NAV data in Power BI, you must have the following:</span></span>  

- <span data-ttu-id="cae9b-113">Přístup k Dynamics NAV.</span><span class="sxs-lookup"><span data-stu-id="cae9b-113">Access to Dynamics NAV.</span></span> <span data-ttu-id="cae9b-114">Další informace naleznete v tématu [Dynamics NAV](http://go.microsoft.com/fwlink/?LinkID=759714).</span><span class="sxs-lookup"><span data-stu-id="cae9b-114">For more information, see [Dynamics NAV](http://go.microsoft.com/fwlink/?LinkID=759714).</span></span>  
- <span data-ttu-id="cae9b-115">Přístup k Power BI.</span><span class="sxs-lookup"><span data-stu-id="cae9b-115">Access to Power BI.</span></span> <span data-ttu-id="cae9b-116">Další informace naleznete v tématu [Power BI](https://powerbi.microsoft.com).</span><span class="sxs-lookup"><span data-stu-id="cae9b-116">For more information, see [Power BI](https://powerbi.microsoft.com).</span></span>

<span data-ttu-id="cae9b-117">Na webu Power BI naleznete další informace o přidání balíčku obsahu Dynamics NAV do Power BI. [Přidání balíčku obsahu Dynamics NAV k Power BI](http://go.microsoft.com/fwlink/?LinkID=760850).</span><span class="sxs-lookup"><span data-stu-id="cae9b-117">On the Power BI site, you can find additional information about [adding the Dynamics NAV content pack to Power BI](http://go.microsoft.com/fwlink/?LinkID=760850).</span></span>  

<span data-ttu-id="cae9b-118">Chcete-li získat přístup k sadě obsahu Dynamics NAV v Power BI, v okně připojení musíte zadat následující informace:</span><span class="sxs-lookup"><span data-stu-id="cae9b-118">To access the Dynamics NAV content pack in Power BI, in the connection window, you must specify the following information:</span></span>

| <span data-ttu-id="cae9b-119">Pole</span><span class="sxs-lookup"><span data-stu-id="cae9b-119">Field</span></span>       | <span data-ttu-id="cae9b-120">Popis</span><span class="sxs-lookup"><span data-stu-id="cae9b-120">Description</span></span>              |
|-------------|--------------------------|
|<span data-ttu-id="cae9b-121">**OData Feed URL**</span><span class="sxs-lookup"><span data-stu-id="cae9b-121">**OData Feed URL**</span></span>|<span data-ttu-id="cae9b-122">OData URL, takže Power BI může mít přístup k datům od vaší společnosti, například https://mybusiness.com:7048/MS/OData/Company('CRONUS%20US').</span><span class="sxs-lookup"><span data-stu-id="cae9b-122">The OData URL so Power BI can access data from your company, such as https://mybusiness.com:7048/MS/OData/Company('CRONUS%20US').</span></span>|
|<span data-ttu-id="cae9b-123">**Metoda ověřování**</span><span class="sxs-lookup"><span data-stu-id="cae9b-123">**Authentication method**</span></span>|<span data-ttu-id="cae9b-124">Zvolte **Základní**.</span><span class="sxs-lookup"><span data-stu-id="cae9b-124">Choose **Basic**.</span></span>|
|<span data-ttu-id="cae9b-125">**Uživatelské jméno**</span><span class="sxs-lookup"><span data-stu-id="cae9b-125">**User name**</span></span>|<span data-ttu-id="cae9b-126">E-mailový účet, který jste použili k registraci pro službu Dynamics NAV například *me@mybusiness.com*.</span><span class="sxs-lookup"><span data-stu-id="cae9b-126">The email account that you used to sign up for Dynamics NAV, such as *me@mybusiness.com*.</span></span>|
|<span data-ttu-id="cae9b-127">**Heslo**</span><span class="sxs-lookup"><span data-stu-id="cae9b-127">**Password**</span></span>|<span data-ttu-id="cae9b-128">Toto je klíč pro přístup k webovým službám pro váš uživatelský účet v Dynamics NAV.</span><span class="sxs-lookup"><span data-stu-id="cae9b-128">This is the web service access key for your user account in Dynamics NAV.</span></span>|

<span data-ttu-id="cae9b-129">Toto znamená, že musíte získat dvě informace z Dynamics NAV: OData URL a klíč pro přístup k webové službě pro váš uživatelský účet.</span><span class="sxs-lookup"><span data-stu-id="cae9b-129">This means that you must get two pieces of information from Dynamics NAV: The OData URL and the web service access key for your user account.</span></span>  
<span data-ttu-id="cae9b-130">**Získání adresy URL**</span><span class="sxs-lookup"><span data-stu-id="cae9b-130">**Getting the URL**</span></span>  
<span data-ttu-id="cae9b-131">Pokud přidáte Dynamics NAV k Power BI, musíte zadat adresu URL, aby mohl mít Power BI přístup k datům vaší společnosti.</span><span class="sxs-lookup"><span data-stu-id="cae9b-131">When you add Dynamics NAV to Power BI, you must specify a URL so Power BI can access data from your company.</span></span> <span data-ttu-id="cae9b-132">V okně připojení je adresa URL označována jako **OData Feed URL** a musí mít následující formát:</span><span class="sxs-lookup"><span data-stu-id="cae9b-132">In the connection window, the URL is referred to as the **OData Feed URL**, and it must have the following format:</span></span>

         https://mybusiness.projectmadeira.com:7048/MS/OData/Company('CRONUS%20US')  
<span data-ttu-id="cae9b-133">V tomto příkladu je *mybusiness* název služby Dynamics NAV a *CRONUS US* je název demonstrační společnosti s *%20* reprezentujícím mezeru v názvu.</span><span class="sxs-lookup"><span data-stu-id="cae9b-133">In this example, *mybusiness* is the name of your Dynamics NAV service, and *CRONUS US* is the name of the demonstration company with *%20* representing the space in the name.</span></span>   
<span data-ttu-id="cae9b-134">Chcete-li získat adresu URL, v aplikaci Dynamics NAV vyhledejte a otevřete okno **Webové služby**.</span><span class="sxs-lookup"><span data-stu-id="cae9b-134">To get the URL, in Dynamics NAV, search for and open the **Web Services** window.</span></span> <span data-ttu-id="cae9b-135">Toto okno obsahuje seznam webových služeb, které jsou aktuálně k dispozici a můžete zkopírovat odkaz z pole **OData URL** pro jednu z výchozích webových služeb OData.</span><span class="sxs-lookup"><span data-stu-id="cae9b-135">This window lists the web services that are currently available, and you can copy the link from the **OData URL** field for one of the default OData web services.</span></span>  
<span data-ttu-id="cae9b-136">**Získání klíče pro přístup k webové službě**</span><span class="sxs-lookup"><span data-stu-id="cae9b-136">**Getting the web service access key**</span></span>  
<span data-ttu-id="cae9b-137">Chcete-li v okně **Připojení k Dynamics NAV** použít data ze služby Dynamics NAV v Power BI, musíte zadat uživatelské jméno, kterým je váš e-mailový účet a heslo.</span><span class="sxs-lookup"><span data-stu-id="cae9b-137">In order to use data from Dynamics NAV, in Power BI, in the **Connect to Dynamics NAV** window, you must specify your user name, which is your email account, and a password.</span></span> <span data-ttu-id="cae9b-138">Heslo je klíč pro přístup k webové službě, který je nastaven pro váš uživatelský účet v Dynamics NAV.</span><span class="sxs-lookup"><span data-stu-id="cae9b-138">The password is the web service access key that is set up for your user account in Dynamics NAV.</span></span>  
<span data-ttu-id="cae9b-139">Chcete-li získat klíč pro přístup k webové službě, vyhledejte v aplikaci Dynamics NAV okno **Uživatelé** a poté otevřete kartu pro svůj uživatelský účet.</span><span class="sxs-lookup"><span data-stu-id="cae9b-139">To get a web service access key, in Dynamics NAV, search for the **Users** window, and then open the card for your user account.</span></span> <span data-ttu-id="cae9b-140">Na **webové službě Access** zkopírujte obsah pole **Klíč webové služby Access**.</span><span class="sxs-lookup"><span data-stu-id="cae9b-140">On the **Web Service Access** FastTab, copy the contents of the **Web Service Access Key** field.</span></span> <span data-ttu-id="cae9b-141">Pokud je pole prázdné, v pásu karet vyberte možnost **Změnit klíč webové služby Access**, vyberte pole **Klíč nikdy nevyprší** a potom klepněte na tlačítko OK.</span><span class="sxs-lookup"><span data-stu-id="cae9b-141">If the field is blank, in the ribbon, choose **Change Web Service Access Key**, choose the **Key Never Expires** field, and then choose the OK button.</span></span> <span data-ttu-id="cae9b-142">Potom můžete klíč zkopírovat.</span><span class="sxs-lookup"><span data-stu-id="cae9b-142">You can then copy the key.</span></span>  

## <a name="getting-data-from-dynamics-nav"></a><span data-ttu-id="cae9b-143">Získání dat z Dynamics NAV</span><span class="sxs-lookup"><span data-stu-id="cae9b-143">Getting Data from Dynamics NAV</span></span>
<span data-ttu-id="cae9b-144">Na řídícím panelu Dynamics NAV se zobrazují nejtypičtější zprávy, které budete chtít použít ke sledování vaší firmy.</span><span class="sxs-lookup"><span data-stu-id="cae9b-144">The Dynamics NAV dashboard shows the most typical reports that you will want to use to track your business.</span></span> <span data-ttu-id="cae9b-145">Data jsou získána z vaší společnosti Dynamics NAV pomocí webových služeb pro čtení reálných dat.</span><span class="sxs-lookup"><span data-stu-id="cae9b-145">The data is extracted from your Dynamics NAV company using web services to read live data.</span></span> <span data-ttu-id="cae9b-146">V okně Dynamics NAV **Webové služby** jsou seznamy webových služeb, které byly pro vás nastaveny včetně následujících, které spotřebovává balíček obsahu v Power BI:</span><span class="sxs-lookup"><span data-stu-id="cae9b-146">In Dynamics NAV, the **Web Services** window lists the web services that have been set up for you, including the following that are consumed by the content pack in Power BI:</span></span>  

- <span data-ttu-id="cae9b-147">ItemSalesAndProfit</span><span class="sxs-lookup"><span data-stu-id="cae9b-147">ItemSalesAndProfit</span></span>  
- <span data-ttu-id="cae9b-148">ItemSalesByCustomer</span><span class="sxs-lookup"><span data-stu-id="cae9b-148">ItemSalesByCustomer</span></span>  
- <span data-ttu-id="cae9b-149">powerbifinance-setup</span><span class="sxs-lookup"><span data-stu-id="cae9b-149">powerbifinance-setup</span></span>  
- <span data-ttu-id="cae9b-150">SalesDashboard</span><span class="sxs-lookup"><span data-stu-id="cae9b-150">SalesDashboard</span></span>  
- <span data-ttu-id="cae9b-151">SalesOpportunities</span><span class="sxs-lookup"><span data-stu-id="cae9b-151">SalesOpportunities</span></span>  
- <span data-ttu-id="cae9b-152">SalesOrdersBySalesPerson</span><span class="sxs-lookup"><span data-stu-id="cae9b-152">SalesOrdersBySalesPerson</span></span>  
- <span data-ttu-id="cae9b-153">TopCustomerOverview</span><span class="sxs-lookup"><span data-stu-id="cae9b-153">TopCustomerOverview</span></span>  

<span data-ttu-id="cae9b-154">**Poznámka**: Pokud změníte název některé z těchto webových služeb, data se nebudou zobrazovat v Power BI.</span><span class="sxs-lookup"><span data-stu-id="cae9b-154">**Note**: If you change the name of any of these web services, the data will not show up in Power BI.</span></span>  
<span data-ttu-id="cae9b-155">Chcete-li přidat další údaje do Power BI, musíte najít tabulky v Dynamics NAV, zobrazit je jako webové služby a přidat je do obsahu.</span><span class="sxs-lookup"><span data-stu-id="cae9b-155">If you want to add use other data in Power BI, you must find the tables in Dynamics NAV, expose them as web services, and then add them to the content pack.</span></span> <span data-ttu-id="cae9b-156">Jedná se o pokročilý scénář a doporučujeme začít s údaji, které jsou již k dispozici v Power BI.</span><span class="sxs-lookup"><span data-stu-id="cae9b-156">This is an advanced scenario, and we recommend that you start with the data that is already available in Power BI.</span></span>  

## <a name="troubleshooting"></a><span data-ttu-id="cae9b-157">Odstraňování problémů</span><span class="sxs-lookup"><span data-stu-id="cae9b-157">Troubleshooting</span></span>
<span data-ttu-id="cae9b-158">Řídicí panel Power BI se spoléhá na publikované webové služby, které jsou uvedeny výše a bude zobrazovat data od demonstrační společnosti nebo vlastní firmy, pokud importujete data z vašeho aktuálního řešení finančního nastavení.</span><span class="sxs-lookup"><span data-stu-id="cae9b-158">The Power BI dashboard relies on the published web services that are listed above, and it will show data from the demonstration company or your own company if you import data from your current finance-setup solution.</span></span> <span data-ttu-id="cae9b-159">Pokud se však něco pokazí, tato část poskytuje řešení pro nejtypičtějších problémy.</span><span class="sxs-lookup"><span data-stu-id="cae9b-159">However, if something goes wrong, this section provides a workaround for the most typical issues.</span></span>  

<span data-ttu-id="cae9b-160">**"Ověření parametrů se nezdařilo, zkontrolujte, zda jsou všechny parametry platné“**</span><span class="sxs-lookup"><span data-stu-id="cae9b-160">**"Parameter validation failed, please make sure all parameters are valid"**</span></span>  
<span data-ttu-id="cae9b-161">Pokud se vám tato chyba zobrazí po zadání adresy URL služby Dynamics NAV, ujistěte se, že jsou splněny následující požadavky:</span><span class="sxs-lookup"><span data-stu-id="cae9b-161">If you see this error after you enter your Dynamics NAV URL, make sure the following requirements are satisfied:</span></span>  

- <span data-ttu-id="cae9b-162">Adresa URL přesně odpovídá tomuto vzoru:</span><span class="sxs-lookup"><span data-stu-id="cae9b-162">The URL follows exactly this pattern:</span></span>

    <span data-ttu-id="cae9b-163">https://mybusiness.projectmadeira.com:7048/MS/OData/Company('CRONUS%20US')</span><span class="sxs-lookup"><span data-stu-id="cae9b-163">https://mybusiness.projectmadeira.com:7048/MS/OData/Company('CRONUS%20US')</span></span>  
- <span data-ttu-id="cae9b-164">Odstraňte jakýkoli text za názvem společnosti v závorkách</span><span class="sxs-lookup"><span data-stu-id="cae9b-164">Delete any text after the company name in parenthesis</span></span>  
- <span data-ttu-id="cae9b-165">Ujistěte se, že na konci adresy URL nejsou žádná lomítka.</span><span class="sxs-lookup"><span data-stu-id="cae9b-165">Make sure there are no trailing forward slash at the end of the URL.</span></span>  
- <span data-ttu-id="cae9b-166">Ujistěte se, že se jedná o zabezpečené připojení, jak je uvedeno na adrese URL začínající *https*.</span><span class="sxs-lookup"><span data-stu-id="cae9b-166">Make sure that it is a secure connection as indicated by the URL starting with *https*.</span></span>  


<span data-ttu-id="cae9b-167">**"Přihlášení se nezdařilo“**</span><span class="sxs-lookup"><span data-stu-id="cae9b-167">**"Login failed"**</span></span>  
<span data-ttu-id="cae9b-168">Pokud při přihlašování k řídicímu panelu se pomocí přihlašovacích údajů Dynamics NAV zobrazí chyba "přihlášení se nezdařilo", může to být způsobeno jedním z následujících problémů:</span><span class="sxs-lookup"><span data-stu-id="cae9b-168">If you get a "login failed" error when you log in to the dashboard, using your Dynamics NAV credentials, then this can be caused by one of the following issues:</span></span>

* <span data-ttu-id="cae9b-169">Účet, který používáte, nemá oprávnění ke čtení dat Dynamics NAV z vašeho účtu.</span><span class="sxs-lookup"><span data-stu-id="cae9b-169">The account you are using does not have permissions to read the Dynamics NAV data from your account.</span></span>

    <span data-ttu-id="cae9b-170">Ověřte svůj uživatelský účet v aplikaci Dynamics NAV a ujistěte se, že jste použili správný přístupový klíč webové služby jako heslo a zkuste to znovu.</span><span class="sxs-lookup"><span data-stu-id="cae9b-170">Verify your user account in Dynamics NAV, and make sure that you have used the right web service access key as the password, and then try again.</span></span>  
* <span data-ttu-id="cae9b-171">Instance Dynamics NAV, ke které se pokoušíte připojit, nemá platný certifikát SSL.</span><span class="sxs-lookup"><span data-stu-id="cae9b-171">The Dynamics NAV  instance that you are trying to connect to does not have a valid SSL certificate.</span></span> <span data-ttu-id="cae9b-172">V takovém případě se zobrazí podrobnější chybová zpráva ("nelze vytvořit důvěryhodný vztah SSL").</span><span class="sxs-lookup"><span data-stu-id="cae9b-172">In this case you'll see a more detailed error message ("unable to establish trusted SSL relationship").</span></span>

    <span data-ttu-id="cae9b-173">**Poznámka**: Samostatně podepsané certifikáty nejsou podporovány.</span><span class="sxs-lookup"><span data-stu-id="cae9b-173">**Note**: Self-signed certificates are not supported.</span></span>  


<span data-ttu-id="cae9b-174">**"Ups“**</span><span class="sxs-lookup"><span data-stu-id="cae9b-174">**"Oops"**</span></span>  
<span data-ttu-id="cae9b-175">Zobrazí-li dialogové okno chybu "Ups" po zadání ověřování dialogového okna, je to nejčastěji způsobeno problémem s připojením k datům pro obsahový balíček.</span><span class="sxs-lookup"><span data-stu-id="cae9b-175">If you see an "Oops" error dialog after you pass the authentication dialog, this is most frequently caused by a problem connecting to the data for the content pack.</span></span>

* <span data-ttu-id="cae9b-176">Ověřte, zda adresa URL odpovídá vzoru uvedenému dříve:</span><span class="sxs-lookup"><span data-stu-id="cae9b-176">Verify that the URL follows the pattern that was specified earlier:</span></span>

    <span data-ttu-id="cae9b-177">https://mybusiness.projectmadeira.com:7048/MS/OData/Company('CRONUS%20US')</span><span class="sxs-lookup"><span data-stu-id="cae9b-177">https://mybusiness.projectmadeira.com:7048/MS/OData/Company('CRONUS%20US')</span></span>  
* <span data-ttu-id="cae9b-178">Obvyklou chybou je nezadání úplné adresy URL konkrétní webové služby:</span><span class="sxs-lookup"><span data-stu-id="cae9b-178">A common mistake is to specify the full URL for a specific web service:</span></span>

    <span data-ttu-id="cae9b-179">https://mybusiness.projectmadeira.com:7048/MS/OData/Company('CRONUS%20US')/powerbifinance-setup</span><span class="sxs-lookup"><span data-stu-id="cae9b-179">https://mybusiness.projectmadeira.com:7048/MS/OData/Company('CRONUS%20US')/powerbifinance-setup</span></span>  
* <span data-ttu-id="cae9b-180">Nebo jste možná zapomněli zadat název společnosti:</span><span class="sxs-lookup"><span data-stu-id="cae9b-180">Or you might have forgotten to specify the company name:</span></span>

    <span data-ttu-id="cae9b-181">https://mybusiness.projectmadeira.com:7048/MS/OData/</span><span class="sxs-lookup"><span data-stu-id="cae9b-181">https://mybusiness.projectmadeira.com:7048/MS/OData/</span></span>  


## <a name="see-also"></a><span data-ttu-id="cae9b-182">Viz také</span><span class="sxs-lookup"><span data-stu-id="cae9b-182">See Also</span></span>
[<span data-ttu-id="cae9b-183">Vítejte v Dynamics NAV</span><span class="sxs-lookup"><span data-stu-id="cae9b-183">Welcome to Dynamics NAV</span></span>](across-get-started.md)  

