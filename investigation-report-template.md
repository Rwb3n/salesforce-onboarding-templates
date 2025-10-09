# generated: 2025-10-09
# System Auto: last updated on: 2025-10-09 07:49:03
# Investigation Report Template
<!-- Use for complex troubleshooting, root cause analysis, and technical investigations -->

**Version:** 1.0
**Purpose:** Standardize investigation documentation, ensure thorough analysis, communicate findings clearly
**Created:** 2025-10-09

---

## When to Use This Template

**Use for:**
- Complex troubleshooting requiring multi-step investigation
- Issues affecting multiple users or requiring configuration changes
- Problems requiring collaboration with team members
- Situations where root cause isn't immediately obvious
- When you need manager approval before implementing solution

**Don't use for:**
- Simple quick fixes (use support ticket format)
- Single-user one-off issues
- Routine configuration changes

---

## Template Structure

### Header Block

```
To: [Manager/Stakeholder]
Subject: RE: [Original Issue Subject] - Investigation Findings
Date: [Date]
Investigator: [Your Name]
Collaborators: [Who helped? e.g., team members]
Investigation Time: [Optional: Hours spent]
```

---

## Section 1: Problem Statement

**What seems to be [User]'s actual problem:**

[Describe the symptoms as the user experiences them - what they see/don't see, what they can't do]

**Key observations:**
- [Bullet point of specific symptoms]
- [What user expects vs. what they're seeing]
- [Examples of affected records/scenarios]

**Users/Scope Affected:**
- Number of users: [X users/profiles/teams]
- Severity: [P1 Critical / P2 High / P3 Medium / P4 Low]
- Business Impact: [How does this block work? What's the consequence?]

---

## Section 2: Investigation Process

**Diagnostic steps taken:**

1. [First step - what you checked]
   - Finding: [What you discovered]

2. [Second step - what you checked next]
   - Finding: [What you discovered]

3. [Continue for each major investigation step]

**Tested scenarios:**
- **as Admin:** [What you can see/do]
- **as [User/Profile]:** [What they can see/do]
- [Include screenshots/examples if relevant]

**Collaboration:**
- Consulted with: [Team member name]
- Findings: [What you discovered together]

---

## Section 3: Root Cause Analysis

**Immediate cause:** [What directly causes the symptom?]

**Root cause:** [Why does that immediate cause exist?]

**Contributing factors:**
- [Factor 1 that makes this problem possible]
- [Factor 2]
- [Configuration/design decision that led to this]

**Why this wasn't caught before:**
- [If relevant: Gap in process, recent change, new user scenario, etc.]

---

## Section 4: Impact Assessment

**Current state:**
- [Describe current workarounds users are using]
- [What functionality is blocked]
- [Data visibility issues]

**If not fixed:**
- [Consequence of leaving as-is]
- [Ongoing efficiency impact]

**Urgency:**
- [Timeline pressure if any]
- [Can wait for next sprint / Needs immediate fix]

---

## Section 5: Solutions Considered

### Option A: [Solution Name]
**Description:** [What this solution entails]

**Pros:**
- [Benefit 1]
- [Benefit 2]

**Cons:**
- [Drawback 1]
- [Drawback 2]

**Decision:** ✓ Recommended / ✗ Rejected because [reason]

---

### Option B: [Alternative Solution]
**Description:** [What this solution entails]

**Pros:**
- [Benefit 1]

**Cons:**
- [Drawback 1]

**Decision:** ✓ Recommended / ✗ Rejected because [reason]

---

### Option C: [If applicable - third option or "do nothing"]
**Description:** [What this entails]

**Decision:** ✗ Rejected because [reason]

---

## Section 6: Recommended Solution

**Proposed approach:**

[Describe recommended solution in clear steps]

1. [Step 1]
2. [Step 2]
3. [Step 3]

**Rationale:**
- [Why this approach is best]
- [How it addresses root cause, not just symptoms]
- [Best practices alignment]

**What this will achieve:**
- [Outcome 1]
- [Outcome 2]

---

## Section 7: Risk Assessment & Mitigation

**Potential risks:**

| Risk | Likelihood | Impact | Mitigation |
|------|------------|--------|------------|
| [Risk 1: e.g., Exposing data to wrong users] | Low/Med/High | Low/Med/High | [How you'll prevent/handle this] |
| [Risk 2: e.g., Breaking existing workflows] | Low/Med/High | Low/Med/High | [Mitigation strategy] |

**Rollback plan:**
- If issues occur: [How to undo the change]
- Time to rollback: [Minutes/hours]
- Who to notify: [Stakeholders]

---

## Section 8: Testing & Validation Plan

**Pre-implementation testing:**
1. [Test in sandbox / with single user / other validation]
2. [Verify specific functionality]
3. [Check edge cases]

**Success criteria:**
- ✓ [Specific measurable outcome 1]
- ✓ [Specific measurable outcome 2]
- ✓ [No unintended side effects observed]

**Post-implementation monitoring:**
- [What to watch for in first 24-48 hours]
- [Who to check in with]

---

## Section 9: Additional Issues Discovered (If Applicable)

**Related Issue 1:** [e.g., Export limitation]
- Description: [What's the problem]
- Cause: [Why it happens]
- Workaround: [Immediate solution if no fix available]
- Long-term solution: [If applicable]

---

## Section 10: Next Steps & Approval Request

**Awaiting your guidance on:**
- [Decision point 1]
- [Question for manager]

**Once approved, I will:**
1. [Implementation step 1]
2. [Implementation step 2]
3. [User communication/follow-up]

**Timeline:**
- Implementation: [How long to execute]
- User notification: [When/how to communicate]

---

## Optional Sections (Add as Needed)

### Replication Steps (For Bug Reports)
```
To reproduce:
1. Log in as [profile/user]
2. Navigate to [location]
3. Observe: [What happens]
4. Expected: [What should happen]
5. Actual: [What actually happens]
```

### Change Management Considerations
- Deployment method: [Sandbox → Production / Direct in Production]
- User communication needed: [Yes/No - draft message if yes]
- Training required: [Yes/No - what needs explaining]
- Timing: [When to implement - business hours / off-hours / no restriction]

### Documentation Updates Required
- [What existing docs need updating]
- [New docs to create]
- [FAQ entries to add]

### Time Investment Tracking
- Investigation: [X hours]
- Collaboration: [Y hours with team]
- Documentation: [Z hours]
- Total: [Total hours]

---

## Template Usage Notes

**Customization:**
- Not every section is required for every investigation
- Add sections as complexity demands
- Remove sections that don't apply
- Adapt language to your organization's style

**Core sections (always include):**
1. Problem Statement
2. Investigation Process
3. Root Cause Analysis
4. Recommended Solution
5. Next Steps/Approval Request

**Optional sections (use when relevant):**
6. Impact Assessment (if high severity)
7. Solutions Considered (if multiple options)
8. Risk Assessment (if implementing changes)
9. Testing Plan (if rollout required)

**Best practices:**
- Be specific (names, numbers, examples)
- Show your work (how you investigated)
- Present options (don't just say "do this")
- Acknowledge uncertainty (if you don't know, say so)
- Credit collaborators (mention who helped)
- Ask for guidance (position as seeking approval, not dictating)

---

**Template Version:** 1.0
**Created:** 2025-10-09
**Last Updated:** 2025-10-09
