# 🔍 Forensic JSON Studio

**Version:** `3.1 Stable (Build 3.2.3)`  
**Role:** Zero-Dependency, High-Performance Forensic Analysis SPA for JSON & HAR datasets.

[![License](https://img.shields.io/badge/License-MIT-blue.svg?style=flat-square)](LICENSE)

---

## 🚀 Overview

**Forensic JSON Studio** is an enterprise-grade, zero-dependency Single Page Application (SPA) engineered for deep forensic inspection of network traffic and complex JSON payloads. Designed with **Privacy-First Architecture**, all operations execute entirely within the local browser sandbox—guaranteeing zero data exfiltration.

---

## ✨ Core Capabilities

### 🌐 Network & Protocol Intelligence
* **HAR Waterfall Visualization:** Interactive timing breakdowns, payload inspection, and domain mapping.
* **Duplicate Request Finder:** Identifies redundant traffic and calculates bandwidth overhead.

### 🔐 Security & Auth Auditing
* **Auth Flow Detector:** Automatic identification and decoding of JWTs, Auth headers, and session cookies.
* **Security Auditor:** Validates headers (`HSTS`, `CSP`, `X-Frame-Options`) and flags plaintext PII.

### 🛠 Advanced Data Manipulation
* **GraphQL Engine:** Specialized parsing for Queries, Mutations, and Subscriptions.
* **Sanitization Engine:** One-click redaction (Emails, IPs, Hostnames, Tokens) for secure LLM ingestion.
* **Deep Diff & Schema Inference:** Recursive JSON comparison and automated schema generation.

---

## ⚡ Performance Engineering

Built to handle large datasets without degrading responsiveness:
* **Size-Aware Gating:** Dynamic feature scaling based on payload size.
* **Memory Discipline:** WebWorker execution pathways optimized for massive files.
* **Lazy DOM Rendering:** Virtualized rendering for deep nested objects.

---

## 🛠 Getting Started

### Option 1: Local Execution
Simply clone the repository and open `index.html` in any modern web browser.

### Option 2: Web Access
Access the live environment directly via your hosted **GitHub Pages** instance.

---
*Maintained under MIT License.*
