---
title: "Návod: Registrace Dynamics NAV na portálu pro správu Azure"
author: edupont04
manager: edupont
ms.author: edupont
ms.custom: na
ms.date: 11/15/2016
ms.reviewer: na
ms.suite: na
ms.tgt_pltfrm: na
ms.topic: article
ms.prod: dynamics-nav-2017
ms.translationtype: HT
ms.sourcegitcommit: 6b60b1344a1e18ad91863046110df880f75f7c04
ms.openlocfilehash: d41b96ab5807402a342991d5c5bc2d672db09e2f
ms.contentlocale: cs-cz
ms.lasthandoff: 07/19/2017

---
# <a name="how-to-register-dynamics-nav-in-the-azure-management-portal"></a>Návod: Registrace Dynamics NAV na portálu pro správu Azure
Pokud chcete používat služby založené na programu Microsoft Azure, musíte registrovat svůj Dynamics NAV na portálu pro správu Azure. Například rozšíření [Prognóza prodeje a zásob](ui-extensions-sales-forecast.md) vyžaduje zadání klíče API a URI API a další služby vyžadují obdobné informace. Takže kde najdete tyto informace?

Pro registraci Dynamics NAV v portálu pro správu můžete použít průvodce **Nastavení portálu pro správu Azure** a extrahovat informace, které potřebujete k používání služeb, jako například prodloužení Prognózy prodeje a zásob, Power BI, Office 365 atd. Na portálu pro správu Azure se stačí registrovat pouze jednou, nicméně musíte být v Dynamics NAV buď správcem nebo superuživatelem.

Bod registrace znamená, že služba Dynamics NAV a služba, kterou chcete připojit, musí o sobě znát podrobnosti Azure Active Directory (Azure AD).

## <a name="to-register-dynamics-nav-in-the-azure-management-portal"></a>Registrace Dynamics NAV v portálu pro správu Azure
1. Přihlaste se k portálu pro správu Azure [https://portal.azure.com](https://portal.azure.com).
    Pokud nejste obeznámeni s portálem pro správu Azure, najdete pokyny v  [Knihovně dokumentace Azure](https://azure.microsoft.com/en-us/documentation/articles).
2. V levém navigačním podokně vyberte možnost **Více služeb**, a poté zvolte **Registrace aplikací**.
3. V horním menu vyberte možnost  **Přidat**, a poté v podokně **Vytvořit** vyplňte pole s následujícími informacemi:
    - **Název**: Zadejte název pro Vaše řešení Dynamics NAV, jako například *Dynamics NAV*.
    - **Typ aplikace**: Vyberte **Webovou aplikaci* rozhraní / API**.
    - **Přidat URL**: Zadejte adresu URL pro vašeho webového klienta Dynamics NAV, například *https://MyServer:8080/DynamicsNAV/WebClient/OAuthLanding.htm*.
        Soubor OAuthLanding.htm je soubor, který pomáhá spravovat výměnu dat mezi službou Dynamics NAV a dalšími službami prostřednictvím služby Azure AD.
4. Zvolte tlačítko **Vytvořit**.
    To přidává Váš Dynamics NAV do **Podokna registrací aplikací**, takže k němu nyní můžete přidat nastavení.
5. V **Seznamu registrací aplikace**, vyberte Vaši novou aplikaci. Pokud se tím neotevře podokno **Nastavení**, měla by se zobrazit akce k otevření **Nastavení**.
6. V podokně **Nastavení**, v sekci **Přístup API**, vyberte **Klíče**.
7. V podokně **Klíče** zadejte popis a pokud chcete, aby klíč vypršel, pak vyberte možnost **Uložit**.
8. Zkopírujte vygenerovaný klíč do dočasného umístění - budete jej potřebovat pro další postup.  
9. V sekci **Přístup API** zvolte **Požadované oprávnění**.
    - Přidejte delegovaná oprávnění k zobrazení všech sestav služby Power BI
    - Přidejte delegovaná oprávnění k Přihlášení a čtení uživatelského profilu v rámci služby Windows Azure Active Directory
    - Opakujte pro další služby, kterým chcete povolit přístup do vašeho Dynamics NAV. 
10. Zavřete podokno **Nastavení** a potom z podokna **Základy** zkopírujte hodnotu **ID aplikace** do dočasného umístění.

Nyní jste zaregistrovali Váš Dynamics NAV na portálu pro správu Azure, dali jste přístup příslušným službám a získali jste informace, které potřebujete v Dynamics NAV.  

## <a name="to-add-the-information-to-dynamics-nav"></a>Přidání informací do Dynamics NAV
1. V pravém horním rohu zvolte ikonu **Hledat stránku nebo sestavu**, zadejte **Nastavení Azure AD** a zvolte související odkaz.
2. V průvodci zvolte **Další**.
3. Do pole **ID klienta** zadejte obsah, který jste předtím zkopírovali z pole **ID aplikace**.
4. Do pole **Tajný klíč**, zadejte obsah, který jste předtím  zkopírovali z pole **Klíče**. 
5. Vyberte možnost **Další**.  Pokud se neobjeví chybová zpráva, jste hotoví.

Váš Dynamics NAV je registrován a připraven k připojení ke službám, jako je například Cortana Intelligence a Power BI.

## <a name="see-also"></a>Viz také
[Prodej a prognóza zásob](ui-extensions-sales-forecast.md)  
[Nastavení Vašeho Dynamics NAV](setup.md)  

