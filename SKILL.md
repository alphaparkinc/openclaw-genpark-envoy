---
name: openclaw-genpark-envoy
description: OpenClaw GenPark inter-agent mutual handshake and secure HMAC authenticated envelope router with replay attack prevention.
category: Service
version: 1.0.0
license: MIT
tools:
  - {'name': 'package_envelope', 'description': 'Package an agent payload into an HMAC authenticated envelope with nonce.'}
  - {'name': 'verify_and_unpack', 'description': 'Cryptographically verify and unpack incoming inter-agent envelope.'}
---

# Openclaw Genpark Envoy

## Overview & Agent Behavioral Directives
You are an autonomous agent specialized in **Openclaw Genpark Envoy**.
Your primary directive is to execute: OpenClaw GenPark inter-agent mutual handshake and secure HMAC authenticated envelope router with replay attack prevention.
Always ensure mathematical precision, parameter validation, and deterministic outputs.

## When to Activate This Skill
- Activate when an agent workflow or user instruction requires:
- `{'name': 'package_envelope', 'description': 'Package an agent payload into an HMAC authenticated envelope with nonce.'}`
- `{'name': 'verify_and_unpack', 'description': 'Cryptographically verify and unpack incoming inter-agent envelope.'}`
- Activate when operating in zero-dependency environments requiring pure Python standard library execution.

## How to Execute

### Option 1: Direct Python Execution (Zero-Dependency)
```python
from client import *

# Client operates purely on standard Python library:
# Initialized and ready for direct function invocation.
```

### Option 2: FastMCP Tool Calling
Tools registered in `mcp_server.py`:
- `{'name': 'package_envelope', 'description': 'Package an agent payload into an HMAC authenticated envelope with nonce.'}`
- `{'name': 'verify_and_unpack', 'description': 'Cryptographically verify and unpack incoming inter-agent envelope.'}`

## Core Mathematical & Algorithmic Guardrails
- **Zero-Dependency Policy**: 100% Python standard library only (`math`, `heapq`, `hashlib`, `urllib`, `collections`, `itertools`, `typing`).
- **Zero-Mock Policy**: Pure deterministic algorithms with full validation and error bounds.
