---
title: "Účtování nákupů"
author: SusanneWindfeldPedersen
ms.custom: na
ms.date: 09/22/2016
ms.reviewer: na
ms.suite: na
ms.tgt_pltfrm: na
ms.topic: article
ms.prod: dynamics-nav-2017
ms.translationtype: HT
ms.sourcegitcommit: 6b60b1344a1e18ad91863046110df880f75f7c04
ms.openlocfilehash: 646ea47adfe2f949e0fdf950607e7d246dcb9f59
ms.contentlocale: cs-cz
ms.lasthandoff: 07/19/2017

---

# <a name="posting-purchases"></a><span data-ttu-id="bbcf8-102">Účtování nákupů</span><span class="sxs-lookup"><span data-stu-id="bbcf8-102">Posting Purchases</span></span>
<span data-ttu-id="bbcf8-103">Ve skupině **Účtování** na nákupním dokladu si můžete vybrat mezi následujícími funkcemi:</span><span class="sxs-lookup"><span data-stu-id="bbcf8-103">In the **Posting group** on a purchase document, you can choose between the following posting functions:</span></span>

- <span data-ttu-id="bbcf8-104">**Účtovat**</span><span class="sxs-lookup"><span data-stu-id="bbcf8-104">**Post**</span></span>
- <span data-ttu-id="bbcf8-105">**Náhled účtování**</span><span class="sxs-lookup"><span data-stu-id="bbcf8-105">**Preview Posting**</span></span>
- <span data-ttu-id="bbcf8-106">**Účtovat a vytisknout**</span><span class="sxs-lookup"><span data-stu-id="bbcf8-106">**Post and Print**</span></span>
- <span data-ttu-id="bbcf8-107">**Testovací sestava**</span><span class="sxs-lookup"><span data-stu-id="bbcf8-107">**Test Report**</span></span>
- <span data-ttu-id="bbcf8-108">**Dávkové účtování**</span><span class="sxs-lookup"><span data-stu-id="bbcf8-108">**Post Batch**</span></span>

<span data-ttu-id="bbcf8-109">Po dokončení všech řádků a zadání všech informací na objednávce ji můžete zaúčtovat, to znamená vytvoření příjemky a faktury.</span><span class="sxs-lookup"><span data-stu-id="bbcf8-109">When you have completed all the lines and entered all the information on the purchase order, you can post it, that is, create a receipt and an invoice.</span></span>

<span data-ttu-id="bbcf8-110">Po zaúčtování nákupní objednávky se aktualizují účty dodavatele, hlavní knihy a položky zboží.</span><span class="sxs-lookup"><span data-stu-id="bbcf8-110">When a purchase order is posted, the vendor's account, the general ledger, and the item ledger entries are updated.</span></span>

<span data-ttu-id="bbcf8-111">Pro každou nákupní objednávku je vytvořena nákupní položka v tabulce **Věcných položek**.</span><span class="sxs-lookup"><span data-stu-id="bbcf8-111">For each purchase order, a purchase entry is created in the **G/L Entry** table.</span></span> <span data-ttu-id="bbcf8-112">Položka je také vytvořena pro účet dodavatele v tabulce **Položka dodavatele** a věcná položka je vytvořena na příslušném účtu závazků.</span><span class="sxs-lookup"><span data-stu-id="bbcf8-112">An entry is also created in the vendor's account in the **Vendor Ledger Entry** table and a G/L entry is created in the relevant payables account.</span></span> <span data-ttu-id="bbcf8-113">Kromě toho může zaúčtování objednávky vést k vytvoření položky DPH a věcné položky pro částku slevy. </span><span class="sxs-lookup"><span data-stu-id="bbcf8-113">In addition, posting the order may result in a VAT entry and a G/L entry for the discount amount.</span></span> <span data-ttu-id="bbcf8-114">Zda je položka pro slevu zaúčtována, závisí na obsahu pole **Účtování slevy** v okně **Nastavení nákupu a závazků**.</span><span class="sxs-lookup"><span data-stu-id="bbcf8-114">Whether an entry for the discount is posted depends on the contents of the **Discount Posting** field in the **Purchases & Payables Setup** window.</span></span>

<span data-ttu-id="bbcf8-115">Pro každý řádek nákupní objednávky bude vytvořena položka zboží v tabulce **Položky zboží** (pokud budou řádky nákupu obsahovat čísla zboží) nebo bude vytvořena věcná položka v tabulce **Věcných položek** (pokud budou řádky nákupu obsahovat finanční účet).</span><span class="sxs-lookup"><span data-stu-id="bbcf8-115">For each purchase order line, an item ledger entry will be created in the **Item Ledger Entry** table (if the purchase lines contain item numbers) or a G/L entry will be created in the **G/L Entry** table (if the purchase lines contain a G/L account).</span></span> <span data-ttu-id="bbcf8-116">Kromě toho jsou nákupní objednávky vždy zaznamenávány v tabulkách **Hlavička nákupní příjemky a   Hlavička nákupní faktury**. </span><span class="sxs-lookup"><span data-stu-id="bbcf8-116">In addition, purchase orders are always recorded in the **Purch. Recpt. Header** and **Purch. Inv. Header** tables.</span></span>

