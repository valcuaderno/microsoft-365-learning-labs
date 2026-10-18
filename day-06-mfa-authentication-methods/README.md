# Day 6: MFA and Authentication Methods

## Objective
Understand Multi-Factor Authentication (MFA), Microsoft Entra ID authentication methods, and basic MFA troubleshooting.

## Key Concepts

### Authentication
Authentication verifies a user's identity.

### Multi-Factor Authentication (MFA)
MFA requires two or more authentication factors from different categories:
- Something you know, such as a password.
- Something you have, such as a registered security key.
- Something you are, such as a fingerprint.

### Authentication Methods
Examples include Microsoft Authenticator and security keys, depending on the organization's configuration.

### Conditional Access
Conditional Access evaluates sign-in conditions and applies access controls based on configured policies and available licensing.

## Troubleshooting Scenario

**Problem:** An employee lost their registered phone and cannot complete MFA.

**Resolution steps:**
1. Confirm the issue and affected account.
2. Verify the employee's identity using the organization's approved procedure.
3. Check available account recovery options.
4. Follow the approved process to register a new authentication method.
5. Test sign-in and document the outcome.

**Security precautions:**
- Never ask the employee to share their password or one-time MFA code.
- Do not disable MFA for the entire organization to resolve one user's issue.
- Follow least-privilege and approval requirements.

## Lab Checklist
- [ ] Watched an MFA tutorial.
- [ ] Reviewed the key concepts.
- [ ] Completed the simulated troubleshooting scenario.
- [ ] Practiced in an authorized test tenant.
- [ ] Documented the results.

## Lab Status
Learning and documentation in progress. Real configuration is pending until an authorized test environment is available.

## References
- https://learn.microsoft.com/en-us/entra/identity/authentication/
- https://learn.microsoft.com/en-us/entra/identity/authentication/concept-mfa-howitworks
- https://learn.microsoft.com/en-us/entra/identity/conditional-access/overview
