---
uid: cabinets.types
title: Cabinet Types/Traditional/Westlock/Bulk
---

# Cabinet Types

Cabinets in FTS can be one of several types. The cabinet type determines whether the cabinet is physical or virtual, and whether it is controlled by a locking mechanism.

**Also known as:** *Cabinet Categories*, *Cabinet Type Options*

---

## Traditional – No Lock
A cabinet or location that is **unmanaged** and not controlled by any locking mechanism.  
- Use this for **Virtual Cabinets** (e.g., coolant shed, warehouse racking, open storage).  
- No Device ID is required.

---

## Westlock
A cabinet controlled by the **FTS Cloud locking mechanism (Nimbis)**.  
- Requires a **Device ID** from the control box.  
- Ensures only authorized users can access the cabinet.

---

## Bulk
A bulk cabinet controlled by the **FTS Cloud bulk locking mechanism (Nimbis)**.  
- Requires a **Device ID** from the control box.  
- Designed for larger-volume storage where bulk access is controlled.

---

## Matrix DLS
A cabinet controlled by the **Matrix** Ethernet controller.  
- Requires a **Device ID** being the IP address of **Matrix** Ethernet controller.  
- Ensures only authorized users can access the cabinet.

## Option A: 13-Drawer Cabinet


### Storage Options
- **12 Drawers**: 3” high each  
- **1 Drawer**: 4” high

### Specifications
- **Electronically Locked Drawers**
- **Manual Override** in case of power failure
- **Direct Network Connection**
- **Single Power Supply**: 110–230V
- **Cabinet Color**: Black
- **Width**: 40”
- **Height**: 48”
- **Depth**: 28.5”
- **Maximum Load per Drawer**: Approx. 440 lbs

## Option B: 8-Drawer Cabinet

### Storage Options
- **3 Drawers**: 4” high each  
- **4 Drawer**: 5” high
- **1 Drawer**: 8” high


### Specifications
- **Electronically Locked Drawers**
- **Manual Override** in case of power failure
- **Direct Network Connection**
- **Single Power Supply**: 110–230V
- **Cabinet Color**: Black
- **Width**: 40”
- **Height**: 48”
- **Depth**: 28.5”
- **Maximum Load per Drawer**: Approx. 440 lbs

---


## Eco Locker
A cabinet controlled by the **Matrix** Ethernet controller.  
- Requires a **Device ID** being the IP address of **Matrix** Ethernet controller.  
- Ensures only authorized users can access the cabinet.

## Option A: 12-Pod Eco Locker (Matrix DLS)


### Storage Options
- **12 -Door lockers are configurable to accommodate larger items

### Specifications
- **Electronically Locked Drawers**
- **Manual Override** in case of power failure
- **Direct Network Connection**
- **Single Power Supply**: 110–230V
- **Cabinet Color**: Black
- **Maximum Load per Pod**: Approx. 75 lbs

## Option B: 21-Pod Eco Locker (Matrix DLS)

### Storage Options
- **21 -Door lockers are configurable to accommodate larger item


### Specifications
- **Electronically Locked Drawers**
- **Manual Override** in case of power failure
- **Direct Network Connection**
- **Single Power Supply**: 110–230V
- **Cabinet Color**: Black
- **Width**: 40”
- **Height**: 48”
- **Depth**: 28.5”
- **Maximum Load per Pod**: Approx. 75 lbs

---

## Matrix Adam DLS
A cabinet controlled by the **Adam** Ethernet controller.  
- Requires a **Device ID** being the IP address of **Adam** Ethernet controller.  
- The Matrix Adam DLS has been discontinued, but is still supported. Use the Matrix DLS for new installations.


### Storage Options
- **3 Drawers**: 4” high each  
- **4 Drawer**: 5” high
- **1 Drawer**: 8” high


### Specifications
- **Electronically Locked Drawers**
- **Manual Override** in case of power failure
- **Direct Network Connection**
- **Single Power Supply**: 110–230V
- **Cabinet Color**: Black
- **Width**: 40”
- **Height**: 48”
- **Depth**: 28.5”
- **Maximum Load per Drawer**: Approx. 440 lbs


---

## Matrix Maxi
A large-capacity cabinet controlled by the **Matrix Ethernet controller**.  
- Requires a **Device ID** (the IP address of the Matrix Ethernet controller).  
- Provides secure access down to the bin level.  

### Storage Options
- **Drawers per cabinet**: 1–12  
- **Drawer heights (net)**: 50mm (2"), 75mm (2.9"), 100mm (3.9"), 125mm (4.9")  
- **Load weight per drawer**: up to 110 lb  
- **Bin configurations**:  
  - 16 bin sizes  
  - 30 drawer options with multiple bin layouts  
  - Maximum **198 bins per drawer**  

### Specifications
- **Cabinet weight** (varies by drawers/auto-locks):  
  - 4 drawers with 4 auto-locks: ~880 lb  
  - 12 drawers: ~600 kg / 1325 lb  
- **Cabinet dimensions**: 1180 mm (47") W × 752 mm (30") D × 1469 mm (58") H  
- **Electrical supply**:  
  - 110 AC ±10% (4.6 A)  
  - 220 AC ±10% (2.2 A)  


---

## Matrix Mini
A small-capacity cabinet controlled by the **Matrix Ethernet controller**.  
- Requires a **Device ID** (the IP address of the Matrix Ethernet controller).  
- Provides secure access down to the bin level.  
- Great for sitting atop a workbench or DLS 4D

### Storage Options
- **Drawers per cabinet**: 1–5
- **Drawer heights (net)**: 50mm (2"), 75mm (2.9"), 100mm (3.9") 
- **Load weight per drawer**: up to 44 lb  
- **Bin configurations**:  
  - 16 bin sizes  
  - 20 drawer options with multiple bin layouts  
  - Maximum **96 bins per drawer**  

### Specifications
- **Cabinet weight** (varies by drawers/auto-locks):  
  - 4 drawers with 4 auto-locks: ~365 lb  
- **Cabinet dimensions**: 860 mm (34") W × 581 mm (23") D × 800 mm (32") H  
- **Electrical supply**:  
  - 110 AC ±10% (4.6 A)  
  - 220 AC ±10% (2.2 A)  


---

## Rapidstock
A cabinet controlled by the **Rapidstock** serial controller.  
- Requires a **Device ID** being the COM port of the **Rapidstock** serial controller.  
- Ensures only authorized users can access the cabinet.

---

## Rapidstock Helix
A helix\coil vending machine controlled by the **Rapidstock** serial controller.  
- Requires a **Device ID** being the COM port of the **Rapidstock** serial controller.  
- Individually dispense product one at a time.

---

## FAQ

### Which cabinet type should I use for a Virtual Cabinet?
Always use **Traditional – No Lock**.

### What is the difference between Westlock and Bulk?
Both are controlled cabinets with Device IDs.  
- **Westlock** is for standard drawer/toolbox style cabinets.  
- **Bulk** is for large-volume storage.

### Do all cabinet types need a Device ID?
No. Only **Westlock** and **Bulk** require a Device ID.  
**Traditional – No Lock** does not.

---

## Related Topics
- [Cabinets (Overview)](xref:cabinets)
- [Creating a New Cabinet](xref:cabinets.add)
- [Stations/Station Groups](xref:stations)
