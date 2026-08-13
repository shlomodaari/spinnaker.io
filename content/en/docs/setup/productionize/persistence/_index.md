---
title: "Persistence"
linkTitle: "Persistence"
weight: 1
description: Configure SQL persistence for Spinnaker services.
---

Spinnaker services can use SQL for durable storage. For Front50, SQL is the
**recommended** metadata store; non-SQL Front50 backends (S3, GCS, Redis, Azure,
Oracle, Swift) are **deprecated** and scheduled for removal after Spinnaker
**2027.0.0**. See [Set up Front50 to use SQL](./front50-sql/).
