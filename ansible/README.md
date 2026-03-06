# Ansible

This folder contains Ansible playbooks and templates designed for automating network configurations across Cisco IOS-XR and IOS-XE devices.

Each playbook is written in YAML and tested in real lab environments using EVE-NG. Tasks range from basic interface configuration to OSPF, VLANs, and loopback interfaces.

## Contents
- `playbooks/` — Reusable playbooks for common network tasks.
- `templates/` — Jinja2 templates used to generate device configs.

## Usage
Playbooks are intended for execution using `ansible-playbook` and require an inventory file. Variables and templates are documented per playbook.

## Requirements
- Ansible 2.9+
- SSH access to network devices
