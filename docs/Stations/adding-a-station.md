---
uid: stations.add
title: Adding/Creating/Setting Up a Station
---

# Creating a New Station (Adding a Station)

**Also known as:** *Create Station*, *New Station*, *Add Station*

To add a new station to the FTS system, follow these steps:

1. Navigate to the **Stations** module from the [Dashboard](xref:dashboard).
2. Click on the **Create New Station** link.
3. Fill in the station details:
   - **Station ID** (short code, best ≤ 6 characters)
   - **Description** (clear name, e.g., Milling Dept., HQ-CA)
   - **Notification Email(s)** (comma-separated addresses for alerts)
   - **Address** (physical location)
   - **Number of Days Until AutoScrap**
   - **Send Undo Notification Email** (checkbox if you want undone transactions sent to the notification emails)
4. Click **Save** to add the station to the system.

> **Tip:** Stations group [Cabinets](xref:cabinets) so you can organize your shop (by area or department) and manage purchasing/visibility separately.


> See also: [Stations (Overview)](xref:stations) · [Items (Item Types)](xref:items)

---

## Required Fields

### Station ID
A short, unique code for the station.  
- **Best practice:** Keep it **6 characters or fewer** (e.g., `ST01`, `MILLA`).  
- Used in reports, purchase orders, and quick identification.

### Description
A clear, unambiguous description of the station.  
- Examples: *Headquarters – California*, *Milling Department*, *Station 03 – Colorado*.

---

## Notification & Address

### Notification Email
The email address(es) that receive station alerts.  
- Enter one or more addresses, **comma-separated** (e.g., `lead@shop.com, manager@shop.com`).  
- Alerts may include:
  - Location alerts
  - Gaging/calibration notices
  - **Undone Transactions** (if the checkbox below is enabled)
  - **Supplier Reference Number expired** notices

### Address
The physical address for this station (used on documents and for reference).

---

## Station Rules & Options

### Number of Days Until AutoScrap
Number of days until **semi-consumable** items are automatically scrapped at this station. 
- Set based on your shop policy and **item type** rules (see [Items](xref:items)).  
- Example: If set to **30**, **semi-consumable** items at this station will auto-scrap after 30 days.

### Send Undo Notification Email
If checked, **Undone Transaction** alerts are sent to the **Notification Email** list above.  
- Useful if you want supervisors alerted whenever a transaction is undone, so they can verify inventory accuracy.

---

## FAQ

### What is a Station?
A Station is a way to group cabinets together.  
Stations can represent physical locations (like California, Nevada, Colorado) or areas inside a shop (like Milling, Deburr, Maintenance).  
They help organize cabinets, control purchasing, and limit visibility for users.

### What’s a good Station ID?
Keep it short and readable (≤ 6 characters). Examples: `ST01`, `MILL`, `DEBURR`, `HQ-CA`.

### Can I add multiple Notification Emails?
Yes. Separate each address with a comma: `user1@shop.com, user2@shop.com`.

### What gets included in Undone Transaction emails?
A brief note that a transaction was undone, including the basic who/what/when details.

### How do AutoScrap days relate to item types?
AutoScrap applies to **semi-consumable** item types that are configured for scrapping. Set the days here, and ensure item types are configured correctly under [Items](xref:items).

### How do I save a new station?
After entering the required details, click **Save**. The station will be added and available for use immediately.


---

## Related Topics
- [Stations/Station Groups](xref:stations)
- [Items (Item Types)](xref:items)
