---
uid: cabinets.location-import
title: Mass Importing/Updating Locations in a Cabinet
---

# Mass Importing and Updating Locations (Location Import Tool)

> See [Locations Overview](xref:cabinets.locations) for more about what locations are and the different ways to create them.

**Also known as:** *Location Import*, *Bulk Location Upload*, *Mass Update Locations*

The **Location Import Tool** lets you add or update many cabinet locations at once using an Excel template. This saves time when setting up a new cabinet, assigning items to locations, or updating details like Min/Max, Capacity, or Restock status.

> **Tip:** Use Location Import when you have many locations to load. If you only need one location, use [Creating a New Location](xref:cabinets.create-location). For building drawers, rows, and columns, use [Cabinet Builder](xref:cabinets.builder).

---

## Before You Begin

- **Item IDs must already exist** in the system before you can import them into a location.  
- Each location must be **unique** — two items cannot share the same drawer/row/column unless Location Expansion is enabled.  
- Use the Western Tool & Supply Item ID whenever possible. This makes purchasing smoother and avoids having to redo imports later.  

---

## Steps to Import Locations

1. Navigate to the **Cabinets** module from the [Dashboard](xref:dashboard).  
2. Select the cabinet you want to update.  
3. Click the **cloud upload button** in the top right corner.  
4. Download the **Location Import Template** (Excel).  
   - You can download a blank template or a sample template (delete sample rows before using).  
5. Fill out the template with your location details and item assignments:  
   - Drawer, Column, Row  
   - Item ID (must already exist in Items)  
   - Min, Max, Capacity, Restock, Expansion (as needed)  
6. Save the file to your computer with a clear name (e.g., `Cabinet1_LocationImport.xlsx`).  
7. Return to the **Import Page** and click **Choose File** to upload your template.  
8. Review the preview for errors (see below).  
9. Click **Import** to create the new locations.  

---

## Updating Existing Locations

If locations already exist and you want to change them:  

1. On the Import Page, toggle from **Create** (default) to **Update**.  
2. Upload your updated template file.  
3. Review the preview to confirm changes.  
4. Click **Update** to apply changes.  
5. Verify that your updates appear in the cabinet.  

> **Tip:** For large changes, first run an **Export** from the Import Page. This gives you a pre-filled template with your current cabinet data. Update only what you need, then re-import.

---

## Common Errors and Fixes

### Item ID Not Found
- Cause: The item doesn’t exist in the system or the ID is incorrect.  
- Fix: Add the item to [Items](xref:items) or correct the ID in your template.  

### Number Formatting
- Cause: Excel may drop leading zeros (e.g., `01` becomes `1`).  
- Fix: Change the cell format to **Text** before saving.  

### Duplicate Locations
- Cause: Two rows in the template define the same drawer/row/column.  
- Fix: Remove duplicates and re-import.  

### Import vs Update
- Cause: Importing a location that already exists.  
- Fix: Switch toggle to **Update** when modifying existing locations.  

---

## FAQ

### When should I use Location Import vs Cabinet Builder?
- **Location Import**: Best for assigning items, updating Min/Max, or editing many locations.  
- **Cabinet Builder**: Best for creating a grid of drawers, rows, and columns during initial setup.  

### Can I assign items to locations during import?
Yes. Add the Item ID to the row for the location. The item must already exist in [Items](xref:items).  

### What happens if my file has errors?
The import preview will highlight issues. Fix the file (e.g., wrong Item ID, duplicates, bad formatting) and upload again. Nothing is saved until you click **Import** or **Update**.  

### Can I undo an import?
No direct undo. To fix mistakes, correct the template and re-import with the **Update** option.

---

## Related Topics
- [Cabinets (Overview)](xref:cabinets)
- [Creating a New Cabinet](xref:cabinets.add)
- [Creating a New Location](xref:cabinets.create-location)
- [Cabinet Builder](xref:cabinets.builder)
- [Items](xref:items)
