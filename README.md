Installation Manual (for setting up the Local Waste Map on WAMP Server)
1.	System Requirements
•	Operating System: Windows 7 or higher
•	Web Server: WAMP Server (Windows Apache MySQL PHP)
•	PHP Version: 7.4 or higher
•	Database: MySQL (Included with WAMP)
•	Browser: Latest version of Chrome, Firefox, or Edge
2.	Software Installation
•	Step 1: Goto https://www.wampserver.com/en/ to download WAMP Server. Install it after downloading.
•	Step 2: While installing, keep the default options and ensure that Apache and MySQL services are running after installation.
•	Step 3: Run the WAMP application and look for the green icon in the system tray to make sure its running status.
3.	Setting Up the Project
•	Step 1: Goto to the link https://github.com/kinga-yeshi/LocalWasteMap to download the project file. 
•	Step 2: Extract the downloaded project files and copy it to the C:\wamp64\www\ directory.
•	Step 3: Create a MySQL database:
o	Open your browser and go to the localhost/phpMyAdmin page. 
o	Log in with the default credentials (root with no password).
o	Create a database with the name “local_waste_map” by clicking on create a new database.

•	Step 4: Import the database schema:
o	Select your newly created database (local_waste_map) in phpMyAdmin.
o	Click on the import tab and select the SQL file (local_waste_map.sql) from the project file. 
•	Step 6: Open your web browser and navigate to the link http://localhost/your_project_folder to access the Local Waste Map website.
4.	Testing the System
•	Check if the Homepage loads correctly or not. 
•	Test each functionality of each:
o	Recycling Tips Page with FAQs and Resource Library.
o	Map & Locations Page with search and filter options.
o	Report Issues Page for submitting reports, community reporting, and tracking issues.
o	Feedback Form to submit user feedback.
•	If everything works as expected, the system is correctly set up.
User Manual (for using the Local Waste Map system)
1.	Introduction
The Local Waste Map system is dev to help users navigate waste management areas, access recycling tips, report issues, and track reported waste-related problems.
2.	Accessing the System
•	Open your browser and navigate to http://localhost/your_project_folder after installing the project.

3.	Features & Usage	
Home Page
•	The home page provides an overview of the Local Waste Map services, including featured articles and interactive maps.
Recycling Tips Page
•	Navigate to the Recycling Tips page to:
o	View recycling and waste reduction tips.
o	Expand sections for more detailed information using the “Read More” button.
o	Access the FAQ section to get answers to frequently asked questions about recycling.
o	Download resources from the Resource Library (e.g., guides on recycling and composting).
Map & Locations Page
•	Use the interactive map to find waste disposal and recycling locations.
•	Use the Search bar to find specific locations based on keywords (e.g., "recycling centers").
•	Filter locations by type using the Filter dropdown (e.g., waste disposal, hazardous waste).
•	Click on a location to view details like operating hours and accepted materials.
Report Issues Page
•	Use the Report Issue Form to report problems such as illegal dumping or overflowing bins.
o	Enter the issue type, location, and description.
o	Submit the form to generate a Tracking ID for the issue.
•	View the Community Reporting section to see issues reported by other users.
•	Track the status of your report by entering your Tracking ID in the Track Your Issue section.

Feedback Form
•	Navigate to the Feedback page to submit any comments, questions, or suggestions about the system.
•	Enter your name, email, and feedback message, and submit it.
Contact Page
•	Use the Contact page to get in touch with the website administrators.
•	Contact information for local waste management authorities is also available here.
4.	Troubleshooting
•	If the website is not loading, ensure that the WAMP server is running (the icon should be green in the system tray).
•	Check the database connection settings in config.php to ensure the correct credentials are used. 
•	If you encounter issues with any functionality, try restarting WAMP or clearing your browser cache.
