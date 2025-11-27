---
title: "Verify service worker registers, activates, and controls the root scope (\"/\")"
story_id: "147"
priority: "P2"
suite: "General"
preconditions: |
  Application is deployed on HTTPS
  Browser: Chrome (Desktop or Android)
  DevTools accessible
steps: |
  Step 1: Open the site
  Go to https://wazobialist.com/
  Important: Use the root / because SW scope is linked to the root.
  If the site loads, you are ready to check if SW exists.
  
  Step 2: Open DevTools → Application → Service Workers
  Open Chrome DevTools (Ctrl+Shift+I / Cmd+Option+I)
  
  Click Application → Service Workers
  Source: sw.js
  Status: Installed and Activated
  Clients: > 0
  
  Step 3: Check the scope
  Scope tells you what parts of the site the SW controls
  For PWA, it should be / → controls all pages
  Example: if you go to /listing/123 later, SW still works
  
  Step 4: Hard Reload
  Press Ctrl+Shift+R (Windows) / Cmd+Shift+R (Mac) or use right-click → Hard Reload
  Why: Some SWs get disabled on normal reloads
  Check if SW stays activated
  Confirm scope still /
  
  Step 5: Unregister + reload
  Click Unregister in DevTools
  Reload page normally
  Check if SW re-registers automatically
  This is important because SW should self-register when the user visits the site.
  
  Step 6: Check console logs
  In DevTools → Console, you may see:
  Service worker registered
  Service worker activated
  
  
  
expected: |
  Navigate to https://wazobialist.com/
   (root /)
  Expected Result: Homepage loads successfully without errors.
  
  Open Chrome DevTools → Application → Service Workers
  Expected Result: Service worker /sw.js is listed, Installed, and Activated.
  
  Check the Scope in Service Workers panel
  Expected Result: Scope shows / (root), meaning it controls all pages.
  
  Perform a Hard Reload (Ctrl+Shift+R / Cmd+Shift+R or right-click → Hard Reload)
  Expected Result: Service worker remains Activated; scope still /.
  
  In DevTools → Service Workers, click Unregister
  Expected Result: Service worker is removed from the list.
  
  Refresh the page normally
  Expected Result: Service worker auto-registers again, status Installed & Activated, scope /.
  
  Open DevTools → Console
  Expected Result: Logs show:
  Service worker registered
  Service worker activated
  
env: "prod"
status: "Draft"
created: "2025-11-25T17:00:46.864Z"
created_by: "QUDUS07"
---

# Verify service worker registers, activates, and controls the root scope ("/")

## Story Reference
Story #147

## Preconditions
Application is deployed on HTTPS
Browser: Chrome (Desktop or Android)
DevTools accessible




## Test Steps
Step 1: Open the site
Go to https://wazobialist.com/
Important: Use the root / because SW scope is linked to the root.
If the site loads, you are ready to check if SW exists.

Step 2: Open DevTools → Application → Service Workers
Open Chrome DevTools (Ctrl+Shift+I / Cmd+Option+I)

Click Application → Service Workers
Source: sw.js
Status: Installed and Activated
Clients: > 0

Step 3: Check the scope
Scope tells you what parts of the site the SW controls
For PWA, it should be / → controls all pages
Example: if you go to /listing/123 later, SW still works

Step 4: Hard Reload
Press Ctrl+Shift+R (Windows) / Cmd+Shift+R (Mac) or use right-click → Hard Reload
Why: Some SWs get disabled on normal reloads
Check if SW stays activated
Confirm scope still /

Step 5: Unregister + reload
Click Unregister in DevTools
Reload page normally
Check if SW re-registers automatically
This is important because SW should self-register when the user visits the site.

Step 6: Check console logs
In DevTools → Console, you may see:
Service worker registered
Service worker activated




## Expected Results
Navigate to https://wazobialist.com/
 (root /)
Expected Result: Homepage loads successfully without errors.

Open Chrome DevTools → Application → Service Workers
Expected Result: Service worker /sw.js is listed, Installed, and Activated.

Check the Scope in Service Workers panel
Expected Result: Scope shows / (root), meaning it controls all pages.

Perform a Hard Reload (Ctrl+Shift+R / Cmd+Shift+R or right-click → Hard Reload)
Expected Result: Service worker remains Activated; scope still /.

In DevTools → Service Workers, click Unregister
Expected Result: Service worker is removed from the list.

Refresh the page normally
Expected Result: Service worker auto-registers again, status Installed & Activated, scope /.

Open DevTools → Console
Expected Result: Logs show:
Service worker registered
Service worker activated


## Metadata
- **Priority**: P2
- **Suite**: General

- **Environment**: prod
