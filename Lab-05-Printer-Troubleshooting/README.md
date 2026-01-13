# Lab 5: Printer Troubleshooting

[Recording Link](https://youtu.be/30SwYSYo4qo)

## Objective
Diagnose and resolve a printer error affecting a standard user by identifying and correcting printer configuration issues.

## Environment
- Windows 11 (VMware)
- Local accounts:
  - ITADMIN (Administrator)
  - user1 (Standard User)

## Actions Performed
- Added a local printer using a built-in Windows driver.
- Logged in as a standard user and attempted to print.
- Observed a printer error during the print attempt.
- Diagnosed the issue as an incorrect printer port configuration.
- Identified that the printer was assigned to a legacy LPT1 port.
- Reconfigured the printer to use a FILE virtual port.
- Verified printer functionality as administrator.
- Confirmed successful printing as the standard user.

## Outcome
Printer error was resolved by correcting the printer port configuration. Print jobs processed successfully after reassignment to a virtual port.

## Skills Demonstrated
- Printer installation and configuration
- Printer port troubleshooting
- Driver and queue validation
- Print Spooler awareness
- End-user issue verification
- Windows Help Desk troubleshooting
