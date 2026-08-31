# Intelligent Automated Project Monitoring and Approval Workflow System

**Student:** W.M.S. Udeshika  
**Student ID:** 15022  
**Module:** COM4901 Final Year Project

## Project Overview

This project is an Intelligent Automated Project Monitoring and Approval Workflow System developed using Microsoft Power Platform and GitHub.

The system provides a centralized solution for project submission, approval, monitoring, notifications, document processing, development tracking, and reporting.

## Technologies Used

- Microsoft Power Apps
- Microsoft Dataverse
- Microsoft Power Automate
- Microsoft AI Builder
- Microsoft Power BI
- GitHub
- Office 365 Outlook

## Main Features

- Project submission through Power Apps
- Role-based access for Submitter, Approver, and Administrator
- Automated approval and rejection workflow
- Email notifications for project submission and decisions
- Pending project approval reminders
- Approval history tracking
- Automatic GitHub issue creation
- AI Builder document information extraction
- Power BI project monitoring dashboard
- Mobile dashboard layout

## Power Automate Flows

1. Project Approval Routing
2. Project Submit Notification
3. Approval Decision Notification
4. Pending Project Reminder
5. GitHub Issue Creator
6. AI Document Processing

## Power BI Results

The final dashboard contains 24 project records:

- Approved: 20
- Pending: 1
- Rejected: 3

## Testing

The implemented functions were tested using 16 functional test cases.

- T01–T15: Pass
- T16 AI Document Processing: Partial

The AI Builder model successfully extracted several project fields, but the Date field showed an accuracy limitation during the final test.

## Limitations

- Formal multi-user pilot testing was not conducted.
- Role testing was performed using controlled role switching.
- GitHub integration is currently one-way.
- AI Builder requires further training for better generalization.
- Predictive risk modelling was not implemented.
- The system has not been deployed as an enterprise production system.

## Deployment

The Microsoft Power Platform solution is included in this repository:

`Project_Monitoring_System_15022_Solution.zip`

The solution can be imported into a Microsoft Power Platform environment and the required connections can then be authenticated and configured.

## Security

No passwords, access tokens, or private credentials are included in this repository.

## Author

W.M.S. Udeshika  
Student ID: 15022
