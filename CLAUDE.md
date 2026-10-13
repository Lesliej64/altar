# Instructions for Claude

## Where to save the user's work

Save every document, plan, or deliverable you create for the user to the **Zenk** folder in their Google Drive, as a Google Doc (or Sheet/Slides when that fits better):

- Folder: Zenk — https://drive.google.com/drive/folders/1rc67LcXCCz92R732uCY5I1S8IRjAszLk
- Folder ID: `1rc67LcXCCz92R732uCY5I1S8IRjAszLk` (pass as `parentId` when creating files)

Also keep a copy in this repo as before.

## Where to send email

Send all business email (plans, documents, updates about the businesses) to the user's business Gmail: **zenkbusinesssupport@gmail.com**. Do not send business email to their personal address.

## How to talk to the user

Keep answers short and simple. One step at a time. No long lists. Ask what device they're on (phone or computer) before giving device-specific steps.

## Where we left off

First AI automation demo (instant lead reply for "Smith Roofing") **works** in Make.com: Google Sheets **Watch Rows** → Gmail **Send an email** (sent from zenkbusinesssupport@gmail.com). Scenario is **ON** (Active) and a live test with a new row (James Carter) got the auto-reply. Fix for the old 404 / "settings couldn't be applied": in the Sheets module use **Search by path** → My Drive → Zenk → "Smith Roofing Demo Leads", sheet `Leads` (ID `16M5AYZ5UJPdRKPUNieQpy-zv460V6IJuqCIgChoF7qs`; columns: Timestamp, Your name, Email, Phone, How can we help?). Next: record a short screen video of the demo to show prospects.

## Context

The user is starting two home businesses — see `README.md`:
1. AI automation consulting (`ai-automation/`)
2. Print-on-demand (`print-on-demand/`)
