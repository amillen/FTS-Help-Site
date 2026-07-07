---
uid: installation.cabinet.Troubleshooting
title: Cabinets / Installation / Troubleshooting
---
# Cabinet Drawers are not Opening

After completing the installation and configuration of all locking cabinets, verify communication between the kiosk (Raspberry Pi) and the cabinet hardware. If communication cannot be established, perform the troubleshooting procedures outlined below. These steps resolve the most common communication issues encountered during installation.

--- 

## Step 1: Check Physical Connections

* Verify that all cables are securely connected.
* Confirm the cabinet is properly connected to the kiosk.
* Inspect for any loose, damaged, or disconnected cables.

---

## Step 2: Verify Network Connectivity

1. Go to the kiosk desktop.
    >***Accessing the [Kiosk Desktop](xref:kiosk.setup-wifi)***
2. Open the Terminal application.
3. Ping the cabinet to confirm communication between the kiosk and cabinet.

### Example


`ping <cabinet_ip_address>`
   >***You are looking for packet details to confirm connection***

### If the Ping Fails

* Recheck network cables and connections.
* Verifying the cabinet IP address is correct.
* Confirm the kiosk and cabinet are on the same network.

---

## Step 3: Test Cabinet with Kiosk Wizard

1. Open the Kiosk Wizard application on the desktop of the kiosk.
    >***If you don't see this icon you will need to upgrade your version of FTS***
2. Verify you can connect to the cabinet's IP address.
3. You will need to ensure you have the correct IP Address showing at the top then hit `Enter`.
4. Select the drawer you want to open with the arrows on the keyboard.
5. Hit `Enter` on the keyboard to fire the selected drawer.

----

## Step 4: Use FTS Diagnostics

1. Log in to:
* `ftsware.com`
2. Select the site you are working on.
3. Select the `Cabinet` Module.
4. Locate the cabinet in the cabinet list.
5. Select the gear icon next to the cabinet.
6. Click: `Edit`
7. Use the diagnostic tool to verify connection:
* Hit `Verify` and `Connect`
* Use the `Drawer` drop down to pick the drawer you would like to unlock
* After selecting the drawer hit `Unlock`

### Expected Result

* The cabinet should respond to the unlock commands and the drawer selected should unlock and light up.

---

## Step 5: Test with Cabinet Utility or Matrix Utility

If the cabinet still does not function after completing the previous steps:

Use:

* Cabinet Utility or Matrix Utility software on a computer.

***These tools help determine whether the issue is caused by:***

* An FTS software problem
* A Lantronix communication issue

---
## Escalation

* If you have completed all troubleshooting steps and are still unable to resolve the issue, or if the unit functions properly in Cabinet Utility or Matrix Utility, contact Support for further assistance.

---
## Related Topics
- [Cabinets](xref:cabinets)
- [Kiosk Wifi Setup](xref:kiosk.setup-wifi)
- [Network Requirements](xref:installation.fts.network-requirements)
- [Cabinet Installation](xref:installation.cabinet)