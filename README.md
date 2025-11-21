# TÂCHES Claude Code Resources

A comprehensive collection of custom Claude Code resources, integrating enterprise AI agent orchestration (claude-flow), cognitive frameworks (USACF), and advanced prompting methodologies.

## 🚀 What's Included

- **74+ claude-flow agents** - Enterprise swarm coordination, SPARC methodology, GitHub automation
- **13 USACF agents** - Universal Search and Analysis Cognitive Framework with gamification
- **150+ slash commands** - Coordination, workflows, GitHub integration, and more
- **14 reference frameworks** - SAPPO, CallingBS, PRD templates, testing guides
- **Original TÂCHES resources** - Meta-prompting, todo management, extension creation
- **3 MCP servers** - 110+ tools for orchestration (optional)

## Installation

### Option 1: Plugin Install (Recommended)

```bash
# Add the marketplace
claude plugin marketplace add glittercowboy/taches-cc-resources

# Install the plugin
claude plugin install taches-cc-resources
```

Start a new Claude Code session to use the commands and skills.

### Option 2: Manual Install

```bash
# Clone the repo
git clone https://github.com/glittercowboy/taches-cc-resources.git
cd taches-cc-resources

# Install commands
cp commands/*.md ~/.claude/commands/

# Install skills
cp -r skills/* ~/.claude/skills/
```

Commands install globally to `~/.claude/commands/`. Skills install to `~/.claude/skills/`. Project-specific data (prompts, todos) lives in each project's working directory.

---

## 🌟 Claude Flow Integration

### Enterprise AI Agent Orchestration

**claude-flow** is a comprehensive agent orchestration system with 74+ specialized agents, swarm coordination, and SPARC methodology implementation.

### Core Agents (5)

Foundation agents for common development tasks:

- [`coder`](./agents/claude-flow/core/coder.md) - Implementation specialist for clean, efficient code
- [`planner`](./agents/claude-flow/core/planner.md) - Task decomposition and strategic planning
- [`researcher`](./agents/claude-flow/core/researcher.md) - Information gathering and analysis
- [`reviewer`](./agents/claude-flow/core/reviewer.md) - Code review and quality assurance
- [`tester`](./agents/claude-flow/core/tester.md) - Testing strategy and validation

### Swarm Coordination (15 agents)

Multi-agent coordination with 4 topologies (Hierarchical, Mesh, Ring, Star):

**Swarm Topologies:**
- [`hierarchical-coordinator`](./agents/claude-flow/swarm/hierarchical-coordinator.md) - Queen-led delegation system
- [`mesh-coordinator`](./agents/claude-flow/swarm/mesh-coordinator.md) - Peer-to-peer collaboration
- [`adaptive-coordinator`](./agents/claude-flow/swarm/adaptive-coordinator.md) - Dynamic topology switching

**Consensus Protocols:**
- [`raft-manager`](./agents/claude-flow/consensus/raft-manager.md) - Leader election and log replication
- [`byzantine-coordinator`](./agents/claude-flow/consensus/byzantine-coordinator.md) - Byzantine fault tolerance
- [`crdt-synchronizer`](./agents/claude-flow/consensus/crdt-synchronizer.md) - Conflict-free replicated data
- [`gossip-coordinator`](./agents/claude-flow/consensus/gossip-coordinator.md) - Epidemic protocol sync
- [`quorum-manager`](./agents/claude-flow/consensus/quorum-manager.md) - Majority voting consensus
- [`performance-benchmarker`](./agents/claude-flow/consensus/performance-benchmarker.md) - Consensus performance testing
- [`security-manager`](./agents/claude-flow/consensus/security-manager.md) - Security and authentication

**Hive Mind Architecture:**
- [`queen-coordinator`](./agents/claude-flow/hive-mind/queen-coordinator.md) - Sovereign orchestrator with royal directives
- [`collective-intelligence-coordinator`](./agents/claude-flow/hive-mind/collective-intelligence-coordinator.md) - Democratic consensus
- [`swarm-memory-manager`](./agents/claude-flow/hive-mind/swarm-memory-manager.md) - Shared state management
- [`scout-explorer`](./agents/claude-flow/hive-mind/scout-explorer.md) - Intelligence gathering
- [`worker-specialist`](./agents/claude-flow/hive-mind/worker-specialist.md) - Task execution

### GitHub Automation (13 agents)

Full PR lifecycle, multi-agent code reviews, release coordination:

