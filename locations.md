**Locations Module - User Manual**

---

## **1. Locations Module**
The **Locations Module** in **Teams Core IQ** allows organizations to **track, manage, and organize multiple office locations** efficiently. Administrators can add locations, associate offices with specific cities, and manage **Wi-Fi access points, subnets, and trusted networks** for better network and call tracking.

The **Locations Module** consists of the following key sections:
- **Adding a New Location**
- **Managing Locations**
- **Adding and Managing Places**
- **Managing Subnets, Wi-Fi Access Points, and Switches**
- **Managing Trusted and Non-Trusted Subnets**

---

### **1.1 Adding a New Location**
New locations can be added to the system to represent **offices, branches, or any operational locations**.

#### **1.1.1 Adding a Location**
1. Click on **"Add Location"** (top-right corner of the Locations Page).
2. Enter the **Location Name**.
3. Select the **Country/Region**.
4. Enter the **Address** manually or use one of the following:
   - **Pinpoint on Map** – Click on the map to select the exact location.
   - **Use GPS** – Automatically detect the current location.
5. Click **"Save"** to add the location to the system.

> **Note:** The **map feature** allows precise location input for improved accuracy in tracking.

---

### **1.2 Managing Locations**
Once a location is added, it appears in the **Locations Table**.

#### **1.2.1 Viewing Location Details**
- Click on a **specific location** to view detailed information.
- Each location entry includes:
  - **Location Name**
  - **Number of Offices in the Location**
  - **Address & Location ID**
  - **List of Associated Places**

#### **1.2.2 Searching & Filtering Locations**
- **Search by Location Name or ID**.
- **Filter locations by country, city, or associated offices.**

---

### **1.3 Adding and Managing Places**
A **location** can have multiple **places (offices, floors, or departments)**.

#### **1.3.1 Adding Places to a Location**
1. Inside the **Location Details Page**, click **"Add Place"**.
2. Enter **Place Name** (e.g., **Miami HQ - Floor 3**).
3. Specify details such as **sub-location, office type, or description**.
4. Click **"Save"** to add the place to the location.

#### **1.3.2 Viewing & Managing Places**
- Places within a **location** appear in a **separate table**.
- Each **place** can be searched, filtered, or modified.

---

### **1.4 Managing Subnets, Wi-Fi Access Points, and Switches**
Administrators can associate network components with locations to improve **network monitoring and call routing**.

#### **1.4.1 Adding Network Components**
1. Navigate to the **Location Details Page**.
2. Click on **"Add Subnet/Wi-Fi/Switch"**.
3. Enter the required information:
   - **Subnet Name & IP Range**
   - **Wi-Fi Access Point Name & SSID**
   - **Switch Details (Name, Type, Location)**
4. Click **"Save"** to add the network component.

#### **1.4.2 Managing Network Components**
- Existing network configurations appear under their respective tables.
- Admins can **edit, remove, or update** these components.

---

### **1.5 Managing Trusted and Non-Trusted Subnets**
The **Manage IPs** section allows admins to categorize subnets as **Trusted or Non-Trusted**.

#### **1.5.1 Adding Trusted Subnets**
1. Navigate to **Manage IPs**.
2. Click **"Add Trusted Subnet"**.
3. Enter **Subnet Name & IP Range**.
4. Click **"Save"**.

#### **1.5.2 Tracking Trusted vs. Non-Trusted Calls**
- Calls made from a **trusted subnet** are logged as coming from a **secure location**.
- Calls from **non-trusted subnets** are flagged in the **Call Queue Analysis Page**.
- This helps track whether users are working from the **office or an external network**.

---

### **1.6 Exporting Location Data**
- Click **"Export"** to download all location-related data as a **CSV file**.
- Exported data includes **location details, places, subnets, and network components**.

---

## **Conclusion**
The **Locations Module** in **Teams Core IQ** simplifies **tracking, managing, and securing organizational locations**. With **map-based location selection, network component management, and trusted subnet tracking**, organizations can efficiently monitor their office networks and improve call routing.

For further assistance, refer to **Teams Core IQ Support** or consult internal documentation.

