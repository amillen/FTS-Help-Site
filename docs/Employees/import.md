---
uid: employees.import
title: Employee Import/Uploading/Updating Employees
---

# Importing Employees (Employee Import Tool)

**Also known as:** *Bulk Employee Upload*, *Employee Import File*

The **Employee Import Tool** lets you add or update many employees at once using an Excel template.

---

## Required Fields

Each employee record in the import file must include:  
- **Employee ID**: A unique numeric identifier (employee number or any unique number).  
- **First Name / Last Name**: The employee’s name or a role/generalization (e.g., “Tool Crib”).  

---

## Suggested Fields

- **PIN**: A numeric PIN (recommended 4 digits).  
- **Permissions**: Select Regular User or Supervisor permissions.  

### Regular User Permissions
- Undo, Adjust, Return  

### Supervisor Permissions
- All Regular User permissions plus: Configure Kiosk, Restock, Physical, Adjust All, Return All, Require Password  

---

## Steps to Import

1. Navigate to the **Employees** module from the [Dashboard](xref:dashboard).  
2. Click the **cloud upload button** in the top right corner.  
3. Download the **Employee Import Template**.  
   - Blank template for new employees.  
   - Sample template for reference (delete sample data before use).  
4. Fill out the template with employee details.  
5. Save and upload the file.  
6. Choose whether to **Append** (add new employees) or **Replace** (clear and replace all records).  
7. Review and confirm the import.  

---

## FAQ

### What’s the difference between Append and Replace?
- **Append**: Adds new employees while keeping existing ones.  
- **Replace**: Clears all existing employees and replaces them with the uploaded list.  

### Can I set permissions during import?
Yes. Include the appropriate permission settings in the template file.  

### What happens if I import duplicates?
The system will flag errors. Update the file and re-upload.  

---

## Related Topics
- [Employees (Overview)](xref:employees)  
- [Adding an Employee](xref:employees.add)  
- [Stations](xref:stations)  
