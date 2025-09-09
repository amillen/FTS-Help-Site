---
uid: suppliers.po-approval-process
title: Supplier PO Approval Process/Approval Chains/PO Approval Tab
---

# Supplier Purchase Order Approval Process

**Also known as:** *PO Approval Chains*, *PO Approval Tab*, *Supplier Approvals*

The **PO Approval Process Tab** inside a supplier record allows you to set up a chain of approvers before purchase orders are sent. This creates checks and balances, ensuring large or sensitive orders are reviewed.

---

## Why Use PO Approval Process?

- Adds oversight to supplier orders.  
- Allows setting **dollar limits** for each approver.  
- Supports a chain of approvals (e.g., Champion → Supervisor → Owner → Accounting).  
- Final approver is responsible for sending the PO to the supplier.  

> **Important:** The PO Approval Process workflow applies to **Approved POs**. It prevents a PO from being considered fully approved (ready to send) until all approvers in the chain have signed off.  
> This is different from unchecking the **Approved** box when creating a PO, which creates a **draft PO**. Draft POs are not part of the approval workflow.


---

## Setting Up the Approval Process

1. Navigate to the [Suppliers](xref:suppliers) module from the [Dashboard](xref:dashboard).  
2. Select the supplier you want to configure.  
3. Open the **PO Approval Process Tab**.  
4. Add approvers and assign approval amounts (see below).  
5. Save the supplier record.  

---

## Selecting Approvers

- Click **Select user here** to add an approver.  
- Choose from the list of approved individuals at your site.  
- Only users with backend access will appear in this list.  

---

## Approval Amounts

Each approver must have an approval threshold:  

- **$0** → All POs go through this approver.  
- **$X** (any dollar amount) → Only POs greater than that amount require approval.  

Example: If set at **$200**, this approver only reviews POs above $200. POs under $200 are auto-approved.  

---

## Editing Approvers

- Approvers can be reordered or updated anytime.  
- To edit, click the approver’s name and enter a new dollar threshold.  
- Save changes to update the approval chain.  

---

## Notifications

- Approvers receive an email when a PO requires their review.  
- The email preview shows the PO details and highlights that it is “awaiting approval.”  
- Clicking the PO number in the email opens FTS to review, revise, and approve.  

---

## Reviewing and Approving POs

- **Black Line Item** = Approved & sent to supplier.  
- **Red Line Item** = Not approved, PO will not be processed until approved.  
- Approvers can:  
  - Edit item quantities.  
  - Cancel line items.  
  - Adjust Min/Max settings if needed.  

Each approver clicks **Save** to pass the PO to the next approver.  

---

## Final Approval

- The **last approver** finalizes the PO.  
- They enter the supplier’s email address and send it off.  
- The PO is now active and marked approved.  
- Any changes can be viewed in **View Audits**.  

---

## FAQ

### What happens if no approval process is set for a supplier?
POs are sent directly without requiring approval.

### Can I have multiple approvers?
Yes. You can configure a chain of approvers in sequence.

### What does the $0 threshold mean?
It means all POs for that supplier must go through this approver.

### Who sends the PO to the supplier?
The **final approver** in the chain.

### Where can I see who still needs to approve?
Click **PO Process Active** on the PO to see the list of approvers and their progress.  

---

## Related Topics
- [Suppliers Overview](xref:suppliers)  
- [Adding a Supplier](xref:suppliers.add)  
- [Supplier Features and Settings](xref:suppliers.features)  
- [Purchase Orders Overview](xref:purchase-orders)  
- [Purchase Order Approval Process](xref:purchase-orders.approval-process)  
