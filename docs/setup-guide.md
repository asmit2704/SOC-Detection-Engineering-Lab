# SOC Lab Setup Guide

## Environment

### Virtualization

* VirtualBox

### Machines

#### Kali Linux

Role: Attacker

#### Ubuntu Server

Role: Victim and Log Source

#### Splunk Enterprise

Role: SIEM

## Network Configuration

All virtual machines must be connected using a Host-Only Network.

## Workflow

1. Simulate attack from Kali.
2. Generate logs on Ubuntu.
3. Ingest logs into Splunk.
4. Build detections.
5. Create alerts.
6. Investigate incidents.
7. Document findings.
