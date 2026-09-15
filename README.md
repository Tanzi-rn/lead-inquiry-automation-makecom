# Lead Inquiry Automation (Make.com)

## Overview
An automated workflow that detects new lead form submissions and instantly notifies the team via email — eliminating the need to manually check a spreadsheet for new inquiries.

## Problem It Solves
Manually monitoring a lead-inquiry spreadsheet for new submissions is slow and easy to miss. This automation removes that delay, ensuring every new lead is flagged the moment it comes in.

## How It Works
1. **Trigger:** A user submits a Google Form (name, qualification, email, phone, message).
2. **Data capture:** Responses are automatically logged into a linked Google Sheet.
3. **Automation:** A Make.com scenario watches the Sheet for new rows.
4. **Notification:** When a new row appears, Make.com automatically sends an email containing the lead's full details.

**Flow:** `Google Form → Google Sheet → Make.com (Watch New Rows) → Gmail (Send Email)`

## Tools Used
- Google Forms — data collection
- Google Sheets — data storage
- Make.com — automation/workflow engine
- Gmail API — notification delivery

## Files in This Repo
- `Integration Google Sheets.blueprint.json` — exported Make.com scenario blueprint
- `Screenshot ...103849.png` — visual of the working scenario (Google Sheets → Gmail)
- `Screenshot ...104008.png` — example of the automated notification email received

## Impact
Converts a manual, delay-prone check into an instant, reliable notification — a small-scale example of how repetitive operational tasks can be automated end-to-end.

## Notes
This is a demo/trial project built to practice production-style automation workflows using no-code tools, ahead of applying for roles requiring hands-on automation experience.
