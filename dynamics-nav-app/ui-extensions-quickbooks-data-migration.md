---
title: "POužiPoužití rozšíření QuickBooks Migration"
description: "Popisuje jak použít rozšíření k importu zákazníků, dodavatelů, zboží, a finančních účtů z QuickBooks Desktop do Dynamics NAV."
author: edupont04
ms.prod: dynamics-nav-2018
ms.topic: article
ms.devlang: na
ms.tgt_pltfrm: na
ms.workload: na
ms. search.keywords: app, add-in, manifest, customize, import, implement
ms.date: 03/29/2017
ms.author: edupont
ms.translationtype: HT
ms.sourcegitcommit: 1dfba8b14019991c95f40ffd5f7fbaed5df414eb
ms.openlocfilehash: d0e0f8d69d4fe6966afb53aae476081496acfd8b
ms.contentlocale: cs-cz
ms.lasthandoff: 12/01/2017

---
# <a name="the-quickbooks-data-migration-extension-for-dynamics-nav"></a><span data-ttu-id="5a195-103">Rozšíření migrace dat QuickBooks pro Dynamics NAV</span><span class="sxs-lookup"><span data-stu-id="5a195-103">The QuickBooks Data Migration Extension for Dynamics NAV</span></span>
<span data-ttu-id="5a195-104">Toto rozšíření usnadňuje migraci zákazníků, dodavatelů, zboží a fin. účtů z QuickBooks do [!INCLUDE[d365fin](includes/d365fin_md.md)].</span><span class="sxs-lookup"><span data-stu-id="5a195-104">This extension makes it easy to migrate customers, vendors, items, and accounts from QuickBooks Desktop to [!INCLUDE[d365fin](includes/d365fin_md.md)].</span></span> <span data-ttu-id="5a195-105">Pokud vaše firma používá služby QuickBooks, můžete exportovat příslušné informace a poté otevřít pomocnou instalační příručku pro nahrání dat do [!INCLUDE[d365fin](includes/d365fin_md.md)].</span><span class="sxs-lookup"><span data-stu-id="5a195-105">If your business uses QuickBooks today, you can export the relevant information and then open an assisted setup guide to upload the data to [!INCLUDE[d365fin](includes/d365fin_md.md)].</span></span>  
<span data-ttu-id="5a195-106">Pro více informací bežte na: [Import obchodních dat z jiných finančních systémů](upload-data.md).</span><span class="sxs-lookup"><span data-stu-id="5a195-106">For more information, see [Importing Business Data from Other Finance Systems](upload-data.md).</span></span>

## <a name="exporting-data-from-quickbooks-desktop"></a><span data-ttu-id="5a195-107">Export dat z QuickBooks Desktop</span><span class="sxs-lookup"><span data-stu-id="5a195-107">Exporting Data from QuickBooks Desktop</span></span>
<span data-ttu-id="5a195-108">Musíte exportovat některé nebo všechny své stávající zákazníky, dodavatele, zásoby zboží a účty položky do souboru Intuit Interchange Format (IIF).</span><span class="sxs-lookup"><span data-stu-id="5a195-108">You must have exported some or all of your existing customers, vendors, inventory items, and accounts to an Intuit Interchange Format (IIF) file.</span></span> <span data-ttu-id="5a195-109">Rozšíření migrace dat QuickBooks obsahuje standardní mapování dat služby QuickBooks, takže můžete použít stávající data k otestování nové společnosti v [!INCLUDE[d365fin](includes/d365fin_md.md)].</span><span class="sxs-lookup"><span data-stu-id="5a195-109">The QuickBooks Data Migration extension includes a default mapping of QuickBooks data so that you can use your existing data to test your new [!INCLUDE[d365fin](includes/d365fin_md.md)] company.</span></span> <span data-ttu-id="5a195-110">Výchozí mapování bude v převážné většině případů postačující, ale můžete změnit mapování v příručce pro asistenci.</span><span class="sxs-lookup"><span data-stu-id="5a195-110">The default mapping will be sufficient in the vast majority of cases, but you can change the mapping in the assisted setup guide.</span></span>  
<span data-ttu-id="5a195-111">QuickBooks obsahuje nástroj na export seznamů v menu.</span><span class="sxs-lookup"><span data-stu-id="5a195-111">In QuickBooks, the File menu includes a utility to export lists.</span></span> <span data-ttu-id="5a195-112">Pro účely [!INCLUDE[d365fin](includes/d365fin_md.md)] můžete exportovat následující seznamy:</span><span class="sxs-lookup"><span data-stu-id="5a195-112">For the purposes of [!INCLUDE[d365fin](includes/d365fin_md.md)], you can export the following lists:</span></span>

