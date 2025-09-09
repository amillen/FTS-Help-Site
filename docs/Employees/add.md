---
uid: employees.add
title: Adding/Creating/Setting Up an Employee
---

# Creating a New Employee (Adding an Employee)

**Also known as:** *Add Employee*, *New Employee*, *Set Up Employee*

To add a new employee:

1. Navigate to the **Employees** module from the [Dashboard](xref:dashboard).  
2. Click on **Add New Employee** (or click the blue **plus (+)** button).  
3. Fill in the employee details:  
   - **Employee ID**: Usually the employee’s number, but can be any unique numeric value.  
   - **First Name / Last Name**: The employee’s name (or a role/generalization like “Tool Crib”).  
   - **PIN**: A numeric PIN (recommended 4 digits) used for kiosk login.  
4. Set the correct permissions for the employee (see below).  
5. Click **Add Employee** to save.  

---

## Permissions

### Regular User Permissions
- **Undo**: Cancel a checkout before the drawer is closed (avoids incorrect issues).  
- **Adjust**: Return unused **consumable** items back into inventory.  
- **Return**: Return **semi-consumable** or **durable** items after use.  

### Supervisor Permissions
Includes all regular user permissions plus:  
- **Configure Kiosk**: Manage cabinet visibility, kiosk settings, timeouts, etc.  
- **Restock**: Receive purchase orders into inventory.  
- **Physical**: Perform inventory counts and verifications.  
- **Adjust All**: Adjust items for any employee.  
- **Return All**: Return items for any employee.  
- **Require Password**: Force employees to enter a numeric PIN for extra security.  

---

## Editing Employees
- Select an employee from the list to change details or permissions.  
- Use search or filters to find employees by name or permission.  
- Click **Update Employee** to save changes.  
- **Delete Employee** hides the record (keeps history intact for reports).  

---

## FAQ

### Do employees need an Employee ID?
Yes. It must be unique. If no official number exists, create one (e.g., 1001, 1002).

### Can an employee log in without a PIN?
No. A PIN is required for kiosk access.  

### What happens if I delete an employee?
The record is hidden but not removed — history and reporting remain intact.  

---

## See Also
- [Additional Employee Tabs](xref:employees.additional-tabs) — Configure employee history, access controls, and reporting field default values.

---

## Related Topics
- [Employees (Overview)](xref:employees)  
- [Employee Import](xref:employees.import)  
- [Stations](xref:stations)  
