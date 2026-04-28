---
uid: kiosk.setup-wifi
title: Kiosk / Setup / WiFi Configuration
---

# Kiosk WiFi Setup

This guide explains how to configure **WiFi on a kiosk**.  
**Skip this process if the kiosk is already connected via ethernet.**

---

## How to Set Up WiFi

### 1. Access the Terminal

1. On the kiosk keyboard, press **Ctrl + Alt + F3**.
2. When prompted for login, enter:

   - **Username:** `wifi`
   - **Password:** `setupwifi`  
     *(Note: the password will not appear while typing)*


After logging in, you will see a command prompt similar to:

wifi@ftsware-vend:~$

1. Type `startx`
2. Press **Enter**

This launches the graphical desktop environment.

---

### 2. Connect to a WiFi Network

1. In the **top-right corner**, click the **network / WiFi icon**.
2. Select the desired **WiFi network**.
3. Enter the **WiFi password** when prompted.
4. Confirm the connection.

---

### 3. Reboot the Kiosk

1. Click the **raspberry icon** in the **top-left corner**.
2. Select **Shutdown**.
3. Choose **Reboot**.

The kiosk will restart and connect using the configured WiFi network.

---

## Notes

- These steps are only required for **wireless kiosks**.
- Ethernet-connected kiosks do **not** require WiFi configuration.
- If WiFi does not connect after reboot, repeat the steps and verify the network password.


---

 ## Related Topics

- [Kiosk](xref:kiosk)
- [Kiosk Troubleshooting](xref:kiosk.vending.troubleshooting)
- [Kiosk Logoff](xref:kiosk.logoff-completely)