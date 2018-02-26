---
    title: How to Delete Invoiced Purchase Return Orders | Microsoft Docs
    description: Return orders are usually deleted after they are invoiced. When you post an invoice, it is transferred to the **Posted Purchase Credit Memo** window. If you selected the **Return Shipment on Credit Memo** check box in the **Purchases & Payable Setup** window, then the invoice is transferred to the **Posted Return Shipment** window.
    services: project-madeira
    documentationcenter: ''
    author: SorenGP

    ms.service: dynamics365-financials
    ms.topic: article
    ms.devlang: na
    ms.tgt_pltfrm: na
    ms.workload: na
    ms.search.keywords:
    ms.date: 07/01/2017
    ms.author: sgroespe

---
# Delete Invoiced Purchase Return Orders
Return orders are usually deleted after they are invoiced. When you post an invoice, it is transferred to the **Posted Purchase Credit Memo** window. If you selected the **Return Shipment on Credit Memo** check box in the **Purchases & Payable Setup** window, then the invoice is transferred to the **Posted Return Shipment** window.  
  
 In certain situations, you may need to delete invoiced purchase return orders that were not deleted or you may need to reduce the number of posted invoices. You can delete the documents using the **Delete Invd Purch. Ret. Orders** batch job.  
  
### To delete invoiced purchase return orders  
  
1.  Choose the ![Search for Page or Report](media/ui-search/search_small.png "Search for Page or Report icon") icon, enter **Delete Invoiced Purchase Return Orders**, and then choose the related link.  
  
2.  Set filters in the **No.**, **Buy-from Vendor No.**, and **Pay-to Vendor No.** fields to select the orders to be deleted.  
  
3.  Choose the **OK** button.  
  
 Before deleting, the batch job checks if the purchase return orders are fully shipped and invoiced  
  
## See Also  
 [Combine Return Shipments](../how-to-combine-return-shipments.md)   
 [Delete Invoiced Blanket Purchase Orders](../how-to-delete-invoiced-blanket-purchase-orders.md)   
 [Delete Invoiced Purchase Orders](../how-to-delete-invoiced-purchase-orders.md)