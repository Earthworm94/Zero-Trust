# Conditional Access Policies for AI Systems

## Overview
AI systems must be governed by strict Conditional Access policies to prevent misuse, data leakage, and unauthorized access.

---

## Core Policies

### 1. Require MFA for AI Access
- Applies to all AI tools
- Prevents unauthorized usage

### 2. Block Unmanaged Devices
- AI access restricted to compliant devices
- Reduces data exfiltration risk

### 3. Restrict by User Role
- Admin vs standard user access tiers
- Elevated controls for sensitive roles

### 4. Location-Based Restrictions
- Block high-risk geographies
- Enforce trusted network access

---

## Example Policy Scenarios

### Policy: Secure AI Access
- Require MFA
- Require compliant device
- Block legacy authentication

### Policy: Admin AI Usage
- Require step-up MFA
- Restrict to secure workstations
- Enable full logging

---

## Integration Points
- Microsoft Entra ID
- Device compliance policies
- Identity Protection

---

## Key Principle

**AI access should be governed with the same rigor as privileged system access.**
