# Linux Host-Based Intrusion Detection (auditd)

## Overview
This project demonstrates how I configured Linux auditd as a host-based intrusion detection mechanism on Ubuntu Server 24.04. Custom audit rules were developed to monitor sensitive files and high-risk directories. Simulated malicious activity was performed to validate detection capability and log accuracy.

## Objectives
- Configure and enable auditd service
- Create custom audit rules
- Monitor high-risk directories (/tmp)
- Monitor sensitive files (/etc/passwd)
- Simulate malicious activity (file staging, permission changes)
- Analyze syscall-level logs using ausearch

## Lab Environment
- Ubuntu Server 24.04
- auditd
- Command-line log analysis tools

## Audit Rules Implemented

### Monitor /etc/passwd

### Monitor /tmp directory activity

## Attack Simulation

The following commands were executed to simulate suspicious activity:

## Log Analysis

Logs were analyzed using:

The logs confirmed:
- File modification events
- User attribution (UID)
- Syscall numbers
- Executed binaries
- Timestamp correlation

## Skills Demonstrated

- Host-Based Intrusion Detection
- Linux Security Monitoring
- Syscall-Level Log Analysis
- Threat Simulation
- Security Event Validation
- Forensic Investigation Basics


