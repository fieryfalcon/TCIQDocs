**Auto Attendant Module - User Manual**

---

## **1. Auto Attendant Module**
The **Auto Attendant Module** in **Teams Core IQ** enables organizations to **manage and configure Auto Attendants** within Microsoft Teams. This module extends the standard Microsoft Teams Auto Attendant functionalities by adding **delegation-based access, enhanced call routing, and export options.**

Upon accessing the **Auto Attendant Page**, users can:
- View a list of **existing Auto Attendants**.
- See details such as **language, operator type, and assigned resource accounts**.
- Check **holiday call flows** configured for handling calls during non-working days.
- Assign **call queues or other auto attendants** for further routing.
- Filter **Auto Attendants** based on **language**.
- Perform **search operations** to quickly find specific Auto Attendants.
- **Synchronize Auto Attendants** using the **Delta Sync button**.
- **Export Auto Attendant data** as CSV files.

### **1.1 Managing Auto Attendants**
Users can view and manage all configured Auto Attendants within the **Auto Attendant Management Page**.

#### **1.1.1 Viewing Auto Attendants**
- The table displays:
  - **Auto Attendant Name**
  - **Language**
  - **Operator Type** (Person, Resource Account, External Phone Number)
  - **Assigned Resource Accounts**
  - **Holiday Call Flow Count**
  - **Assigned Call Queues or Other Auto Attendants**
  - **Action Buttons** (Edit, Export, Sync)

#### **1.1.2 Viewing Resource Account Details**
- Clicking the **"i" button** next to a **Resource Account** will show:
  - **Phone Number Assigned**
  - **License Status**

#### **1.1.3 Managing Holiday Call Flow**
- Displays the **number of holiday call flows** configured.
- Users can configure how calls should be handled during holidays.

#### **1.1.4 Assigning Calls to Auto Attendant**
- Displays **linked call queues** or **other Auto Attendants**.
- Helps in managing **call redirection and flow.**

#### **1.1.5 Filtering, Searching, and Syncing**
- **Filter Auto Attendants by Language.**
- **Search for specific Auto Attendants**.
- Click **Delta Sync** to refresh the list.

#### **1.1.6 Exporting Auto Attendant Data**
- Users can **export Auto Attendant details** as a CSV file.
- Complete **Auto Attendant configurations** can be downloaded for auditing.

---

### **1.2 Creating an Auto Attendant**
To create a new **Auto Attendant**, follow these steps:

1. Click on **"Create New Auto Attendant"**.
2. Choose **Clone Workflow** to replicate an existing Auto Attendant (optional).
3. Complete the **five-step configuration process**:
   - **General**
   - **Call Flow**
   - **After-Hours Call Flow**
   - **Holiday Call Flow**
   - **Dial Scope**

#### **1.2.1 General Settings**
- **Auto Attendant Name** – Enter a unique name.
- **Operator Type** – Choose one of the following:
  - **Person in the Organization**
  - **Resource Account**
  - **External Phone Number**
- **Time Zone Selection** – Define business hours based on the time zone.
- **Language Settings** – Select the language used for voicemail and system prompts.
- **Enable/Disable Voice Input** – Allows voice-based navigation.
- **Assign Resource Accounts** – Attach resource accounts for **incoming calls**.

#### **1.2.2 Call Flow Configuration**
- Users can configure how incoming calls are handled:
  - **Greeting Options**:
    - No Greeting
    - Play an Audio File (**Max Size: 10MB**)
    - Add a Greeting Message (**Max 1000 characters**)
  - **Call Routing Options**:
    - Redirect to a Person
    - Redirect to a Call Queue
    - Redirect to an External Number
    - Redirect to Voicemail

#### **1.2.3 After-Hours Call Flow**
- Define **Business Hours** and **After-Hours Handling**.
- Configure **different schedules for different days**.
- Set **Closed Time Handling**:
  - **Play a Custom Greeting**
  - **Redirect Calls** (Same as Call Flow Routing)
- **Enable Keypad Menus**:
  - Assign **dial keys** (e.g., **Press 1 for Sales, Press 2 for Support**)
  - Configure voice commands for key inputs.
  - Redirect calls based on selected menu options.
- **Enable Directories**:
  - **Dial-by-Name** (Search & Connect to a user)
  - **Dial-by-Extension** (Enter an extension number for redirection)

#### **1.2.4 Holiday Call Flow**
- Manage **calls received on holidays**.
- Add a **Holiday List** and define **holiday-specific greetings and call routing**.
- Configure **custom messages and redirection**.
- Assign **keypad menus** (if applicable).

#### **1.2.5 Dial Scope Configuration**
- Defines the **users/groups listed** when a caller dials into the Auto Attendant.
- Callers using **dial-by-name** can be transferred to users **with Microsoft Teams installed**.
- Two sections:
  - **Include in Scope** – Users who should be searchable.
  - **Exclude from Scope** – Users who should not be available for dial-by-name searches.

---

## **1.3 Cloning an Existing Auto Attendant**
Instead of creating an Auto Attendant manually, use the **Clone Workflow** feature:
1. Click **Clone Workflow**.
2. Select an **existing Auto Attendant**.
3. Modify any necessary settings:
   - Auto Attendant Name
   - Operator Type
   - Time Zone & Language
   - Call Routing Settings
   - Business Hours & Holiday Call Flow
   - Dial Scope
4. Click **Save** to finalize the new Auto Attendant.

This feature allows for **quick setup and easy modification** of existing configurations.

---

## **Conclusion**
The **Auto Attendant Module** in **Teams Core IQ** simplifies the management of **Microsoft Teams Auto Attendants**, offering **enhanced delegation, call routing, and automation features**. This guide covered how to **create, manage, and optimize Auto Attendants** efficiently.
