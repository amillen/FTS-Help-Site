---
uid: purchase-orders
title: Purchase Orders/POs
---

# Purchase Orders (POs)

The **Purchase Orders (POs)** module is where all orders to suppliers are managed in FTS. You can create new purchase orders, review open or past orders, approve pending orders, export, or reverse receipts.  

**Also known as:** *POs*, *Supplier Orders*

---

## Types of Purchase Orders

FTS supports three types of purchase orders:  

- **Manual PO**: Create anytime, for any item, directly from the Purchase Orders module.  
- **Automatic PO**: Runs automatically on a schedule based on min/max requirements. Sent directly to the supplier without review.  
- **Unapproved PO**: Runs automatically, but requires manual approval before sending. If not approved in time, it expires.  

> **Note:** Do not confuse **Unapproved POs** with **draft POs**.  
> - A **draft PO** is created when you uncheck the **Approved** box while creating a PO. Draft POs are incomplete orders, not tied to the approval workflow.  
> - The **PO Approval Process workflow** applies only to Approved POs and must be completed before the PO is sent to the supplier.


---

## Approval Process

Purchase Orders can optionally use an **Approval Process**:  
- Create a chain of approvers.  
- Apply spending limits per person.  
- Require final approval before sending to supplier.  

See [Purchase Order Approval Process](xref:purchase-orders.approval-process).  

---

## Common Tasks

- [Create a Manual PO](xref:purchase-orders.add-manual)  
- [Create an Automatic PO](xref:purchase-orders.add-auto)  
- [Create an Unapproved PO](xref:purchase-orders.add-unapproved)  
- [Export a PO](xref:purchase-orders.export)  

---

## FAQ

### What’s the difference between Automatic and Unapproved POs?
- **Automatic PO**: Sent directly to the supplier as soon as it runs.  
- **Unapproved PO**: Requires manual approval first; if not approved, it expires.  

### Can I run POs for a single station?
Yes. When creating an Auto or Manual PO, you can select **All Stations** or a single station.

### Can I export POs for recordkeeping?
Yes. Use the **Export** option to download POs in Excel format. See [Exporting Purchase Orders](xref:purchase-orders.export).  

---

## Related Topics
- [Suppliers](xref:suppliers)  
- [Items](xref:items)  
- [Stations](xref:stations)  
- [Employees](xref:employees)  
- [Reporting Fields](xref:reporting-fields)  
