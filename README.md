# Learn With Michael LMS
Version 1.3

Author: Michael Wimmenauer

License: GPL3

Learn With Michael LMS is a robust WordPress plugin designed to help users easily manage courses, lessons, and quizzes on their website. This plugin offers a clean, modern interface with drag-and-drop functionality for course creation and powerful tools for enhancing learning experiences.

## Features
Create and manage courses, lessons, and quizzes with ease.
Modern and futuristic admin interface.
Bulk actions for managing courses, including delete and download options.
AJAX-powered course, lesson, and quiz management.
Debug feature that displays script execution logs.
Optimized for mobile and responsive design.
Error handling and progress loading bar for real-time feedback during operations.

## Installation
Prerequisites
WordPress version 5.6 or higher
PHP version 7.4 or higher
MySQL version 5.6 or higher
Steps
Download the repository.
Upload the plugin folder to /wp-content/plugins/ directory.
Activate the plugin through the Plugins menu in WordPress.
Once activated, navigate to the Learn With Michael LMS section in the WordPress admin dashboard.

## Usage
Create a Course
In the admin dashboard, under Learn With Michael LMS, fill out the form to create a new course by providing a course title and description.

Manage Courses
From the course management section, you can:

Edit or delete existing courses.
Download course details.
Apply bulk actions (delete or download).
Create Lessons and Quizzes
Each course can have lessons and quizzes added via the lesson and quiz creation forms. Drag-and-drop support is provided for easy management.

## File Structure
bash
Copy code
lwm-lms/
│
├── assets/
│   ├── css/
│   │   └── style.css         # Admin styles for the plugin interface
│   └── js/
│       └── script.js         # JavaScript file for handling AJAX operations
│
├── includes/
│   └── admin-page.php        # Main admin page for the LMS interface
│
├── lwm-lms-plugin.php        # Main plugin file
├── readme.md                 # Documentation file
└── uninstall.php             # Clean up when the plugin is uninstalled

## Debugging
To toggle the debug mode and view script execution logs:

Enable the "Debug Mode" option from the plugin settings. Logs of all steps, including pass/fail results, will be shown on the admin page.

## Development
If you are a developer and would like to contribute to this plugin:

Fork the repository.
Create your feature branch: git checkout -b feature-name.
Commit your changes: git commit -m 'Add some feature'.
Push to the branch: git push origin feature-name.
Open a pull request.

## To Do
Implement a drag-and-drop quiz question editor.
Add student enrollment tracking.
Expand error reporting for edge cases.

## License
This plugin is licensed under the GPL-3.0 License. See the LICENSE file for more details.
