---
layout: default
title: Linux-Mirror Repository
---

# 🐧 Linux-Mirror: System Images Repository

A centralized repository of Linux distribution installation files for system administrators, developers, and IT professionals.

## Available Images

{% for file in site.repository_files %}
- **{{ file.name }}**
  - Filename: `{{ file.file }}`
  - Size: {{ file.size }}
  - Added: {{ file.date }}
{% endfor %}

## About This Mirror

This repository provides quick and easy access to Linux distribution installation files, enabling:
- 📥 Fast system image downloads
- 🌐 Local access to Linux distribution ISOs
- 💾 Centralized storage of installation files
- 🚀 Simplified OS deployment

**Last Updated**: {{ site.last_updated }}
