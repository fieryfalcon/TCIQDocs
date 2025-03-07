**Resource Account Module - User Manual**

---

## **1. Resource Account Module**

The **Resource Account Module** in **Teams Core IQ** allows organizations to **create, manage, and export resource accounts** within **Microsoft Teams**. Resource accounts are specialized, non-user accounts designed to represent system resources such as **Auto Attendants, Call Queues, or Meeting Rooms**. These accounts provide a unique identity for services within Teams.

The **Resource Account Module** consists of two main sections:

- **Managing & Exporting Resource Accounts**
- **Creating a New Resource Account**

---

### **1.1 Managing & Exporting Resource Accounts**

Users can **view, manage, and export** existing resource accounts from the **Resource Account Management Page**.

#### **1.1.1 Viewing Resource Accounts**

- The **table displays key information** about each resource account:
  - **Display Name** – Name of the resource account.
  - **User Principal Name (UPN)** – The unique identifier for the resource account.
  - **License Status** – Indicates whether the account is **licensed** or **unlicensed**.
  - **Phone Number Assigned** – Shows the **phone number** linked to the resource account (if assigned).
  - **Account Type** – Defines whether the resource account is:
    - **Call Queue**
    - **Auto Attendant**
    - **Unassigned** (Idle Resource Account)
  - **Assigned Call Queue/Auto Attendant** – Displays the associated **Auto Attendant or Call Queue**.

#### **1.1.2 Identifying Idle Resource Accounts**

- Resource accounts that are **not assigned** to a **Call Queue or Auto Attendant** are flagged with a **red indicator**.
- These flagged accounts should be **reviewed and assigned** accordingly.

#### **1.1.3 Managing Resource Accounts**

Users can manage resource accounts through the **Action Menu (three-dot button)**:

- **Assign a Phone Number** – Attach a new phone number to the resource account.
- **Unassign a Phone Number** – Remove an existing phone number.
- **Assign a Call Queue/Auto Attendant** – Link the resource account to a call queue or auto attendant.
- **Remove Call Queue/Auto Attendant** – Detach an assigned queue or auto attendant from the resource account.

#### **1.1.4 Synchronizing Resource Accounts**

- Click the **Sync Button** (near the Resource Accounts title) to **retrieve the most recent data** from Microsoft Teams.
- Ensures that all resource account data is **up-to-date**.

#### **1.1.5 Searching & Filtering Resource Accounts**

- **Search Functionality**:
  - Allows users to **quickly locate** a specific resource account.
  - Search by **Display Name** or **User Principal Name (UPN)**.
- **Filter Options**:
  - Filter by **Account Type**:
    - Show only **Call Queue Resource Accounts**.
    - Show only **Auto Attendant Resource Accounts**.

#### **1.1.6 Exporting Resource Accounts**

- Users can export resource account data as a **CSV file**.
- The exported file includes:
  - **Resource Account Name**
  - **User Principal Name**
  - **License Status**
  - **Assigned Phone Numbers**
  - **Account Type**
  - **Linked Call Queue/Auto Attendant**
- Useful for **reporting, auditing, and backup purposes**.

---

### **1.2 Creating a Resource Account**

To create a new **Resource Account**, follow these steps:

#### **1.2.1 Accessing the Create Resource Account Form**

1. Click on **"Create Resource Account"**.
2. A **dialog box** will appear prompting for input fields.

#### **1.2.2 Entering Resource Account Details**

- **Display Name** – Provide a name for the resource account.
- **User Principal Name (UPN)** – Enter a unique identifier.
- **Domain** – Select the domain under which the resource account will be created.
- **Account Type** – Choose one of the following:
  - **Auto Attendant**
  - **Call Queue**
  - **Unassigned** (Idle Resource Account)

#### **1.2.3 Finalizing the Resource Account Creation**

1. Click **"Create"** to finalize the process.
2. The resource account will be added to the **Resource Account List**.
3. Assign the resource account to an **Auto Attendant or Call Queue** (if applicable).
4. Assign a **Phone Number** (if required).

---

## **Conclusion**

The **Resource Account Module** in **Teams Core IQ** streamlines the management of **Microsoft Teams Resource Accounts**, ensuring **proper delegation, organization, and tracking**. This guide covered **creating, managing, and exporting resource accounts** efficiently.
