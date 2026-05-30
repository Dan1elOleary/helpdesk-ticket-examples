# Printer Mapping Example

## Ticket Title

User unable to print to department network printer

---

## Ticket Information

| Field | Details |
|---|---|
| User | Example User |
| Device Name | LAPTOP-001 |
| Operating System | Windows 11 |
| System | Network Printer |
| Priority | Low |
| Status | Resolved |

---

## Issue Summary

The user reported that they were unable to print to the department printer. The printer was not listed as an available printer on the user’s workstation.

---

## User Impact

The user was unable to print required documents from their workstation, which interrupted normal department workflow.

---

## Environment

- Windows 11 laptop
- Network printer
- Corporate network connection
- Standard user permissions
- Department printer queue

---

## Troubleshooting Steps

1. Confirmed the printer name and location with the user.
2. Verified that the user was connected to the corporate network.
3. Checked whether the printer appeared under **Settings > Bluetooth & devices > Printers & scanners**.
4. Confirmed that other users could print to the same printer.
5. Verified that the printer was powered on and online.
6. Attempted to add the printer manually.
7. Connected to the printer using the printer queue path.
8. Installed the required printer driver if prompted.
9. Printed a test page.
10. Had the user print a test document from their application.

---

## Findings

The printer was online and available to other users. The issue was isolated to the user’s workstation because the printer queue was not mapped.

---

## Root Cause

The department printer had not been added to the user’s Windows profile.

---

## Resolution

The network printer was manually added to the user’s workstation. A test page was printed successfully, and the user confirmed they could print from their application.

---

## User Communication

The user was informed that the printer had been added to their workstation and was available for use.

The user was also shown where to select the printer when printing from applications.

---

## Follow-Up Notes

No additional printing issues were reported.

If the printer disappears again, additional troubleshooting may be needed for printer deployment policy, print server connectivity, or user profile issues.

---

## Closure Summary

Mapped the department network printer to the user’s workstation and confirmed successful printing. Ticket resolved.
