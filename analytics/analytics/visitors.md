---
type: analytics-visitors
title: Visitors and engagement
description: One row per learner (keyed by email when available). Visits and reply totals drive return-rate and engagement metrics.
tags: [analytics, engagement]
timestamp: 2026-06-18T00:00:00Z
---

# Visitors and engagement

`visits` = distinct conversations for this learner (returns). `total_replies` = sum of every
conversation's assistant reply count. Average replies for a person = `total_replies / visits`.
Unique visitors = number of rows. See [analytics-schema.md](../analytics-schema.md).

| learner | display_name | role | department | first_seen | last_seen | visits | total_replies |
|---------|--------------|------|------------|------------|-----------|--------|---------------|