- [`pr-manager`](./agents/claude-flow/github/pr-manager.md) - Comprehensive PR management with swarm coordination
- [`code-review-swarm`](./agents/claude-flow/github/code-review-swarm.md) - Multi-agent code reviews
- [`issue-tracker`](./agents/claude-flow/github/issue-tracker.md) - Issue management and tracking
- [`release-manager`](./agents/claude-flow/github/release-manager.md) - Release coordination and automation
- [`workflow-automation`](./agents/claude-flow/github/workflow-automation.md) - CI/CD workflow orchestration
- [`multi-repo-swarm`](./agents/claude-flow/github/multi-repo-swarm.md) - Cross-repository coordination
- [`sync-coordinator`](./agents/claude-flow/github/sync-coordinator.md) - Multi-repo synchronization
- And 6 more specialized GitHub agents...

### SPARC Methodology

**Specification → Pseudocode → Architecture → Refinement → Code**

5-phase development lifecycle with dedicated agents for each phase.

### Additional Categories

- **Analysis** (4 agents) - Performance, bottleneck, metrics analysis
- **Architecture** (2 subdirs) - System design, ML architecture
- **Development** (1 subdir) - Backend development
- **DevOps** (1 subdir) - CI/CD automation
- **Documentation** (1 subdir) - API documentation
- **Flow-Nexus** (5 agents) - Cloud orchestration platform
- **Goal** (3 agents) - Objective-driven planning
- **Neural** (27 agents) - Pre-trained models with WASM acceleration
- **Optimization** (6 agents) - Performance and resource optimization
- **Reasoning** (4 agents) - Advanced reasoning patterns
- **Specialized** (1 subdir) - Mobile development
- **Templates** (3 agents) - Code generation templates
- **Testing** (2 subdirs) - Unit and validation testing

### Command Categories

150+ slash commands organized in:

- `/coordination` - Swarm initialization and task orchestration
- `/sparc` - SPARC methodology workflows
- `/github` - GitHub automation and PR management
- `/hive-mind` - Hive coordination and royal directives
- `/memory` - Shared state management
- `/monitoring` - Performance and health monitoring
- `/optimization` - Resource and performance optimization
- `/swarm` - Swarm topology management
- `/workflows` - Complex workflow orchestration
- `/training` - Neural model training

### Performance Metrics

- **84.8% SWE-Bench solve rate** - Leading industry performance
- **32.3% token reduction** - Optimized communication patterns
- **2.8-4.4x WASM acceleration** - Enhanced swarm coordination (with ruv-swarm MCP)

---

## 🧠 USACF Integration

### Universal Search and Analysis Cognitive Framework

13-agent cognitive system with gamification, confidence scoring, and memory coordination.

### USACF Agents

**Discovery Phase:**
- [`meta-learning-orchestrator`](./agents/usacf/meta-learning-orchestrator.md) - Step-back prompting, principle extraction
- [`structural-mapper`](./agents/usacf/structural-mapper.md) - System structure analysis
- [`flow-analyst`](./agents/usacf/flow-analyst.md) - Information flow mapping
- [`self-ask-decomposer`](./agents/usacf/self-ask-decomposer.md) - Question decomposition
- [`ambiguity-clarifier`](./agents/usacf/ambiguity-clarifier.md) - Uncertainty resolution

**Analysis Phase:**
- [`gap-hunter`](./agents/usacf/gap-hunter.md) - Missing information detection
- [`risk-analyst`](./agents/usacf/risk-analyst.md) - Risk assessment and mitigation
- [`step-back-analyzer`](./agents/usacf/step-back-analyzer.md) - High-level principle extraction
- [`opportunity-generator`](./agents/usacf/opportunity-generator.md) - Innovation identification

**Synthesis Phase:**
- [`adversarial-reviewer`](./agents/usacf/adversarial-reviewer.md) - Red team critique, bias detection
- [`confidence-quantifier`](./agents/usacf/confidence-quantifier.md) - Statistical confidence calibration
- [`synthesis-specialist`](./agents/usacf/synthesis-specialist.md) - Executive report generation

See [`USACF.md`](./agents/usacf/USACF.md) for complete framework documentation.

### USACF Commands

- [`/verify-claims`](./commands/usacf/verify-claims.md) - Bergstrom-West bullshit detection framework
- [`/create-adr`](./commands/usacf/create-adr.md) - Architecture Decision Records for AI agents
- [`/detect-hallucinations`](./commands/usacf/detect-hallucinations.md) - Gamified hallucination detection with XP rewards

### Gamification System

**XP Rewards:**
- 100-500 XP per discovery, depending on complexity
- 50-150 XP for critical insights
- Progressive levels with unlockable capabilities
- Achievement tracking and leaderboards

**Quality Standards:**
- >95% accuracy in hallucination detection
- <5% false positive rate
- 100% actionable guidance
- Full transparency in methods

