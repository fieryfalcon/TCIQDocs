**Migration Module - User Manual**

---

## **1. Migration Module**
The **Migration Module** in **Teams Core IQ** enables administrators to migrate users in batches efficiently by assigning **DID numbers and policies** in an automated or scheduled manner. The module provides **batch processing, user review, number mapping, policy assignment, and post-migration management**.

The **Migration Module** consists of the following key sections:
- **Creating a Batch Migration**
- **Managing Batch Migration**
- **Assigning DID Numbers**
- **Assigning Mapped Policies**
- **Post Migration Steps**

---

### **1.1 Creating a Batch Migration**
The migration process begins with **creating a new batch**.

#### **1.1.1 Defining a Batch**
1. Click on **"Create New Batch"** (top-right corner of the Migration Page).
2. Enter the **Batch Name**.
3. Choose how to **import users**:
   - **Manually Select Users** – Choose users from the drop-down list.
   - **Upload Users via CSV** – Bulk upload users by generating a CSV file.

#### **1.1.2 Uploading Users via CSV**
1. Click **"Customize Your CSV Template"**.
2. Select **Batch Type**:
   - **Department-based batch**
   - **Country-based batch**
   - **User-based batch**
3. Generate the CSV file and modify it as needed.
4. Re-upload the **CSV file** for batch processing.

#### **1.1.3 Reviewing Users**
- After defining the batch, the selected users appear in a **review table**.
- If a user was missed in the previous step, click **"Add More Users"** (top-right corner).
- Verify that all required users are present before proceeding.

---

### **1.2 Assigning DID Numbers**
Once the batch is created, **DID numbers** must be assigned.

#### **1.2.1 Selecting DID Numbers**
- The number of users in the batch determines how many **unassigned DID numbers** need to be selected.
- Users can choose **from the list of available DID numbers**.

#### **1.2.2 Scheduling DID Assignment**
1. Click **"Assign DID Numbers"**.
2. Choose one of the following options:
   - **Instant Assignment** – Assigns DID numbers immediately.
   - **Scheduled Assignment** – Assigns numbers at a later specified time.
3. If scheduling, enter the **desired date and time**.
4. Confirm the **DID Assignment**.

---

### **1.3 Assigning Mapped Policies**
After DID numbers are assigned, policies need to be mapped to users.

#### **1.3.1 Policy Assignment Options**
1. Click **"Assign Mapped Policies"**.
2. Choose the method for assignment:
   - **Auto Assignment** – Policies are assigned automatically based on predefined logic.
   - **Bulk or Custom Assignment** – Requires a CSV upload for custom policy mapping.

#### **1.3.2 Scheduling Policy Assignment**
- Choose between **Instant Policy Assignment** and **Scheduled Policy Assignment**.
- If scheduling, provide the **execution date and time**.

---

### **1.4 Post Migration Steps**
After DID assignment and policy mapping, the final step is to **complete the migration**.

#### **1.4.1 Finalizing Migration**
1. Click **"Post Migration Setup"**.
2. Choose between:
   - **Instant Execution**
   - **Scheduled Execution**
3. Confirm the **Post Migration Setup** to finalize the process.

#### **1.4.2 Monitoring Migration Progress**
- Each batch's **status updates** will be reflected in the homepage table.
- Progress indicators will show which phases are **completed, pending, or in progress**.
- Admins can monitor ongoing migrations and take necessary actions.

---

### **1.5 Managing Existing Batches**
After a migration batch is created, it is listed in the **Migration Table** on the homepage.

#### **1.5.1 Viewing Batch Details**
- The table displays:
  - **Batch Name**
  - **Ongoing Phase** (e.g., DID Assignment, Policy Assignment, Post Migration)
  - **Phase Progress Status** (Not Scheduled, Scheduled, Completed)
  - **Created By** (Admin who created the batch)
  - **Created & Updated Timestamps**
- Click **"View Details"** under the **Action** column to open batch-specific details.

#### **1.5.2 Batch Details Page**
Inside each **Batch Details Page**, you can find:
- **General Batch Information**
  - Batch Creation & Update Time
  - Phase Progress Status
  - DID Assignment & Policy Assignment Status
- **Users Info**
  - List of users included in the migration
  - DID Assignment & Policy Assignment statuses per user
  - Telephone numbers assigned to each user
- **Activity Logs & Migration Logs**
  - Track system-generated events related to the batch.
  - Review **PowerShell execution details** and **error reports** if applicable.

#### **1.5.3 Additional Actions**
From the batch details page, admins can:
- **Assign New Users to the Batch**
- **Reassign DID Numbers**
- **Reassign Policies**
- **Review and Monitor Logs**

---

## **Conclusion**
The **Migration Module** in **Teams Core IQ** provides an efficient way to **batch migrate users with automated DID number and policy assignments**. With **structured batch processing, scheduling options, and monitoring tools**, admins can seamlessly migrate users with minimal manual effort.

For further assistance, refer to **Teams Core IQ Support** or consult internal documentation.

