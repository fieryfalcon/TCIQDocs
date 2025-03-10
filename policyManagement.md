**Policy Management Module - User Manual**

---

## **1. Policy Management Module**
The **Policy Management Module** in **Teams Core IQ** allows administrators to **review, compare, and track policy changes** for individual users and the entire tenant. While this module does not support creating or modifying policies, it provides a **backup and comparison system** to track changes over time.

The **Policy Management Module** consists of the following key sections:
- **Backing Up and Downloading Policies**
- **Comparing Policies**
- **Viewing Individual Policy Details**

---

### **1.1 Backing Up and Downloading Policies**

Since **policy configurations** frequently change, administrators can **backup the existing policies** for future reference.

#### **1.1.1 Backing Up Policies**
1. Click on the **"Backup"** button (top-right corner of the Policy Management Page).
2. The system will create a **snapshot of the current policies**.
3. The backup is stored within the system for future comparison.

#### **1.1.2 Downloading Policies as CSV**
- Click **"Download CSV"** to export the current policy configurations.
- The CSV file provides a **detailed list of policies**, categorized by type and country.
- This helps in **tracking changes over time** and **auditing policy configurations.**

---

### **1.2 Comparing Policies**

Whenever there is a **change in any policy**, the system allows administrators to **compare** the current configuration with the last backed-up version.

#### **1.2.1 How to Compare Policies**
1. Click the **"Compare"** button on a policy card.
2. The system will **highlight changes** made since the last backup.
3. Users can review **modifications to dial plans, voice routing, emergency calling, and other policies.**

#### **1.2.2 Tracking Policy Changes**
- If there is a **change in any policy**, the system flags it in the **comparison view**.
- This helps administrators **identify updates made to policies** and **ensure compliance.**

---

### **1.3 Viewing Individual Policy Details**

Each policy type can be **individually reviewed** for further details.

#### **1.3.1 How to View Policies**
1. Click **"View"** on any policy card.
2. The page will display **country-specific policies** with configuration details.
3. Users can **review the latest settings** applied to each policy.

#### **1.3.2 Types of Policies in Policy Management**
The module provides **read-only access** to various Microsoft Teams policies. Below is a brief overview of each policy type:

##### **1. Voice Routing Policy**
- Defines **how outbound calls are routed** within Microsoft Teams.
- Specifies **which PSTN routes** are used for different users or groups.

##### **2. Dial Plan Policy**
- Configures **how phone numbers are interpreted and dialed** within Teams.
- Allows organizations to define **normalization rules and calling behavior**.

##### **3. Tenant Dial Plan**
- Similar to **Dial Plan Policy**, but applied at the **tenant level**.
- Ensures **uniform dialing rules** across all users.

##### **4. Emergency Calling Policy**
- Configures **how emergency calls are handled** within the organization.
- Specifies **emergency numbers, routing, and notification settings**.

##### **5. Meeting Policies**
- Defines **how Teams meetings are configured**.
- Controls features like **recording, screen sharing, and participant permissions**.

##### **6. Messaging Policies**
- Manages **chat and messaging settings** for users.
- Allows admins to enable or disable **chat history, file sharing, and priority messaging.**

##### **7. Teams App Setup Policy**
- Determines **which apps are available** in Teams for users.
- Controls **pre-installed apps and permissions**.

##### **8. Live Events Policy**
- Governs **how live events are managed** in Microsoft Teams.
- Controls **who can create and broadcast live events**.

---

## **Conclusion**
The **Policy Management Module** in **Teams Core IQ** helps administrators **track and compare policy changes efficiently**. With **backup, comparison, and review functionalities**, organizations can **ensure compliance, maintain consistency, and audit policy changes seamlessly**.

For further assistance, refer to **Teams Core IQ Support** or consult internal documentation.

