# Zero Trust for AI Systems

## Overview
Traditional Zero Trust models focus on users, devices, and networks. AI systems introduce a new dimension: decision-making entities acting on behalf of users.

---

## The AI Trust Chain

User → AI System → Data → Output

Each step must be independently verified.

---

## Key Principle

**Zero Trust must extend beyond users to include prompts, models, and outputs.**

---

## Core Controls

### 1. User Verification
- Identity authentication
- Device compliance
- Role-based access

### 2. Prompt Validation
- Input filtering
- Prompt injection detection
- Context grounding

### 3. Data Access Control
- Retrieval scoped to user permissions
- Data classification enforcement

### 4. Output Monitoring
- Response filtering
- Logging and auditing

---

## Continuous Verification

AI systems must continuously validate:
- Who is asking
- What is being asked
- What data is accessed
- What is returned

---

## Summary
Zero Trust in AI is not a perimeter—it is a continuous, identity-driven validation process across every interaction.
