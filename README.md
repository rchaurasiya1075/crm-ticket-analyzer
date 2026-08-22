# CRM Ticket Analyzer v2

Celerity / HCI Escalation Mail Generator + Analysis Dashboard

## New in v2 (matching your mail format)

- **Separate mails for Celerity and HCI**
- Exact style: Dear Support + Outage Reason summary + Location summary + Detailed tickets list
- Supports your columns:
  - Incident ID, Site Code, State, Submitted Time, CurrentStatus, Owner
  - Remarks, Branch Person Name, Contact, Alternate Number
  - **Down Time Aging**, ETR
- One Site Code → multiple Incident IDs supported
- Open / Resolve / Overall Excel alag-alag paste / upload kar sakte ho
- Auto category from remarks (Fiber Cut, Team Checking, Link up confirmation, Vendor change/NOC, etc.)

## How to use

1. Open call Excel se data copy karke paste karo **ya** file upload
2. Dashboard me State / Reason / ISP wise summary dekh lo
3. **Generate Celerity Mail** ya **Generate HCI Mail** dabao
4. Copy Full Mail → Outlook me paste

## Live Site

After enabling GitHub Pages:

https://rchaurasiya1075.github.io/crm-ticket-analyzer/

## Enable GitHub Pages

Repo → Settings → Pages → Source: Deploy from a branch → `main` / root → Save
