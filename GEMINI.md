# UiTM E-Course Portal Prototype

## Project Overview
This project is a standalone, responsive web-based prototype for the **UiTM E-Course Portal**. It is designed as a single-page application (SPA) to demonstrate the user interface and interactions for student course registration, financial management, and dashboard monitoring.

## Technology Stack
*   **HTML5:** Structure and semantic markup.
*   **CSS3:** Styling, using CSS Variables (`:root`), Flexbox, CSS Grid, and Media Queries for responsiveness.
*   **JavaScript:** Client-side logic for navigation, modal management, simulated data interactions, and dynamic content updates.
*   **External Dependencies:**
    *   [Font Awesome 6.4.0](https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css) (via CDN) for icons.

## Key Features

### 1. Dashboard
*   **Real-Time Seat Tracker:** Visual progress bars simulating course availability.
*   **Financial Status:** Quick view of outstanding balance.
*   **Countdown Timer:** Displays the remaining time for the "Add/Drop" deadline.

### 2. Course Registration
*   **Course List:** Displays available courses with code, name, and group.
*   **Course Details Modal:** View detailed information like lecturer, venue, and time.
*   **Add Course Logic:** Simulates registering for a course, updating button states and total credit hours.

### 3. Financial Module
*   **Payment Simulation:** Modal to select payment method (Maybank2U, CIMB Clicks) and simulate a successful transaction.
*   **Deferment Application:** Modal to apply for fee deferment.
*   **Document Upload:** Simulated file input for sponsoring documents.

### 4. User Support
*   **Live Chat:** A toggleable chat box with simulated bot responses.
*   **Responsive Design:** Sidebar acts as a drawer on mobile devices with an overlay.

## Usage
Since this is a standalone HTML file, no build process is required.

1.  **Open:** Simply double-click `e-course-registration.html` to open it in any modern web browser (Chrome, Firefox, Edge, Safari).
2.  **Edit:** Open the file in any text editor (VS Code, Notepad++, Sublime Text) to modify the code.

## Development Notes
*   **Inline Code:** All CSS and JavaScript are contained within the `<style>` and `<script>` tags in the HTML file for portability.
*   **Simulated Data:** Data for courses and interactions are hardcoded in the JavaScript section (`availableCourses` array).
*   **Responsiveness:** The layout automatically adjusts for mobile screens (max-width: 768px).
