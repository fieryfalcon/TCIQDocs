**Settings Module - User Manual**

---

## **1. Settings Module**
The **Settings Module** in **Teams Core IQ** provides administrators with the ability to configure key system settings, manage user roles, and integrate external services. The module consists of the following three sub-modules:

- **Organization Details**
- **Integrations**
- **Teams Management**

---

### **1.1 Organization Details**
The **Organization Details** section stores essential information about the organization.

#### **1.1.1 Configuring Organization Details**
Administrators can enter and manage the following information:
- **Organization Name**
- **Industry/Sector**
- **Contact Name (Admin or IT Representative)**
- **Email Address of the Organization**
- **Physical Address**
  - City
  - State
  - Country
  - Postal Code
- **Currency** (for financial and subscription-related details)

All changes made in this section **must be saved** for them to take effect.

---

### **1.2 Integrations**
The **Integrations** sub-module allows users to manage various external service integrations used within the Teams Core IQ platform.

#### **1.2.1 Types of Integrations Available**
Users can configure and update credentials for the following integrations:
1. **Microsoft App Registration** – Manages application authentication and API access.
2. **Microsoft 365 Credentials (for PowerShell Actions)** – Used for running automated scripts.
3. **ServiceNow Integration** – Handles incident and alert notifications.
4. **Azure Communication Services** – Manages voice and messaging functionalities.
5. **EzAIx Network Monitoring Agent** – Enables tracking of network and system performance.

#### **1.2.2 Updating Integration Credentials**
1. Click on the specific integration that needs updating.
2. Enter new credentials or modify existing ones.
3. Click **"Save"** to apply changes.

> **Note:** Changes made in this section will reflect across the platform immediately.

---

### **1.3 Teams Management**
The **Teams Management** section allows administrators to define user access levels and manage permissions.

#### **1.3.1 User Roles and Permissions**
There are three primary user roles:
- **Owner** – Full platform access.
- **Admin** – Restricted read/write access.
- **Manager** – Read-only access.

#### **1.3.2 Assigning Delegations to Users**
Each user can be assigned specific delegations based on:
- **Country Delegation** – Limits access based on country.
- **Department Delegation** – Limits access to a specific department.
- **Call Queue Assignments** – Grants access to selected call queues.
- **Auto Attendant Assignments** – Allows access to specific auto attendants.

#### **1.3.3 Child Element Inclusion**
- Users can opt to **include child elements** of assigned auto attendants.
- This grants access to **nested auto attendants** under a primary auto attendant.

#### **1.3.4 Adding New Users**
1. Click **"Add User"**.
2. Enter user details and assign a role.
3. Configure delegations and permissions.
4. Click **"Save"** to finalize the user addition.

#### **1.3.5 Filtering and Searching Users**
Users can be filtered based on:
- Role (Owner, Admin, Manager)
- Country or Department Delegation
- Call Queue or Auto Attendant Assignments


## **Conclusion**
The **Settings Module** in **Teams Core IQ** provides centralized control over **organization settings, integrations, and user management**. With role-based access, external service configurations, and platform-wide sync capabilities, this module ensures seamless administration and security.

For further assistance, refer to **Teams Core IQ Support** or consult internal documentation.

