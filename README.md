# MGM Ganesh Utsav 2025 – Event Registration

Live registration form for MGM Ganeshotsav 2025.

## Setup Steps

### 1. Google Sheet
Create a sheet with these exact headers in Row 1:
```
Timestamp | Registrant Name | Registrant Email | WhatsApp No | Building | Wing | Flat No | Volunteer Event | No. of Participants | Participant 1 Name | Participant 1 Age | Participant 1 Events | Participant 2 Name | Participant 2 Age | Participant 2 Events | Participant 3 Name | Participant 3 Age | Participant 3 Events | Participant 4 Name | Participant 4 Age | Participant 4 Events | Participant 5 Name | Participant 5 Age | Participant 5 Events | Participant 6 Name | Participant 6 Age | Participant 6 Events
```

### 2. Apps Script
- Sheet → Extensions → Apps Script
- Paste `doPost` script into Code.gs
- Deploy → New Deployment → Web App
- Execute as: Me | Access: Anyone
- Copy the Web App URL

### 3. Paste URL into index.html
Find this line in `index.html`:
```js
const SCRIPT_URL = "YOUR_APPS_SCRIPT_URL_HERE";
```
Replace with your actual URL. Commit the change.

### 4. Connect to Netlify
- app.netlify.com → Add new site → Import from GitHub
- Select this repo → Deploy
- Done ✅

## Features
- Dynamic participant fields (1–6)
- Duplicate flat detection → updates existing row
- Volunteer event selection
- Mobile responsive
- Ganesh festival themed UI
# MGM-Ganesh-Utsav-Event-Registration-2026
