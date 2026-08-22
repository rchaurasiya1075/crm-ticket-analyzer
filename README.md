# CRM Ticket Analyzer

Excel jaisa web tool for CRM ticket analysis + Escalation mail generator.

## Features

- **Paste Excel data** (Ctrl+C from Excel → Ctrl+V) or upload `.xlsx` / `.csv`
- Auto column detection (Owner, Assign time, Comment, State, Resolved/Close, Caller...)
- **Dashboard**: Total / Open / Hold / Resolved, total & average downtime
- **Location (State) wise** open tickets + total downtime hours
- **Category / Reason** auto detection from remarks:
  - Pending FE Assignment
  - Awaiting Hughes / Customer Confirmation
  - Link Up – Pending Confirmation
  - Power / Fiber / Equipment issues
  - Other
- **Open tickets table** with Severity (Critical >24h, High 8-24h, Medium 4-8h, Low <4h)
- **Escalation Mail Formats** ready to copy-paste:
  - Individual mail per open ticket
  - Combined summary mail for all open tickets
- Resolved tickets analysis (average resolution time)
- 100% client-side – data browser me hi rehta hai, server pe nahi jata

## How to use

1. Excel se data select karke **Copy**
2. Site pe paste box me **Paste** → **Parse Pasted Data**
3. Ya file upload karo
4. Dashboard + Table + Escalation mails auto ban jayenge
5. Severity ke hisab se Critical tickets pehle escalate karo

## GitHub Pages pe host

1. Is repo ko fork / clone karo
2. Settings → Pages → Source: Deploy from branch `main` / root
3. 1-2 minute me site live ho jayegi: `https://<username>.github.io/crm-ticket-analyzer/`

## Local test

Sirf `index.html` browser me open karo (file:// se bhi chalega, lekin clipboard ke liye modern browser better).

---

Made for Xtranet / FE Rollout Partner ticket tracking.
