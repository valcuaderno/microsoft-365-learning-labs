
# Day 21 — PowerShell System Inventory

## Environment
- OS: Windows 10 Pro VM
- Tool: Windows PowerShell
- Privilege: Standard user

## Commands Tested
- `$env:COMPUTERNAME`
- `whoami`
- `Get-ComputerInfo`
- `Get-NetIPConfiguration`

## Results
- Computer name: [record privately or use a placeholder]
- Windows version: [record]
- Architecture: [record]
- Network configuration retrieved: Yes / No

## Safety
- Read-only commands used
- No network or security settings changed
- Sensitive information excluded from public evidence
## Step 2 — Windows Service Inventory

- Listed Windows services: Success / Failed
- Counted services: [Enter result]
- Listed running services: Success / Failed

## Security relevance
Service inventory is a foundation for investigating
unexpected or suspicious Windows services.

## Safety
- Read-only commands used.
- No services were modified.
- Sensitive information excluded from public evidence.
