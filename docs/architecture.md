# SOC Detection Engineering Lab Architecture

## Overview

This project simulates a Security Operations Center (SOC) environment for attack simulation, detection engineering, log analysis, dashboard creation, and incident investigation.

## Architecture

Kali Linux (Attacker)
|
v
Ubuntu Server (Victim)
|
v
Splunk Enterprise (SIEM)

## Components

### Kali Linux

Used to simulate attacks such as:

* SSH Brute Force
* Port Scanning
* Password Spraying
* Reverse Shells

### Ubuntu Server

Used as the victim machine generating logs.

Key Logs:

* /var/log/auth.log
* /var/log/syslog

### Splunk Enterprise

Used for:

* Log ingestion
* Detection engineering
* Dashboard creation
* Alerting
* Incident investigation

## Objectives

* Simulate realistic attacks
* Develop detection rules
* Create SOC dashboards
* Build incident reports
* Practice threat hunting
