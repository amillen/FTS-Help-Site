---
uid: reporting-fields.import
title: Importing/Uploading/Updating Reporting Field Data
---

# Importing Data into a Reporting Field

**Also known as:** *Upload Reporting Field Data*, *Import Dropdown Values*

The **Import Tool** lets you load many dropdown options into a reporting field at once using an Excel template.

> **Tip:** Importing is the fastest way to populate large dropdown lists (e.g., job numbers, part numbers).

---

## Steps to Import

1. Navigate to the **Reporting Fields** module from the [Dashboard](xref:dashboard).  
2. Select the reporting field you want to import data into.  
3. Click the **cloud upload button**.  
4. Download the **Import Template** (Excel).  
   - Blank template for new data.  
   - Sample template for reference (delete sample data before using).  
5. Fill out the template with your data list.  
6. Save the file and upload it using **Choose File → Open**.  
7. Select whether to **Append** (add new data to the list) or **Replace** (clear and replace all data).  
8. Click **Import** to load the data.  

---

## Error Handling

- **Duplicates**: If duplicate values exist, import will fail until fixed. Remove duplicates in the file or cancel them in the upload list.  
- **Replace Warning**: If you choose Replace, you must confirm before existing data is cleared.  
- **Import Failed**: If issues remain, you’ll see a failure screen. Repair the file and re-upload.  

---

## At Checkout

- If the field has a dropdown list, users will see only those options.  
- If **Allow User Input** is enabled, users can either pick from the list or type a new value.  
- If disabled, they must select from the list only.  

---

## FAQ

### Can I import into multiple reporting fields at once?
No. Imports are done one field at a time.

### What’s the difference between Append and Replace?
- **Append** keeps existing values and adds new ones.  
- **Replace** deletes all current values and loads only the new list.  

### What happens if I forget to delete the sample data?
It will be imported into your list unless removed before upload.

---

## Related Topics
- [Reporting Fields Overview](xref:reporting-fields)  
- [Creating a New Reporting Field](xref:reporting-fields.add)  
- [Items](xref:items)
