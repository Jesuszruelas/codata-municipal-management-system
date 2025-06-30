
Built by https://www.blackbox.ai

---

# COData

COData is a Municipal Management System designed to streamline the management of local issues, such as public maintenance requests, while providing users with easy access to report tracking and status updates.

## Project Overview

The COData project provides an interface for users to report municipal issues and track their status using a modern, user-friendly web application. Users can log in to access their personalized dashboards, view reports, and check maps with details of ongoing maintenance tasks.

## Installation

To install and run the COData application locally, follow these steps:

1. **Clone the repository:**
   ```bash
   git clone https://github.com/yourusername/codata.git
   cd codata
   ```

2. **Open `index.html` in your web browser** (This project does not require a backend server):
   - You may use a simple HTTP server, such as Python's built-in server:
   ```bash
   python -m http.server
   ```

3. **Access the application:**
   Open your web browser and navigate to `http://localhost:8000` (or the appropriate port if different).

## Usage

1. **Login:** Use the credentials provided in the UI:
   - User: `usuario@cdata.com` / Password: `user123`
   - Admin: `admin@cdata.com` / Password: `admin123`

2. **Navigate through the application:** You can interact with different sections via the side menu, such as:
   - Dashboard
   - Reports
   - Evidence Capture
   - Notifications
   - Profile
   - Maps

3. **Logout:** Click the logout button in the profile section to exit the application.

## Features

- **User Authentication:** Users can log in as either a regular user or an admin.
- **Profile Management:** Users can view and manage their profiles.
- **Report Management:** Users can submit and track reports, including adding evidence.
- **Map Visualization:** Display the status of reports on a map using the Leaflet library.
- **Responsive Design:** Optimized for various devices using Tailwind CSS.

## Dependencies

This project relies on several key libraries and resources:

- [Tailwind CSS](https://tailwindcss.com/) for styling.
- [Font Awesome](https://fontawesome.com/) for icons.
- [Leaflet](https://leafletjs.com/) for mapping functionality.

These libraries are included through CDN links in the `index.html` file.

## Project Structure

```
COData/
│
├── index.html           # Main application page
├── login.html           # Login page for authenticating users
├── script.js            # JavaScript file containing application logic
└── styles.css           # CSS styles (if external styles are added)
```

### File Descriptions

- **index.html**: Contains the structure of the application, including navigation, sections for reports, maps, etc.
- **login.html**: A dedicated page for user authentication.
- **script.js**: JavaScript logic responsible for interactivity and functionality, such as loading pages, handling user roles, and managing reports.
- **styles.css**: Additional styles can be added here to customize the appearance of the application.

## Contributing

If you want to contribute to the COData project, feel free to create a pull request or open an issue for discussion.

## License

This project is licensed under the MIT License. See the LICENSE file for details.

---

Feel free to modify this README file according to your preferences and requirements.