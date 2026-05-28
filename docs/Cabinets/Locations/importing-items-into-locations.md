---
uid: cabinet.importing-items-into-cabinets
title: Cabinets / Importing Items & Locations
---

# Importing Cabinets

Importing cabinets allows administrators to **upload multiple item IDs and assign them to cabinet bin locations in bulk**, saving significant setup time. The import process ensures accurate locations, inventory rules, and item configuration within the FTS system.

**Also known as:** *Cabinet Imports*, *Location Imports*, *Bulk Item Uploads*

---

## Before You Begin (Important)

- **Item IDs must already exist in the database** before importing cabinet locations.
- Each item must be assigned to a **unique cabinet/bin location**.

---

## How to Import Cabinet Locations

### 1. Navigate to the Import Tool

1. From the **Dashboard**, click the **Cabinets** module.
2. Click the **cloud upload icon** in the upper-right corner to access the import page.

---

### 2. Download the Import Template

1. On the **Location Import** page, click the template download link.
2. Choose either:
   - A **blank template**, or
   - A **sample template** (delete all sample data before uploading).

---

### 3. Build Your Import Template

- Enter **all required fields** for each item and location.
- Ensure:
  - Correct **Item IDs**
  - Proper **cabinet, drawer, row, and column numbering**
  - Leading zeros are included where required (e.g., `01` instead of `1`).
- Save the completed template to your computer.

---

### 4. Upload the Template

1. Return to the **Cabinets** module.
2. Click the **cloud upload icon**.
3. Select **Choose File**, locate your saved template, and upload it.

---

### 5. Verify the Import

- The system validates your data before importing.
- A **clean import** will show:
  - No error messages
  - No highlighted fields

If errors appear:
- Review the highlighted fields
- Correct the template or inline cloud data
- Re-upload after fixing issues

---


### Import vs. Update Confusion
- **Import** = creating new locations (default)
- **Update** = modifying existing locations  
Switch to **Update** if locations already exist.

---

## Updating Existing Cabinet Data

1. Toggle the import mode from **Create** to **Update**.
2. Modify only the fields that require changes.
3. Click **Update** to apply corrections.
4. Verify the updates were saved successfully.


---

## Related Topics

- [Items](xref:items)
- [Cabinets](xref:cabinets.locations)
- [Stations](xref:stations)