# Day 9: Microsoft Entra ID Sign-in Logs

## Objective
Learn to investigate sign-in failures using Entra ID sign-in logs.

## Key Concepts
- User and application identify the sign-in context.
- Status indicates whether sign-in succeeded or failed.
- Authentication details show which steps succeeded or failed.
- Conditional Access results help identify policy-related blocks.

## Simulated Scenario
**Problem:** An employee enters the correct password but cannot sign in.

**Evidence:**
- Password authentication: Successful
- MFA: Not completed
- Conditional Access: Failure

**Investigation steps:**
1. Confirm the affected user, application, and approximate time.
2. Review the sign-in event if authorized.
3. Check authentication details and the applicable Conditional Access policy.
4. Follow the approved process to restore access.
5. Retest and document the result.

## Lab Checklist
- [ ] Watched a sign-in logs tutorial.
- [ ] Learned the main event fields.
- [ ] Completed the simulated scenario.
- [ ] Reviewed real logs in an authorized tenant, if available.
- [ ] Saved the notes to GitHub.

## Lab Status
Simulated practice unless a real tenant was actually used.

## Reference
https://learn.microsoft.com/en-us/entra/identity/monitoring-health/concept-sign-ins
