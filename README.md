# powerautomate
1. Migrate Files from Sharepoint to PostgreSQL
- Trigger: When a file is created or modified in a folder (SharePoint).
- Action: Get file content (SharePoint).
- Action: Parse CSV (if the file is a CSV).
- Action: Insert row (PostgreSQL).
Example Flow Configuration
Trigger:
Site Address: Your SharePoint site URL.
Folder: The folder to monitor.
Get File Content:
File Identifier: Select from dynamic content.
Parse CSV (if applicable):
Content: Select the file content from the previous step.
Insert Row:
Connection Name: Your PostgreSQL connection.
Table: The table where you want to insert the data.
Columns: Map the parsed data to the appropriate columns.
