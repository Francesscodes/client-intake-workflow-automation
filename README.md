
Overview

This repository documents a Zapier automation that streamlines client or project intake by automatically creating a structured workspace and task entry the moment a Google Form is submitted.

The workflow ensures that every new request is properly logged, organized, and ready for execution—without manual setup.

Use Case- Client onboarding, Project intake forms, Service requests, Internal task submissions, Operations and workflow automation

Tools & Technologies : Zapier, Google Forms, Google Sheets, Google Drive, Monday.com

Workflow Breakdown : Trigger: Google Forms, Event: New Form Response, Captures incoming client or project details in real time

 Data Reset: Google Sheets: Action: Clear Spreadsheet Row(s), Resets or cleans specific rows to prevent data duplication or conflicts in subsequent runs

Workspace Creation: Google Drive: Action: Create Folder, Automatically creates a dedicated folder for each client or project, Can be named dynamically using form responses (e.g., Client Name or Project Title)

Project Tracking: Monday.com- Action: Create Item, Creates a new task or project entry on a Monday.com board, Links intake data to ongoing work and execution

 Benefits- Eliminates manual setup after form submissions, Creates consistent folder structures, Improves project visibility and accountability, Reduces operational friction for teams, Scales easily as request volume grows

Repository Structure
/
├── README.md
├── zap-workflow.png   # Screenshot of the Zapier automation

Security & Privacy - No API keys or credentials are stored in this repository, Automation logic is documented for educational and portfolio purposes only

 Future Enhancements - Add automatic Slack or email notifications, Attach Google Drive folder links to Monday.com items, Log submissions in Airtable or Notion, Add conditional paths for different service types

 Author
Francess Ekezie
