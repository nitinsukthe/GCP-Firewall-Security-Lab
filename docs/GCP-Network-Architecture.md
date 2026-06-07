# GCP Network Architecture

## Architecture Overview

The environment consists of a Compute Engine virtual machine deployed within a Google Cloud VPC network protected by firewall rules.

---

## Components

### GCP Project

The project acts as the logical container for all cloud resources.

Project Name:

gcp-vpc-firewall-security-lab

---

### VPC Network

Custom VPC Network:

secure-vpc

Purpose:

- Network isolation
- Resource segmentation
- Controlled communication paths

---

### Compute Engine VM

VM Name:

secure-vm

Operating System:

Debian Linux

Purpose:

- Secure cloud workload
- Administrative access testing
- Firewall validation

---

### Firewall Rule

Firewall Rule:

allow-ssh-from-my-ip

Purpose:

- Restrict SSH access
- Allow only trusted IP addresses
- Reduce attack surface

---

## Architecture Flow

Internet User
      │
      ▼
Public IP Address
      │
      ▼
Firewall Rule
(TCP Port 22 Only)
      │
      ▼
Network Tag
ssh-secure
      │
      ▼
Compute Engine VM
secure-vm

---

## Security Benefits

- Reduced exposure to the internet
- Controlled administrative access
- Protection against unauthorized SSH attempts
- Improved cloud security posture
