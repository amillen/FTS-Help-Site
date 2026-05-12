---
uid: items.import-items
title: Items / Import Items / Bulk Upload
---

# Import Items

Importing items allows administrators to **upload multiple items at once** into the FTS system using a spreadsheet template. This process saves time by eliminating manual item entry and ensures consistency across item IDs, suppliers, pricing, and locations.

**Also known as:** *Item Import*, *Bulk Item Upload*

---

## Overview

The Import Items feature enables you to:

- Upload large numbers of items simultaneously
- Assign Item IDs, suppliers, prices, and descriptions
- Reduce data entry errors when setting up inventory
- Update existing items using export/import workflows

A correctly completed import updates the site database once submitted with no errors.

---

## Key Requirements

Before importing, ensure the following required fields are completed in the template:

- **Item ID**
- **Supplier**
- **Description**
- **Unit Price**

Missing or incorrect information in these fields will cause import errors.

> **Important:** It is strongly recommended to use the **Supplier Item ID** to ensure accurate purchasing and prevent rework later.

---

## How to Import Items

### 1. Access the Import Page

1. Log in to your dashboard.
2. Navigate to the **Items** module.
3. Click the **cloud upload** icon to open the Import page.

---

### 2. Download the Import Template

- Click the provided link to download the **Item Import Template**
- Optionally:
  - View a sample template (delete sample data before use)
  - Download an export of current site data to make bulk changes

Save the file locally in Excel format.

---

### 3. Complete the Template

Fill in all required fields accurately.  
**If updatiing only change the data you intend to update**


### 4. Upload the Template

1. Return to the Import page.
2. Click **Choose File** and select your completed template.
3. Upload the file to the system.

---

### 5. Review and Import

- The system will scan for:
  - Missing required data
  - Duplicate Item IDs
  - Invalid Item IDs
- Use **Show Errors Only** to isolate issues

Once all errors are resolved, click **Import** to finalize the upload.

---

## Import Errors and Troubleshooting

### Common Issues

- **Duplicate Item IDs**
- **Missing required fields**
- **Invalid or incorrect Item IDs**

### Resolving Errors

- Delete problematic rows using the **X** icon
- Correct data directly in the import page
- Re-upload a corrected template if multiple errors exist

Errors must be cleared before a successful import can occur.

---

## Verification

After import confirmation:

- Return to the **Item List**
- Search using one of the imported Item IDs to verify successful upload

---

## Related Topics

- [Items](xref:items) 
- [Suppliers](xref:suppliers)
- [Item Unit Info](xref:items.unit-info)
