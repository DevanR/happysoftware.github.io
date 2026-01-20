---
layout: default
title: CronPing
---

# CronPing

**Cron job monitoring service that alerts you when your scheduled tasks fail.**

[Visit CronPing](https://ping.happy.software)

## Overview

CronPing is a SaaS application for monitoring cron jobs and scheduled tasks. It provides a simple ping-based monitoring system with multi-channel notifications to ensure you know immediately when your background jobs stop running.

## Key Features

- **Simple Ping Monitoring** - Each check gets a unique URL; ping it from your cron job to confirm it ran
- **Grace Periods** - Configure how long to wait before marking a job as down
- **Multi-Channel Notifications** - Get alerts via email, webhook, Slack, Discord, or Telegram
- **Run History** - Full history of all pings with timestamps and metadata
- **Dashboard** - Monitor all your checks at a glance with status indicators

## Technologies

- Django
- PostgreSQL
- Redis
- Celery
- Stripe (billing)

[Back to Portfolio](./index.html)
