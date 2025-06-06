# Milestone 2
**Table of Contents**
1. [Work Breakdown Structure](#work-breakdown-structure)
2. [Gantt Chart  & Network Diagram](#gantt-chart-and-network-diagram)
3. [Detailed Requirements Document](#detailed-requirements-document)
4. [Fully Dressed Use Cases and Use Case Diagram](#fully-dressed-use-cases-and-use-case-diagram)
5. [Research on other systems](#research-on-other-systems)
6. [API Descriptions](#api-descriptions)

# Work Breakdown Structure

| Task ID | Task Name | Duration (hours) | Start Date | Finish Date | Predecessors |
|---------|------------|-----------------|------------|-------------|--------------|
| 1 | Project Initiation | 8 | 02/05/2025 | 02/06/2025 | - |
| 1.1 | Define Project Scope and Objectives | 4 | 02/05/2025 | 02/05/2025 | 1 |
| 1.2 | Identify Project Stakeholders | 4 | 02/06/2025 | 02/06/2025 | 1 |
| 2 | Requirements Gathering Phase | 40 | 02/07/2025 | 02/13/2025 | 1.1, 1.2 |
| 2.1 | Define Data Collection Methodologies | 16 | 02/07/2025 | 02/09/2025 | 2 |
| 2.1.1 | Conduct Interviews with Stakeholders | 8 | 02/07/2025 | 02/08/2025 | 2.1 |
| 2.1.2 | Collect Survey Responses | 8 | 02/09/2025 | 02/09/2025 | 2.1 |
| 2.2 | Analyze Legal and Compliance Requirements | 12 | 02/10/2025 | 02/11/2025 | 2.1, 2.1.2 |
| 2.2.1 | Review Privacy Regulations | 6 | 02/10/2025 | 02/10/2025 | 2.2 |
| 2.2.2 | Review Security Standards | 6 | 02/11/2025 | 02/11/2025 | 2.2 |
| 3 | Requirements Analysis and Documentation | 30 | 02/14/2025 | 02/20/2025 | 2.2.2 |
| 3.1 | Analyze Stakeholder Input | 12 | 02/14/2025 | 02/16/2025 | 3 |
| 3.1.1 | Analyze Interview Data | 6 | 02/14/2025 | 02/15/2025 | 3.1 |
| 3.1.2 | Analyze Survey Data | 6 | 02/16/2025 | 02/16/2025 | 3.1 |
| 3.2 | Document Functional Requirements | 18 | 02/17/2025 | 02/20/2025 | 3.1.1, 3.1.2 |
| 4 | Database Design and Implementation | 50 | 02/21/2025 | 03/02/2025 | 3.2 |
| 4.1 | Define Database Schema | 20 | 02/21/2025 | 02/25/2025 | 4 |
| 4.1.1 | Define Tables and Relationships | 12 | 02/21/2025 | 02/23/2025 | 4.1 |
| 4.1.2 | Define Data Entry Rules | 8 | 02/24/2025 | 02/25/2025 | 4.1 |
| 4.2 | Database Implementation | 30 | 02/26/2025 | 03/02/2025 | 4.1.1, 4.1.2 |
| 4.2.1 | Create Database Tables | 16 | 02/26/2025 | 02/28/2025 | 4.2 |
| 4.2.2 | Implement Data Entry Rules | 14 | 03/01/2025 | 03/02/2025 | 4.2 |
| 5 | User Interface Design and Development | 70 | 03/03/2025 | 03/16/2025 | 4.2.2 |
| 5.1 | Design User Interface Mockups | 30 | 03/03/2025 | 03/09/2025 | 5 |
| 5.1.1 | Create Mockups for Main Pages | 18 | 03/03/2025 | 03/07/2025 | 5.1 |
| 5.1.2 | Gather Feedback on Mockups | 12 | 03/08/2025 | 03/09/2025 | 5.1 |
| 5.2 | Develop User Interface | 40 | 03/10/2025 | 03/16/2025 | 5.1.2 |
| 5.2.1 | Implement Main Page UI | 24 | 03/10/2025 | 03/14/2025 | 5.2 |
| 5.2.2 | Implement Feedback-Driven Revisions | 16 | 03/15/2025 | 03/16/2025 | 5.2.1 |
| 6 | Backend Development | 90 | 3/17/2025 | 4/3/2025 | 5.2.2 |
| 6.1 | Develop Core System Logic | 40 | 3/17/2025 | 3/24/2025 | 6 |
| 6.1.1 | Implement User Authentication | 18 | 3/17/2025 | 3/20/2025 | 6.1 |
| 6.1.2 | Implement Data Handling Functions | 22 | 3/21/2025 | 3/24/2025 | 6.1 |
| 6.2 | Integrate Database Functionality | 30 | 3/25/2025 | 3/31/2025 | 6.1.2 |
| 6.2.1 | Integrate User Data Handling | 16 | 3/25/2025 | 3/28/2025 | 6.2 |
| 6.2.2 | Integrate Reporting Functionality | 14 | 3/29/2025 | 3/31/2025 | 6.2.1 |
| 6.3 | Implement Security Measures | 20 | 4/1/2025 | 4/3/2025 | 6.2.2 |
| 7 | Integration and Testing | 50 | 4/4/2025 | 4/16/2025 | 6.3 |
| 7.1 | Integrate UI, Backend, and Database | 30 | 4/4/2025 | 04/10/2025 | 7 |
| 7.1.1 | Integrate User Interface and Backend | 18 | 4/4/2025 | 04/07/2025 | 7.1 |
| 7.1.2 | Integrate Database Functionality | 12 | 04/08/2025 | 04/10/2025 | 7.1.1 |
| 7.2 | Conduct System Testing | 20 | 04/11/2025 | 04/15/2025 | 7.1.2 |
| 7.2.1 | Develop Testing Scenarios | 10 | 04/11/2025 | 04/13/2025 | 7.2 |
| 7.2.2 | Perform System Testing | 10 | 04/14/2025 | 04/15/2025 | 7.2.1 |
| 7.3 | Bug Fixing and Final Testing | 10 | 4/16/2025 | 4/16/2025 | 7.2.2 |
| 8 | Security and Compliance Implementation | 30 | 4/17/2025 | 4/21/2025 | 7.3 |
| 8.1 | Data Encryption and Security Measures | 20 | 4/17/2025 | 4/19/2025 | 8 |
| 8.2 | Compliance with Privacy Regulations | 10 | 4/20/2025 | 4/21/2025 | 8.1 |
| 9 | Training Material Development | 20 | 4/22/2025 | 4/25/2025 | 8.2 |
| 9.1 | Create Training Modules | 10 | 4/22/2025 | 4/24/2025 | 9 |
| 9.2 | Develop User Guides | 10 | 4/25/2025 | 4/25/2025 | 9.1 |
| 10 | User Training | 40 | 4/26/2025 | 5/4/2025 | 9.2 |
| 10.1 | Develop Training Schedule | 15 | 4/26/2025 | 4/29/2025 | 10 |
| 10.2 | Conduct Training Sessions | 25 | 4/30/2025 | 5/4/2025 | 10.1 |
| 11 | System Rollout | 20 | 5/5/2025 | 05/08/2025 | 10.2 |
| 11.1 | Pre-Rollout Checklist | 10 | 5/5/2025 | 5/7/2025 | 11 |
| 11.2 | Launch System to Users | 10 | 05/08/2025 | 05/08/2025 | 11.1 |
| 12 | Project Closure and Evaluation | 16 | 05/09/2025 | 05/12/2025 | 11.2 |
| 12.1 | Evaluate Project Success | 8 | 05/09/2025 | 05/10/2025 | 12 |
| 12.2 | Document Lessons Learned | 8 | 05/11/2025 | 05/12/2025 | 12.1 |
| 13 | Documentation and Knowledge Transfer | 36 | 05/13/2025 | 05/17/2025 | 12.2 |
| 13.1 | Create User Manuals | 16 | 05/13/2025 | 05/15/2025 | 13 |
| 13.2 | Develop Technical Documentation | 20 | 05/16/2025 | 05/17/2025 | 13.1 |
| 14 | Post-Implementation Review | 24 | 05/18/2025 | 05/21/2025 | 13.2 |
| 14.1 | Gather User Feedback | 12 | 05/18/2025 | 05/19/2025 | 14 |
| 14.2 | Evaluate System Performance | 12 | 05/20/2025 | 05/21/2025 | 14.1 |
| 15 | Project Closure and Reporting | 20 | 05/22/2025 | 05/26/2025 | 14.2 |
| 15.1 | Finalize Project Documentation | 10 | 05/22/2025 | 05/24/2025 | 15 |
| 15.2 | Generate Project Report | 10 | 05/25/2025 | 05/26/2025 | 15.1 |

[Download Work Breakdown Structure](https://github.com/taylorsharperson/Quantum-Mavericks-StudyBuddy/raw/main/Milestone2.xlsx)

# Gantt Chart & Network Diagram
[Downloadable Project Management File](https://github.com/cis-famu/Quantum-Mavericks-StudyBuddy/raw/main/WBSChart.mpp)

# Detailed Requirements Document
[Downloadable Detailed Requirements File](https://github.com/cis-famu/Quantum-Mavericks-StudyBuddy/blob/main/Detailed%20Requirements%20Document.pdf)
# 1 - Quantum Mavericks  
## Detailed Requirements Document

---

## Functional Requirements

### I. Search & Browse
- Allows students to search for specific classes to view future assignments  
- Enables searching for assignments by title for quick access  
- Provides a browsing feature to view each class with its respective assignments  
- Includes a schedule browsing function to check upcoming deadlines, study sessions, and important dates  

### II. User Interactions
- Students can add assignments manually or through LMS synchronization  
- Allows students to set study sessions for quizzes, tests, or general review  
- Users can modify schedules dynamically to adjust for workload changes  
- Supports study session reminders based on upcoming deadlines and user preferences  

### III. System Updating
- AI generates personalized study recommendations based on past performance and engagement  
- Assignment tracking syncs automatically with the LMS to ensure real-time updates  
- Due dates and submissions are updated in real-time as changes occur in the LMS  
- Teacher recommendations and feedback are pushed to student dashboards  

### IV. Permissions & Role-Based Access Control
- Students can view assignments, study schedules, AI-generated recommendations, and grades  
- Professors can push study recommendations and monitor aggregated study trends  
- Administrators can update system content, manage user roles, and push routine platform updates  
- Role-based access ensures data privacy and restricts certain features based on the user type  

### V. Data Management
- Study history and submission records are stored in a structured and accessible format  
- Tracks assignment completion status seamlessly upon submission  
- Maintains a performance tracking system to show grade trends over time  
- Ensures secure storage of user data with controlled access  

### VI. Integration Requirements
- Canvas LMS integration ensures real-time syncing of assignments, due dates, and grades  
- API interactions facilitate seamless communication between the system and the database  
- The system supports third-party API authentication for secure data access  
- Ensures that updates in the LMS are reflected immediately within the StudyBuddy platform  

---

## Non-Functional Requirements

### I. Performance & Scalability
- The system should support a substantial amount of concurrent users without performance degradation  
- The response time for retrieving assignments, schedules, and AI recommendations should be under a certain number of seconds  
- The system must be able to scale dynamically to accommodate increased user traffic  

### II. Security & Privacy
- User data, including study history and grades, must be encrypted at rest and in transit  
- Role-based access control should be implemented to restrict unauthorized access to sensitive data  
- The platform must comply with FERPA regulations for handling student data  
- Passwords must be stored securely using encryption methods  

### III. Usability & UI
- The platform should have an intuitive and easy-to-use UI that requires minimal training  
- Users should be able to navigate between features within 3 clicks  
- The interface should be responsive and accessible across various environments  
- The system must provide clear feedback and confirmations for user actions (assignments added, schedule updates)  

### IV. Maintainability & Support
- The system codebase must be modular and well-documented for easy maintenance  
- System updates should be deployed with minimal downtime, ideally through rolling updates  
- Logs should be maintained for error tracking and debugging, with automated alerts for critical failures  
- The system should allow for easy integration of new AI models for improved recommendations  

### V. Availability & Reliability
- The system should have a high percentage uptime, excluding scheduled maintenance  
- Automatic failover mechanisms must be in place to handle server failures without significant downtime  
- A backup system should be in place to restore lost or corrupted data within a reasonable time  

### VI. Compatibility & Integration
- The platform must be compatible with major web browsers (Chrome, Firefox, Safari, Edge)  
- StudyBuddy should seamlessly integrate with LMS and future LMS platforms  
- The system should support OAuth authentication for secure third-party integrations  


# Fully Dressed-Use Cases and Use Case Diagram
[Downloadable Use Cases File](https://github.com/cis-famu/Quantum-Mavericks-StudyBuddy/blob/main/StudyBuddy%20Use%20Cases.pdf)

# Research on other systems
[Downloadable Information on Relatable Platforms](https://github.com/cis-famu/Quantum-Mavericks-StudyBuddy/blob/main/Relatable%20Platforms.pdf)
  
---

**StudyBuddy** is an AI-powered study management tool designed to help college students optimize time management, track assignments, and improve academic performance through personalized study schedules, assignment tracking, and AI-driven study recommendations. The platform plans to integrate several student-catered systems into one manageable and user-friendly interface that helps students succeed in their academic careers.

### Learning Management Systems (LMS)

StudyBuddy will implement LMS features similar to popular platforms to support assignment tracking, coursework management, and professor interaction.

- **Canvas**: A widely used LMS that allows assignment tracking, grading, and scheduling  
- **Blackboard**: Offers assignment submissions, discussion boards, and academic scheduling  
- **Moodle**: An open-source LMS used by universities for course and assignment management  

> While these platforms effectively manage assignments and schedules, they lack AI-based study recommendations and detailed study tracking like StudyBuddy.

---

### AI-Powered Study Assistants

StudyBuddy will feature a user-friendly AI assistant to help students optimize their study habits, drawing inspiration from popular tools:

- **Quizlet**: Offers AI-generated flashcards and personalized practice tests  
- **Grammarly**: Provides AI-driven writing suggestions and academic feedback  
- **Cram**: Focuses on memorization and adaptive learning strategies  

> StudyBuddy enhances these concepts by combining content memorization, personalized schedules, and academic time management into one platform.

---

### Task Management & Scheduling

StudyBuddy is also centered around improving productivity and time management, taking inspiration from general task management tools:

- **Google Calendar**: A basic scheduling platform with reminders, not designed for academic-specific needs  
- **Notion**: A flexible planning tool with a complex UI and limited student-focused features  
- **Todoist**: Task manager with reminders and due dates, but lacks LMS integration and AI support  

> These platforms assist with general organization but do not provide AI-driven recommendations or sync with academic systems.

---

### Learning & Tutoring Platforms

StudyBuddy also draws inspiration from educational platforms that support learning and adaptive tutoring:

- **Khan Academy**: Offers personalized learning paths based on progress  
- **Duolingo**: Provides adaptive learning for language acquisition  
- **Coursera**: Recommends courses based on learner preferences  

> Unlike these platforms, StudyBuddy is focused on **personalized study management**, **LMS integration**, and **real-time academic tracking**.

---

**Conclusion**:  
StudyBuddy aims to unify and extend the best features of LMS platforms, AI assistants, task managers, and educational tools — creating a one-stop solution tailored to the unique needs of college students.

# API Descriptions
[Downloadable API Descriptions File](https://github.com/cis-famu/Quantum-Mavericks-StudyBuddy/blob/main/API%20Descriptions.pdf)

I. API Descriptions  
### Learning Management System (LMS) APIs  
Automatically import assignments and deadlines into the platform; track grade progress and notify students of changes  

- Endpoint: /api/v1/courses/{course_id}/assignments  
  Functionality  
  - Retrieves the list of assignments for specific course  
  - Fetch due dates and submission statuses  
  - Pull grade data for performance tracking  

- Endpoint: /api/v1/users/self/enrollments  
  Functionality  
  - Fetch enrolled courses for a student  
  - Sync class schedule and course information  


### II. AI & Machine Learning APIs  
OpenAI API: Analyze study habits and recommend optimal study sessions; suggest topics to review based on past performance  

- Endpoint: /v1/completions  
  Functionality  
  - Generate AI-driven study recommendations based on user input  
  - Suggest focus areas based on previous study sessions and grades  


### III. Calendar & Scheduling APIs  
Allow users to sync their study schedules with Google Calendar; Send push notifications for upcoming deadlines and sessions  

- Endpoint: https://www.googleapis.com/calendar/v3/calendars/{calendarId}/events  
  Functionality  
  - Add study sessions and assignment deadlines to personal calendar  
  - Send reminders for upcoming study sessions  


### IV. User Authentication & Security APIs  
Enable single sign-on (SSO) with university credentials; ensure secure, role-based access for different user types  

- Endpoint: /OAuth/token  
  Functionality  
  - Secure log in using university credentials or third-party authentication (Google, Microsoft, etc)  
  - Ensure role-based access control (students, professors, administrators)  


### V. Notification & Messaging APIs  
Notify students about assignment updates and study reminders; send alerts for recommended study topics based on AI insights  

- Endpoint: /2010-04-01/Accounts/{AccountSid}/Messages.json  
  Functionality  
  - Send SMS reminders for due dates and study sessions  
  - Push AI-generated study tips to users  

- Endpoint: https://fcm.googleapis.com/fcm/send  
  Functionality  
  - Send real-time push notifications to mobile and web users

