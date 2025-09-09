---
uid: reporting-fields
title: Reporting Fields/Custom Reporting Fields
---

# Reporting Fields

Reporting fields are the backbone for tracking usable data in FTS reports. They are used to associate items with additional information (such as part numbers, job numbers, or cost codes) so that the right data is captured at checkout.  

**Also known as:** *Custom Reporting Fields*, *User-Defined Fields*

---

## What Reporting Fields Are (and Are Not)

- Used to track data that matters for reporting and analytics.  
- Can be made **required** at checkout to ensure users enter data.  
- Can be configured as **free entry** (user input) or **dropdown selection** (predefined list).  
- **Items can be associated with multiple reporting fields**.  
- **Employees can be assigned default values** for reporting fields so they don’t have to re-enter the same data each time. This is commonly used for departments or cost centers. See [Employee Tabs](xref:employees.additional-tabs).  
- **Not used** for search or browsing: Do not confuse Reporting Fields with [Categories](xref:categories).  
  - Categories help users **find and group items**, but they are **not included in reporting**.  
  - Reporting Fields capture metadata at checkout that is used in reports.  


---

## Why Use Reporting Fields

- **Job/Part Tracking**: Track which job, part, or process consumed an item.  
- **Cost Allocation**: Assign usage to specific projects or departments.  
- **Analytics**: Build custom fields that match your shop’s processes for deeper reporting insights.  

---

## Field Settings

When creating or editing a reporting field, you can control:  
- **Required**: Must be filled out before checkout is allowed.  
- **Allow User Input**: Users can type or scan values at checkout. If unchecked, users must choose from a dropdown.  
- **Restrict User Input**: Allows users to type into this field, but only accepts values that already exist in the preloaded list.  
  - Useful when there are many possible values and you want to prevent mistakes.  
  - Works well with barcode scanners — users can scan a valid value instead of typing it.  
- **Enable**: Activates or deactivates the field at checkout.  
- **Name**: The name of the field (can be edited later).  
- **View Order**: Sets the order in which fields appear at the kiosk. Lower numbers show first.  
- **Character Min**: Minimum number of characters the user must enter if typing.  
- **Character Max**: Maximum number of characters the user can enter if typing.  


---

## Ways to Add Data

- **Manually**: Add entries one by one to create a dropdown list.  
- **Import**: Upload a spreadsheet of values to create or update a list (see [Importing Data](xref:reporting-fields.import)).  

---

## FAQ

### Can reporting fields be required?
Yes. If a field is marked **Required**, users must provide a value before checkout.

### Can I use reporting fields as search categories?
No. Use [Categories](xref:categories) for grouping and searching items. Reporting fields are only used to capture data at checkout.

### Can employees have default reporting field values?
Yes. Employees can be assigned **default values** for reporting fields so they don’t have to re-enter the same data every time they issue an item.  
- Commonly used for departments, jobs, or cost centers where the values rarely change.  
- Defaults are set in the [Employee Tabs](xref:employees.additional-tabs).  

---

## Related Topics
- [Creating a New Reporting Field](xref:reporting-fields.add)  
- [Importing Data into a Reporting Field](xref:reporting-fields.import)  
- [Items](xref:items)  
