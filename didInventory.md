**DID Management Module - User Manual**

---

## **1. DID Management Module**
The **DID (Direct Inward Dialing) Management Module** in **Teams Core IQ** allows organizations to **manage, track, and configure DID numbers** efficiently. These numbers enable external callers to reach internal users or specific endpoints directly, bypassing a central reception or switchboard.

The **DID Management Module** consists of four key sub-modules:
- **DID Inventory**
- **DID Treatment**
- **Block Number / Rules**
- **DID Tags**

---

### **1.1 DID Inventory**
The **DID Inventory** displays all the DID numbers available within the organization, providing an overview of **total numbers, reserved numbers, and unassigned numbers**.

#### **1.1.1 Overview & Syncing**
- The **top section** displays a **summary**:
  - **Total Numbers** – The total count of DID numbers in the system.
  - **Reserved Numbers** – Numbers marked as reserved.
  - **Unassigned Numbers** – Numbers currently not in use.
- **Sync Button**: Click the **"Sync"** button to refresh and fetch updated DID data.
- **Export Button**: Download the entire DID inventory as a **CSV file**.
- **Add New Number Button**: Users can **manually add numbers** or **bulk upload a CSV file**.

#### **1.1.2 Adding DID Numbers**
1. Click **"Add New Number"**.
2. Select either:
   - **Add Numbers Manually**
   - **Upload DID Numbers CSV** (for bulk addition)
3. If adding manually, enter the following details:
   - **Country & City**
   - **Department**
   - **Provider** (Organization providing the DID number)
   - **Number Range (Start & End Number)**
   - **Number Type** (Direct Routing / Operator Connect)
   - **Status** (Reserved / Unused)
4. Click **"Add"** to finalize.

#### **1.1.3 Viewing & Filtering DID Numbers**
- The DID Inventory lists numbers across **multiple pages** (e.g., 250+ records per page).
- **Filters & Search Options**:
  - Filter by **Tags** (Refer to **1.4 DID Tags**).
  - Filter by **Status** (User Assigned, Reserved, Unused).
  - Search for numbers based on **User Principal Name (UPN)** or **DID Number**.

#### **1.1.4 DID Number Fields**
Each DID Number entry includes:
- **Provider** – The service provider for the number.
- **Type** – The type of number (**Calling Plan, Direct Routing, or Operator Connect**).
- **Assigned Department** – The department to which the number is linked.
- **Status**:
  - **User Assigned** – Number is actively assigned to a user.
  - **Reserved** – Number is reserved for future use.
  - **Unused** – Number is available but unassigned.
- **User Principal Name (UPN)** – If assigned, the UPN of the user using this number.

#### **1.1.5 DID Tags (Linked to 1.4 DID Tags)**
- Users can **add, edit, and manage tags** for each DID number (Refer to **1.4 DID Tags**).
- Tags allow for **quick filtering and categorization**.

#### **1.1.6 Managing DID Numbers**
- **Edit Button** – Modify status, assigned user, or tags.
- **Delete Button** – Remove a DID number from the inventory.

---

### **1.2 DID Treatment**
The **DID Treatment** sub-module provides a **read-only view** of all configured DID treatments.

#### **1.2.1 Viewing DID Treatments**
- Each entry includes:
  - **Treatment ID**
  - **User Principal Name (UPN)**
  - **DID Pattern**
  - **Target Type**
- **Filters & Search**:
  - Filter by **Target Type**.
  - Search by **DID Pattern** or **Treatment ID**.

#### **1.2.2 Exporting DID Treatments**
- Users can **export DID treatments** as a **CSV file** for auditing purposes.
- Since this is a **read-only module**, no editing or addition is allowed.

---

### **1.3 Block Number / Rules**
The **Block Number / Rules** sub-module allows users to **create, manage, and edit blocking rules** for specific numbers.

#### **1.3.1 Viewing Blocked Numbers**
- The table displays:
  - **Blocking Rule Name**
  - **Description** (e.g., "Block all numbers starting with 185")
  - **Blocking Pattern** – Defines the format of numbers to be blocked.

#### **1.3.2 Managing Blocking Rules**
- **Add New Rule**:
  1. Click **"Add New Rule"**.
  2. Enter **Rule Name & Description**.
  3. Define the **Number Pattern** to be blocked.
  4. Click **"Save"** to finalize.
- **Edit / Delete Blocking Rules**:
  - Users can **modify or delete** existing blocking patterns.
- **Filtering & Search**:
  - Search blocked numbers by pattern or rule name.
  - Filter blocking rules for quick navigation.
- **Sync Button**:
  - Click the **"Sync"** button to update and fetch the latest blocking rules.

---

### **1.4 DID Tags**
The **DID Tags** sub-module allows users to **create and manage tags** for DID numbers.

#### **1.4.1 Managing DID Tags**
- All tags created within **DID Inventory (1.1.5)** are listed here.
- Tags help **organize DID numbers** and improve filtering efficiency.

#### **1.4.2 Creating a New DID Tag**
1. Click **"Add New Tag"**.
2. Enter **Tag Name & Description**.
3. Choose a **Color Code** for easy identification.
4. Click **"Save"** to create the tag.

#### **1.4.3 Using DID Tags in DID Inventory** (Linked to **1.1.5**)
- Tags created here can be **applied to DID numbers** in **DID Inventory**.
- Filtering in **DID Inventory (1.1.3)** can be performed using these tags.

---

## **Conclusion**
The **DID Management Module** in **Teams Core IQ** provides an **efficient solution for managing, filtering, and organizing DID numbers**. With powerful tagging, blocking, and inventory tracking capabilities, organizations can effectively **monitor and optimize their direct inward dialing numbers.**


