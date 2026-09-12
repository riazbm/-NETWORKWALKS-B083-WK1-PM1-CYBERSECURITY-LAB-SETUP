# Kali Linux Lab Setup

## Objective

Set up Kali Linux as a virtual cybersecurity laboratory environment
for hands-on learning, security testing, networking, and future
cybersecurity projects.

## Lab Environment

- Host Operating System: Fedora Linux
- Virtualization Platform: Oracle VirtualBox
- Guest Operating System: Kali Linux
- Architecture: AMD64

## Setup Process

The Kali Linux virtual machine was configured using VirtualBox.
The setup included importing the Kali Linux virtual machine,
checking the virtual machine configuration, and attempting the
initial boot.

## Troubleshooting

During the setup, the virtual machine initially encountered
virtualization-related errors. The issue involved AMD-V/SVM
virtualization being used by another hypervisor on the Fedora host.

The system was investigated using Linux commands such as:

```bash
lsmod | grep kvm

