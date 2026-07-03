This project automates the client onboarding process by designing and deploying a 3-step linear automation pipeline using either Make. The goal is to eliminate manual tasks by triggering an automated workflow the moment a new client is logged in a spreadsheet.Pipeline Workflow1

The automation follows a 3-step continuous chain:1
Spreadsheet Trigger (Google Sheets): Watch for new rows containing client details (Client Name, Company Name, and Client Email).1
Cloud Folder Creator (Google Drive): Automatically create a new folder for the client. The folder must be dynamically named using the format: [Company Name] - Project Files.1
Email Delivery (Gmail/Email): Automatically send an onboarding email to the client using the email address from Step 1. The body must include the unique web link to the folder created in Step 2.1
Deliverables

The implementation contains the following assets which are attached:
1. Workflow Blueprint: An exported .json or blueprint file of the completed configuration.
2. Walkthrough Video: A screen recording (under 2 minutes) demonstrating the workflow execution from data entry in the spreadsheet to the final email delivery.1
3. Screenshorts.
