# Use Cases for Population Information System

## Use Case 1: View Population Data for a Selected City
- **Actor**: Data Analyst
- **Precondition**: The system has population data available.
- **Main Flow**:
    1. The data analyst selects a city from the dropdown menu.
    2. The system retrieves population data for the selected city.
    3. The system displays the population data.
- **Alternate Flow**:
    - If the selected city has no population data available, the system displays a "No data available" message.

---

## Use Case 2: Generate Population Report
- **Actor**: Government Official
- **Precondition**: The system has population data and the user is logged in.
- **Main Flow**:
    1. The government official navigates to the report generation section.
    2. The official selects filters (age group, gender, region).
    3. The system generates a report based on the selected criteria.
    4. The official clicks on the "Export" button.
    5. The system prompts for export format (PDF, Excel, CSV).
    6. The system generates the report in the selected format and prompts the user to download it.
- **Alternate Flow**:
    - If the selected filters yield no results, the system displays a "No data available for the selected criteria" message.

---

## Use Case 3: Compare Population Data Between Regions
- **Actor**: City Planner
- **Precondition**: The system has population data for multiple regions available.
- **Main Flow**:
    1. The city planner selects two or more regions from the comparison tool.
    2. The planner clicks on the "Compare" button.
    3. The system retrieves population data for the selected regions.
    4. The system displays the comparison in a side-by-side format with charts.
- **Alternate Flow**:
    - If data for any selected region is missing, the system displays a message indicating which regions lack data.

---

## Use Case 4: Import Population Data
- **Actor**: Data Manager
- **Precondition**: The user has the necessary permissions to import data.
- **Main Flow**:
    1. The data manager navigates to the data import section.
    2. The manager selects a data file (CSV or Excel) to upload.
    3. The system validates the data format and content.
    4. If valid, the system imports the data into the database.
    5. The system displays a confirmation message upon successful import.
- **Alternate Flow**:
    - If the data format is invalid, the system displays an error message indicating the issue.
    - If the data contains duplicate entries, the system prompts the user to confirm whether to overwrite existing data.

---

## Use Case 5: User Login and Access Management
- **Actor**: Administrator
- **Precondition**: The administrator has valid credentials to log in.
- **Main Flow**:
    1. The administrator navigates to the login page.
    2. The administrator enters their username and password.
    3. The system verifies the credentials.
    4. If valid, the system grants access to the administration dashboard.
    5. The administrator manages user roles and permissions.
- **Alternate Flow**:
    - If the credentials are invalid, the system displays an "Invalid username or password" message.
    - If the administrator has forgotten their password, the system provides a password reset option.

---

## Use Case 6: Visualize Population Trends
- **Actor**: Data Analyst
- **Precondition**: The system has population data available for visualization.
- **Main Flow**:
    1. The data analyst navigates to the visualization section.
    2. The analyst selects the type of visualization (e.g., bar chart, line graph).
    3. The analyst chooses the parameters for the visualization (e.g., age group, time period).
    4. The system generates the selected visualization.
    5. The analyst can download or print the visualization.
- **Alternate Flow**:
    - If there is insufficient data for the selected parameters, the system displays a "Not enough data to create visualization" message.
