# Lab 1: Software Installation & NTFS Permissions

[Recording Link](./Lab-01-recording-link.md)

## Objective
Demonstrate proper handling of software installation for a standard user and enforce NTFS permissions using least-privilege principles.

## Environment
- Windows 11 (VMware)
- Local accounts:
  - ITADMIN (Administrator)
  - user1 (Standard User)

## Actions Performed
- Attempted software installation as a standard user.
- Observed UAC elevation requirement for system-wide installer.
- Installed software using administrator credentials without granting admin rights to the user.
- Created a lab folder and configured NTFS permissions.
- Assigned Read & Execute permissions to a standard user.
- Tested access denial when attempting file creation.
- Modified permissions to allow controlled access.
- Verified permission behavior by switching user contexts.

## Outcome
Software installation required administrator elevation as expected. NTFS permissions were enforced correctly, allowing visibility without modification until permissions were explicitly changed.

## Skills Demonstrated
- Software installation troubleshooting
- User Account Control (UAC)
- NTFS permission configuration
- Least-privilege access enforcement
- Windows Help Desk fundamentals
