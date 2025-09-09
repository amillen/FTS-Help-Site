---
uid: purchase-orders.add-unapproved
title: Adding/Creating/Setting Up an Unapproved Purchase Order
---

# Creating an Unapproved Purchase Order (Unapproved PO)

**Also known as:** *Add Unapproved PO*, *Pending Approval PO*, *Approval Required PO*

An **Unapproved Purchase Order** is created automatically by the system but requires manual approval before being sent to the supplier. If not approved within the expiration window, it is canceled.

---

## Steps to Create an Unapproved PO

1. Navigate to the **Purchase Orders** module from the [Dashboard](xref:dashboard).  
2. Click on **Create Unapproved PO**.  
3. Fill in the header details:  
   - [Supplier](xref:suppliers) (the vendor you are ordering from).  
   - **Station** (choose All Stations or a single station).  
   - **Delivery Date** (optional expected delivery date).  
   - **Reference Number** (optional).  
4. Select items for the PO:  
   - Suggested automatically from **Min/Max levels**.  
   - Review, add, or remove items as needed.  
5. Save the PO. It is now marked as **Unapproved**.  
6. A notification is sent to the designated approvers.  

---

## Approval Workflow

- Approvers must log in to review and approve the PO.  
- If approved, the PO is transmitted to the supplier.  
- If not approved before the expiration period, the PO is canceled.  
- Approvers can add notes or comments as part of the approval process.  

---

## FAQ

### What happens if an Unapproved PO isn’t approved in time?
It expires and is automatically canceled. No order is sent to the supplier.

### Can I change items in an Unapproved PO?
Yes. Items can be adjusted while the PO is pending approval.

### Who gets notified when an Unapproved PO is created?
Approvers set in the [Approval Process](xref:purchase-orders.approval-process) will be notified.

### Can I resend approval requests?
Yes. Approval requests can be resent if an approver did not respond.  

---

## Related Topics
- [Purchase Orders Overview](xref:purchase-orders)  
- [Creating a Manual PO](xref:purchase-orders.add-manual)  
- [Creating an Automatic PO](xref:purchase-orders.add-auto)  
- [Approval Process](xref:purchase-orders.approval-process)  
- [Exporting a PO](xref:purchase-orders.export)  
