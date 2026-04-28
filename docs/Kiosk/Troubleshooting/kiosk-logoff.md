---
uid: kiosk.logoff-completely
title: Kiosk / Logoff Completely
---

# Kiosk Logoff Completely

Logging off the kiosk completely allows administrators to **reset the kiosk, verify or change the assigned site, and reconfigure cabinet access**. This process is commonly used during initial setup, site changes, or troubleshooting scenarios.

**Also known as:** *Kiosk Reset*, *Site Reset*, *Full Kiosk Logoff*

---

## When to Log Off the Kiosk Completely

You should perform a full kiosk logoff when:

- The kiosk is logged into the **wrong site**
- The **administrator or site champion has changed**
- Cabinets need to be **reassigned**
- The kiosk requires a **complete reset or not logging in**

---

## How to Log Off the Kiosk Completely

### 1. Access the Hidden Reset Login

1. Go to the kiosk screen.
2. In the **bottom-left corner**, click the hidden reset area.
   - This button is invisible; click in the bottom-left corner even though nothing appears.
3. A reset text box will display.

---

### 2. Initiate the Site Reset

1. Click inside the reset text box.
2. Type **`Millen`**  
   - This entry **is case sensitive**.
3. Click **Submit**.

The kiosk screen will darken and prompt you for reset login credentials.

---

### 3. Sign Back In (Administrator Required)

1. Enter the **Login Email** of a user with **administrator rights** in the FTS Backend.
2. Enter the corresponding **Password**.
3. Click **Login**.

This action restarts the kiosk and returns it to the site login workflow.

---

## Select the Correct Site

1. Click **Select** next to your site.

If you have access to multiple sites, use the search field to narrow the results.

---

## Kiosk Setup: Assign Cabinets

After selecting the site, configure cabinet access:

1. For each cabinet, choose one of the following:
   - **Vend** – Enables vending from the cabinet
   - **View Only** – Displays inventory without allowing vending  
     *(Useful for viewing cabinets at other locations)*
2. Click **Select Cabinets** to activate the kiosk.
3. **Recommended setting:**  
   - Auto Logout Time: **1 minute**
   - If using a touchscreen you can **Enable Virtual Keyboard**

The kiosk will now be assigned only to the selected cabinets.

---

## Restored Kiosk Behavior

Once setup is complete:

- Users can sign in with their credentials
- Employees can enter their information and click **Submit**
- The kiosk will allow access to items assigned to the selected site and cabinets

---

## Related Topics

- [Issue Items / Checkout Inventory](xref:kiosk.issue-items)
- [Cabinets](xref:cabinets)
- [Stations](xref:stations)
- [Kiosk](xref:kiosk)
- [Kiosk Troubleshooting](xref:kiosk.vending.troubleshooting)