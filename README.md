# Power BI Dashboard Integration with Angular

Project Overview
This project demonstrates the integration of a Power BI dashboard into an Angular web application. It features a login and registration system, providing users with access to the Power BI reports directly within the Angular interface. This solution allows users to interact with embedded Power BI reports, making it easier to visualize and analyze data directly from the web application.

Key Features
User Authentication: Login and registration pages to allow user access to the dashboard.
Power BI Dashboard Integration: Embeds Power BI reports within the Angular application using an embedded URL.
Dynamic Data Visualization: Displays interactive and dynamic reports from Power BI, enabling users to filter and analyze data in real-time.
Responsive UI: Designed with a mobile-first approach, ensuring smooth user experience across devices.
Technologies Used
Angular: Frontend framework for building the user interface and handling the application logic.
Power BI: Business analytics tool used for creating interactive reports and dashboards.
Power BI Embedded: Embedding Power BI reports and dashboards into the Angular application using an embedded URL.
JavaScript/TypeScript: For the interactive and dynamic aspects of the application.
HTML/CSS: For building the structure and styling of the pages.
Installation
To get started with the project locally, follow these steps:

Prerequisites
Node.js and npm installed on your machine.
Power BI account (for generating the embedded report URL).
Steps
Clone the repository:

bash
Copy code
git clone https://github.com/your-username/your-repository-name.git
Navigate to the project directory:

bash
Copy code
cd your-repository-name
Install the required dependencies:

bash
Copy code
npm install
Set up Power BI Integration:

Sign in to Power BI and create the reports you want to embed.
Obtain the embed URL for your report and configure it in the Angular project where necessary (usually in the environment files or component).
Run the application:

bash
Copy code
ng serve
Open the app in your browser:

bash
Copy code
http://localhost:4200
Usage
Upon successful login, users can view the embedded Power BI dashboard with full interactivity.
The dashboard allows users to filter and explore data based on the available metrics.
The system ensures that only authenticated users can access the dashboard.
Future Enhancements
Role-based Access: Implement role-based authentication to provide different access levels to the dashboard.
Improved UI/UX: Enhance the design and responsiveness for better user experience.
Custom Power BI Reporting: Add features to allow users to create and customize reports directly from the application.
Contributing
Feel free to fork the repository, contribute, and submit pull requests. Contributions to improve functionality, UI/UX, or any other part of the application are welcome.

License
This project is licensed under the MIT License - see the LICENSE file for details.
