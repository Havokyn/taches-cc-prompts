---
name: create-adr
description: Generate Architecture Decision Records for AI agent development decisions
category: documentation
priority: medium
---

# Create ADR Command

Generate comprehensive Architecture Decision Records (ADRs) for AI agent development decisions, ensuring traceability and decision rationale documentation.

## Usage

```bash
/create-adr [decision context or problem statement]
```

## ADR Structure

This command generates ADRs with:

### 1. ADR Metadata
- ADR ID (auto-generated)
- Agent ID and Task ID
- Timestamp and duration
- Status (Proposed → Accepted → Implemented)
- AI Model/Version
- Confidence Level

### 2. Executive Summary
One-sentence decision summary for quick reference

### 3. Context & Problem Statement
- Problem description
- Constraints & requirements (functional, non-functional, technical, business)
- Triggering event

### 4. Decision Drivers & Criteria
- Primary decision factors
- Evaluation criteria with weights
- Scoring matrix

### 5. Options Considered
For each option:
- Detailed description
- Pros and cons
- Score against criteria
- Implementation complexity
- Risk assessment

### 6. Decision Outcome
- Chosen solution with justification
- Alternative rejection rationale
- Trade-off analysis

### 7. Implementation Strategy
- Execution plan
- Required resources
- Timeline and milestones
- Rollback plan

### 8. Consequences
- Positive outcomes
- Negative impacts
- Technical debt implications
- Monitoring metrics

### 9. Compliance & Validation
- Verification checklist
- Testing strategy
- Review sign-offs

### 10. Related Decisions
- Dependencies and references
- Superseded ADRs
- Future decision points

## USACF Integration

Deploys specialized agents for:
- **meta-learning-orchestrator**: Extract decision patterns and principles
- **structural-mapper**: Analyze architectural implications
- **risk-analyst**: Assess decision risks and trade-offs
- **synthesis-specialist**: Generate comprehensive ADR documentation

## Output Format

Markdown ADR file saved to:
- `docs/architecture/decisions/ADR-[ID]-[slug].md`
- Automatically linked in decision log

## Integration Points

- Works with `/sparc architecture` for architectural alignment
- Coordinates with `/claude-flow memory` for decision history
- Integrates with `/github pr-manager` for PR documentation

## Reference Material

Full template: `prompts/references/ADR.md`
USACF agents: `agents/usacf/`
