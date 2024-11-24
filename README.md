# Chime & Charm: Event Management RBAC System
Welcome to Chime & Charm, a Role-Based Access Control (RBAC) system tailored to streamline event management operations. From managing clients to coordinating vendors, our secure and user-friendly platform ensures seamless collaboration for every role involved.

# Overview
Chime & Charm empowers event management companies to assign roles and permissions to various stakeholders like Event Managers, Clients, Vendors, and Staff. The platform provides an intuitive interface for planning and executing events while maintaining secure access controls.

## Features
### User Management:
- Add, update, and remove users.
- Assign roles and set user statuses (e.g., Active, Inactive).
### Role Management:
- Define roles such as Event Managers, Vendors, and Clients.
- Customize permissions for each role.
### Event Management:
- Create, edit, and view event details.
- Assign vendors, staff, and clients to events.
### Vendor Coordination:
- Manage vendor details and services (e.g., catering, décor, photography).
### Permission Management:
- Allow role-based access to event data, budgets, and schedules.
### Dynamic Dashboards:
- Provide role-specific dashboards with relevant information.
### Mock API Integration (Optional):
- Simulate API calls for CRUD operations on events, users, and roles.
## Tech Stack
### Frontend Framework: FlutterFlow
### Database: Firebase Firestore
### Authentication: Firebase Authentication
### Hosting: Firebase Hosting (Optional for deployment)
## Pages Overview
1. Login Page
- Secure login for all users with role-based redirection to dashboards.
- Includes “Forgot Password” feature.
2. Admin Dashboard
- Add and manage users, roles, and permissions.
- View all ongoing and past events.
- Generate event performance reports.
3. Event Manager Dashboard
- View assigned events.
- Coordinate with vendors and staff.
- Manage event timelines and client communications.
4. Vendor Dashboard
- Access event assignments.
- View and manage service requirements.
- Update service status (e.g., In Progress, Completed).
5. Client Dashboard
- View event details, timelines, and budgets.
- Provide feedback or approvals for vendor services.
- Chat with assigned Event Manager.
6. Role Management Page
- Define and customize roles like Admin, Event Manager, Vendor, Client, and Staff.
- Assign permissions dynamically to suit business needs.
7. Event Management Page
- Create and update events with key details (name, date, venue, budget, assigned personnel).
- Track progress and milestones for each event.
## Setup Instructions
1. Clone the Repository
git clone https://github.com/your-username/chime-charm-rbac.git
2. Open in FlutterFlow
Log in to FlutterFlow.
Import the project files from the repository.
3. Configure Firebase
Create a Firebase project.
Enable Firestore Database and Firebase Authentication.
Add your Firebase configuration to the FlutterFlow project.
4. Run the Application
Use FlutterFlow's "Run Mode" to preview the app in the browser.
Alternatively, download the project code and run it locally:
flutter pub get
flutter run
Usage Instructions
### Admin Login: Log in as an admin to manage users, roles, permissions, and events.
### Event Creation: Create a new event and assign relevant roles (e.g., Event Managers, Vendors).
### Role-Specific Dashboards: Explore tailored dashboards for Event Managers, Vendors, Clients, and Staff.
### Dynamic Permissions: Modify permissions as needed to suit organizational requirements.
## Future Enhancements
Integration with third-party calendars for event scheduling.
Real-time notifications for users (e.g., task updates, approvals required).
Analytics dashboard for insights into event performance and vendor efficiency.
Contributing
Contributions are welcome! To contribute:
Fork the repository.
Create a new branch: git checkout -b feature-branch-name.
Commit your changes: git commit -m "Feature description".
Push to the branch: git push origin feature-branch-name.
Open a pull request.
