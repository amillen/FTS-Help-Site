---
uid: items.unit-info
title: Item Units/Unit Info/Units of Measure
---

# Unit Info (Units of Measure)

**Also known as:** *Item Units*, *Unit Info*, *Units of Measure*

The **Unit Info** tab defines how an item is measured, issued, and purchased in FTS. It ensures consistent quantities across purchase orders, stocking, and employee checkouts.

---

## Key Unit Fields

### Base Unit
The smallest measurable unit of the item.  
- All other unit conversions are calculated from the base unit.  
- Example: **Each** drill bit, **Box** of 10, **Case** of 100.  
- Reports and purchasing always calculate back to the base unit.

### Default Issue Unit
The unit most commonly issued to employees at the kiosk.  
- Example: If base unit is **Each**, you may set **Pack of 5** as the default issue.  
- At checkout, this unit will be pre-selected.  

### Default Purchase Unit
The unit most commonly used when ordering from a supplier.  
- Example: A supplier may only sell in **Boxes of 10**.  
- When creating purchase orders, this unit will be the default.

### Allow Issue
Determines which units are allowed to be issued at the kiosk.  
- You may allow multiple units (e.g., Each, Pack, Box).  
- Employees can choose any of the allowed units when checking out the item.

---

## How Units Work Together

- **Base Unit** = the foundation (1 unit).  
- **Default Issue** = what employees most often take.  
- **Default Purchase** = how suppliers deliver it.  
- **Conversions** ensure that every transaction converts back to the base unit for accurate tracking.  

> **Example:**  
> - Base Unit = **Each**  
> - Default Issue = **Pack of 5**  
> - Default Purchase = **Box of 20**  
>  
> If an employee checks out 1 pack, the system deducts **5 Each** from stock.  
> If a purchase order is placed for 1 box, the system adds **20 Each** into stock.

---

## FAQ

### What’s the difference between Base Unit and Default Issue Unit?
- **Base Unit**: The smallest measurement the system uses for calculations.  
- **Default Issue Unit**: The unit pre-selected for employees when they check out the item.

### Can I have multiple purchase units?
Yes. You can define multiple purchase units, but one must be set as the **default**.

### Do all items need a Barcode tied to their units?
No. A barcode is optional, but recommended if items are scanned at checkout.

### What happens if I change the Base Unit later?
Changing the Base Unit will affect all transactions, reporting, and conversions. Avoid changing it once items have history.

---

## Related Topics
- [Items Overview](xref:items)  
- [Creating a New Item](xref:items.add)  
- [Additional Item Tabs](xref:items.additional-tabs)  
- [Suppliers](xref:suppliers)  
- [Reporting Fields](xref:reporting-fields)  
