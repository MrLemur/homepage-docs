---
title: Proxmox Backup Server
description: Proxmox Backup Server Widget Configuration
layout: ../../../layouts/MainLayout.astro
---

Allowed fields: `["datastore_usage", "failed_tasks_24h", "cpu_usage", "memory_usage"]`.

```yaml
widget:
    type: proxmoxbackupserver
    url: https://proxmoxbackupserver.host:port
    username: api_token_id
    password: api_token_secret
```

*Added in v0.6.4*
