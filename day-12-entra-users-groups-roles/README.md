# Day 12 — Microsoft Entra ID Users, Groups, and Roles

## 1. Objective

Understand how Microsoft Entra ID users, groups, and administrative roles support access management, RBAC, and the principle of least privilege.

## 2. Lab Environment

- **Platform:** Microsoft Entra admin center
- **Lab type:** Read-only inspection and simulated access-management scenario
- **Group inspection:** Completed
- **User Administrator role inspection:** Completed
- **Permissions changed:** None

## 3. Key Concepts

### Users

User accounts represent identities that can access organizational resources.

### Groups

Groups organize users or devices. They can simplify access management and assignments when configured appropriately.

### Administrative Roles

Administrative roles provide specific permissions to perform management tasks.

Examples:
- **User Administrator:** Manages many user-account tasks within the role's defined permissions.
- **Global Administrator:** Has broad administrative authority across Microsoft Entra ID and other supported services.

### Role-Based Access Control (RBAC)

RBAC assigns permissions through roles based on responsibilities.

### Principle of Least Privilege

Users and administrators should receive only the permissions needed for their assigned tasks.

## 4. Lab Procedure

1. Open the Microsoft Entra admin center.
2. Navigate to Entra ID → Groups → All groups.
3. Open an authorized group and inspect its details.
4. Navigate to Entra ID → Roles & admins.
5. Open User Administrator and review its description.
6. Compare its scope with Global Administrator.
7. Record the findings without changing assignments or permissions.

## 5. Findings

| Check | Result |
|---|---|
| Group details | Viewed |
| User Administrator role | Viewed |
| Understanding of least privilege | Needs further practice |
| Configuration changes | None |

## 6. Simulated Access-Management Scenario

**Scenario:** Five new IT support staff need to be organized into a group. An authorized administrator needs to manage user accounts without having unrestricted tenant-wide permissions.

**Proposed approach:**

1. Create or use an appropriate IT support group, subject to authorization.
2. Determine the specific administrative tasks required.
3. Select a role whose permissions cover those tasks.
4. Configure the appropriate assignment separately, following organizational policy.
5. Verify that access is limited to the intended responsibilities.

**Security note:** Group membership alone does not automatically grant Entra administrative privileges. Any role assignment must be configured and authorized separately.

## 7. Troubleshooting and Security Considerations

- Avoid assigning Global Administrator when a more limited role is sufficient.
- Review role permissions before assigning a role.
- Follow organizational approval procedures for privileged access.
- Do not modify production access settings during a read-only learning exercise.
- Remember that even a limited administrative role can have significant permissions.

## 8. What I Learned

I learned that groups organize users, while administrative roles determine what authorized administrators can do.

RBAC helps align permissions with responsibilities, and least privilege reduces unnecessary access and the potential impact of mistakes or compromised accounts.

I also learned that group membership and administrative role assignments are separate concepts.

## 9. Lab Status

- [x] Inspected a group
- [x] Inspected the User Administrator role
- [x] Identified the difference between groups and roles
- [x] Reviewed the least-privilege principle
- [ ] Practiced selecting a role based on a detailed task list
- [ ] Verified a configured role assignment in an authorized lab

**Status:** Initial inspection completed; further practical role-selection exercises recommended.
