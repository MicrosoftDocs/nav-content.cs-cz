<properties
                pageTitle="Návod: Přecenění zásob | Dynamics NAV"
                description="Popisuje, jak ocenit nebo odepsat hodnoty jednoho nebo více zboží v zásobách zaúčtováním jejich aktuální vypočtené hodnoty."
                services="project-madeira"
                documentationCenter=""
                authors="SorenGP"
/>
<tags
    ms.service="project-madeira"
    ms.topic="article"
    ms.devlang="na"
    ms.tgt_pltfrm="na"
    ms.workload="na"
    ms.date="11/07/2016"
    ms.author="SorenGP" />


# <a name="how-to-revalue-inventory"></a><span data-ttu-id="bf43b-103">Návod: Přecenění zásob</span><span class="sxs-lookup"><span data-stu-id="bf43b-103">How to: Revalue Inventory</span></span>   
<span data-ttu-id="bf43b-104">Chcete-li ocenit nebo odepsat zboží nebo položku, musíte použít deník přecenění.</span><span class="sxs-lookup"><span data-stu-id="bf43b-104">If you want to appreciate or depreciate an item or a specific item ledger entry, you must use the revaluation journal.</span></span>

## <a name="to-revalue-inventory"></a><span data-ttu-id="bf43b-105">Přecenění zásob</span><span class="sxs-lookup"><span data-stu-id="bf43b-105">To revalue inventory</span></span>
1. <span data-ttu-id="bf43b-106">V pravém horním rohu vyberte ikonu **Vyhledat stránku nebo sestavu**, zadejte **Deníky přecenění** a pak zvolte související odkaz.</span><span class="sxs-lookup"><span data-stu-id="bf43b-106">In the top right corner, choose the **Search for Page or Report** icon, enter **Revaluation Journal**, and then choose the related link.</span></span>
2. <span data-ttu-id="bf43b-107">Vyberte akci **Vypočítat hodnotu zásob**.</span><span class="sxs-lookup"><span data-stu-id="bf43b-107">Choose the **Calculate Inventory Value** action.</span></span>
3. <span data-ttu-id="bf43b-108">V okně **Vypočítat hodnotu zásob** vyplňte pole podle potřeby.</span><span class="sxs-lookup"><span data-stu-id="bf43b-108">In the **Calculate Inventory Value** window, fill in the fields as necessary.</span></span> <span data-ttu-id="bf43b-109">Vybrat pole k zobrazení krátkého popisu nebo odkazu pro více informací.</span><span class="sxs-lookup"><span data-stu-id="bf43b-109">Choose a field to read a short description of the field or link to more information.</span></span>
4. <span data-ttu-id="bf43b-110">Zvolte tlačítko **OK**.</span><span class="sxs-lookup"><span data-stu-id="bf43b-110">Choose the **OK** button.</span></span>
5. <span data-ttu-id="bf43b-111">Na každém řádku v okně **Deník přecenění** v poli **Pořizovací cena (přeceněná)** zadejte novou pořizovací cenu.</span><span class="sxs-lookup"><span data-stu-id="bf43b-111">On each line in the **Revaluation Journal** window, in the **Unit Cost (Revalued)** field, enter the new unit cost.</span></span> <span data-ttu-id="bf43b-112">Případně zadejte novou celkovou částku do pole **Hodnota zásob (přeceněná)**.</span><span class="sxs-lookup"><span data-stu-id="bf43b-112">Alternatively, enter the new total amount in the **Inventory Value (Revalued)** field.</span></span>

    <span data-ttu-id="bf43b-113">Příslušná pole jsou automaticky aktualizována.</span><span class="sxs-lookup"><span data-stu-id="bf43b-113">The relevant fields are automatically updated.</span></span> <span data-ttu-id="bf43b-114">Všimněte si, že pole **Částka** zobrazuje skutečnou změnu hodnoty zásob pro vybranou položku zboží.</span><span class="sxs-lookup"><span data-stu-id="bf43b-114">Note that the **Amount** field shows the actual change in inventory value for the selected item ledger entry.</span></span> <span data-ttu-id="bf43b-115">Vypočítá rozdíl mezi polem **Hodnota zásob (vypočtená)** a **Hodnota zásob (přeceněná)**.</span><span class="sxs-lookup"><span data-stu-id="bf43b-115">It calculates the difference between the **Inventory Value (Calculated)** field and the **Inventory Value (Revalued)** field.</span></span>

6. <span data-ttu-id="bf43b-116">Jakmile dokončíte všechny řádky v deníku přecenění, vyberte akci **Účtovat**.</span><span class="sxs-lookup"><span data-stu-id="bf43b-116">When you have completed all lines in the revaluation journal, choose the **Post** action.</span></span>

<span data-ttu-id="bf43b-117">Nové položky přecenění jsou nyní vytvořeny tak, aby odrážely přecenění, která jste zaúčtovali.</span><span class="sxs-lookup"><span data-stu-id="bf43b-117">New value entries are now created to reflect the revaluations that you have posted.</span></span> <span data-ttu-id="bf43b-118">Nové hodnoty můžete vidět na příslušných kartách zboží.</span><span class="sxs-lookup"><span data-stu-id="bf43b-118">You can see the new values on the respective item cards.</span></span>

## <a name="see-also"></a><span data-ttu-id="bf43b-119">Viz také</span><span class="sxs-lookup"><span data-stu-id="bf43b-119">See Also</span></span>
[<span data-ttu-id="bf43b-120">Správa skladů</span><span class="sxs-lookup"><span data-stu-id="bf43b-120">Manage Inventory</span></span>](inventory-manage-inventory.md)  
[<span data-ttu-id="bf43b-121">Správa prodeje</span><span class="sxs-lookup"><span data-stu-id="bf43b-121">Manage Sales</span></span>](sales-manage-sales.md)  
[<span data-ttu-id="bf43b-122">Správa nákupu</span><span class="sxs-lookup"><span data-stu-id="bf43b-122">Manage Purchasing</span></span>](purchasing-manage-purchasing.md)  
[<span data-ttu-id="bf43b-123">Práce s Dynamics NAV</span><span class="sxs-lookup"><span data-stu-id="bf43b-123">Work With Dynamics NAV</span></span>](ui-work-product.md)

