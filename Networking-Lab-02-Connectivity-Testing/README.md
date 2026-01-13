# Networking Lab 2: Connectivity Testing (Ping & Tracert)

[Recording Link](https://youtu.be/mWkL-z-591Y)

## Objective
Test and verify network connectivity at different levels using basic command-line networking tools.

## Environment
- Windows 11 (VMware)
- Network connection via virtual network adapter

## Actions Performed
- Used ping to test local TCP/IP functionality.
- Pinged the system’s own IP address to verify adapter operation.
- Pinged the default gateway to confirm local network connectivity.
- Pinged an external IP address to verify internet access.
- Used tracert to observe the network path to an external destination.
- Interrupted traceroute after gathering sufficient diagnostic information.

## Outcome
Network connectivity was successfully verified from the local system through the gateway to the internet. Disabling the network adapter caused connectivity failure, which was resolved by restoring the adapter.

## Skills Demonstrated
- Network connectivity testing
- Ping and traceroute usage
- Layered troubleshooting approach
- Command-line network diagnostics
- Basic network path awareness
