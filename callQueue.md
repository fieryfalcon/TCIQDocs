**Call Queue Module - User Manual**

---

## **1. Call Queue Module**
The **Call Queue Module** in **Teams Core IQ** enables organizations to efficiently manage **Microsoft Teams Call Queues**, including the creation, configuration, monitoring, and modification of call queues. It extends Microsoft Teams' native functionalities by providing **department-based delegation, enhanced routing options, and additional automation features**.

### **1.1 Creating a Call Queue**
To create a new **Call Queue**, follow these steps:

1. Click on **"Add New Call Queue"** (top-right corner of the Call Queue page).
2. You will be guided through a **five-step process**:
   - **General**
   - **Call Greetings**
   - **Call Answering**
   - **Call Back**
   - **Exception Handling**

#### **1.1.1 General Settings**
The first step in creating a call queue is configuring general settings:
- **Queue Name** – Enter a unique name for the call queue.
- **Resource Accounts** – Assign resource accounts linked to this call queue.
- **Calling IDs** – Configure calling IDs for outbound calls.
- **Service Level Threshold** – Enable or disable service-level tracking.
- **Language Settings** – Set the default voicemail language.

#### **1.1.2 Call Greetings**
Call Greetings allow users to configure **custom messages or audio** played to callers while they wait.
- **Add Greetings**:
  - No Greeting
  - Play an Audio File (**Max Size: 5MB - 10MB**)
  - Add a Greeting Message (**Max 1000 characters**)
- **Music on Hold**:
  - Play Default Music
  - Play an Audio File

#### **1.1.3 Call Answering**
Define **who will answer the calls** and the preferred routing method.
- **Select Call Answer Group**:
  - **A Team** – Select a Microsoft Teams group.
  - **A User or Group** – Assign specific users or groups.
- **Conference Mode** – Toggle to allow or disable conferencing.
- **Routing Method**:
  - **Attendant Routing** – Calls ring all agents simultaneously.
  - **Serial Routing** – Calls are routed sequentially.
  - **Round Robin** – Each agent receives an equal number of calls.
  - **Longest Idle** – Calls are routed to the agent available for the longest time.
- **Presence-Based Routing** – Controls call presentation to agents.
- **Call Agent Settings**:
  - **Enabled** – Agents can choose whether to answer calls.
  - **Disabled** – Calls are automatically assigned to agents.

#### **1.1.4 Call Back**
Allows configuring **automated callback requests** instead of keeping users waiting in the queue.
- **Enable Callback** – Toggle ON/OFF.
- **Eligibility Conditions**:
  - **Time in Queue** – Set the threshold for callback eligibility.
  - **Calls in Queue** – Define the maximum number of calls in the queue before allowing callbacks.
  - **Agent Availability Check** – Configure minimum agent availability for callback requests.
- **Greeting**:
  - Play an Audio File
  - Add a Greeting Message (**Max 1000 characters**)
- **Callback Key** – Configure a key for users to press to request a callback.
- **Email Notification** – Send callback failure alerts to a **Microsoft 365 Group**.

#### **1.1.5 Exception Handling**
Define **actions** when a queue reaches capacity or times out.
- **Maximum Calls Reached**:
  - Disconnect the call.
  - Redirect the call to:
    - **Voice Agent**
    - **Resource Account**
    - **Voicemail (Shared/Personal)**
    - **Specific User**
  - Play an Audio File / Greeting Message.
- **Call Timeout Handling**:
  - Disconnect the call.
  - Redirect the call with customizable settings.

### **1.2 Cloning an Existing Call Queue**
The **Clone Workflow** feature allows users to replicate an existing **Call Queue** configuration instead of manually creating a new one from scratch. This is useful when multiple call queues require similar settings.

To clone a call queue:
1. Click on the **Clone Workflow** option at the top right.
2. Select an existing **Call Queue** from the dropdown.
3. Review and modify the following settings if needed:
   - **Queue Name**
   - **Resource Accounts**
   - **Call Agents**
   - **Call Routing Methods**
   - **Greeting Messages**
   - **Exception Handling Rules**
4. Click **Save** to create the cloned call queue.

This feature ensures **faster setup** and minimizes errors when configuring multiple similar call queues.

### **1.3 Viewing & Managing Call Queues**
Once created, **Call Queues** appear in the **Call Queue Management Page**. This section provides an **overview and management functionalities**.

#### **1.3.1 Search & Filter Call Queues**
- Use the **search bar** to quickly find a specific **Call Queue**.
- Apply **filters** based on Resource Accounts, Call Agents, and Queue Settings.

#### **1.3.2 Columns & Key Information Display**
The **Call Queue Management Table** includes the following key details:
- **Queue Name** – Identifies the call queue.
- **Resource Accounts** – Displays linked resource accounts.
- **Call Agents** – Shows assigned agents.
- **Maximum Wait Time** – Displays the configured call queue timeout limit.
- **Maximum Calls** – Indicates the maximum number of queued calls before redirection.

#### **1.3.3 Editing a Call Queue**
To modify an existing **Call Queue**:
1. Click on the **Call Queue Name** to view details.
2. Click **Edit** under the **Action** column.
3. Update any of the **Call Queue Settings**.
4. Click **Save** to apply changes.

#### **1.3.4 Viewing Resource Account Details**
- Click the **"i" button** next to the Resource Account column.
- View all **associated resource accounts**.
- Check if a resource account has a **license assigned**.
- Check if the resource account has a **phone number assigned**.

#### **1.3.5 Viewing Call Agent Details**
- Click the **"i" button** in the Call Agents column.
- View details including:
  - **Agent Name**
  - **Phone Number**
  - **Email Address**
  - **Assigned Call Queue**
- **Export Agent List** as **CSV**.

#### **1.3.6 Exporting Call Queue Data**
Users can export various details for **reporting & auditing**:
- **Download Call Queue List** as **CSV**.
- **Export Call Agent List**.
- **Export Complete Call Queue Configuration**.

#### **1.3.7 Refreshing Call Queues**
To **sync the latest Call Queues** from **Microsoft Teams**:
- Click the **Refresh (Delta Sync)** button.
- The system will **fetch & display** new call queues using **PowerShell commands**.

---

## **Conclusion**
The **Call Queue Module** of **Teams Core IQ** streamlines **Microsoft Teams telephony management** by providing advanced **routing, delegation, and monitoring features**. This guide covered **creating, managing, and optimizing** call queues efficiently.


