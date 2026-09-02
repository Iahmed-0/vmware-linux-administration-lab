# VMware Virtualization and Linux Administration Lab

## Overview

This project documents the creation and configuration of VMware virtual machines and the installation of Linux. I used Linux command-line and system tools to complete configuration, administration, system-inspection, and network-troubleshooting exercises.

## Skills demonstrated

- VMware virtual-machine creation and resource configuration
- Linux installation and initial system configuration
- User, file, directory, ownership, and permission administration
- Service and process inspection
- IP addressing, routing, DNS, and connectivity checks
- Log review and command-line troubleshooting
- Repeatable technical documentation

## Lab environment

| Component | Lab value |
| --- | --- |
| VMware product and version | [VALUE] |
| Host operating system | [VALUE] |
| Linux distribution and version | [VALUE] |
| VM CPU, memory, and storage | [VALUE] |
| Network adapter mode | [NAT / HOST-ONLY / BRIDGED / CUSTOM] |
| Snapshot strategy | [VALUE] |

## Implementation summary

1. Created a VMware virtual machine and allocated compute, memory, storage, and networking resources.
2. Installed Linux and completed initial operating-system configuration.
3. Practised command-line navigation, file operations, permissions, users, and groups.
4. Inspected services, processes, system resources, and logs.
5. Tested network interface configuration, addressing, routes, DNS resolution, and connectivity.
6. Recorded configuration steps, test results, and troubleshooting observations.

## Administration exercises

Only retain rows that match exercises you completed.

| Exercise | Tools or commands used | Result/evidence |
| --- | --- | --- |
| Inspect users and groups | `[ADD ACTUAL COMMANDS]` | [LINK] |
| Manage files and permissions | `[ADD ACTUAL COMMANDS]` | [LINK] |
| Inspect services | `[ADD ACTUAL COMMANDS]` | [LINK] |
| Inspect processes and resources | `[ADD ACTUAL COMMANDS]` | [LINK] |
| Review system logs | `[ADD ACTUAL COMMANDS]` | [LINK] |
| Inspect interface and IP configuration | `[ADD ACTUAL COMMANDS]` | [LINK] |
| Inspect routes and DNS | `[ADD ACTUAL COMMANDS]` | [LINK] |
| Test network connectivity | `[ADD ACTUAL COMMANDS]` | [LINK] |

Common tools you may have used include `ip`, `ping`, `ss`, `systemctl`, `journalctl`, `ps`, `top`, `df`, `lsblk`, `dig`, `nslookup`, `traceroute`, `chmod`, and `chown`. Do not list a tool unless it appears in your real work.

## Validation

| Test | Expected result | Actual result | Evidence |
| --- | --- | --- | --- |
| VM boots successfully | [EXPECTED] | [ACTUAL] | [LINK] |
| User or permission change works | [EXPECTED] | [ACTUAL] | [LINK] |
| Required service is active | [EXPECTED] | [ACTUAL] | [LINK] |
| Interface receives intended configuration | [EXPECTED] | [ACTUAL] | [LINK] |
| Local and remote connectivity behave as intended | [EXPECTED] | [ACTUAL] | [LINK] |
| DNS lookup succeeds | [EXPECTED] | [ACTUAL] | [LINK] |

## Screenshots to add

- VMware VM hardware and network settings
- Linux version and sanitized hostname output
- User, group, or permission exercise
- Service and process inspection
- Sanitized network interface and routing output
- Connectivity and DNS tests
- Relevant sanitized log evidence

## Troubleshooting

Use `docs/troubleshooting-log-template.md` to document a real problem, such as a disconnected virtual adapter, incorrect IP configuration, DNS failure, permission denial, or failed service.

## Lessons learned

- [WHAT YOU LEARNED ABOUT VM RESOURCE OR NETWORK SETTINGS]
- [WHAT YOU LEARNED FROM LINUX LOGS OR COMMAND-LINE TOOLS]
- [HOW YOU NARROWED DOWN A NETWORK OR SYSTEM PROBLEM]

## Security note

Do not commit VM disk files, ISO images, passwords, SSH private keys, unredacted configuration exports, or confidential packet captures.
