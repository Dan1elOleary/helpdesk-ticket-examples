# MFA Reset Example

## Ticket Title

User unable to complete Microsoft 365 MFA verification

---

## Ticket Information

| Field | Details |
|---|---|
| User | Example User |
| System | Microsoft 365 / Entra ID |
| Authentication Method | Microsoft Authenticator |
| Priority | Medium |
| Status | Resolved |

---

## Issue Summary

The user reported that they were unable to complete multi-factor authentication when signing into Microsoft 365. The user recently changed phones and no longer had access to the previous Microsoft Authenticator registration.

---

## User Impact

The user was unable to access Microsoft 365 services, including Outlook, Teams, and OneDrive. This prevented the user from accessing email, meetings, and company files.

---

## Environment

- Microsoft 365 account
- Microsoft Entra ID authentication
- Microsoft Authenticator app
- New mobile device
- Standard user account

---

## Troubleshooting Steps

1. Verified the user’s identity according to internal support procedures.
2. Confirmed the user no longer had access to the previous authentication device.
3. Reviewed the user’s sign-in issue.
4. Accessed the Microsoft Entra admin center.
5. Located the user account.
6. Reviewed registered authentication methods.
7. Removed the outdated Microsoft Authenticator registration.
8. Required the user to re-register MFA.
9. Guided the user through installing and setting up Microsoft Authenticator on the new phone.
10. Confirmed successful MFA registration.
11. Had the user test sign-in to Microsoft 365.

---

## Findings

The user’s previous MFA method was still tied to an old mobile device. Since the user no longer had access to that device, they could not approve sign-in prompts.

---

## Root Cause

The user replaced their mobile phone and did not have Microsoft Authenticator restored or re-registered on the new device.

---

## Resolution

The outdated MFA method was removed from the user’s account. The user completed MFA registration on the new mobile device and successfully signed into Microsoft 365.

---

## User Communication

The user was informed that their old authentication method was removed and replaced with a new Microsoft Authenticator registration.

The user was reminded to contact IT before replacing or wiping a phone used for MFA when possible.

---

## Follow-Up Notes

Recommended that the user add a backup authentication method if permitted by company policy.

Confirmed successful access to Outlook and Teams after MFA re-registration.

---

## Closure Summary

Reset the user’s MFA registration, assisted with Microsoft Authenticator setup on the new device, and confirmed successful Microsoft 365 sign-in. Ticket resolved.
