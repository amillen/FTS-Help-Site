---
uid: suppliers.auto-purchase-orders
title: Adding/Creating/Setting Up Automatic Purchase Orders
---

# Automatic Purchase Orders

To schedule automatic purchase orders (or related supplier reports), configure the options below and apply the selected report. These settings are available when [creating or editing a supplier](xref:suppliers.add) under the **Automated PO** tab.

**Also known as:** *Automated POs*, *Scheduled PO emails*, *Supplier auto-order schedule*

> See also: [Suppliers](xref:suppliers) · [Adding a Supplier](xref:suppliers.add) · [Supplier Features and Settings](xref:suppliers.features)

---

## 1) Select Report Type

Use the **Report Type** picker to choose what will be generated/sent for this supplier.  

### Available Report Types
- **Purchase Order**: Creates and sends an order to the supplier based on inventory levels.  
- **Open Purchase Order – Report**: Lists all open (not yet received) purchase orders.  
- **Reorder Report**: Shows items that are low or out of stock and need to be reordered based on the **Purchase Method** selected below. This has the same items and quantities as a **Purchase Order** but does not create a PO in the system.  
- **Unapproved Purchase Order**: Generates a PO that must be approved before being sent to the supplier. This is great for managers who want to review orders before they are placed.
- **Calibration Order**: Creates an order for tools/gages that need calibration.  
- **Calibration Order Report**: A report showing which tools/gages require calibration and their status.  This is the same as a **Calibration Order** but does not create one in the system.

---

## 2) Purchase Method

Choose the **Method** used when an automated PO/report is generated.  
- **At or Below Min**: Runs the Purchase Order (PO) only if the total inventory is at or below the item's Min level.  
- **Below Max**: Runs the Purchase Order (PO) only if the total inventory is below the item's Max level.  

---

## 3) Schedule: Days to Run

Select when the automation should run.

- **Monthly**: Runs the report on the 1st of each month.  
- **All Days**: Runs the report every day of the week.  
- **Specific Days**: Check individual weekdays as needed.  

---

## 4) Schedule: Time of Day

Set the run time for the automated PO/report.

> Example: 02 : 30 PM  

---

## 5) Recipients

**Email Addresses** receives the generated PO/report.  

> Tip: Separate multiple addresses with commas (e.g., `buyer@acme.com, alt@acme.com`).  

---

## 6) Report-Specific Options

Different reports expose different extra fields.

> Note: **Calibration Orders** and **Calibration Order Reports** are only available if your environment is configured for gaging and the supplier has calibrator enabled.

### Purchase Order
- **Minimum Order Amount ($)**: Only generate a PO when this amount is met.  

### Unapproved Purchase Order
- **Expiration Days**: If an **Unapproved PO** is not approved within this many days, it will be canceled.  

### Calibration Order / Calibration Order Report
- **% of Gage Usage Left**: Set the threshold for when a gage should be calibrated (based on usage vs. allowed uses).  
- **Number of days until (or within) expiration**: Set how many days before a gage's expiration date it should be included in the order/report.  

---

## 7) Reference Number (Optional)

**Reference Number**: An optional number you can set to include on the PO when the automated PO/report is generated.  

> **Precedence note:** If the Automated PO **Reference Number** is set here, it **overrides** the Supplier’s **Default Reference Number** when automated POs are created.  

---

## FAQ

### Can I run the same supplier on multiple schedules?
Yes. Create additional schedules by selecting another report type (or different days of the week), then click **Apply**.  

### How do I send automated POs to multiple recipients?
Enter multiple addresses in **Email Addresses**, separated by commas.  

### Do **Reference Number** settings conflict with supplier defaults?
If the automated PO has a **Reference Number** here, it takes precedence over the Supplier’s **Default Reference Number** from [Supplier Features and Settings](xref:suppliers.features).  

---

## Related Topics
- [Adding a Supplier](xref:suppliers.add)  
- [Supplier Features and Settings](xref:suppliers.features)  
- [Suppliers (Overview)](xref:suppliers)  
- [Purchase Orders](xref:purchase-orders)