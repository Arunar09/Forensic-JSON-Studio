# Forensic JSON Studio

**Version:** 3.1 Stable (v3.2.3 Build)
**Role:** Senior Forensic Analysis SPA for JSON and HAR data.

## Overview
Forensic JSON Studio is a high-performance, zero-dependency Single Page Application (SPA) designed for deep inspection of network traffic and complex JSON datasets. It functions entirely offline, ensuring maximum data privacy for sensitive forensic audits.

## Key Features
- **🌐 Network Intelligence:** Waterfall vizualization, timing breakdowns, and domain mapping.
- **🔐 Auth Flow Detector:** Automatic detection and decoding of JWTs, Auth headers, and session cookies.
- **🛡 Security Auditor:** Automated checks for HSTS, CSP, X-Frame-Options, and PII leakage over plaintext.
- **◈ GraphQL Engine:** Specialized parsing for GraphQL operations (Queries, Mutations, Subscriptions).
- **♊ Duplicate Finder:** Identifies redundant network calls and calculates wasted bandwidth.
- **🛡 Sanitization Engine:** One-click masking of Emails, IPs, Tokens, and Hostnames for safe sharing with LLMs.
- **📐 Schema Inference:** Automatic generation of JSON Schema from live data.
- **🔀 Deep Diff:** Recursive comparison engine for identifying structural changes between JSON blobs.

## Performance
- **Size-Aware Gating:** Automatically optimizes UI features based on file size.
- **Memory Discipline:** Optimized for large files (>20MB) via WebWorker parsing and raw-mode fallbacks.
- **Lazy Loading:** Chunks DOM rendering to maintain responsiveness during deep tree exploration.

## Usage
Simply open `Json&HAR_analyser_v3.1_stable.html` in any modern web browser. No installation or internet connectivity required.