<span data-ttu-id="bbcf8-117">Než začnete účtovat, můžete vytisknout testovací sestavu, která obsahuje všechny informace z nákupní objednávky a označuje případné chyby.</span><span class="sxs-lookup"><span data-stu-id="bbcf8-117">Before you start to post, you can print a test report that contains all the information in the purchase order and indicates any errors there.</span></span> <span data-ttu-id="bbcf8-118">Chcete-li sestavu vytisknout, zvolte možnost **Účtovat** a poté zvolte **Testovací sestava**.</span><span class="sxs-lookup"><span data-stu-id="bbcf8-118">To print the report, choose **Posting**, and then choose **Test Report**.</span></span>

<span data-ttu-id="bbcf8-119">**Důležité**: Když zaúčtujete objednávku, můžete vytvořit jak příjemku, tak fakturu. </span><span class="sxs-lookup"><span data-stu-id="bbcf8-119">**Important**: When you post an order, you can create both a receipt and an invoice.</span></span> <span data-ttu-id="bbcf8-120">To může být provedeno současně nebo nezávisle.</span><span class="sxs-lookup"><span data-stu-id="bbcf8-120">These can be done simultaneously or independently.</span></span> <span data-ttu-id="bbcf8-121">Můžete také vytvořit částečnou příjemku a částečnou fakturu tím, že předtím než zaúčtujete, vyplníte pole **Množ. k příjmu** a **Množ. k fakturaci** na jednotlivých řádcích nákupní objednávky. </span><span class="sxs-lookup"><span data-stu-id="bbcf8-121">You can also create a partial receipt and a partial invoice by completing the **Qty. to Receive** and **Qty. to Invoice** fields on the individual purchase order lines before you post.</span></span> <span data-ttu-id="bbcf8-122">Všimněte si, že nemůžete vytvořit fakturu za něco, co nebylo přijato.</span><span class="sxs-lookup"><span data-stu-id="bbcf8-122">Note that you cannot create an invoice for something that has not been received.</span></span> <span data-ttu-id="bbcf8-123">To znamená, že předtím, než budete moci fakturovat, musíte mít zaznamenanou příjemku, nebo musíte vybrat přijmout a fakturovat současně. </span><span class="sxs-lookup"><span data-stu-id="bbcf8-123">That is, before you can invoice, you must have recorded a receipt, or you must choose to receive and invoice at the same time.</span></span>

<span data-ttu-id="bbcf8-124">Můžete buď účtovat, nebo účtovat a tisknout.</span><span class="sxs-lookup"><span data-stu-id="bbcf8-124">You can either post, or post and print.</span></span> <span data-ttu-id="bbcf8-125">Pokud zvolíte účtovat a tisknout, pak se sestava vytiskne v okamžiku, kdy je objednávka účtována. </span><span class="sxs-lookup"><span data-stu-id="bbcf8-125">If you choose to post and print, a report is printed when the order is posted.</span></span> <span data-ttu-id="bbcf8-126">Můžete také zvolit funkci **Dávkové účtování**, která umožňuje účtovat více objednávek najednou.</span><span class="sxs-lookup"><span data-stu-id="bbcf8-126">You can also choose the **Post Batch** function, which lets you post several orders at the same time.</span></span>

<span data-ttu-id="bbcf8-127">Když je účtování kompletní, zaúčtované nákupní řádky jsou z objednávky odebrány.</span><span class="sxs-lookup"><span data-stu-id="bbcf8-127">When the posting is completed, the posted purchase lines are removed from the order.</span></span> <span data-ttu-id="bbcf8-128">Jakmile je účtování dokončeno je zobrazena zpráva.</span><span class="sxs-lookup"><span data-stu-id="bbcf8-128">A message tells you when the posting is completed.</span></span> <span data-ttu-id="bbcf8-129">Poté budete moci v různých oknech zobrazit zaúčtované položky jako jsou **Položky dodavatele**, **Věcné položky**, **Položky zboží**, **Nákupní příjemky** a **Zaúčtované nákupní faktury**.</span><span class="sxs-lookup"><span data-stu-id="bbcf8-129">After this, you will be able to see the posted entries in the various windows that contain posted entries, such as the **Vendor Ledger Entries**, **G/L Entries**, **Item Ledger Entries**, **Purchase Receipts**, and **Posted Purchase Invoices** windows.</span></span>

## <a name="see-also"></a><span data-ttu-id="bbcf8-130">Viz také</span><span class="sxs-lookup"><span data-stu-id="bbcf8-130">See Also</span></span>
[<span data-ttu-id="bbcf8-131">Účtovat doklady a deníky</span><span class="sxs-lookup"><span data-stu-id="bbcf8-131">Post Documents and Journals</span></span>](ui-post-documents-journals.md)

