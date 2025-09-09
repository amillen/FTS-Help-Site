---
uid: reporting-fields.add
title: Adding/Creating/Setting Up a Reporting Field
---

# Creating a New Reporting Field (Adding a Reporting Field)

**Also known as:** *Add Reporting Field*, *New Reporting Field*, *Custom Field*

To create a new reporting field:

1. Navigate to the **Reporting Fields** module from the [Dashboard](xref:dashboard).  
2. Click on **Add New Reporting Field**.  
3. Fill in the reporting field details:  
   - **Name**: The field label (e.g., Part Number, Job Number).  
   - **Required**: Must be filled out before checkout is allowed.  
   - **Allow User Input**: Lets users type or scan data at checkout. If unchecked, users must choose from a dropdown.  
   - **Restrict User Input**: Allows users to type into this field, but only accepts values that already exist in the preloaded list.  
     - Useful when there are many possible values and you want to prevent mistakes.  
     - Works well with barcode scanners — users can scan a valid value instead of typing it.

   - **Enable**: Activates or deactivates the field at checkout.  
   - **View Order**: Sets the order in which fields appear at the kiosk. Lower numbers show first.  
   - **Character Min**: Minimum number of characters the user must enter if typing.  
   - **Character Max**: Maximum number of characters the user can enter if typing.  
4. Click **Add Reporting Field**.  

---

## After Creating a Field

- Use the **Settings** button to adjust requirements.  
- Add data options by either:  
  - Typing and clicking the **+** button (adds a single value).  
  - Uploading a list (see [Importing Data](xref:reporting-fields.import)).  

---

## FAQ

### What happens if a field is required?
Users cannot complete checkout unless they provide a value for that field.

### Can I change a field’s name later?
Yes. The field name can be edited from the Settings screen.

### Can I deactivate a field without deleting it?
Yes. Uncheck **Enable** to disable the field at checkout.

### What is View Order?
It controls the order in which reporting fields are shown at the kiosk. For example, a field with **View Order = 1** will appear above a field with **View Order = 2**.

### What are Character Min and Max?
- **Character Min**: The minimum number of characters a user must enter.  
- **Character Max**: The maximum number of characters a user is allowed to enter.  
These settings only apply if **Allow User Input** is enabled.

### What does Restrict User Input mean?
This setting lets users type into the field, but only accepts values that already exist in the preloaded list.  
- Helps prevent typos or invalid entries.  
- Often paired with barcode scanners so users can scan valid values directly.


---

## Related Topics
- [Reporting Fields Overview](xref:reporting-fields)  
- [Importing Data into a Reporting Field](xref:reporting-fields.import)  
- [Items](xref:items)