* <span data-ttu-id="5a195-113">Seznam zákazníků</span><span class="sxs-lookup"><span data-stu-id="5a195-113">Customer List</span></span>  
* <span data-ttu-id="5a195-114">Seznam dodavatelů</span><span class="sxs-lookup"><span data-stu-id="5a195-114">Vendor List</span></span>  
* <span data-ttu-id="5a195-115">Seznam zboží</span><span class="sxs-lookup"><span data-stu-id="5a195-115">Item List</span></span>  
* <span data-ttu-id="5a195-116">Seznam účtů</span><span class="sxs-lookup"><span data-stu-id="5a195-116">Account List</span></span>  

<span data-ttu-id="5a195-117">Exportovaná data jsou uložena jako soubor typu IIF, který můžete poté nahrát do aplikace [!INCLUDE[d365fin](includes/d365fin_md.md)].</span><span class="sxs-lookup"><span data-stu-id="5a195-117">The exported data is saved as an IIF file that you can then upload to [!INCLUDE[d365fin](includes/d365fin_md.md)].</span></span>

## <a name="finding-the-quickbooks-data-migration-extension"></a><span data-ttu-id="5a195-118">Nalezení rozšíření QuickBooks Data Migration</span><span class="sxs-lookup"><span data-stu-id="5a195-118">Finding the QuickBooks Data Migration Extension</span></span>
<span data-ttu-id="5a195-119">Rozšíření QuickjBooks Data Migration je instalováno a připraveno k použití jako integrovaná část asistovaného nastavení migrace dat.</span><span class="sxs-lookup"><span data-stu-id="5a195-119">The QuickBooks Data Migration extension is installed and ready to go as an integrated part of the Data Migration assisted setup guide.</span></span> <span data-ttu-id="5a195-120">Pokud jste připraveni začít a máte exportovaná vaše data z QuickBooks, zvolte ikonu ![Vyhledat stránku nebo sestavu](media/ui-search/search_small.png "Ikona Vyhledat stránku nebo sestavu"), zadejte **Asistovaná nastavení** a vyberte související odkaz.</span><span class="sxs-lookup"><span data-stu-id="5a195-120">If you are ready to get started now, and have exported your data from QuickBooks, choose the ![Search for Page or Report](media/ui-search/search_small.png "Search for Page or Report icon") icon, enter **Assisted Setup**, and then choose the related link.</span></span> <span data-ttu-id="5a195-121">Vyberte **Migrovat obchodní data** a sledujte následující kroky v průvodci.</span><span class="sxs-lookup"><span data-stu-id="5a195-121">Choose **Migrate business data**, and then follow the steps in the guide.</span></span>  

## <a name="see-also"></a><span data-ttu-id="5a195-122">Viz také</span><span class="sxs-lookup"><span data-stu-id="5a195-122">See Also</span></span>
[<span data-ttu-id="5a195-123">Importování obchodních dat z jiných finančních systémů</span><span class="sxs-lookup"><span data-stu-id="5a195-123">Importing Business Data from Other Finance Systems</span></span>](upload-data.md)  
<span data-ttu-id="5a195-124">[Přizpůsobení [!INCLUDE[d365fin](includes/d365fin_md.md)] Pomocí rozšíření ](ui-extensions.md)</span><span class="sxs-lookup"><span data-stu-id="5a195-124">[Customizing [!INCLUDE[d365fin](includes/d365fin_md.md)] Using Extensions ](ui-extensions.md)</span></span>  

