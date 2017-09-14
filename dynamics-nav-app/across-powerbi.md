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
ms.translationtype: Human Translation
ms.sourcegitcommit: 51adfb3588099c496f0946ff71da5c6fe518f070
ms.openlocfilehash: 6351e4819a2f3665cc561b5b1f868eea5d435f75
ms.contentlocale: cs-cz
ms.lasthandoff: 06/26/2017

---

# <a name="using-the-dynamics-nav-content-pack-for-power-bi"></a>Použití balíčku obsahu [!INCLUDE[navnowlong](includes/navnowlong_md.md)] pro Power BI
Získejte přehled o vašich datech v [!INCLUDE[navnow](includes/navnow_md.md)] pomocí funkce Power BI a balíčku obsahu [!INCLUDE[navnow](includes/navnow_md.md)]. Power BI načítá vaše data a poté sestaví řídící panel a přehledy vycházející z těchto dat.  

Balíček obsahu je překonfigurován pro práci s prodejními a finančními daty od demonstrační společnosti, které získáte při registraci k [!INCLUDE[navnow](includes/navnow_md.md)].  

- Vyberte si jakýkoli vizuál na řídícím panelu, abyste získali jednu ze sedmi podkladových zpráv.  
- Filtrování sestavy nebo přidání polí, které chcete sledovat.  
- Připojte toto přizpůsobené zobrazení k řídicímu panelu a pokračujte ve sledování.  
Řídicí panel a podkladové zprávy se denně aktualizují. Můžete upravit plán obnovení a upravit frekvenci v datovém souboru.  

## <a name="accessing-dynamics-nav-in-power-bi"></a>Přístup k [!INCLUDE[navnow](includes/navnow_md.md)] v Power BI
Chcete-li zobrazit údaje [!INCLUDE[navnow](includes/navnow_md.md)] v Power BI, musíte mít následující:  

