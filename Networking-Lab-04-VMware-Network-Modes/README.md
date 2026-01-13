# Networking Lab 4: VMware NAT vs Host-Only Networking

[Recording Link](https://youtu.be/jRO-tiz0xcQ)

## Objective
Understand how different VMware network adapter modes affect connectivity, isolation, and internet access for a virtual machine.

## Environment
- Windows 11 (VMware)
- VMware network adapter configurations:
  - NAT
  - Host-only

## Actions Performed
- Identified the default VMware network adapter mode.
- Configured the virtual machine to use NAT networking.
- Verified IP configuration and confirmed internet connectivity.
- Reconfigured the virtual machine to use Host-only networking.
- Observed changes in IP address and network range.
- Verified loss of internet connectivity in Host-only mode.
- Restored NAT networking and confirmed connectivity was re-established.

## Outcome
The effects of VMware network adapter modes were successfully demonstrated. NAT mode provided internet access, while Host-only mode isolated the virtual machine from external networks.

## Skills Demonstrated
- Virtual network configuration
- VMware networking concepts
- NAT vs Host-only behavior
- Network isolation awareness
- Connectivity verification and testing
