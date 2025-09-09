---
uid: cabinets.locations.additional-tabs
title: Location Tabs/Open POs/Alerts/History/Audit Logs
---

# Additional Location Tabs

Each location in a cabinet has several tabs that provide extra details and controls. These tabs are visible when viewing a location.

---

## Open POs
Displays information about the **open purchase orders** for this location.  
- Shows details of any active POs.  
- Provides a link to navigate directly to the PO.

---

## Alerts
The **Alerts** tab is used to set up critical quantity notifications for a location.  
When the quantity falls to or below a set point, alerts are sent to the station and/or supplier.

### How to Open the Alerts Tab
1. Navigate to the **Cabinets** module from the [Dashboard](xref:dashboard).  
2. Select the cabinet that contains the location you want to set alerts for.  
3. Click on the location.  
4. Open the **Alerts** tab.  

---

### How to Set an Alert
1. Type in the **Alert Quantity** (the level at which you want to be notified).  
2. Optionally, add a **Note** to remind you why you set the alert.  
3. Click the **plus (+) button** to save the alert.  
4. Choose one or more notification options:  
   - **Email Supplier**: Send an alert to the Supplier’s email(s).  
   - **Email Supervisor**: Send an alert to the Station’s Notification email(s).  
   - **Alert Once**: Only send the email once when the quantity reaches the alert level. If unchecked, emails will be sent every time the quantity is reduced to or below the alert level.  

---

### FAQ: Alerts

#### What is an Alert Quantity?
A threshold you set for an item’s on-hand quantity. When the item reaches or falls below this number, an alert is triggered.

#### Who gets alerted?
- [Suppliers](xref:suppliers): if “Email Supplier” is checked.  
- **Station Supervisors**: if “Email Supervisor” is checked.  

#### What does “Alert Once” mean?
- **Checked**: Sends a single alert the first time the quantity hits or drops below the alert level.  
- **Unchecked**: Sends an alert **every time** the quantity decreases while at or below the alert level.

#### Can I add notes to alerts?
Yes. Notes are optional and can help remind you why an alert was created (e.g., “Critical for maintenance” or “Backup supplier delay”).

#### Can I set multiple alerts for the same location?
Yes. You can create more than one alert with different quantities or notification options.

---

## History
Shows the [Transactions](xref:transactions) for this location.  
- Similar to Station History, but limited only to this location.  
- Use grid filters to search by date, item, or transaction type.

---

## Audit Logs
Shows all changes that have been made to this location since it was created.  
- Includes **who** made the change and **when** it was made.  
- Useful for compliance and tracking adjustments.

---

## Related Topics
- [Locations Overview](xref:cabinets.locations)  
- [Creating a New Location](xref:cabinets.create-location)  
- [Cabinet Builder](xref:cabinets.builder)  
- [Location Import](xref:cabinets.location-import)  
- [Stations/Station Groups](xref:stations)  