- Přístup k [!INCLUDE[navnow](includes/navnow_md.md)]. Další informace naleznete v tématu [[!INCLUDE[navnow](includes/navnow_md.md)]](http://go.microsoft.com/fwlink/?LinkID=759714).  
- Přístup k Power BI. Další informace naleznete v tématu [Power BI](https://powerbi.microsoft.com).

Na webu Power BI naleznete další informace o přidání balíčku obsahu [!INCLUDE[navnow](includes/navnow_md.md)] do Power BI. [Přidání balíčku obsahu [!INCLUDE[navnow](includes/navnow_md.md)] k Power BI](http://go.microsoft.com/fwlink/?LinkID=760850).  

Chcete-li získat přístup k sadě obsahu [!INCLUDE[navnow](includes/navnow_md.md)] v Power BI, v okně připojení musíte zadat následující informace:

| Pole       | Popis              |
|-------------|--------------------------|
|**OData Feed URL**|OData URL, takže Power BI může mít přístup k datům od vaší společnosti, například https://mybusiness.com:7048/MS/OData/Company('CRONUS%20US').|
|**Metoda ověřování**|Zvolte **Základní**.|
|**Uživatelské jméno**|E-mailový účet, který jste použili k registraci pro službu [!INCLUDE[navnow](includes/navnow_md.md)] například *me@mybusiness.com*.|
|**Heslo**|Toto je klíč pro přístup k webovým službám pro váš uživatelský účet v [!INCLUDE[navnow](includes/navnow_md.md)].|

Toto znamená, že musíte získat dvě informace z [!INCLUDE[navnow](includes/navnow_md.md)]: OData URL a klíč pro přístup k webové službě pro váš uživatelský účet.  
**Získání adresy URL**  
Pokud přidáte [!INCLUDE[navnow](includes/navnow_md.md)] k Power BI, musíte zadat adresu URL, aby mohl mít Power BI přístup k datům vaší společnosti. V okně připojení je adresa URL označována jako **OData Feed URL** a musí mít následující formát:

         https://mybusiness.projectmadeira.com:7048/MS/OData/Company('CRONUS%20US')  
V tomto příkladu je *mybusiness* název služby [!INCLUDE[navnow](includes/navnow_md.md)] a *CRONUS US* je název demonstrační společnosti s *%20* reprezentujícím mezeru v názvu.   
Chcete-li získat adresu URL, v aplikaci [!INCLUDE[navnow](includes/navnow_md.md)] vyhledejte a otevřete okno **Webové služby**. Toto okno obsahuje seznam webových služeb, které jsou aktuálně k dispozici a můžete zkopírovat odkaz z pole **OData URL** pro jednu z výchozích webových služeb OData.  
**Získání klíče pro přístup k webové službě**  
Chcete-li v okně **Připojení k [!INCLUDE[navnow](includes/navnow_md.md)]** použít data ze služby [!INCLUDE[navnow](includes/navnow_md.md)] v Power BI, musíte zadat uživatelské jméno, kterým je váš e-mailový účet a heslo. Heslo je klíč pro přístup k webové službě, který je nastaven pro váš uživatelský účet v [!INCLUDE[navnow](includes/navnow_md.md)].  
Chcete-li získat klíč pro přístup k webové službě, vyhledejte v aplikaci [!INCLUDE[navnow](includes/navnow_md.md)] okno **Uživatelé** a poté otevřete kartu pro svůj uživatelský účet. Na **webové službě Access** zkopírujte obsah pole **Klíč webové služby Access**. Pokud je pole prázdné, v pásu karet vyberte možnost **Změnit klíč webové služby Access**, vyberte pole **Klíč nikdy nevyprší** a potom klepněte na tlačítko OK. Potom můžete klíč zkopírovat.  

## <a name="getting-data-from-dynamics-nav"></a>Získání dat z [!INCLUDE[navnow](includes/navnow_md.md)]
Na řídícím panelu [!INCLUDE[navnow](includes/navnow_md.md)] se zobrazují nejtypičtější zprávy, které budete chtít použít ke sledování vaší firmy. Data jsou získána z vaší společnosti [!INCLUDE[navnow](includes/navnow_md.md)] pomocí webových služeb pro čtení reálných dat. V okně [!INCLUDE[navnow](includes/navnow_md.md)] **Webové služby** jsou seznamy webových služeb, které byly pro vás nastaveny včetně následujících, které spotřebovává balíček obsahu v Power BI:  

- ItemSalesAndProfit  
- ItemSalesByCustomer  
- powerbifinance-setup  
- SalesDashboard  
- SalesOpportunities  
- SalesOrdersBySalesPerson  
- TopCustomerOverview  

**Poznámka**: Pokud změníte název některé z těchto webových služeb, data se nebudou zobrazovat v Power BI.  
Chcete-li přidat další údaje do Power BI, musíte najít tabulky v [!INCLUDE[navnow](includes/navnow_md.md)], zobrazit je jako webové služby a přidat je do obsahu. Jedná se o pokročilý scénář a doporučujeme začít s údaji, které jsou již k dispozici v Power BI.  

## <a name="troubleshooting"></a>Odstraňování problémů
Řídicí panel Power BI se spoléhá na publikované webové služby, které jsou uvedeny výše a bude zobrazovat data od demonstrační společnosti nebo vlastní firmy, pokud importujete data z vašeho aktuálního řešení finančního nastavení. Pokud se však něco pokazí, tato část poskytuje řešení pro nejtypičtějších problémy.  

**"Ověření parametrů se nezdařilo, zkontrolujte, zda jsou všechny parametry platné“**  
Pokud se vám tato chyba zobrazí po zadání adresy URL služby [!INCLUDE[navnow](includes/navnow_md.md)], ujistěte se, že jsou splněny následující požadavky:  

- Adresa URL přesně odpovídá tomuto vzoru:

    https://mybusiness.projectmadeira.com:7048/MS/OData/Company('CRONUS%20US')  
- Odstraňte jakýkoli text za názvem společnosti v závorkách  
- Ujistěte se, že na konci adresy URL nejsou žádná lomítka.  
- Ujistěte se, že se jedná o zabezpečené připojení, jak je uvedeno na adrese URL začínající *https*.  


**"Přihlášení se nezdařilo“**  
Pokud při přihlašování k řídicímu panelu se pomocí přihlašovacích údajů [!INCLUDE[navnow](includes/navnow_md.md)] zobrazí chyba "přihlášení se nezdařilo", může to být způsobeno jedním z následujících problémů:

* Účet, který používáte, nemá oprávnění ke čtení dat [!INCLUDE[navnow](includes/navnow_md.md)] z vašeho účtu.

    Ověřte svůj uživatelský účet v aplikaci [!INCLUDE[navnow](includes/navnow_md.md)] a ujistěte se, že jste použili správný přístupový klíč webové služby jako heslo a zkuste to znovu.  
* Instance [!INCLUDE[navnow](includes/navnow_md.md)], ke které se pokoušíte připojit, nemá platný certifikát SSL. V takovém případě se zobrazí podrobnější chybová zpráva ("nelze vytvořit důvěryhodný vztah SSL").

    **Poznámka**: Samostatně podepsané certifikáty nejsou podporovány.  


**"Ups“**  
Zobrazí-li dialogové okno chybu "Ups" po zadání ověřování dialogového okna, je to nejčastěji způsobeno problémem s připojením k datům pro obsahový balíček.

* Ověřte, zda adresa URL odpovídá vzoru uvedenému dříve:

    https://mybusiness.projectmadeira.com:7048/MS/OData/Company('CRONUS%20US')  
* Obvyklou chybou je nezadání úplné adresy URL konkrétní webové služby:

    https://mybusiness.projectmadeira.com:7048/MS/OData/Company('CRONUS%20US')/powerbifinance-setup  
* Nebo jste možná zapomněli zadat název společnosti:

    https://mybusiness.projectmadeira.com:7048/MS/OData/  


## <a name="see-also"></a>Viz také
[Vítejte v [!INCLUDE[navnow](includes/navnow_md.md)]](across-get-started.md)  

