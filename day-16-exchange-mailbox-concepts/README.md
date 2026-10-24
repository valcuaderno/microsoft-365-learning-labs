# Day 16 — Exchange Mailbox Concepts and Troubleshooting

## Objective
Understand Exchange Online mailbox types, mailbox permissions, and common mailbox support scenarios.

## Lab Environment
- Microsoft 365 / Exchange Online concepts
- Simulated support tickets
- No paid subscription or live tenant changes required

## 1. Mailbox Types

| Type | Purpose |
|---|---|
| User mailbox | Stores an individual user's email, calendar, and related data |
| Shared mailbox | Provides a common mailbox for authorized users |
| Email alias | Additional email address associated with an existing mailbox |
| Distribution group | Distributes messages to its members |

## 2. Mailbox Permissions

| Permission | Purpose |
|---|---|
| Full Access | Open and manage mailbox contents |
| Send As | Send messages that appear to come directly from the mailbox |
| Send on Behalf | Send messages that identify the sender as acting on behalf of the mailbox |

**Important:** Full Access does not automatically grant Send As or Send on Behalf permissions.

## 3. Troubleshooting Workflow

### Shared mailbox is not visible
1. Verify the user and mailbox identities.
2. Confirm the required permission was assigned.
3. Allow time for permission changes to propagate.
4. Check Outlook configuration and test web access if available.

### User cannot send from a shared mailbox
1. Identify whether Send As or Send on Behalf is required.
2. Verify the authorization request.
3. Inspect the existing permissions.
4. Grant only the required permission through an authorized administrator.
5. Test and document the outcome.

### Email is not received
1. Verify the recipient address or alias.
2. Ask the sender to check for a non-delivery report.
3. Check message trace if available.
4. Investigate routing, delivery restrictions, or mailbox configuration based on the evidence.

### Multiple employees need one common inbox
Consider a shared mailbox and grant appropriate access and sending permissions.

### Multiple employees need the same announcement
Consider a distribution group.

## 4. Key Findings
- Mailbox type selection depends on the business requirement.
- Permissions must follow least privilege.
- Receiving email at an alias does not automatically guarantee permission to send from that alias.
- Troubleshooting should be evidence-based.
- Never grant Global Administrator merely to resolve an ordinary mailbox access issue.

## 5. Lab Outcome
Completed eight simulated support-ticket exercises covering mailbox selection, permission troubleshooting, aliases, distribution groups, and email delivery.

## 6. Limitations
This was a conceptual lab using simulated cases. No live Exchange Online configuration was changed. Production procedures should be validated in an authorized environment.

## 7. Skills Practised
- Exchange mailbox concepts
- Permission selection and least privilege
- Shared mailbox troubleshooting
- Basic email delivery investigation
- IT ticket documentation
