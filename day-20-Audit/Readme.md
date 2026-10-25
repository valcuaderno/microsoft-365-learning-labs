
## Lab 01 — Investigate Security Events

### Step 2: Inspect a Security Event
- **Environment:** Windows 10 Pro VM
- **Tool:** Event Viewer
- **Log:** Windows Logs > Security
- **Event ID inspected:** 4624, if available
- **Purpose:** Understand how to inspect Windows security events.
- **Fields reviewed:** Logged time, account name, logon type, and source details if present.
- **Changes made:** None; read-only inspection.
- **Result:** Pending verification.

### Security Notes
- Do not publish usernames, source IPs, or other sensitive event details.
- Do not clear event logs or change audit policies during this lab.

### Interpret Logon Type
- Event ID: 4624
- Logon Type: [your number]
- Meaning: [reference table description]
- Security interpretation: A successful logon was recorded.
- Configuration changes: None
- Evidence: Screenshot of Event Properties with sensitive details hidden.

- 
### Step 6: Record Investigation Findings
- Event ID: 4624
- Logon Type: 2 — Interactive
- Account and timestamp: Matched expected lab activity
- Event source: [record the displayed source]
- Security log modified: No
- Audit settings changed: No

### Conclusion
Inspected a successful interactive logon in Windows Event Viewer.
The account and timestamp matched expected lab activity.
No configuration changes were made.

# Day 20 — Security and Audit Basics

## Lab 01: Investigate Security Events

### Findings
- Operating system: Windows 10 Pro VM
- Tool: Event Viewer
- Log: Windows Logs > Security
- Event ID: 4624
- Event meaning: Successful logon
- Logon Type: 2 — Interactive logon
- Account and timestamp: Matched expected lab activity
- Source: Windows Security Auditing
- Security log cleared: No
- Audit settings changed: No

### Conclusion
Inspected a successful interactive logon using Windows Event Viewer.
Reviewed the event details and confirmed that the account and
timestamp matched expected lab activity.

### Skills Practiced
- Navigating Windows Security logs
- Identifying event IDs
- Interpreting logon types
- Reviewing event metadata
- Documenting security investigations