---

## 📚 Reference Materials

14 comprehensive frameworks in [`prompts/references/`](./prompts/references/):

- **SAPPO.md** - Software Architecture Problem Prediction Ontology (gamified)
- **CallingBS.md** - Evidence-based verification (Bergstrom-West methodology)
- **Enhanced-Universal-PRD-Blueprint.md** - 660-line comprehensive PRD template
- **goodtestsguide.md** - FIRST principles, testing pyramid, academic citations
- **goodcodeguide.md** - SOLID, DRY/KISS/YAGNI, code quality principles
- **gametasknosec.md** - SPARC-SAPPO Agentic Development Framework v7.1
- **Gametaskbp.md** - Gamified Task Blueprint v6.0 (RISC protocol)
- **MetaPromptGenerator.md** - Universal Gamification Meta-Prompt Generator
- **truthprompt.md** - Radical Candor Truth Framework
- **promptbest.md** - Dynamic best practices (CoT, CoVE, ToT, ReAct)
- **claudeflow.md** - Claude Flow Universal Development Guide
- **playwrightbestpractices.md** - E2E testing with Playwright
- **AI Hallucination Detection.md** - Gamified detection with behavioral patterns
- **ADR.md** - Architecture Decision Record template

---

## ⚙️ Configuration

Configuration files in [`config/`](./config/):

- **swarm-config.json** - Agent performance profiles (conservative, balanced, aggressive)
- **pipeline-config.json** - Learning rates and optimization strategies
- **agents-profiles.json** - Individual agent performance metrics
- **claude-flow-plugin.json** - MCP server configurations

### MCP Servers (Optional)

3 MCP servers providing 110+ tools:

1. **claude-flow** - Core orchestration (40+ tools) - Required
2. **ruv-swarm** - WASM acceleration (2.8-4.4x speedup) - Optional
3. **flow-nexus** - Cloud platform (70+ tools, auth required) - Optional

---

## Commands

### Meta-Prompting

Separate analysis from execution. Describe what you want in natural language, Claude generates a rigorous prompt, then runs it in a fresh sub-agent context.

- [`/create-prompt`](./commands/create-prompt.md) - Generate optimized prompts with XML structure
- [`/run-prompt`](./commands/run-prompt.md) - Execute saved prompts in sub-agent contexts

### Todo Management

Capture ideas mid-conversation without derailing current work. Resume later with full context intact.

- [`/add-to-todos`](./commands/add-to-todos.md) - Capture tasks with full context
- [`/check-todos`](./commands/check-todos.md) - Resume work on captured tasks

### Context Handoff

Create structured handoff documents to continue work in a fresh context. Reference with `@whats-next.md` to resume seamlessly.

- [`/whats-next`](./commands/whats-next.md) - Create handoff document for fresh context

### Create Extensions

Wrapper commands that invoke the skills below.

- [`/create-agent-skill`](./commands/create-agent-skill.md) - Create a new skill
- [`/create-meta-prompt`](./commands/create-meta-prompt.md) - Create staged workflow prompts
- [`/create-slash-command`](./commands/create-slash-command.md) - Create a new slash command
- [`/create-subagent`](./commands/create-subagent.md) - Create a new subagent
- [`/create-hook`](./commands/create-hook.md) - Create a new hook

### Audit Extensions

Invoke auditor subagents.

- [`/audit-skill`](./commands/audit-skill.md) - Audit skill for best practices
- [`/audit-slash-command`](./commands/audit-slash-command.md) - Audit command for best practices
- [`/audit-subagent`](./commands/audit-subagent.md) - Audit subagent for best practices

### Self-Improvement

- [`/heal-skill`](./commands/heal-skill.md) - Fix skills based on execution issues

## Agents

Specialized subagents used by the audit commands.

- [`skill-auditor`](./agents/skill-auditor.md) - Expert skill auditor for best practices compliance
- [`slash-command-auditor`](./agents/slash-command-auditor.md) - Expert slash command auditor
- [`subagent-auditor`](./agents/subagent-auditor.md) - Expert subagent configuration auditor

## Skills

### [Create Agent Skills](./skills/create-agent-skills/)

Build skills by describing what you want. Asks clarifying questions, researches APIs if needed, and generates properly structured skill files. When things don't work perfectly, `/heal-skill` analyzes what went wrong and updates the skill based on what actually worked.

Commands: `/create-agent-skill`, `/heal-skill`, `/audit-skill`

### [Create Meta-Prompts](./skills/create-meta-prompts/)

The skill-based evolution of the meta-prompting system. Builds prompts with structured outputs (research.md, plan.md) that subsequent prompts can parse. Adds automatic dependency detection to chain research → plan → implement workflows.

