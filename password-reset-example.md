# Password Reset Example

## Ticket Title

User requested password reset for Microsoft 365 account

---

## Ticket Information

| Field | Details |
|---|---|
| User | Example User |
| System | Microsoft 365 / Entra ID |
| Issue Type | Password Reset |
| Priority | Medium |
| Status | Resolved |

---

## Issue Summary

The user contacted the help desk because they were unable to sign into their Microsoft 365 account. The user stated that their current password was not being accepted.

---

## User Impact

The user was unable to access Microsoft 365 services, including Outlook, Teams, OneDrive, and SharePoint.

---

## Environment

- Microsoft 365 account
- Microsoft Entra ID
- Standard user account
- MFA enabled
- User accessing services from company workstation

---

## Troubleshooting Steps

1. Verified the user’s identity according to internal support procedures.
2. Confirmed the username being used for sign-in.
3. Checked the user account status in the admin portal.
4. Confirmed the account was not disabled.
5. Confirmed whether the account was locked.
6. Performed a password reset.
7. Required the user to change the temporary password at next sign-in.
8. Had the user attempt to sign in with the temporary password.
9. Confirmed MFA prompt was completed successfully.
10. Verified access to Outlook and Teams.

---

## Findings

The user account was active. The password reset was completed successfully, and the user was able to sign in after updating their password.

---

## Root Cause

The user was unable to authenticate with their previous password. The exact cause was not confirmed, but the issue was resolved through a password reset.

---

## Resolution

Reset the user’s Microsoft 365 password and required a password change at next sign-in. The user successfully created a new password and accessed Microsoft 365 services.

---

## User Communication

The user was informed that their password was reset and that they would be prompted to create a new password during sign-in.

The user was reminded not to share passwords and to use a secure password that meets company policy.

---

## Follow-Up Notes

Confirmed the user could access Outlook and Teams after the password reset.

No further sign-in issues were reported.

---

## Closure Summary

Verified user identity, reset Microsoft 365 password, confirmed successful sign-in, and validated access to Microsoft 365 services. Ticket resolved.
