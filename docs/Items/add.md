---
uid: items.add
title: Adding/Creating/Setting Up an Item
---

# Creating a New Item (Adding an Item)

**Also known as:** *Add Item*, *New Item*, *Set Up Item*

To create a new item:

1. Navigate to the **Items** module from the [Dashboard](xref:dashboard).  
2. Click on **Add New Item** (or the **plus (+)** button).  
3. Fill in the item details (see below).  
4. Click **Save** to create the item.  

---

## Item Details

### Item ID
A unique identifier for the item. Must be unique across all items.  

### Supplier
The supplier that will receive purchase orders for this item.  

### Reference Item ID
Another identifier for the item (often an internal part number).  

### Barcode
The item’s barcode data, used when searching with a barcode scanner.  

### Commodity Code
Code used to group and report spend (often a GL code).  
> **Tip:** Commodity Codes are used for spend reporting. For tracking job/part/cost center data, use [Reporting Fields](xref:reporting-fields).

### Minimum Order Quantity
The minimum number of units that must be ordered before the item appears on a purchase order.  

### Default Purchase Unit Size
Defines multiples in which the item is ordered.  

### Type
Determines how the item behaves in inventory:  
- **Consumable**: Not expected to be returned.  
- **Semi-Consumable**: May be reused or scrapped. Enables extra fields: *Usage Tracking Enabled*, *Auto Scrap*, *Return As Other Item*.  
- **Durable**: Must be returned to remain in inventory.  
- **Used**: Marks the item as previously used.  
- **Assembly Kit Enabled**: Turns the item into a kit (sum of other items). Opens the [Assembly](xref:items.assembly) tab.  

---

## Saving the Item

Once the core details are filled in:  
- Click **Save** to create the item.  
- Additional tabs will appear (see [Unit Info](xref:items.unit-info), [Additional Item Tabs](xref:items.additional-tabs), and [Assembly](xref:items.assembly)).  

---

## FAQ

### Can an item have more than one ID?
Each item has one **Item ID**, but it may also have a **Reference Item ID** and a **Barcode**.

### What’s the difference between a Commodity Code and a Reporting Field?
- **Commodity Code** groups spend for reporting by item type or GL code.  
- [Reporting Fields](xref:reporting-fields) capture additional data at checkout (job, part, cost center).  

### Why don’t I see the Assembly tab?
The **Assembly Kit Enabled** box must be checked for the Assembly tab to appear.

### Do I need to set a Minimum Order Quantity?
Not always. Use it only if suppliers require minimum purchases.  

---

## Related Topics
- [Items Overview](xref:items)  
- [Unit Info](xref:items.unit-info)  
- [Assembly Kits](xref:items.assembly)  
- [Additional Item Tabs](xref:items.additional-tabs)  
- [Suppliers](xref:suppliers)  
- [Categories](xref:categories)  
- [Reporting Fields](xref:reporting-fields)  
