# Milestone 2
**Table of Contents**
1. [Work Breakdown Structure](#work-breakdown-structure)
2. [Gantt Chart  & Network Diagram](#gantt-chart-and-network-diagram)
3. [Detailed Requirements Document](#detailed-requirements-document)
4. [Fully Dressed-Use Cases](#fully-dresses-use-cases-and-use-case-diagram)
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

# Fully Dressed-Use Cases and Use Case Diagram
[Downloadable Use Cases File](https://github.com/cis-famu/Quantum-Mavericks-StudyBuddy/blob/main/StudyBuddy%20Use%20Cases.pdf)

# Research on other systems
[Downloadable Information on Relatable Platforms](https://github.com/cis-famu/Quantum-Mavericks-StudyBuddy/blob/main/Relatable%20Platforms.pdf)

# API Descriptions
[Downloadable API Descriptions File](https://github.com/cis-famu/Quantum-Mavericks-StudyBuddy/blob/main/API%20Descriptions.pdf)
