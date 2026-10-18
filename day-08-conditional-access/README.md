# Day 8: Microsoft Entra Conditional Access

## Objective
Understand how Conditional Access evaluates sign-ins and applies access controls.

## Key Concepts
- Assignments: Users, groups, and target resources.
- Conditions: Factors such as location, device, and risk where supported.
- Grant controls: Require MFA, require supported device controls, or block access.
- Report-only mode: Evaluate policy impact without enforcing the policy.
- Least privilege: Apply only the access needed for the task.

## Troubleshooting Scenario
**Problem:** An employee enters their password but receives an MFA prompt.

**Investigation:**
1. Confirm the application and reported error.
2. Determine whether the MFA prompt is expected.
3. Review sign-in logs if authorized.
4. Identify the applicable Conditional Access policy and result.
5. Follow approved authentication and troubleshooting procedures.
6. Document the outcome.

## Safety Notes
- Do not disable a company-wide security policy to resolve an isolated issue.
- Test policy changes carefully and maintain an appropriate emergency-access strategy.
- Policy features and licensing depend on the tenant configuration.

## Lab Status
- [ ] Watched a Conditional Access tutorial.
- [ ] Explained assignments, conditions, and grant controls.
- [ ] Completed the troubleshooting scenario.
- [ ] Tested a policy in an authorized lab, or documented a simulation.
- [ ] Saved notes and evidence.

## References
- https://learn.microsoft.com/en-us/entra/identity/conditional-access/overview
- https://learn.microsoft.com/en-us/entra/identity/conditional-access/concept-conditional-access-report-only
