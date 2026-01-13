# Networking Lab 3: DNS Troubleshooting

[Recording Link](https://youtu.be/xz4sJi-7xXY)

## Objective
Identify and troubleshoot a DNS-related connectivity issue where IP connectivity is functional but domain name resolution fails.

## Environment
- Windows 11 (VMware)
- Network connection via virtual network adapter

## Actions Performed
- Verified internet connectivity by pinging an external IP address.
- Confirmed initial DNS resolution using domain name pings and nslookup.
- Manually configured an invalid DNS server address.
- Disabled and re-enabled the network adapter to clear resolver behavior.
- Flushed the DNS cache.
- Observed successful IP connectivity with failed domain name resolution.
- Restored automatic DNS configuration.
- Verified DNS resolution and connectivity were restored.

## Outcome
DNS failure was successfully simulated and identified. IP connectivity remained functional while name resolution failed, confirming a DNS-specific issue. Restoring valid DNS settings resolved the problem.

## Skills Demonstrated
- DNS troubleshooting
- IP vs name resolution analysis
- DNS cache management
- Network adapter management
- Layered network diagnostics
