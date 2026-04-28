---
uid: installation.cabinet
title: Cabinets / Installation and IP Configuration
---

# Cabinet Installation

Installing and configuring all locking cabinets ensures proper communication between the kiosk (Raspberry Pi) and cabinet hardware. This process includes physical setup, IP configuration, and registering the cabinet in FTS.

**Also known as:** *Cabinet Setup*, *Cabinet IP Assignment*

---

## How to Install and Configure a Locking Cabinets

### 1. Required Hardware

Before beginning installation, verify you have the following:

- Raspberry Pi (kiosk)
- Locking cabinet(s)
- USB Ethernet adapter
- Network switch (required for multiple cabinets)
- Ethernet cables
- Laptop for configuration if needed

---

### 2. Physical Network Connections

There are two supported connection methods depending on the number of cabinets.

#### Option A: Single Cabinet (No Switch)

1. Plug the **USB Ethernet adapter** into the Raspberry Pi.
2. Connect the cabinet Ethernet cable directly to the USB Ethernet adapter.
3. Plug the customer’s wired Ethernet directly into the Raspberry Pi.

#### Option B: Multiple Cabinets (Using a Switch)

1. Plug the customer’s Ethernet directly into the Raspberry Pi.
2. Connect the **USB Ethernet adapter** to the Raspberry Pi.
3. Connect the USB Ethernet adapter and all cabinets to the provided switch.

---

### 3. Default Cabinet IP Addresses

All cabinets ship with a default IP address that must be used during initial setup:

- **DLS Cabinets:** `192.168.127.107`
- **Lockers:** `192.168.127.109`
- **Maxi Unit** `192.168.127.100`

These IP addresses are entered into FTS as the **Device ID**.

---

### 4. Add Cabinet Device ID in FTS

1. Open FTS.
2. Navigate to **Cabinet Module**.
3. Select the gear icon on the cabinet you will be adding the IP address to
4. Select the type of cabinet you are connecting to the kiosk
5. Enter the cabinet IP address as the **Device ID**.
6. Save the configuration.

---

### 5. Configure IP Addresses (Multiple Cabinets Only)

If installing more than one cabinet, each cabinet must have a **unique IP address**.


### Option A: Updating IP Address with a laptop


1. Connect cabinet to Laptop with ethernet cable
2. Laptop and cabinet must be on subnet `192.168.127.xxx`
- Laptop IP must be **below `.100`**  
  - Example: `192.168.127.99`
3. Open Lantronix software
4. Computer will scan for cabinet that is connected
5. Select **xPort-05**
6. Select **Assign IP** from menu across the top
7. Input new IP address 
- Cabinet IP must be **above `.100`**  
  - Example: `192.168.127.108`
8. Hit **OK** at bottom 
9. Select **Assign IP**
10. Once done hit **Finish**

---


### Option A: Updating IP Address Using the Kiosk


Log into the to the administrator side of the kiosk

- Refer to [Kiosk Wifi Setup](xref:kiosk.setup-wifi) to access the desktop

1. Once on the desktop **Open** a browser
2. Put in the IP address of the cabinet you are updating
   - Example: `192.168.127.107`
3. Just hit **Enter** on the username and password screen no infomation is required
4. Once on the Lantronix site **select Network**
5. Cabinet IP must be **above `.100`** then **select OK**
   - Example: `192.168.127.108`
6. Select **Apply Settings** on the left hand side
7. You will see a message that the cabinet has reconnected


---

### 6. Access Raspberry Pi Network Settings

1. Open the Raspberry Pi desktop.
- Refer to [Kiosk Wifi Setup](xref:kiosk.setup-wifi) to access the desktop
2. Select the **Wi‑Fi icon** or **two blue arrows**.
3. Choose **Advanced Options → Edit Connections**.
4. Double‑click:
   - **Wired Connection 1** (This is used for customer internet)
   - **USB Ethernet** (This will be preconfiged with IP address of `192.168.127.99`)
   - **Wi-Fi** (This is if you are connecting to the customer wireless network)

---

## Related Topics
- [Cabinets](xref:cabinets)
- [Creating a New Cabinet](xref:cabinets.add)
- [Kiosk Wifi Setup](xref:kiosk.setup-wifi)
- [Network Requirements](xref:installation.fts.network-requirements)