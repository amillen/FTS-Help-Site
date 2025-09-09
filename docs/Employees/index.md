---
uid: employees
title: Employees/Employee Management
---

# Employees

The **Employees** module is where you manage the people who can access and use FTS. Employees can be added individually or imported in bulk.  

**Also known as:** *User Management*, *Employee Records*

---

## What Employees Are

- Every person who uses FTS is tracked as an **Employee record**.  
- Employees can be given permissions that define what they are allowed to do at kiosks or in the system.  
- Permissions can range from basic checkout functions to advanced supervisor tasks like restocking and adjusting.  

---

## What You Can Do in the Employee Module

- **Add New Employees**: Create records for employees one at a time (see [Adding an Employee](xref:employees.add)).  
- **Import Employees**: Upload multiple employees at once from a template (see [Employee Import](xref:employees.import)).  
- **Edit Employees**: Change permissions or update employee information.  
- **Search/Filter**: Quickly find employees by name or by specific permissions.  
- **Deactivate Employees**: Hide employees without deleting their history (keeps reports accurate).  

---

## Permissions Overview

Employee permissions control what users can do. Here is a typical setup for **Regular Users** and **Supervisors**.  

| Permission            | Regular User | Supervisor |
|------------------------|--------------|------------|
| Issue items            | ✅           | ✅         |
| Undo (cancel checkout before drawer closes) | ✅ | ✅ |
| Adjust (return consumables) | ✅ | ✅ |
| Return (return semi-consumables and durables) | ✅ | ✅ |
| Configure Kiosk        | ❌           | ✅         |
| Restock (receive POs)  | ❌           | ✅         |
| Physical (inventory counts) | ❌       | ✅         |
| Adjust All (for any employee) | ❌     | ✅         |
| Return All (for any employee) | ❌     | ✅         |
| Require Password (extra security for kiosk access) | ❌ | ✅ |

---

## Related Topics
- [Adding an Employee](xref:employees.add)  
- [Employee Import](xref:employees.import)  
- [Stations](xref:stations)  
- [Cabinets](xref:cabinets)  
