---
uid: items
title: Items/Inventory Items
---

# Items

The **Items** module is where you manage every item in FTS. Items can represent anything from cutting tools to maintenance supplies, and they are the backbone of the system.  

**Also known as:** *Inventory Items*, *Parts*, *Tools*

---

## What Items Are

- Each item has a unique **Item ID** that identifies it in the system.  
- Items can be linked to [Suppliers](xref:suppliers), [Categories](xref:categories), [Locations](xref:cabinets.locations), and [Reporting Fields](xref:reporting-fields). 
- Items can be issued, returned, adjusted, or scrapped depending on their type.  
- An item may have additional settings that appear based on its type (e.g., Semi-Consumables).  

---

## Item Types

There are three main item types in FTS:

- **Consumable**: Items that are not expected to be returned once issued.  
  - Example: inserts, paper, cleaning supplies.  
  - Can be **Adjusted** (returned unused into stock).  

- **Semi-Consumable**: Items that may be reused but are eventually scrapped.  
  - Extra options:  
    - **Usage Tracking Enabled**: Prompts for usage details when the item is returned. Data appears in the [Transaction Report](xref:transactions).  
    - **Auto Scrap**: After a set number of days (set at the [Station](xref:stations) level), the item is automatically scrapped if not returned.  
    - **Return As Other Item**: Allows the item to be returned as a different item (commonly used for returning “used” versions).  
  - Example: drill bits, end mills, safety gear with limited life.  
  - Can be **Returned** (back into stock).  

- **Durable**: Items that must be returned to remain in inventory.  
  - Extra option:  
    - **Usage Tracking Enabled**: Prompts for usage details when returned. Data appears in the [Transaction Report](xref:transactions).  
  - Example: gages, power tools, staplers.  
  - Must be **Returned** (cannot be adjusted like consumables).  

---

## Item Flags

In addition to the three item types, items can be marked with special flags:  

- **Used**: Marks the item as used. This is for reference only — FTS does not treat it differently in inventory.  
- **Assembly Kit Enabled**: Makes the item an [Assembly Kit](xref:items.assembly). The item itself becomes a virtual container for its component items.  

---

## Item Type Comparison

| Feature / Action                | Consumable | Semi-Consumable | Durable |
|---------------------------------|------------|-----------------|---------|
| **Can be Adjusted** (put back unused) | ✅ | ❌ | ❌ |
| **Can be Returned** (after use) | ❌ | ✅ | ✅ |
| **Usage Tracking Enabled**      | ❌ | ✅ | ✅ |
| **Auto Scrap**                  | ❌ | ✅ | ❌ |
| **Return As Other Item**        | ❌ | ✅ | ❌ |

---

> **Quick Tip:**  
> - Use **Consumable** for items that are gone once issued.  
> - Use **Semi-Consumable** when items may come back, but eventually expire or get scrapped.  
> - Use **Durable** for items that must always be returned and reused.  


---

## Item Flags

In addition to the three item types, items can be marked with special flags:  

- **Used**: Marks the item as used. This is for reference only — FTS does not treat it differently in inventory.  
- **Assembly Kit Enabled**: Makes the item an [Assembly Kit](xref:items.assembly). The item itself becomes a virtual container for its component items.  


---

## Key Item Fields

- **Item ID**: Unique identifier for the item.  
- **Supplier**: [Supplier](xref:suppliers) used when generating purchase orders.  
- **Reference Item ID**: Secondary identifier (often an internal part number).  
- **Barcode**: Barcode data, used for scanning and searching.  
- **Commodity Code**: Code used to track spend by group (often tied to GL codes).  
- **Minimum Order Quantity**: Minimum base-unit quantity required for purchase.  
- **Default Purchase Unit Size**: Order multiples for the item.  

> **Note:** Commodity Codes are used for spend reporting. If you need to capture job/part/cost center data at checkout, use [Reporting Fields](xref:reporting-fields) instead.

---

## Item Tabs

When viewing or editing an item, you will see several tabs:  
- [Unit Info](xref:items.unit-info)  
- [Locations](xref:cabinets.locations)  
- [Categories](xref:categories)  
- [Open POs](xref:purchase-orders)  
- [History](xref:transactions)  
- [Notes](xref:items.additional-tabs)  
- [Access Control](xref:access-controls)  
- [Assembly](xref:items.assembly) (if enabled)  
- [Audit Logs](xref:items.additional-tabs)  

> See [Additional Item Tabs](xref:items.additional-tabs) for details.

---

## FAQ

### What’s the difference between Adjust and Return?
- **Adjust**: Used for **Consumable items**. If a consumable is issued but not actually used, it can be adjusted back into stock.  
- **Return**: Used for **Semi-Consumable and Durable items**. These items are expected to come back after use, so they are returned into stock rather than adjusted.

### Why can’t Consumables be Returned?
Consumables are treated as “used up” once issued. If you need to put one back, it must be done through an **Adjust**, not a Return.

### Why can’t Durables be Adjusted?
Durables must always be returned to stay in inventory. Adjust is reserved for unused consumables only.

### Which item types can use Auto Scrap?
Only **Semi-Consumables**. After a set number of days (configured at the [Station](xref:stations) level), unreturned Semi-Consumables will be automatically scrapped.

### Which item types can use Usage Tracking?
Both **Semi-Consumable** and **Durable** items can have **Usage Tracking Enabled**, so extra details are logged when they are returned.

---

## Related Topics
- [Creating a New Item](xref:items.add)  
- [Unit Info](xref:items.unit-info)  
- [Assembly Kits](xref:items.assembly)  
- [Additional Item Tabs](xref:items.additional-tabs)  
- [Suppliers](xref:suppliers)  
- [Categories](xref:categories)  
- [Reporting Fields](xref:reporting-fields)
- [Reporting Fields](xref:reporting-fields)  
- [Transactions](xref:transactions)  