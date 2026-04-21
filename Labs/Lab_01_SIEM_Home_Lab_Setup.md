# Lab 01 — SIEM Home Lab Setup

## Objective

Build a simple home SOC workflow using a log source and centralized visualization.

SY0-701 objective alignment: 4.2 Monitoring, Detection, and Analysis

## Suggested Tooling

- Wazuh or Elastic stack
- One Windows endpoint VM
- One Linux endpoint VM

## Prerequisites

- 8 GB+ RAM available for lab VMs
- Virtualization platform installed
- Admin access to all lab systems

## Step-by-Step Procedure

1. Deploy SIEM server VM and confirm web console access.
2. Install endpoint agent on Windows and Linux test VMs.
3. Register agents and confirm heartbeat/check-in status.
4. Generate normal activity baseline:
   - Successful logins
   - Normal web browsing
   - Basic process execution
5. Build a dashboard for:
   - Failed logins
   - New process creation
   - Outbound connection anomalies
6. Trigger controlled suspicious events:
   - Five failed login attempts in 60 seconds
   - Launch command shell from unusual parent process
7. Verify that alerts appear with usable context.

## Validation Checkpoints

- All endpoints appear online in SIEM
- Relevant logs are searchable
- At least one custom alert is triggered and documented

## Tasks

1. Configure endpoint log forwarding.
2. Confirm ingestion into SIEM platform.
3. Build dashboard for authentication events.
4. Trigger a test failed login burst and verify alert visibility.

## Troubleshooting Tips

- No logs visible: confirm agent service status and network reachability.
- Time mismatch: align VM clocks using NTP.
- Alert did not fire: verify rule conditions and event source mapping.

## Deliverable

- Screenshot of dashboard
- One-page incident note describing one suspicious pattern observed

---

Next: [Lab 02](Lab_02_Vulnerability_Management_Cycle.md)