Commands: `/create-meta-prompt`

### [Create Slash Commands](./skills/create-slash-commands/)

Build commands that expand into full prompts when invoked. Describe the command you want, get proper YAML configuration with arguments, tool restrictions, and dynamic context loading.

Commands: `/create-slash-command`, `/audit-slash-command`

### [Create Subagents](./skills/create-subagents/)

Build specialized Claude instances that run in isolated contexts. Describe the agent's purpose, get optimized system prompts with the right tool access and orchestration patterns.

Commands: `/create-subagent`, `/audit-subagent`

### [Create Hooks](./skills/create-hooks/)

Build event-driven automation that triggers on tool calls, session events, or prompt submissions. Describe what you want to automate, get working hook configurations.

Commands: `/create-hook`

---

More resources coming soon.

---

## 🔗 Integration Synergies

### How These Systems Work Together

**1. USACF + claude-flow Swarm Coordination**
- USACF agents can be deployed as swarm workers in claude-flow hierarchical topologies
- Meta-learning-orchestrator coordinates with queen-coordinator for strategic planning
- Adversarial-reviewer integrates with code-review-swarm for comprehensive analysis

**2. SPARC + USACF Methodology Integration**
- SPARC Specification phase uses meta-learning-orchestrator for requirements discovery
- SPARC Architecture phase uses structural-mapper and risk-analyst
- SPARC Code phase uses adversarial-reviewer for critical review

**3. GitHub Automation + USACF Quality Gates**
- PR-manager deploys confidence-quantifier for merge readiness scoring
- Code-review-swarm uses adversarial-reviewer for bias detection
- Release-manager uses risk-analyst for deployment risk assessment

**4. Memory Coordination Across All Systems**
- claude-flow agents use `mcp__claude-flow__memory_usage` with namespace "coordination"
- USACF agents share discovery patterns and confidence scores
- Original TÂCHES commands integrate with shared memory for context preservation

**5. Gamification + Performance Metrics**
- USACF XP rewards combine with claude-flow performance benchmarking
- Progressive levels unlock advanced agent capabilities
- Achievement tracking motivates continuous improvement

### Example Workflows

**Complex Feature Development:**
```
1. /create-meta-prompt → Generate SPARC workflow
2. SPARC Specification → Deploy USACF meta-learning-orchestrator
3. SPARC Architecture → Deploy structural-mapper + risk-analyst
4. SPARC Code → Deploy claude-flow coder swarm
5. /github pr-manager → Multi-agent code review
6. /detect-hallucinations → Quality validation
7. /verify-claims → Evidence-based approval
```

**Security Audit:**
```
1. /verify-claims → Audit security claims
2. Deploy adversarial-reviewer → Red team analysis
3. Deploy security-manager → Byzantine fault detection
4. /detect-hallucinations → False security detection
5. /create-adr → Document security decisions
```

**Multi-Repo Coordination:**
```
1. /github multi-repo-swarm → Initialize coordination
2. Deploy hierarchical-coordinator → Strategic oversight
3. Deploy worker-specialists → Parallel implementation
4. Deploy sync-coordinator → Cross-repo synchronization
5. /verify-claims → Validate integration points
```

---

## 📊 Quick Start Guide

### For New Users

1. **Start Simple**: Try `/create-prompt` and `/run-prompt` for meta-prompting
2. **Add Todo Management**: Use `/add-to-todos` and `/check-todos`
3. **Create Extensions**: Experiment with `/create-slash-command`

### For Advanced Users

1. **Enable MCP Servers**: Configure claude-flow MCP for full orchestration
2. **Deploy Swarm Agents**: Use `/coordination` commands for multi-agent tasks
3. **Apply SPARC**: Use `/sparc` methodology for complex development
4. **Integrate USACF**: Use `/verify-claims` and `/detect-hallucinations` for quality

### For Enterprise Users

1. **Configure Swarm Topologies**: Edit `config/swarm-config.json`
2. **Customize Agent Profiles**: Modify `config/agents-profiles.json`
3. **Set Up GitHub Automation**: Configure `/github` commands for your workflow
4. **Enable Neural Training**: Activate pre-trained models for WASM acceleration

---

## 🤝 Credits

**Original TÂCHES Resources**: glittercowboy
**claude-flow Integration**: https://github.com/ruvnet/claude-flow
**USACF Framework**: https://github.com/Havokyn/UsefulPrompts
**Community**: All contributors and community members

---

**Community Ports:** [OpenCode](https://github.com/stephenschoettler/taches-oc-prompts)

—TÂCHES
