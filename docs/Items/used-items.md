---
uid: items.used-items
title: Items / Used Items
---

# Used Items

Used Items allow inventory that has been checked out to be **returned as used**, tracked separately from new inventory, and optionally **auto‑scrapped after a defined period**. This feature helps extend tool life, control access, and maintain accurate inventory counts.

**Also known as:** *Returned Used Items*, *Semi‑Consumable Used Inventory*

---

## What Are Used Items?

Used Items are created by copying an existing item and designating it as a **used version** (example: labeled with `-USED`).  
When a new item is checked out and later returned, the system can reclassify it as a **used item**, making it available for future checkout based on defined rules and access controls.

---

## How to Create Used Items

### 1. Open the Items Module

1. From the **Dashboard**, click **Items**.
2. Locate the item you want to convert:
   - Scroll through the item list, or
   - Use the **search bar** to narrow results.

---

### 2. Change the Item Type

1. Select the item.
2. Click **Item Type**.
3. Change the type to **Semi‑Consumable**.
4. Click **Update Item**.

This enables additional configuration options required for used items.

---

### 3. Enable Used Item Options

After updating the item type:

- Check **Enable Used** to allow items to be returned as used.
- (Optional) Check **Auto Scrap** to automatically scrap items after a set time (default: 30 days).
- Click **Update Item** to save changes.

> ***Tip*** The **Auto Scrap** timeframe can be changed under the **Station module** 

---

### 4. Create the Used Item Copy

1. Click **Item Copy** icon next to the **Item_id** box.
2. The system creates a duplicate item and you can add **“-USED”** to the name.
3. Click **Create Item**.

The used item will receive its own **item ID**.

---

## Access Control (Optional)

Access Control can require certain employees to **issue a used item before accessing a new one**.

### Configure Access Control

1. Click the **Access Control Key** on the used item.
2. Use **Quick Rule Edit** to:
   - Select employees
   - Apply restrictions
3. Click **OK** to save.

This feature is optional but commonly used to reduce new‑item consumption.


---

## Frontend Kiosk Experience

### Item Visibility

- The **new item** appears in the kiosk with a **Returnable** tag.
- The **used item** does not appear until an item has been returned as used.

---

### Returning an Item

1. Select **Return Item** at the kiosk.
2. Enter the quantity being returned.
3. Choose **Return As**:
   - **Green** – New
   - **Yellow** – Used
   - **Red** – Scrap
4. Selecting **Yellow (Used)** automatically maps the return to the `-USED` item ID.

---

### Bin Location Assignment

- If no bin location is assigned, the system prompts for one during return.
- Once the used item is issued again, the bin becomes available for reuse.
- (Optional) A permanent bin location can be assigned through the **Item Module** or **Location Module**

---

## Next Time an Item Is Issued

When an employee checks out the item again:

- Both **New** and **Used** options may be available.
- If Access Control is enabled, restricted employees will be required to **issue the used item first**.

---

## Related Topics

- [Issue Items](xref:kiosk.issue-items)
- [Items](xref:items)
- [Stations](xref:stations)
- [Access Control](xref:access-controls)
- [Add an Item to a Location Through Item Module](xref:items.assign-location)
- [Add an Item to a Location Through the Location Module](xref:cabinet.add-item-location)