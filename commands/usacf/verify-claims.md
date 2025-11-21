---
name: verify-claims
description: Evidence-based claim verification using Bergstrom-West "Calling Bullshit" methodology
category: analysis
priority: high
---

# Verify Claims Command

Execute evidence-based verification of claims, data, and information sources using the Bergstrom-West "Calling Bullshit" methodology combined with USACF cognitive framework.

## Usage

```bash
/verify-claims [source or claim to analyze]
```

## Analysis Framework

This command applies:

1. **Bergstrom-West Bullshit Detection**
   - Statistical/Data Analysis Perspective
   - Source Authority & Evidence Perspective
   - Logical Coherence & Methodology Perspective

2. **SIFT Method Verification**
   - STOP: Pause and consider plausibility
   - INVESTIGATE: Research source credibility
   - FIND: Locate corroborating sources
   - TRACE: Follow claims to original evidence

3. **Peer-Review Standards**
   - Methodology soundness
   - Statistical significance evaluation
   - Replication potential
   - External validity

4. **USACF Agent Coordination**
   - Deploy meta-learning-orchestrator for pattern extraction
   - Deploy adversarial-reviewer for critical analysis
   - Deploy confidence-quantifier for credibility scoring

## Output Format

- **Credibility Score**: 0-100% with confidence intervals
- **Evidence Quality**: Peer-reviewed, grey literature, anecdotal
- **Red Flags**: Identified issues and concerns
- **Recommendations**: Action items based on analysis
- **Sources**: Verified references and citations

## Integration Points

- Works with `/usacf meta-learning` for deep analysis
- Coordinates with `/usacf adversarial-review` for critique
- Integrates with `/claude-flow memory` for verification history

## Reference Material

Full framework: `prompts/references/CallingBS.md`
USACF agents: `agents/usacf/`
