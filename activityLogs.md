**Activity Logs Module - User Manual**

---

## **1. Activity Logs Module**
The **Activity Logs Module** in **Teams Core IQ** provides a detailed record of all actions performed on the platform. This enables **admins to review, track, and audit user activities** efficiently.

The activity logs capture all **user-initiated changes, automated background processes, and system events** in a structured format. Logs are categorized based on their **level type**, providing better visibility into different types of actions.

The **Activity Logs Module** consists of the following key features:
- **Exporting Activity Logs**
- **Filtering & Searching Logs**
- **Viewing Detailed Logs**

---

### **1.1 Exporting Activity Logs**
Users can **export activity logs as CSV files** for documentation or auditing purposes.

#### **1.1.1 Export Options**
Upon clicking the **Export Button**, two options are available:
1. **Export Current Page Logs** – Downloads logs only for the currently visible page.
2. **Export All Logs** – Downloads all available activity logs across multiple pages.

These exports help in **offline reviews and reporting** of user activities.

---

### **1.2 Filtering & Searching Logs**
To efficiently locate specific logs, the module offers **multiple filtering and search options**.

#### **1.2.1 Filter by Log Level Type**
Each activity log entry is classified under a **specific level type**, allowing users to filter logs based on importance or severity.

Available log levels:
- **Info** – General informational logs.
- **Success** – Logs related to successfully completed actions.
- **Warning** – Logs indicating potential issues.
- **Failed** – Logs related to failed actions or errors.
- **Major** – Logs of significant changes or critical events.

Users can **select a specific level type** to view logs of that category alone.

#### **1.2.2 Filter by Username**
- Users can **search for activity logs based on a specific username**.
- This helps identify actions performed by a particular user and **pinpoint issues related to specific accounts**.

#### **1.2.3 Filter by Date Range**
- Users can specify a **Start Date** and **End Date** to fetch logs **within a specific time range**.
- This is useful when **investigating incidents or reviewing past activities.**

#### **1.2.4 Search Functionality**
- Users can perform a **text-based search** to locate logs based on keywords or action descriptions.
- This is useful for quickly identifying specific events.

---

### **1.3 Viewing Detailed Logs**
Each **activity log entry** records essential details about user actions. In some cases, additional information is available via an **info (i) button** next to the log entry.

#### **1.3.1 Understanding the Log Structure**
Each log entry includes:
- **Action Performed** – The specific change or operation.
- **User** – The user who initiated the action.
- **Timestamp** – The date and time the action was performed.
- **Status** – Indicates whether the action was successful, failed, or pending.

#### **1.3.2 Using the Info (i) Button**
- Some logs, especially those related to **PowerShell executions**, **background tasks**, or **system-generated actions**, provide additional insights.
- Clicking the **"i" button** next to an entry reveals:
  - **PowerShell Execution Logs**
  - **Detailed Request Parameters**
  - **Success/Failure Messages**
  - **Error Reports (if applicable)**
- If an operation **fails**, this section provides information on **where and why the failure occurred**.

---

## **Conclusion**
The **Activity Logs Module** in **Teams Core IQ** ensures **accountability, transparency, and system monitoring** by maintaining a structured log of all user actions. With **advanced filtering, exporting, and detailed reporting**, admins can efficiently review and manage activities.


