---
    title: How to Set Up a Document Exchange Service
    description: You use an external service provider to exchange electronic documents with your trading partners by using "Doc Exch. Service Setup".
    author: SorenGP

    ms.service: dynamics365-business-central
    ms.topic: conceptual
    ms.devlang: na
    ms.tgt_pltfrm: na
    ms.workload: na
    ms.search.keywords:
    ms.date: 06/11/2021
    ms.author: edupont

---
# Set Up a Document Exchange Service
You use an external service provider to exchange electronic documents with your trading partners. For more information, see [Exchanging Data Electronically](across-data-exchange.md).  

## To set up a document exchange service  
1. Choose the ![Lightbulb that opens the Tell Me feature](media/ui-search/search_small.png "Tell me what you want to do") icon, enter **Doc. Exch. Service Setup**, and then choose the related link.  
2. Fill the fields as described in the following table.  

    |Field|Description|  
    |---------------------------------|---------------------------------------|  
    |**User Agent**|Enter any text that can be used to identify your company in document exchange processes.|  
    |**Doc. Exch. Tenant ID**|Enter the tenant in the document exchange service that represents your company. This is provided by the document exchange service provider.|  
    |**Enabled**|Specify if the service is enabled. **Note:**  As soon as you enable the service, at least two job queue entries are created to process the traffic of electronic documents in and out of [!INCLUDE[prod_short](includes/prod_short.md)]. When you disable the service, the job queue entries are deleted.|  
    |**Signup URL**|Specify the web page where you sign up for the document exchange service.|  
    |**Service URL**|Specify the address of the document exchange service, which will be called when you send and receive electronic documents.|  
    |**Login URL**|Specify the logon page for the document exchange service, which is where you enter your company’s user name and password to log on to the service.|  
    |**Consumer Key**|Enter the 3-legged OAuth key for the consumer key. This is provided by the document exchange service provider.|  
    |**Consumer Secret**|Enter the secret that protects the consumer key. This is provided by the document exchange service provider.|  
    |**Token**|Enter the 3-legged OAuth key for the token. This is provided by the document exchange service provider.|  
    |**Token Secret**|Enter the secret that protects the token. This is provided by the document exchange service provider.|  

    > [!NOTE]  
    > You login data is automatically encrypted.

## See Also  
[Setting Up Data Exchange](across-set-up-data-exchange.md)  
[Exchanging Data Electronically](across-data-exchange.md)


[!INCLUDE[footer-include](includes/footer-banner.md)]