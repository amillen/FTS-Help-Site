---
uid: purchase-orders.approval-process
title: Purchase Order Approval Process/PO Approvals
---

# Purchase Order Approval Process

**Also known as:** *PO Approvals*, *Approval Chain*, *Approval Workflow*

The **Purchase Order Approval Process** ensures that certain POs are reviewed and approved before being sent to suppliers. This is most commonly used for **Unapproved POs**, but can also apply when company policy requires oversight based on spend or item type.

---

## How Approvals Work in POs

1. A purchase order is created.  
   - If the supplier has an **Approval Process workflow**, the PO cannot be marked **Approved** until the full workflow is complete.  
   - This is different from creating a draft PO by unchecking the **Approved** box. Draft POs are simply incomplete orders and are not tied to the approval workflow.  
2. If the workflow applies, the PO is marked **Pending Approval**.  
3. Approvers are notified by email and inside FTS.  
4. Each approver reviews the PO:  
   - Approve (moves to the next approver or to supplier if final).  
   - Reject (sends the PO back to the creator).  
   - Add notes or comments to explain decisions.  
5. Once the final approver approves, the PO is considered **Approved** and ready to send to the supplier.

---

## Approval Chains

- You can configure multiple approvers in a **chain**.  
- Each approver must approve in order before the PO is sent.  
- Approvers can have **spending limits**, so higher-value POs require additional sign-off.  
- If an approver rejects a PO, it stops the approval process until corrected.  

---

## Spending Limits

- Each approver can have a **dollar threshold**.  
- If the PO amount is below the threshold, that approver can finalize it.  
- If the PO amount is above the threshold, it moves on to the next approver in the chain.  

---

## Notifications

- Approvers are automatically notified when a PO needs their approval.  
- Creators are notified once the PO is approved, rejected, or expired.  
- Approval requests can be **resent** if an approver does not respond.  

---

## FAQ

### What happens if a PO is not approved in time?
It expires and no order is sent to the supplier.

### Can I have multiple approvers for the same PO?
Yes. Approval chains allow multiple approvers in sequence.

### Can I set spending limits?
Yes. Approvers can have dollar thresholds. If a PO exceeds their limit, it moves to the next approver.

### Can I resend an approval request?
Yes. Approval requests can be resent if an approver does not act.

### Can approvers add notes?
Yes. Approvers can include notes or comments when approving or rejecting a PO.

### What’s the difference between an unapproved PO and a draft PO?
- **Unapproved PO**: A system-created PO type that requires approval before sending. If not approved in time, it expires.  
- **Draft PO (unchecking Approved box)**: A PO that has not yet been finalized by the creator. It is not part of the approval workflow and simply sits in draft until marked Approved.


---

## Related Topics
- [Purchase Orders Overview](xref:purchase-orders)  
- [Creating an Unapproved PO](xref:purchase-orders.add-unapproved)  
- [Creating a Manual PO](xref:purchase-orders.add-manual)  
- [Creating an Automatic PO](xref:purchase-orders.add-auto)  
- [Exporting a PO](xref:purchase-orders.export)  
