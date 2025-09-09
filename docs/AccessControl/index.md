---
uid: access-controls
title: Access Control/Restrictions/Permissions
---

# Access Control

The **Access Control** module allows administrators to restrict employee access to items, drawers, cabinets, or stations. Rules are created that define who can (or cannot) issue items and under what conditions.  

**Also known as:** *Restrictions*, *Permissions*, *Access Rules*

---

## What Access Control Is

- Access Control creates **rules** that limit inventory access.  
- Rules can apply to:  
  - **Item** – restrict how much or how often an item can be issued.  
  - **Drawer** – limit access to specific cabinet drawers.  
  - **Cabinet** – limit access to an entire cabinet.  
  - **Station** – limit access to everything within a station.  
  - **Issue Other Item** – require employees to issue a substitute item before issuing the original.  

> **Important:** Access Control is a **software restriction only**. It cannot physically stop an employee from opening a drawer if the cabinet locks are shared. Always treat it as an inventory management tool, not a security system.

---

## Examples

- Limit safety glasses to **1 pair per employee per week**.  
- Restrict a supervisor-only drawer to supervisors.  
- Block the Milling department from seeing or issuing items at the Lathe station.  
- Require employees to issue “old stock” (e.g., older inserts) before they can issue “new stock.”  

---

## Adding a New Rule

1. Navigate to the **Access Control** module from the [Dashboard](xref:dashboard).  
2. Click **Add New Rule**.  
3. Choose a **Rule Type**: Item, Drawer, Cabinet, Station, or Issue Other Item.  
4. Select the item, drawer, cabinet, or station to apply the rule.  
5. Configure options (time intervals, quantity limits, or substitute items).  
6. Choose which employees the rule applies to (or doesn’t apply to).  
7. Save the rule.  

---

## Audit Logs Tab

The **Audit Logs** tab shows all changes made to access control rules.  
- Includes **who** made the change and **when**.  
- Provides accountability for all rule creation, edits, and deletions.  

---

## FAQ

### Can I restrict access by employee?
Yes. When creating a rule, choose which employees the rule **Applies To** or **Doesn’t Apply To**.

### Can I limit how often an item can be issued?
Yes. Create an **Item rule**, enable **Time Options**, and set a quantity limit with a time interval (e.g., 1 pair of safety glasses per week).

### Can I require substitutes to be used before an item?
Yes. Use the **Issue Other Item** rule to make employees issue a secondary item before the primary one.

### Does Access Control prevent drawer opening?
No. Drawer restrictions are **software-only**. All drawers open on the same lock backbone — so use these rules for inventory control, not physical security.

---

## Related Topics
- [Employees](xref:employees)  
- [Items](xref:items)  
- [Stations](xref:stations)  
- [Cabinets](xref:cabinets)  
