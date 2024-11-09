# PDF Comparison App

## Project Overview
**Project Title:** PDF Comparison App  
**Description:**  
The PDF Comparison App is a web-based tool designed to help users upload PDF files, extract structured data, and compare different versions of similar documents by visualizing the differences using charts or graphs. This tool is intended for industries that require tracking document changes over time, such as contracts, reports, or regulatory documents.

The app is built using **React** (frontend), **Node.js** (backend), and a **MySQL database** for data storage. It integrates an AI model for data extraction and provides a user-friendly interface for comparing document versions.

## Goals
The main objective of the PDF Comparison App is to create an efficient, reliable, and user-friendly platform for:
- Uploading and storing PDF files.
- Extracting and storing structured data from PDFs.
- Comparing and visualizing differences between document versions.

## Setup Instructions
To set up the development environment for the PDF Comparison App:

1. **Clone the Repository:**
   ```bash
   git clone https://github.com/your-username/PDF-Comparison-App.git
   cd PDF-Comparison-App


### Install Dependencies

- **Frontend:** Navigate to the frontend directory and install dependencies.
    ```bash
    cd frontend
    npm install
    ```

- **Backend:** Navigate to the backend directory and install dependencies.
    ```bash
    cd backend
    npm install
    ```

### Database Setup
1. Ensure you have MySQL installed.
2. Create a MySQL database and configure the connection settings in the backend environment file.

### Run the Application

- **Start the backend server:**
    ```bash
    cd backend
    npm start
    ```

- **Start the frontend:**
    ```bash
    cd frontend
    npm start
    ```

### Authentication Setup
Follow the OAuth setup instructions to enable Google sign-in for user authentication.

## Scrum Information
We are using GitHub Projects to manage our Scrum workflow. Our board includes the following columns:

- **Backlog:** Contains tasks and features not yet scheduled for a sprint.
- **To Do:** Tasks that are planned for the current sprint.
- **In Progress:** Tasks currently being worked on.
- **Review:** Completed tasks pending review.
- **Done:** Fully completed tasks.

### Project Board
You can view our project board (https://github.com/paracode2020/CSAI-203-.git).

### Sprint Planning Process
Our project is divided into four sprints, each focusing on a specific feature set:

1. **Sprint 1:** User authentication and profile management.
2. **Sprint 2:** PDF upload and data extraction.
3. **Sprint 3:** Data comparison and visualization.
4. **Sprint 4:** Notifications and additional features.

We use milestones to track sprint progress and assign tasks accordingly.

### Task Assignment
Each task is assigned to team members based on their roles and expertise. Tasks are managed through GitHub Issues, and each sprint is associated with a milestone.

### Roles and Responsibilities
- **Scrum Master:** [Your Name] - Oversees the Scrum process and ensures team efficiency.
- **Product Owner:** [Teammate’s Name] - Manages the product backlog and prioritizes tasks.
- **Development Team:** [List of team members] - Responsible for developing features and meeting sprint goals.

## Team Members
- **[Your Name]** - Scrum Master
- **[Teammate’s Name]** - Product Owner 
- **[Other Teammate’s Name]** - Developer 

## Features and Functional Requirements

1. **User Registration and Authentication:** Secure access using OAuth with Google.
2. **PDF Upload:** Registered users can upload PDF files.
3. **Data Extraction:** AI model extracts structured data from PDFs.
4. **Data Storage:** Extracted data is stored in a MySQL database.
5. **Data Comparison:** Users can compare different PDF versions.
6. **Data Visualization:** Differences displayed as charts or graphs.
7. **Version Management:** History of PDF versions.
8. **Notification System:** Users notified on successful actions.
9. **Settings and Profile Management:** Users can update their profiles.
10. **Help and Documentation:** Access to FAQs and help content.

## Non-Functional Requirements

- **Performance:** Supports simultaneous uploads and comparisons with minimal latency.
- **Scalability:** Designed to handle up to 1000 active users concurrently.

## Tools and Technologies

- **Frontend:** React, Python for data visualization
- **Backend:** Node.js, Express.js for server API
- **Database:** MySQL for structured data storage
- **PDF Extraction:** Python libraries, integrated via API
- **CI/CD:** GitHub Actions for continuous integration and deployment
- **Authentication:** OAuth for secure user login
- **Containerization:** Docker for easy deployment and scalability
