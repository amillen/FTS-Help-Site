---
uid: items.assembly
title: Assembly Kits/Item Assemblies
---

# Assembly Kits

**Also known as:** *Item Assemblies*, *Kit Items*, *Assembly Build*

The **Assembly** tab allows you to create items that represent a sum of other items. When enabled, an “Assembly Kit” becomes its own item but is tied to the quantities of its component parts.

---

## Enabling an Assembly Kit

1. Navigate to the **Items** module from the [Dashboard](xref:dashboard).  
2. Create or edit the item you want to use as a kit.  
3. Check **Assembly Kit Enabled**.  
   - The **Assembly** tab will appear.  
4. On the Assembly tab, add the component items and their required quantities.  
5. Save changes.

---

## How Assemblies Work

- The Assembly Kit is issued like a normal item.  
- When issued, the system automatically deducts quantities of the **component items** from inventory.  
- The kit itself does not hold stock — inventory is tracked at the component level.  

> **Example:**  
> Assembly Kit = *Starter Pack*  
> - 1 × Safety Glasses  
> - 2 × Gloves (Pair)  
> - 1 × Dust Mask  
>  
> Issuing 1 Starter Pack deducts these items from inventory.

---

## Editing or Removing Assemblies

- To **edit quantities**, change the number on the Assembly tab.  
- To **remove an item** from the assembly, delete it from the list.  
- To **disable the assembly kit**, remove all items from the Assembly tab and uncheck **Assembly Kit Enabled**.

---

## Assembly Kits at the Kiosk

- Employees see the Assembly Kit as one item.  
- When they check it out, the linked items are deducted automatically.  
- If any component is out of stock, the system will not issue the kit.

---

## FAQ

### What is the difference between an Assembly Kit and a regular item?
An Assembly Kit is a “virtual item” that consumes multiple other items when issued.

### Can an item be both a normal stock item and part of an assembly?
Yes. Items can be issued individually and also be part of one or more assembly kits.

### What happens if one of the components is out of stock?
The assembly cannot be issued until all required items are available.

### Can assemblies be nested?
No. You cannot include an assembly kit inside another assembly kit.

---

## Related Topics
- [Items Overview](xref:items)  
- [Creating a New Item](xref:items.add)  
- [Unit Info](xref:items.unit-info)  
- [Additional Item Tabs](xref:items.additional-tabs)  
- [Suppliers](xref:suppliers)  
