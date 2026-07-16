#Google Drive File Sharing Automation


A simple n8n workflow that automatically shares a Google Drive file and creates a record in Airtable.

## Features
- 📂 Monitors Google Drive for newly uploaded files.
- 🔗 Automatically shares the uploaded file.
- 📝 Saves the file information as a record in Airtable.
- ⚡ Built with n8n.


## Workflow Architecture

```text
┌─────────────────────┐
│ Google Drive Folder │
└──────────┬──────────┘
           │
           ▼
┌─────────────────────┐
│ Detect New File     │
└──────────┬──────────┘
           │
           ▼
┌─────────────────────┐
│ Share File          │
│ with Recipient      │
└──────────┬──────────┘
           │
           ▼
┌─────────────────────┐
│ Save Metadata       │
│ to Airtable         │
└─────────────────────┘
```
## Workflow Preview

![Workflow](screenshots/workflow-success.png)

