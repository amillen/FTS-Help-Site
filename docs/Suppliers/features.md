---
uid: suppliers.features
title: Supplier Features and Settings
---

# Supplier Features and Settings

When creating or editing a supplier, you’ll see additional optional settings.  
These are not required when adding a new supplier, but they can be filled out to customize supplier behavior.

---

## Email Images
Determines whether item images are included in emails sent to this supplier.

---

## Email Extended Description
Includes extended item descriptions in supplier communications.

---

## Calibrator Enabled
Enables calibrator tracking for items associated with this supplier.

---

## Supplier Disabled
Disables the supplier without deleting it.  
Useful when you no longer order from them but want to keep history.

---

## Default Delivery Instructions
Instructions automatically added to purchase orders for this supplier.

---

## Send Notes
Allows sending the notes below to the supplier on purchase orders.

## Notes
Free-form notes for internal or external reference depending if Send Notes is checked.

---

## Payment Terms
Sets the default payment terms for this supplier.

---

## Target Order Amount
Setting a target order amount will display a warning message when creating a PO if the PO total amount is less than the target order amount.

---

## Hide PO Pricing
Hides pricing information on supplier-facing POs.

---

## Prepend Station ID To PO Number
Adds the station ID at the start of the purchase order number.

---

## Default Reference Number
This value will be the 'Default Reference Number' used at the 'Reference Number'on a PO. The Default Reference Number will not be used after the Experation Date below. Note: Automated PO 'Reference Number' takes precedence over Supplier 'Default Reference Number' when automated POs are created and Automated PO 'Reference Number' has a value.

## Expiration Date
Defines the expiration date for the Default Reference Number above. An email will be sent to the supplier when the date passes.


---

## PO Approval Process
Configure a chain of approvers and dollar thresholds before POs are sent to this supplier.  
- Useful when you want oversight of large or sensitive purchases.  
- Approvers are notified when a PO is pending and must approve it before it is sent.  
- Final approver sends the PO to the supplier.  

See [Supplier PO Approval Process](xref:suppliers.po-approval-process) for details.
