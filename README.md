# SOC Analyst Home Lab Project

This repository provides a detailed walkthrough for setting up and running the SOC Analyst Home Lab. It is based on the blog post, with step-by-step instructions and images to guide you through the process.

---

## Table of Contents
1. [Introduction](#introduction)
2. [Prerequisites](#prerequisites)
3. [Lab Setup](sections/lab_setup.md)
4. [Tools Installation](sections/tools_installation.md)
5. [Payload Generation and Detection](#payload-generation-and-detection)
6. [Conclusion](#conclusion)

---

## Introduction

This lab focuses on building a simulated home lab environment for SOC analysts to practice detection and response techniques.

---

## Prerequisites

- A computer capable of running multiple VMs.
- Virtualization software (e.g., VirtualBox, VMware).
- ISO files for Ubuntu and Windows OS.
- Internet connection for downloading tools.

---

## Payload Generation and Detection

Use Sliver C2 to generate and deploy payloads. Monitor activity using LimaCharlie.

```bash
# Generate a Sliver payload
./sliver-client generate beacon --os windows --arch amd64

# Serve the payload using a Python HTTP server
python3 -m http.server
```

---

## Conclusion

Congratulations! You’ve successfully set up the SOC Analyst Home Lab.
