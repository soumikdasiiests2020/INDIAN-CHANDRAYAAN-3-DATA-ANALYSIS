# INDIAN-CHANDRAYAAN-3-DATA-ANALYSIS
_**Project Summary:**_

This Python code analyzes the mass and power budgets of a lunar lander mission, offering valuable insights into the design and feasibility of the mission. It utilizes the following libraries:

pandas: For creating DataFrames to organize mission data.
matplotlib: For generating bar charts to visualize the mass and power budgets.
plotly.express: For creating interactive bar charts enhancing user experience.
numpy (optional): For handling scientific notation, if needed.
**Key Functionalities:**

**Data Organization:**
Reads mission data from provided dictionaries and creates separate DataFrames for the lander, rover, and overall mission using pandas.
**Value Extraction:**
Extracts numerical values from textual data points within the "Specifications" column, utilizing regular expressions to handle diverse formats.
**Calculations:**
Calculates essential mission parameters, including:
Propellant mass required for the lander to achieve the desired delta-v (change in velocity) using the Tsiolkovsky rocket equation.
Rover operating time based on the lander's battery capacity and the rover's power requirement.
**Visualizations:**
Generates interactive bar charts with Matplotlib and plotly.express, providing a clear visual representation of:
Mass Budget: Lander dry mass, Rover mass, and Propellant mass.
Power Budget: Rover power requirement and Lander battery capacity.
**Additional Insights:**
Offers commentary on the potential mobility of the rover based on its mass.
Displays the number of scientific payloads carried by the rover.
**Usage:**

Clone or download the repository.
Install required libraries:
Run pip install pandas matplotlib plotly numpy in your terminal (if using numpy).
Execute the script:
Run python script.py (replace script.py with the actual filename) in your terminal.
**Output:**

Printed Information:
Detailed output will be displayed in your terminal, including:
Mass Budget: Listing the lander's dry mass, rover mass, and propellant mass required.
Power Budget: Details of the rover's power requirement, lander battery capacity, and estimated rover operating time based on the battery.
Mobility Assessment: Comments on the rover's potential mobility based on its mass.
Payloads: The number of scientific payloads carried by the rover.
**Visualizations:**
Two interactive bar charts will be displayed, depicting:
Mass Budget: Visualizes the distribution of the mission's mass across lander, rover, and propellant.
Power Budget: Demonstrates the relationship between the rover's power demand and the lander's battery capacity.
**Further Development:**

**Error Handling:** Implement robust error handling to gracefully handle user errors or unexpected input formats.
**Customization:** Allow users to customize various calculation parameters, such as delta-v or battery capacity, enabling exploration of different mission scenarios.
**Visualization Enhancements:** Explore alternative visualization libraries or techniques, potentially incorporating data tables or interactive elements for a richer user experience.
Unit Conversion: Consider adding functionalities for converting units between different measurement systems to increase flexibility.
**Contribution:**

I encourage contributions to this project! Feel free to:

Fork the repository: Create a copy of the project on your GitHub account.
Make changes: Modify the code, documentation, or functionalities as you see fit.
Submit a pull request: Share your improvements with the original project maintainers for potential inclusion.

**License**

This project is licesed under [MIT License](License)
