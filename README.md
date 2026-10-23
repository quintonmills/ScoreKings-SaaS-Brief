# ScoreKings — Technical Architecture Brief

This repository hosts the web-based **Technical Architecture Brief** for **ScoreKings**, an automated real-time sports data ingestion and generative AI media rendering platform.

> 🌐 **Live Technical Brief:** [https://quintonmills.github.io/ScoreKings-SaaS-Brief/](https://quintonmills.github.io/ScoreKings-SaaS-Brief/)

---

## Overview

ScoreKings captures courtside game telemetry via a low-latency React PWA and transforms raw event streams into high-impact player media assets and verified league analytics using a Node.js backend integrated with the OpenAI API for dynamic image generation.

This brief outlines the system architecture, core tech stack, key technical capabilities, strategic trade-offs, and market positioning of the platform.

---

## Platform Architecture

```text
React PWA Client ──► Express API Gateway ──► OpenAI API Service ──► MongoDB Atlas ──► Static CDN Delivery
