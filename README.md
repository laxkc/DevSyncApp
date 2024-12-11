DevSync - .NET MAUI Application
===============================

**DevSync** is a productivity and balance tracking application built with .NET MAUI, designed to help developers maintain a healthy balance between work, education, self-care, relationships, and personal projects. The app provides features like task management, project tracking, and data visualization, with support for both dark mode and light mode themes.

Features
--------

*   **Charts**: Visualize time spent across various categories like Work, Education, Self-care, Relationships, and Projects.
    
*   **Categories**: Organize tasks into categories such as Work, Personal, Health, Family, etc.
    
*   **Task Management**: Easily add, edit, and delete tasks with due dates and priorities.
    
*   **Sidebar Navigation**: Quick access to Projects, Dashboard, and Meta Management sections.
    
*   **Project Management**: Add, list, and track the progress of your ongoing projects.
    
*   **Dark Mode/Light Mode**: Toggle between dark and light themes to match your preference.
    
*   **Dashboard**: Overview of your activities and productivity, with visual representations of time allocation.
    

Technologies Used
-----------------

*   **.NET MAUI**: Cross-platform framework for building native apps for Android, iOS, macOS, and Windows.
    
*   **MVVM Architecture**: Separation of concerns with Models, Views, and ViewModels.
    
*   **SQLite**: Local database for storing tasks and project data, ensuring offline functionality.
    
*   **Charts**: Built-in charting components for displaying visual data regarding activities and progress.
    

Screenshots
-----------

_The Developer Balance Dashboard showing an overview of your activity and time distribution._

_Task management interface where you can add, edit, and track your tasks._

Installation
------------

### Prerequisites

To build and run the Developer Balance app locally, ensure you have the following installed:

*   **.NET SDK 9** or later: [Install .NET](https://dotnet.microsoft.com/download)
    
*   **Visual Studio 2022** or later with the .NET MAUI workload enabled.
    
*   **Xcode** for macOS users or **Android Studio** for Android emulation.
    

Usage
-----

Once the application is running, you can:

*   **Add Tasks**: Go to the Tasks section to add new tasks, categorize them (Work, Personal, Health, etc.), and set priorities.
    
*   **Manage Projects**: Use the Projects section to add, view, and track the progress of your projects.
    
*   **Track Time**: Use the charts on the Dashboard to monitor how much time you're spending in different areas (Work, Education, etc.).
    
*   **Switch Themes**: Toggle between dark and light mode for a personalized UI experience.
    
*   **Manage Meta**: View and modify metadata associated with your tasks and projects, such as due dates or completion status.
    

Code Structure
--------------

*   **Models**: Defines the data structures for Tasks, Projects, and Categories.
    
*   **ViewModels**: Contains business logic for managing tasks, projects, and themes.
    
*   **Views**: XAML files defining the UI components like task list, project list, and dashboard.
    
*   **Services**: Handles data persistence (using SQLite) and manages theme settings.

## Team

- **Laxman KC** (Team Leader)
- **Raj Yadav**
- **Bishesh Basnet**
- **Anmol Singh**