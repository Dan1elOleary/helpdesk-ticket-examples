# VPN Connectivity Example

## Ticket Title

User unable to connect to company VPN

---

## Ticket Information

| Field | Details |
|---|---|
| User | Example User |
| Device Name | LAPTOP-001 |
| Operating System | Windows 11 |
| System | Company VPN |
| Priority | Medium |
| Status | Resolved |

---

## Issue Summary

The user reported that they were unable to connect to the company VPN while working remotely. The VPN client displayed a connection failure message.

---

## User Impact

The user was unable to access internal company resources, including file shares, internal applications, and remote management tools.

---

## Environment

- Windows 11 laptop
- Remote network connection
- Company VPN client
- Microsoft 365 account
- MFA enabled

---

## Troubleshooting Steps

1. Confirmed the error message with the user.
2. Verified the user had an active internet connection.
3. Confirmed the user could access public websites.
4. Restarted the VPN client.
5. Restarted the workstation.
6. Confirmed the user was entering the correct username.
7. Verified MFA approval was being completed.
8. Checked whether the VPN client was updated.
9. Tested VPN connection again.
10. Confirmed successful connection.
11. Verified access to internal resources after VPN connection.

---

## Findings

The user had working internet access, and the issue was limited to the VPN connection. After restarting the VPN client and workstation, the user was able to reconnect successfully.

---

## Root Cause

The VPN client appeared to be stuck in a failed connection state. Restarting the client and workstation cleared the issue.

---

## Resolution

Restarted the VPN client and workstation, then confirmed the user could successfully connect to the VPN and access internal resources.

---

## User Communication

The user was informed that the VPN client appeared to have been stuck and that restarting the application and workstation resolved the issue.

The user was advised to restart the VPN client first if the issue occurs again.

---

## Follow-Up Notes

If the issue repeats, additional troubleshooting may be needed for VPN client updates, cached credentials, MFA prompts, network restrictions, or firewall settings.

---

## Closure Summary

Resolved VPN connectivity issue by restarting the VPN client and workstation. Confirmed successful VPN connection and access to internal resources. Ticket resolved.
