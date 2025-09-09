---
uid: transactions
title: Transactions/Transaction Records
---

# Transactions

**Also known as:** *Activity Records*, *Inventory Movements*

A **Transaction** is recorded any time an item’s quantity changes in FTS. Transactions provide the history of how, when, and by whom items were used, returned, adjusted, or restocked.

---

## What Creates a Transaction?

Any action that increases or decreases an item’s stock creates a transaction:

- **Issue**: Item checked out by an employee.  
- **Return**: Item returned (Semi-Consumable or Durable).  
- **Adjust**: Consumable item added back into stock if unused.  
- **Restock**: Item received into inventory from a purchase order.  
- **Auto Scrap**: Semi-Consumable item automatically scrapped after expiration.  
- **Move**: Item moved from one location to another.  

---

## Where Transactions Are Used

- **History Tabs**: Found in [Items](xref:items.additional-tabs), [Stations](xref:stations.additional-tabs), [Locations](xref:cabinets.locations.additional-tabs), and [Employees](xref:employees.additional-tabs). Each history tab displays the transactions for that record.  
- **Reports**: Transactions are the foundation of many reports, including Transaction Report, Usage Per Month, and Unreturned Inventory.  
- **Audit and Compliance**: Transactions provide a complete audit trail of all inventory activity.  

---

## Example Transaction Record

- Date/Time  
- Employee  
- Item ID and Description  
- Station / Cabinet / Location  
- Action (Issue, Return, Adjust, Restock, Scrap, Move)  
- Quantity Change  
- Notes (if provided)  

---

## FAQ

### What’s the difference between a Transaction and an Audit Log?
- **Transaction**: Records item quantity changes (e.g., issue, return, restock).  
- **Audit Log**: Records *system changes* to item or supplier settings (e.g., Min/Max changed, email updated).  

### Where can I see all Transactions?
Use the **Reports** module and run a **Transaction Report**.  

### Do all inventory actions create a transaction?
Yes. Any action that changes item stock creates a transaction.  

---

## Related Topics
- [Items](xref:items)  
- [Stations](xref:stations)  
- [Locations](xref:cabinets.locations)  
- [Employees](xref:employees)  
- [Reports](xref:reports)  
- [Audit Logs](xref:items.additional-tabs)  
