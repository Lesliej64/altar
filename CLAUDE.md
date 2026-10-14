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

First AI automation demo (instant lead reply for "Smith Roofing") **works** in Make.com: Google Sheets **Watch Rows** → Gmail **Send an email** (sent from zenkbusinesssupport@gmail.com). Scenario is **ON** (Active) and a live test with a new row (James Carter) got the auto-reply. Fix for the old 404 / "settings couldn't be applied": in the Sheets module use **Search by path** → My Drive → Zenk → "Smith Roofing Demo Leads", sheet `Leads` (ID `16M5AYZ5UJPdRKPUNieQpy-zv460V6IJuqCIgChoF7qs`; columns: Timestamp, Your name, Email, Phone, How can we help?). Screen recording skipped for now (Snipping Tool had no video, Game Bar did nothing; Loom is the fallback). Demo #2 (review requester) **works**: separate Make scenario, Sheets Watch Rows on tab `Completed Jobs` (Date Completed, Customer Name, Email, Job) → Gmail review-request email. Tested OK. Review link in the email is a placeholder. Demo #3 (FAQ chatbot) **works**: Tidio free plan with Lyro AI (Chatbase wanted payment), Live chat channel, knowledge = `ai-automation/demos/smith-roofing-faq.md`. All 3 demos done. Week 2 started: target area Arkadelphia, AR. Prospect list (10 roofers) = Google Sheet "Roofing Prospects - Arkadelphia AR" in Zenk (ID `1i3kMDyM5d64ZRvcCdppJxs5DEWBNv-os-d_c_o88Zc4`) + `ai-automation/prospects-arkadelphia.csv`. Arkadelphia is small, so expand to Malvern / Hot Springs / Hope for more. Note: "Smith Contracting" is a real Arkadelphia business, so consider renaming the demo away from "Smith Roofing" before showing prospects.

## Context

The user is starting two home businesses — see `README.md`:
1. AI automation consulting (`ai-automation/`)
2. Print-on-demand (`print-on-demand/`)
