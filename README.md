# Servify - Community Service Website

### A Platform for Community Service Management

Servify is a web-based platform designed to connect communities and individuals with service providers to address service needs such as repairs, maintenance, and assistance. The platform enables users to submit service requests, track progress, and communicate with service providers.

## Features
1. **User Registration and Authentication**: Users can create accounts, log in, and manage their service requests.
2. **Service Requests**: Users can submit requests for community services like repair, cleaning, or assistance.
3. **Request Tracking**: Users can view the status of their submitted service requests.
4. **Admin Dashboard**: Administrators can manage service requests, assign service providers, and monitor request progress.
5. **Notifications**: Users receive updates when their service requests are acknowledged, in-progress, or completed.

## Project Overview
The project was developed to address the growing need for streamlined community service management, providing both users and service providers with an easy-to-use interface to handle requests and assignments efficiently. The platform aims to improve the coordination of community service efforts by making the process more transparent and organized.

### Core Responsibilities
1. **Backend Development**: Handled data management and service requests using **Django** and **Django Rest Framework**.
2. **Data Handling**: Managed database interactions using **PostgreSQL**, ensuring seamless request tracking and user management.
3. **User Experience**: Developed user-friendly interfaces with a focus on clear navigation and easy access to service request details.

## Tech Stack
- **Backend**: Django (Python)
- **Frontend**: HTML, CSS, Bootstrap
- **Database**: PostgreSQL
- **Authentication**: Django's built-in authentication system
- **API Integration**: Django Rest Framework for communication between frontend and backend
- **Deployment**: Deployed on a cloud platform (e.g., Heroku or DigitalOcean)

## Installation and Setup
1. **Clone the repository**:
   ```bash
   git clone https://github.com/yourusername/servify-community-service.git
   ```
2. **Create a virtual environment**:
   ```bash
   python -m venv venv
   ```
3. **Activate the virtual environment**:
   - On Windows:
     ```bash
     venv\Scripts\activate
     ```
   - On macOS/Linux:
     ```bash
     source venv/bin/activate
     ```
4. **Install dependencies**:
   ```bash
   pip install -r requirements.txt
   ```
5. **Set up the database**:
   - Configure PostgreSQL or your preferred database in `settings.py`.
   - Run migrations:
     ```bash
     python manage.py migrate
     ```
6. **Run the server**:
   ```bash
   python manage.py runserver
   ```

## Usage
- **User Registration**: New users can sign up and log in to submit service requests.
- **Submit a Request**: After logging in, users can create a new service request by providing details of the issue.
- **Track Requests**: Users can view the status of their request (e.g., pending, in-progress, completed) on their dashboard.

## Contributions
This project was developed as part of a group effort to provide a practical solution for community service management. Contributions included:
- Backend development
- Data management with PostgreSQL
- Request tracking functionality
- Admin dashboard integration

## License
This project is open-source and available under the MIT License.

---
