# PR Automation with n8n

This project contains demo workflows built with [n8n](https://n8n.io).

## Workflows
- **email-routing.json** → Routes incoming emails to the right mailbox.  
- **follow-up.json** → Sends follow-up emails if no response is received.  
- **google-calendar-scheduler.json** → Automatically schedules meetings when someone replies.  

## How to Use
1. Open [n8n](https://n8n.io) (self-hosted or cloud).  
2. Create a new workflow.  
3. Use **Import from File** and select one of the JSON files from the `workflows/` folder.  
