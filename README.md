# googlecloudSDK-app-engine-python
# Deployment on Google Cloud App Engine
## Live URL
https://assignmentcc1.el.r.appspot.com

This repository documents the step-by-step process of deploying a Python (Flask) application
to Google Cloud App Engine using Google Cloud SDK.

## Tech Stack
- Python 3.11
- Flask
- Google Cloud App Engine (Standard)
- Google Cloud SDK

## Steps Followed

1. Installed Google Cloud SDK
2. Created a Google Cloud project using gcloud
3. Enabled Billing (required for App Engine)
4. Enabled 2-Step Verification (MFA) on Google account
5. Created required files:
   - app.yaml
   - main.py
   - requirements.txt
6. Updated runtime to python311 (python39 is deprecated)
7. Fixed IAM permissions for App Engine service account
8. Deployed

## Common Errors & Fixes

### Billing Not Enabled
App Engine requires billing even for free-tier usage.

### Runtime Error
`python39` is no longer supported. Updated to `python311`.

### Cloud Build Permission Error
Fixed by granting Storage Admin and Cloud Build roles

   
