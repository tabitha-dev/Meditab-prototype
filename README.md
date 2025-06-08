# MediTab - Healthcare Coordination Prototype

**MediTab** is a high-fidelity, interactive prototype of a healthcare communication application designed to streamline clinical workflows and improve patient care. Developed by **Tabitha-dev**, this project demonstrates a multi-role dashboard system that addresses the persistent fragmentation of information among healthcare teams.

This prototype is built entirely with **HTML, CSS, and vanilla JavaScript**, showcasing a modern, responsive, and intuitive interface without relying on a backend or complex frameworks.

## Live Demo

[Link to your live demo - e.g., deployed on GitHub Pages or Netlify]

## Problem Statement

In many healthcare settings, clinical teams rely on disconnected and outdated tools like pagers, spreadsheets, and separate messaging apps. This fragmentation leads to communication breakdowns, delays in care, and an increased risk of medical errors. MediTab was designed to solve this by unifying secure messaging, task management, patient data, and administrative reporting into a single, cohesive platform.

## Features

This prototype simulates a multi-user environment with four distinct roles, each with a dashboard tailored to their specific responsibilities:

* **Doctor Dashboard:**
    * **Patient Overview:** View a list of assigned patients and their current status.
    * **Interactive Patient Details:** Click on a patient to open a modal with their chart, notes, and current medications.
    * **Data Visualization:** A pie chart displays the distribution of patient statuses (e.g., Stable, Needs Review, Monitored).
    * **Secure Messaging:** A feed shows recent messages from nurses and other system alerts.

* **Nurse Dashboard:**
    * **Live Task List:** View and manage patient-related tasks (e.g., administer medication, check vitals).
    * **Interactive Task Status:** Update the status of any task (Pending, In Progress, Completed) directly from the dashboard.

* **Manager Dashboard:**
    * **KPI Monitoring:** View key performance indicators, including tasks completed, average response time, and active staff.
    * **Data Visualization:** A line chart shows task completion trends over the week.
    * **High-Priority Alerts:** A dedicated section highlights critical issues, such as staffing shortages or ER delays.

* **Patient Portal:**
    * **Central Hub:** A main menu provides access to appointments, lab results, medications, billing, and a help center.
    * **Schedule Appointments:** A dedicated button opens a modal to request a new appointment.
    * **Live Chat Simulation:** The Help Center includes a "Live Chat" feature that opens a simulated chat window.

* **Global Features:**
    * **Role-Based Access:** A mock login screen allows you to select a role and view the corresponding dashboard.
    * **Notification System:** A global notification icon alerts users to unread messages or new events.
    * **Dark/Light Mode:** A theme toggle allows users to switch between light and dark modes for accessibility and user preference.

## Technologies Used

This project was built from the ground up using fundamental web technologies to create a fast, responsive, and dependency-free user experience.

* **HTML5:** For the core structure and content.
* **CSS3 & Tailwind CSS:** For modern styling, layout, and a responsive design that works on all screen sizes.
* **Vanilla JavaScript (ES6+):** For all application logic, including state management, DOM manipulation, and interactivity.
* **Chart.js:** For creating beautiful and interactive data visualizations.
* **Lucide Icons:** For clean and modern iconography throughout the application.

## Getting Started

Since this is a pure front-end prototype, there is no complex setup required.

1.  **Clone the repository:**
    ```bash
    git clone [https://github.com/tabitha-dev/Meditab-prototype.git](https://github.com/tabitha-dev/Meditab-prototype.git)
    ```
2.  **Open the `index.html` file:**
    * Navigate to the project directory and open the `index.html` file in your web browser.

That's it! The application is fully self-contained and will run directly in your browser.

## Usage

1.  **Select a Role:** On the main screen, choose a role (Doctor, Nurse, Manager, or Patient) by clicking on the corresponding card.
2.  **Explore the Dashboard:** Interact with the dashboard specific to the role you selected. Click on patients, update task statuses, view charts, and explore the different features.
3.  **Use Global Features:** Try toggling the theme, checking notifications, or logging out to return to the role selection screen.

## Contributing

This project was created for an academic assignment and is not currently open for external contributions. However, you are welcome to fork the repository and expand upon it for your own projects.

## License

This project is licensed under the MIT License. See the `LICENSE` file for details.
