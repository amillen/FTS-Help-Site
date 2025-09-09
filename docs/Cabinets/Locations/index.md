---
uid: cabinets.locations
title: Locations/Bins
---

# Locations

A **Location** (sometimes called a *bin*) is the smallest unit of storage inside a cabinet. Every item in FTS must be assigned to a location so its quantity, min/max levels, and activity can be tracked.  

Locations are defined in a **grid pattern** inside each cabinet — made up of drawers, columns, and rows (similar to Excel).  

**Also known as:** *Bins*, *Cabinet Locations*, *Storage Locations*

---

## Why Locations Matter

- **Inventory Tracking**: Each location holds the current quantity of its assigned item.  
- **Purchasing Control**: Min/Max values on a location determine when items are re-ordered.  
- **Flexibility**: Locations can be created manually, in bulk with Cabinet Builder, or with a spreadsheet import.  
- **Accuracy**: Keeping item assignments and counts tied to locations ensures clean reporting and auditing.  
- **Mobility**: Items can be moved between locations when needed, and all of their data (open POs, transactions, on-hand quantities, alerts, etc.) moves with them.  

---

## Methods to Create Locations

There are three ways to create locations inside a cabinet. Each method is best for a different situation.  

| Method | Best For | How It Works | Example Use Case |
|--------|----------|--------------|------------------|
| [Create a New Location](xref:cabinets.create-location) | One-off, single locations | Manually add a single location by selecting drawer, column, row, and optional item details. | You need to add a new location in drawer 3, row 5, column B. |
| [Cabinet Builder](xref:cabinets.builder) | Building many empty locations quickly | Select drawers, rows, and columns to auto-generate multiple locations at once. | You’re setting up a new cabinet with 10 drawers, each with 6 columns and 5 rows. |
| [Location Import](xref:cabinets.location-import) | Assigning items or updating many locations | Fill out an Excel template with locations, items, Min/Max, Capacity, etc., then upload it. | You want to update 200 locations to assign items and adjust Min/Max values. |

---

## Quick Recommendations

- Use **Create a New Location** for *one location at a time*.  
- Use **Cabinet Builder** for *bulk creation of empty grids*.  
- Use **Location Import** for *bulk updates or assigning items to many locations*.  

---

## FAQ

### What is a location?
A location (or bin) is a storage spot inside a cabinet, defined by drawer, column, and row.

### Do items have to be assigned to a location?
Yes. Every item must be tied to a location so the system can track quantities and purchasing rules.

### Can I move items between locations?
Yes. Items can be moved to a new location using the **Move** link. When an item is moved (or swapped), all of its associated data — including open purchase orders, transactions, on-hand quantities, unreturned inventory, alerts, and min/max settings — moves with it.

### Which method should I use to create locations?
- **Few locations** → Create a New Location  
- **Lots of locations** (rows/columns) → Cabinet Builder  
- **Lots of items or updates** → Location Import  

### Can a location hold more than one item?
Yes, if **Location Expansion** is enabled.

---

## Related Topics
- [Cabinets (Overview)](xref:cabinets)  
- [Creating a New Cabinet](xref:cabinets.add)  
- [Creating a New Location](xref:cabinets.create-location)  
- [Cabinet Builder](xref:cabinets.builder)  
- [Location Import](xref:cabinets.location-import)  
- [Items](xref:items)  
