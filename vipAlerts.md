# VIP Alerts Module - User Manual

## 1. VIP Alerts Module

The VIP Alerts Module in Teams Core IQ allows administrators to set up and manage alert rules for monitoring critical events within the platform. These alerts can be configured based on specific conditions and are integrated with ServiceNow for incident management.

The VIP Alerts Module consists of the following key sections:

- Adding an Alert Rule
- Managing Alert Rules
- Viewing Alerts and Incidents

### 1.1 Adding an Alert Rule

To create a new alert rule:

#### Navigate to the VIP Alerts Module:

- Click on the "VIP Alerts" tab in the main navigation menu.

#### Initiate a New Alert Rule:

- Click on the "Add Alert Rule" button located at the top-right corner.

#### Configure the Alert Rule:

- **Title**: Enter a descriptive name for the alert rule.
- **Condition**: Select the parameter to monitor (e.g., user activities, system errors). Choose specific users or groups if applicable.
- **Urgency and Impact**: Set the urgency and impact levels for the alert. These determine the priority of the incident in ServiceNow.
    - **Urgency** refers to the speed at which the business expects the incident to be resolved.
    - **Impact** measures the effect of the incident on business processes.
- **Threshold**: Define the number of occurrences before a notification is triggered.
- **Separate Notification**: Enable this to create individual incidents for each user; otherwise, a single incident is created for all users.
- **Sleep Mode**: Configure periods during which alerts should not trigger notifications.

#### Save the Alert Rule:

- Click "Create" to save the alert rule.

### 1.2 Managing Alert Rules

After creating alert rules, they appear in a table within the VIP Alerts Module.

#### Edit or Delete Rules:

- Use the "Edit" button to modify an existing rule.
- Use the "Delete" button to remove a rule.

#### Enable or Disable Rules:

- Toggle the "Enable/Disable" switch to activate or deactivate a rule.

#### Filter and Search:

- Utilize the filter options to sort rules based on urgency, impact, or type.
- Use the search functionality to locate specific rules quickly.

### 1.3 Viewing Alerts and Incidents

The Alerts/Incidents tab displays all triggered alerts and their details.

#### Search and Filter:

- Use the search bar to find specific alerts.
- Apply filters to view alerts based on criteria like date, severity, or status.

#### Incident Details:

- Click on an alert to view detailed information, including the condition that triggered it and the associated users.

## 2. Integration with ServiceNow

The VIP Alerts Module integrates with ServiceNow to manage incidents effectively.

### 2.1 Understanding Urgency and Impact in ServiceNow

In ServiceNow, Impact and Urgency are critical factors in determining the Priority of an incident.

#### Impact assesses the effect of an incident on business processes:

- **High**: A large number of staff or customers are affected; significant financial impact; severe reputational damage.
- **Medium**: A moderate number of staff or customers are affected; noticeable financial impact; moderate reputational damage.
- **Low**: A minimal number of staff or customers are affected; minor financial impact; minimal reputational damage.

#### Urgency determines how quickly an incident needs resolution:

- **High**: Rapid escalation; highly time-sensitive tasks; immediate action required to prevent major incidents.
- **Medium**: Considerable escalation over time; time-sensitive tasks; prompt action needed.
- **Low**: Marginal escalation over time; non-time-sensitive tasks; standard response acceptable.

The combination of Impact and Urgency defines the Priority of an incident, guiding response and resolution times.

## 3. Conclusion

The VIP Alerts Module in Teams Core IQ provides a robust framework for monitoring critical events and integrating with ServiceNow for incident management. By configuring alert rules with appropriate conditions, urgency, and impact levels, administrators can ensure timely responses to significant issues within the platform.

For further assistance, refer to the Teams Core IQ Support or consult the ServiceNow Documentation for more details on incident management and priority definitions.