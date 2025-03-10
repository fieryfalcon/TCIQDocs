**User Management Module - User Manual**

---

## **1. User Management Module**
The **User Management Module** in **Teams Core IQ** provides a centralized interface to **view, manage, and track users within an organization's Microsoft Teams tenant**. It allows administrators to **assign numbers, update policies, manage call handling settings, monitor voicemail configurations, and review Azure AD users.**

The **User Management Module** consists of the following sub-modules:
- **User Info**
- **Call Handling**
- **Voicemail**
- **AD Users**

---

### **1.1 User Info**
The **User Info** sub-module provides a detailed list of **all users** in the tenant along with key details related to their telephony setup.

#### **1.1.1 Overview Section**
At the top of the **User Info Page**, three summary tiles display:
- **Total Users** – The total number of users in the tenant.
- **Voice Enabled Users** – Users who have been assigned a phone number.
- **Unassigned Users** – Users who do not have an assigned phone number.

#### **1.1.2 Viewing User Details**
Each user is listed in a **table** containing:
- **Display Name** – The full name of the user.
- **User Principal Name (UPN)** – The user's unique Microsoft identifier.
- **Phone Number Assigned** – If assigned, displays the **phone number linked to the user**.
- **Account Type** – Indicates whether the user is:
  - **A standard user**
  - **A resource account**
- **Phone Number Type** – Identifies whether the number is:
  - **Direct Routing**
  - **Operator Connect**
- **Location Details**:
  - **City**
  - **Country**
- **Department** – Displays the user's department.
- **Teams Calling & Routing Policies**:
  - **Teams Calling Policy**
  - **Voice Routing Policy**
  - **Caller ID Policy**
  - **Emergency Call Routing Number**
  - **Tenant Dial Plan Policy**
  - **Voicemail Policy**
  - **Dial-out Policy**

#### **1.1.3 Managing Users**
Each user entry provides the following management options:
- **Assign / Unassign Phone Number**
  - Clicking **Assign** allows the admin to **select and assign an available phone number**.
  - Clicking **Unassign** removes the phone number from the user.
- **Update Calling Policies**
  - Clicking **Update Policy** opens a panel where admins can modify **Teams Calling Policies, Voice Routing Policies, Caller ID Policies, and more.**

#### **1.1.4 Bulk User Actions**
- **Bulk Enable / Auto Assign Users** – Allows uploading a **CSV file** to enable or assign numbers to multiple users at once.
- **CSV Format Requirements**:
  - **Phone Number**
  - **Display Name**
  - **User Principal Name**

#### **1.1.5 Searching & Filtering Users**
- **Filter by:**
  - **Number Type** (Direct Routing / Operator Connect)
  - **Department**
  - **Country**
- **Search by:**
  - **User Name**
  - **Phone Number**
  - **User Principal Name (UPN)**

#### **1.1.6 Exporting & Syncing User Data**
- **Export User List** – Downloads all user details as a **CSV file**.
- **Delta Sync** – Click **Sync** to refresh user data and **retrieve the latest updates**.

---

### **1.2 Call Handling**
The **Call Handling** sub-module provides insights into how **calls are managed for each user**.

#### **1.2.1 Viewing Call Handling Details**
Each user entry contains the following call settings:
- **Delegators** – Lists users who can manage calls on behalf of the user.
- **Group Member Details** – Displays group-based call handling settings.
- **Call Group Targets & Details** – Defines call distribution among group members.
- **Call Group Delay** – Configured delay time before transferring a call.
- **Call Group Overflow Handling** – Specifies how overflow calls are handled.
- **Forwarding Target & Type** – Determines call forwarding rules (if applicable).

#### **1.2.2 Filtering, Searching & Exporting**
- **Search by User Name or UPN**.
- **Filter based on call handling types**.
- **Export call handling settings as CSV**.

> **Note:** Call Handling settings are **read-only** and cannot be modified from this module.

---

### **1.3 Voicemail**
The **Voicemail** sub-module provides **visibility into users' voicemail settings**, allowing admins to track how voicemails are configured.

#### **1.3.1 Viewing Voicemail Settings**
For each user, the following voicemail details are displayed:
- **Greeting Prompts** – Indicates whether a user has configured a voicemail greeting.
- **Out of Office Greeting** – Specifies if an out-of-office voicemail greeting is active.
- **Automatic Greeting** – Indicates if automatic greeting messages are enabled.
- **Call Answering Rules** – Determines how calls are handled when reaching voicemail.

#### **1.3.2 Filtering, Searching & Exporting**
- **Search for users by Name or UPN**.
- **Filter users based on voicemail settings**.
- **Export voicemail data as CSV**.

> **Note:** Voicemail settings are **read-only** and cannot be modified from this module.

---

### **1.4 AD Users**
The **AD Users** sub-module provides a **synchronized list of all users** from **Azure Active Directory (AAD)**.

#### **1.4.1 Viewing AD Users**
- Displays all **users from the organization's Azure AD directory**.
- Allows **tracking and monitoring user details**.

#### **1.4.2 Searching & Filtering AD Users**
- **Search by Name or UPN**.
- **Filter users by department, location, or other attributes.**

> **Note:** This section is **read-only**; modifications must be made directly within the **Teams Admin Center or Azure AD**.

---

## **Conclusion**
The **User Management Module** in **Teams Core IQ** simplifies **user tracking, telephony management, and call handling analysis**. With structured filtering, bulk actions, and detailed reporting, organizations can efficiently manage their **Teams tenant users and communication policies.**

For further assistance, refer to **Teams Core IQ Support** or consult internal documentation.

