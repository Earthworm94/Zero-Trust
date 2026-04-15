# AI Data Protection Strategy

## Overview
AI systems introduce new risks around data exposure, particularly when interacting with sensitive internal information.

---

## Key Risks

- Sensitive data entered into prompts
- Unauthorized data retrieval
- Data leakage through AI responses

---

## Core Controls

### 1. Input Protection
- Block sensitive data entry
- Apply DLP policies
- User awareness training

### 2. Retrieval Control (RAG)
- Only retrieve data user is authorized to access
- Enforce role-based filtering

### 3. Output Protection
- Filter sensitive outputs
- Prevent overexposure of data

---

## Data Classification

- Public
- Internal
- Confidential
- Restricted

AI systems must respect classification boundaries.

---

## Key Principle

**AI must never expose data beyond the permissions of the requesting user.**
