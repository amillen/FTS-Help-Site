---
uid: cabinets.add
title: Adding/Creating/Setting Up a Cabinet
---

# Creating a New Cabinet (Adding a Cabinet)

**Also known as:** *Add Cabinet*, *New Cabinet*, *Set Up Cabinet*

To add a new cabinet to the FTS system, follow these steps:

1. Navigate to the **Cabinets** module from the [Dashboard](xref:dashboard).
2. Click on the **Create New Cabinet** link.
3. Fill in the cabinet details:
   - **Station** (choose the [Station](xref:stations) this cabinet belongs to from the dropdown list).
   - **Cabinet ID** (a short identifier, often a number or short code).
   - **Description** (clear description so everyone knows what the cabinet is used for).
   - **Cabinet Type** (see [Cabinet Types](xref:cabinets.types) for options).
   - **Device ID** (only for cabinets with locking mechanisms).
4. Click **Save** to add the cabinet.

> **Tip:** Cabinets can be **physical** (e.g., Lista toolbox, vending drawer) or **virtual** (e.g., coolant shed, warehouse racking).  
> Virtual Cabinets must use the cabinet type **Traditional – No Lock**.

---

## Cabinet Type Options

- **Traditional – No Lock**  
  Cabinet or location is unmanaged and not controlled by a locking mechanism.  
  - Use this for **Virtual Cabinets** (non-physical storage areas).  

- **Westlock**  
  Cabinet controlled by the FTS Cloud locking mechanism (Nimbis).  

- **Bulk**  
  Bulk cabinet controlled by the FTS Cloud bulk locking mechanism (Nimbis).  

> For more details, see [Cabinet Types](xref:cabinets.types).

---

## Device ID

- A unique identifier printed on the bottom of the FTS Cloud Control Box.  
- Required for cabinets with locking mechanisms (**Westlock** or **Bulk**).  
- Not required or shown for **Traditional – No Lock** cabinets.  

---

## FAQ

### What is a good Cabinet ID?
Keep it short and easy to recognize, such as `CAB01`, `TOOLBOXA`, or `VEND01`.

### Which Cabinet Type should I use for a Virtual Cabinet?
Always use **Traditional – No Lock**.

### Where do I find the Device ID?
Look on the bottom of the FTS Cloud Control Box. You only need this if the cabinet has a locking mechanism.

### Can I assign a cabinet to more than one station?
No. Each cabinet belongs to exactly one [Station](xref:stations).

---

## Related Topics
- [Cabinets/Virtual Cabinets (Overview)](xref:cabinets)
- [Stations/Station Groups](xref:stations)
- [Creating a New Station](xref:stations.add)
- [Cabinet Types](xref:cabinets.types)
