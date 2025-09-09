---
uid: cabinets.create-location
title: Creating/Adding/Setting Up a Location
---

# Creating a New Location (Adding a Location)

> See [Locations Overview](xref:cabinets.locations) for more about what locations are and the different ways to create them.

**Also known as:** *Create Location*, *Add Location*, *Set Up Location*, *Bin*

To create a new location inside a cabinet, follow these steps:

1. Navigate to the **Cabinets** module from the [Dashboard](xref:dashboard).  
2. Click on the cabinet where you want to create a location.  
3. Click on **Create New Location**.  
4. Fill in the location details (see below).  
5. Click **Save** to add the location.  

> **Tip:** Locations are defined in a grid pattern inside drawers — with rows and columns, similar to Excel.

---

## Location Fields
*(same as before — Drawer, Column, Row, Item, Min, Max, Capacity, Location Expansion, Restock)*

---

## Moving an Item to a New Location

When an item is assigned to a location, a **Move** link will appear. This lets you move the item to a different location.

### What Moving Includes
When you move an item to a new location (or swap it with another item), all data tied to the original location moves with it. This includes:  
- Open purchase orders  
- Transaction history  
- Quantity on hand  
- Unreturned inventory  
- Alerts  
- Min/Max values  
- Capacity setting  

In short: moving an item is a **full relocation** of the item and its associated data.

---

### How to Move an Item
1. Click the **Move** link next to the item.  
2. A modal window will open.  
3. Choose the destination:  
   - **Station**  
   - **Cabinet**  
   - **Drawer**  
   - **Column**  
   - **Row**  
4. Select the new location:  
   - You may choose an empty location, or  
   - You may choose a location that already has an item.  

#### If the Destination Location is Empty
- The item (and all associated data) will be moved directly to that location.  

#### If the Destination Location Already Has an Item
- A confirmation dialog will appear asking if you want to **swap locations**.  
- Click **Yes**: The two items (and all their associated data) will switch places.  
- Click **No**: The move process is canceled.  

---

## FAQ

### What is a location?
A location is a *bin* inside a cabinet. Each location is defined by a drawer, column, and row.

### Do I have to assign an item when creating a location?
No. Items can be assigned later if needed.

### How do Min and Max affect purchasing?
- **Min**: When stock falls to or below this amount, the item appears on the next PO.  
- **Max**: The PO will order enough to bring the quantity back up to this amount.

### What’s the difference between Capacity and Max?
- **Capacity**: Theoretical number of items that could fit in the location.  
- **Max**: How much the system will order up to.  
Capacity does not restrict receiving or purchasing.

### How do I move an item to a new location?
Click the **Move** link, choose the destination, and confirm. If the new location has an item, you can choose to swap them or cancel.

### What happens when I move an item?
All of the item’s data moves with it — including open POs, transactions, on-hand quantity, unreturned inventory, alerts, min/max, and capacity settings.

---

## Related Topics
- [Locations Overview](xref:cabinets.locations)  
- [Creating a New Cabinet](xref:cabinets.add)  
- [Cabinet Builder](xref:cabinets.builder)  
- [Location Import](xref:cabinets.location-import)  
- [Items](xref:items)
