Electronic Press Kit (EPK) Web App
Overview

This project aims to develop an Electronic Press Kit (EPK) web application for bands. An EPK is a digital package containing information for booking purposes or for media outlets interested in learning more about a band. The web application allows users to manage multiple bands under their account and provides features for creating and editing band EPKs.
Features

    User Authentication: Users can register and log in to the system. Each user can manage multiple bands.
    Dashboard: Users have access to a dashboard where they can view and update their user profile and navigate to the EPKs of the bands they manage.
    Band EPK: Each band EPK consists of a page with a cover photo, a short description, a biography text, and the ability to embed YouTube videos. The background and text colors are customizable.
    Guest Access: Guests can search for bands by name. Search results display band names, short descriptions, and cover photos. Clicking on a band name takes the guest to the band's EPK page.
    Database Schema: The database schema includes tables for users, bands, EPKs, and related entities. There are relational connections between these tables.

Technology Stack

    Framework: Laravel
    Database: MySQL (or preferred database system)
    Frontend: HTML, CSS, JavaScript (with potential framework like Vue.js or React)
    Deployment: The application will be deployed on a web server.

Folder Structure

    app: Contains the application's models, controllers, and other PHP classes.
    database: Contains migrations and seeds for database setup.
    resources: Contains views, assets, and frontend components.
    routes: Contains route definitions.
    tests: Contains test cases (if applicable).

Installation and Setup

    Clone the repository: git clone https://github.com/your-username/epk-web-app.git
    Navigate to the project directory: cd epk-web-app
    Install dependencies: composer install
    Set up environment variables: Copy .env.example to .env and configure the database connection.
    Run migrations: php artisan migrate
    Generate application key: php artisan key:generate
    Serve the application: php artisan serve

Team Collaboration

    The project should be collaborated on by a team of at least two members.
    Each team member is expected to contribute an equal number of commits.
    Utilize Git for version control. Maintain branches and use tags for sprints.
    Use a sprint board to track progress and regularly capture screenshots for documentation.

Demonstration

    The team will demonstrate the working software to the stakeholders.

Additional Requirements

    Documentation: Provide a functional overview document detailing the project's objectives and features.
    Upload Functionality: Implement features for uploading photos or other media files.
    Consultation: Ensure the project meets the specified requirements by consulting with a course instructor.
    Submission: Submit the project via the specified platform in a compressed zip file format.

