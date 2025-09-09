---
uid: access-controls.add
title: Adding/Creating/Setting Up an Access Control Rule
---

# Creating a New Access Control Rule (Adding a Rule)

**Also known as:** *Add Access Rule*, *New Restriction*, *Set Up Access Control*

To create a new access control rule:

1. Navigate to the **Access Control** module from the [Dashboard](xref:dashboard).  
2. Click on **Add New Rule**.  
3. Choose a **Rule Type** (see below).  
4. Configure the rule details.  
5. Select which employees the rule applies to (or does not apply to).  
6. Save the rule.  

---

## Rule Types

### Item Rule
Restricts use of a specific item.  
- Can limit how many times it can be issued.  
- Can set a time window (e.g., 1 per day, 3 per week).  
- Example: Safety glasses limited to **1 pair per employee per week**.  

### Drawer Rule
Restricts access to a cabinet drawer.  
- Example: Only supervisors can access Drawer 4 in Cabinet A.  

### Cabinet Rule
Restricts access to an entire cabinet.  
- Example: Block employees in the Milling department from accessing the Lathe cabinet.  

### Station Rule
Restricts access to all cabinets within a station.  
- Example: Limit certain employees to the “Maintenance” station only.  

### Issue Other Item Rule
Requires employees to issue one item before another.  
- Example: Employees must issue “Old Inserts” before they can issue “New Inserts.”  

---

## Employee Scope

When creating a rule, you can specify:  
- **Applies To**: Employees who the rule affects.  
- **Does Not Apply To**: Employees who are exempt.  

> **Tip:** Use this to apply rules to departments, roles, or individuals.  

---

## Audit Logs

All rule changes are recorded in the [Audit Logs tab](xref:access-controls).  
- Shows who created, edited, or deleted a rule.  
- Provides accountability and traceability.  

---

## FAQ

### Can I restrict an item to supervisors only?
Yes. Create an **Item Rule** and set the **Does Not Apply To** list to include only supervisors.

### How do I limit frequency of issuing an item?
Use an **Item Rule** with **Time Options** (e.g., max 1 issue per week).

### Can I block an entire cabinet?
Yes. Use a **Cabinet Rule** to restrict access to the whole cabinet.

### What’s the difference between Drawer and Cabinet rules?
- **Drawer Rule** = restricts a single drawer.  
- **Cabinet Rule** = restricts every drawer in the cabinet.  

### Can I use Issue Other Item for safety stock rotation?
Yes. For example, require employees to issue “Old Stock” before they can issue “New Stock.”  

---

## Related Topics
- [Access Control Overview](xref:access-controls)  
- [Employees](xref:employees)  
- [Items](xref:items)  
- [Stations](xref:stations)  
- [Cabinets](xref:cabinets)  
