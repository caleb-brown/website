---
title: "Temper"
date: 2026-07-05T14:03:08-04:00
draft: false
---

# Description

**Status: Work in progress**

Temper is a self-hosted AI pull-request reviewer for Forgejo-first teams. It receives Forgejo webhooks, reviews pull-request diffs with an OpenAI-compatible model, and posts a managed review summary with high-confidence inline findings.

## Current Features

- Secure webhook ingestion with signature validation and delivery de-duplication
- Forgejo OAuth integration for statuses, summaries, and inline review comments
- Configurable LLM providers and reviewer profiles
- Secret redaction and encrypted credential storage
- Maintainer-controlled reviews for pull requests from untrusted forks

## Technologies

- Python and FastAPI
- PostgreSQL and SQLAlchemy
- Redis and Celery
- Docker Compose
- Forgejo and OpenAI-compatible APIs

### Links

- [Source repository](https://git.caleb-brown.dev/caleb-brown/temper)
