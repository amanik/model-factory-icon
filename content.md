# Model Training Factory — Editable Content
<!--
  HOW TO USE: Edit any text below. Keep the section headers (## and ###) intact.
  Hand this file back to have both HTML versions regenerated.

  Formatting:
  - **bold** for emphasis
  - Regular paragraphs for body text
  - Bulleted lists with -
  - > blockquotes for callouts
  - Tables use | pipes |

  Notes:
  - icon.html is the primary/presentation version
  - explainer.html is the long-form reference version
  - Where the explainer has different text, it is noted with <!-- explainer variant: ... -->
  - The explainer has a TL;DR section not present in icon.html
-->

## Meta
- title: The Model Training Factory
- subtitle: Blue Yonder AI Platform
- conference: ICON 2026
- footer: Model Training Factory — ICON 2026 Sales Enablement

<!-- explainer variant title: "How the Model Training Factory works" -->
<!-- explainer variant eyebrow: "Blue Yonder AI Platform · sales enablement" -->

## Hero / Masthead

### Eyebrow
Blue Yonder AI Platform

### Heading
The Model Training **Factory**

### Intro
A repeatable system for building custom supply-chain models trained to operate like subject matter experts in the Blue Yonder ecosystem. Owned intelligence, not rented — built to scale across the business.

### Factory Flow Diagram (pipeline stages)
1. Operational Data
2. Simulation / Gym
3. Training & Evaluation
4. Specialized Models
5. Platform Integration
- Feedback loop label: Continuous Improvement

### TL;DR (explainer only)
<!-- This section only appears in explainer.html -->
**TL;DR** — The Model Factory is a repeatable system for building, evaluating, and deploying specialized AI capabilities for supply chain operations. It combines operational data, simulation environments, layered training (SFT, DPO, RL), and continuous evaluation to produce operational agents — not chatbots. The first agent investigates allocation shortages end-to-end in warehouse operations.

---

## Section 01: What We Are Building

### Intro
The Model Factory is Blue Yonder's repeatable system for building operational AI capabilities for supply chain workflows. Rather than building isolated copilots or one-off AI demos, the Model Factory creates specialized AI systems that can reason about operational scenarios, interact with enterprise workflows, and continuously improve through evaluation and learning loops.

### Agent Capabilities
The goal is not simply to answer questions. The goal is to create operational agents that can:
- Understand warehouse and supply chain workflows
- Investigate operational problems
- Execute structured workflows
- Interact with enterprise systems
- Learn from evaluations and operational feedback

### Callout
> At its core, the Model Factory is a scalable capability-generation system for operational AI — owned intelligence, not rented intelligence, built in a repeatable way we can scale across the business.

### How Does the Model Training Process Work?
Define the supply-chain job to be done, build an agent and success criteria to evaluate it, run the agent through thousands of related tasks while benchmarking where frontier models fail, generate high-quality training data, fine-tune the model, train against good and bad traces and failure modes, run it through repeated evaluation, and keep iterating until the model performs the workflow the way Blue Yonder wants it to.

---

## Section 02: Why Generic AI Is Not Enough

### Intro
Frontier models are extremely capable at language understanding and general reasoning. However, supply chain operations introduce a fundamentally different problem space. This is why operational AI requires a dedicated system architecture rather than simply adding prompts on top of a general-purpose model.

<!-- explainer variant intro: "General-purpose LLMs are strong at language understanding, but supply chain operations require capabilities that generic models don't provide out of the box." -->

### Comparison: Generic AI vs Operational AI

| Generic AI | Operational AI (Model Factory) |
|---|---|
| Broad conversational intelligence | Deep operational context awareness |
| Static prompt-based reasoning | Structured workflow reasoning |
| No operational workflow context | Tool orchestration across enterprise APIs |
| Optimized for plausible answers | Consistent and auditable execution |
| No enterprise system integration | Safe handling of operational edge cases |
| No evaluation against operational outcomes | Deterministic and repeatable behavior |
| | Evaluated against measurable operational outcomes |

<!-- explainer variant Generic AI column:
- General-purpose language understanding
- Prompt-based, stateless interactions
- No operational context or workflow awareness
- Cannot execute against enterprise systems
- No continuous improvement from operations
-->

<!-- explainer variant Operational AI column:
- Domain-specialized reasoning
- Structured multi-step planning
- Deep operational context and state awareness
- Tool orchestration and API execution
- Continuous learning from evaluation loops
-->

### Callout
> Generic AI systems are optimized for broad conversational intelligence. Operational AI systems must instead understand workflows and state transitions, navigate enterprise APIs and systems, reason over operational data, execute tasks reliably, and be evaluated against measurable outcomes.

<!-- explainer variant callout: "The output of the Model Factory is not a chatbot. It is an operational agent combining reasoning, operational context, workflow execution, and enterprise integrations into a unified system." -->

---

## Section 03: The Model Factory Architecture

### Intro
The Model Factory combines operational data, simulation systems, evaluation pipelines, and continuous learning loops into a scalable operational AI platform.

<!-- explainer variant intro: "Each component feeds the next. Evaluation results loop back into the data layer, creating a continuous improvement flywheel." -->

### Architecture Flow (visual summary)
1. Operational Data Layer — WMS workflows, transactions, simulations, evaluations, SME knowledge
2. Cognitive Gym — High-speed simulation mirroring operational workflows and APIs
3. Training & Continuous Learning — SFT, DPO, reinforcement learning, evaluation harnesses
4. Operational Agents — Reasoning + context + workflow execution + integrations
5. Evaluation & Safety — Scenario replay, benchmarks, guardrails, human review

### 1. Operational Data Layer
Operational intelligence requires operational data. The Model Factory uses multiple sources of operational context and workflow information to build operational realism and workflow diversity that allows models to generalize across different warehouse environments and scenarios.

- Warehouse operational workflows
- Transactional patterns
- Simulation trajectories
- Evaluation datasets
- SME-guided operational examples

### 2. Cognitive Gym
A high-speed simulation environment that mirrors operational workflows and APIs without impacting production systems. The gym allows the team to move beyond static prompting into iterative operational systems training.

- Rapid experimentation
- Safe failure testing
- Reinforcement learning
- Trajectory generation
- Repeatable evaluations
- Scalable operational learning

<!-- explainer variant bullets add "episodes" and "at scale" qualifiers:
- Reinforcement learning episodes
- Trajectory generation at scale
-->

### 3. Training & Continuous Learning
The Model Factory uses a layered learning approach to specialize models for supply chain execution. Rather than training frontier-scale foundation models from scratch, Blue Yonder builds on top of strong open-source foundation models and specializes them for operational workflows.

- Domain adaptation
- Supervised Fine-Tuning (SFT)
- Preference Optimization (DPO)
- Reinforcement Learning
- Evaluation Harnesses
- Regression Testing
- Continuous trajectory collection

### 4. Operational Agents
The output of the Model Factory is not a chatbot. It is an operational agent combining reasoning, operational context, workflow execution, and enterprise integrations into a unified operational system.

- Understanding operational state
- Investigating warehouse scenarios
- Using enterprise tools and APIs
- Executing structured workflows
- Recommending operational actions
- Supporting workflow automation

### 5. Evaluation & Safety
Evaluation is a first-class component of the Model Factory. Operational AI systems require measurable reliability, consistency, and safety. The goal is operational correctness and repeatability — not simply generating plausible answers.

- Scenario replay
- Benchmark suites
- Automated evaluation pipelines
- Human review
- Regression testing
- Confidence thresholds
- Guardrails and escalation mechanisms

<!-- explainer variant combines first two bullets: "Scenario replay and benchmark suites" and uses "Human review gates" -->

---

## Section 04: Why This Matters

### Intro
The Model Factory enables Blue Yonder to move beyond static AI assistants toward operational intelligence systems. The long-term advantage does not come from prompts or a single model — it compounds from systems, data, and continuous learning.

### Business Impact
- Faster operational issue resolution
- Workflow automation
- Scalable operational expertise
- Continuous capability improvement
- Reduced operational overhead

<!-- explainer variant has expanded descriptions:
- **Faster resolution** — Operational issues investigated and resolved in minutes, not hours
- **Workflow automation** — Multi-step processes executed end-to-end by agents
- **Scalable expertise** — Operational knowledge available 24/7 across all sites
- **Continuous improvement** — Every interaction makes the system better
- **Reduced overhead** — Less manual investigation, more strategic decision-making
-->

### Strategic Impact
- Operational data flywheels
- Domain expertise accumulation
- Evaluation infrastructure
- Simulation environments
- Workflow integrations
- Continuous learning systems

<!-- explainer variant has expanded descriptions:
- **Operational data flywheel** — Each deployment generates training signal
- **Domain expertise accumulation** — Tacit knowledge captured systematically
- **Evaluation infrastructure** — Measurable, repeatable quality standards
- **Simulation environments** — Safe learning at scale
- **Workflow integrations** — Deep enterprise system connectivity
- **Continuous learning systems** — Always improving, never static
-->

### Callout
> Together, these create compounding operational intelligence over time. The advantage is not in a single model — it is in the system and flywheel around the model.

### Levels of Autonomy
The Model Factory enables progression toward higher levels of intelligent automation in supply chain.

| Step | Label | Sublabel | Status |
|---|---|---|---|
| 1 | Chat | Q&A | done |
| 2 | Copilots | Assisted | done |
| 3 | Workflow | Execution | done |
| 4 | Operational Agents | We are here | current |
| 5 | Autonomous | Operations | future |

<!-- explainer variant uses "Agents" instead of "Operational Agents" for step 4 label -->

### Continuous Learning Flywheel
The system continuously improves through evaluation and operational feedback loops.

Center label: Learning Flywheel

Nodes (clockwise):
1. Operational Scenarios
2. Trajectories
3. Evaluation
4. Fine-Tuning
5. Deployment
6. New Interactions
7. More Scenarios

---

## Section 05: First Example — Allocation Shorts Agent

### Intro
The first operational agent built using the Model Factory addresses one of the most common and time-consuming warehouse challenges: investigating allocation shortages.

### Tag
Warehouse Operations

### What the Agent Does
#### Allocation Shorts Investigation
When a warehouse cannot fully allocate inventory to outbound orders, operators must investigate why. This involves navigating multiple systems, checking inventory status, reviewing order priorities, and identifying root causes. Today, this process is manual, time-consuming, and requires deep operational knowledge.

The Allocation Shorts Agent automates this investigation workflow end-to-end, combining reasoning about operational state with structured tool use across enterprise systems.

### Image Caption
Agent conversation: structured investigation with tool calls, data tables, and operational recommendations

<!-- explainer variant caption: "Agent resolves allocation shorts: identifies recoverable inventory, executes yard move, tracks fulfillment via Live Activity" -->

### Agent Workflow Steps
1. User Request
2. **Agent Reasoning** (highlighted)
3. Tool / API Calls
4. Operational Analysis
5. **Recommendation** (highlighted)

<!-- explainer variant uses "Analysis" instead of "Operational Analysis" for step 4 -->

### Additional Use Cases
- Short order investigation
- Yard management
- Inventory analysis
- Workflow optimization
- Operational exception handling

<!-- explainer variant has slightly expanded items:
- Short order investigation
- Yard management optimization
- Inventory analysis and reconciliation
- Workflow optimization
- Operational exception handling

And adds intro text: "The same Model Factory infrastructure supports building agents for:"
-->

---

## Section 06: Sales Enablement

### Intro
Resources and materials structured for pre-sales teams to effectively demonstrate, explain, and position the Model Factory during customer engagements.

<!-- explainer variant intro: "Structured resources for pre-sales teams to demonstrate, explain, and position the Model Factory during customer engagements." -->

### Track 1: Capability Walkthrough
Slides walking through core capabilities, positioned for business and technical audiences.

- What the Model Factory is and why it matters
- Architecture overview (5 components)
- Generic AI vs Operational AI positioning
- Levels of autonomy progression
- First agent use case demo flow

Tip: Press **P** on this page to enter presentation mode.

### Track 2: Functionality Deep Dive
Detailed list of new functionality, configuration guidance, and targeted business use cases.

- Operational Agent capabilities and tool use
- Cognitive Gym simulation environment
- Evaluation and benchmarking pipelines
- Continuous learning and feedback loops
- Enterprise API integration patterns

Placeholder: [Screenshot placeholders — to be populated by team with execution examples]

### Track 3: Demo Access
Working demonstrations accessible in demo environments with pre-configured data for example executions.

- Demo environment access and credentials
- Pre-configured scenarios to walk through
- Step-by-step guide for driving example executions
- Data ingestion setup and sample datasets

Placeholder: [Demo environment details — TBD by team. Ideally in standard demo envs, separate env if needed.]

### Track 4: Limitations & Roadmap
Known limitations, pitfalls to watch for, and future directions for the Model Factory initiative.

- **Current scope:** Warehouse operations focus (WMS-centric)
- **Data dependency:** Quality of operational data directly impacts agent performance
- **Human oversight:** Agents augment operators, not replace them
- **Evaluation maturity:** Benchmark suites expanding continuously

#### Future Directions
- World models for supply chain simulation
- Autonomy labs for advanced agent research
- Expanded domain coverage beyond warehouse
- Cross-environment generalization improvements

<!-- explainer variant Track 4 is condensed:
- **Current scope:** WMS-centric warehouse operations
- **Data dependency:** Quality impacts agent performance
- **Human oversight:** Agents augment, not replace
- **Future:** World models, autonomy labs, expanded domains
-->

---

## Section 07: Questions & Answers

### Tab: Fundamentals

#### Q1: What exactly is a "Model Factory"?
A model factory is a repeatable system for building, evaluating, improving, and deploying AI capabilities at scale. Key aspects include:

- Continuous data ingestion
- Simulation and trajectory generation
- Evaluation and benchmarking
- Fine-tuning and reinforcement learning
- Operational deployment and monitoring

The goal is not to build one-off models, but to create a scalable capability production system for supply chain AI.

<!-- explainer variant is a single paragraph: "A repeatable system for building, evaluating, improving, and deploying AI capabilities at scale. It includes continuous data ingestion, simulation and trajectory generation, evaluation and benchmarking, fine-tuning and reinforcement learning, and operational deployment and monitoring. The goal is not one-off models, but a scalable capability production system." -->

#### Q2: Why does supply chain need specialized AI models?
General-purpose models are very strong at language understanding, but supply chain operations require:

- Deep operational context
- Structured reasoning
- Workflow execution
- Tool orchestration
- Consistent and auditable decision-making

We specialize models for warehouse and supply chain execution to improve operational correctness, reliability, and business value.

#### Q3: How is this different from simple RAG or chatbot systems?
RAG retrieves information from documents. Our approach goes significantly further:

- Operational reasoning
- Multi-step planning
- Tool execution
- Workflow automation
- Learning from operational trajectories
- Continuous improvement through evaluation loops

We are building operational agents, not document chatbots.

### Tab: Technical Approach

#### Q4: How exactly do you train your models?
We use a layered training approach:

- Frontier foundation models as base intelligence
- Domain adaptation using warehouse workflows
- Supervised Fine-Tuning (SFT)
- Preference optimization (DPO)
- Reinforcement learning using simulation environments ("gym")

The models continuously improve through evaluation feedback and operational learning loops.

#### Q5: Are you training foundation models from scratch?
No — we are not training frontier-scale foundation models completely from scratch. Instead, we build on top of strong open-source foundation models and specialize them for supply chain and warehouse operations. Our focus is on:

- Domain adaptation
- Supervised Fine-Tuning (SFT)
- Preference optimization (DPO)
- Reinforcement learning approaches
- Operational evaluation and feedback loops

This allows us to leverage the massive investment already made in general-purpose intelligence while focusing our efforts on operational reasoning, workflow execution, and enterprise-specific capabilities.

#### Q6: What role does reinforcement learning play?
Reinforcement learning helps the model improve decision-making through simulation. The "gym" environment allows us to:

- Run scenarios safely
- Test many operational variations quickly
- Reward successful task execution
- Improve agent behavior iteratively

This enables scalable learning without impacting production systems.

#### Q13: Can you explain the architecture in a few sentences?
The architecture combines:

- A simulation environment ("gym")
- Operational APIs and tool interfaces
- Data flywheel pipelines
- Evaluation harnesses
- Fine-tuning and RL pipelines

Together, this creates a closed-loop learning system for warehouse operations.

#### Q14: What is the purpose of the "gym"?
The gym is a fast, safe simulation environment that mirrors warehouse operations. It enables:

- Rapid experimentation
- Trajectory generation
- Reinforcement learning
- Failure testing
- Repeatable evaluations

This allows scalable learning without impacting production systems.

### Tab: Data & Privacy

#### Q7: Where does the training data come from?
Our agentic Operator models are training with 100% synthetic data. The data comes from multiple sources:

- Warehouse operational workflows
- Transactional patterns
- Simulation trajectories
- SME-guided examples
- Evaluation datasets

All customer data usage follows contractual permissions and governance controls.

#### Q8: How do you handle privacy and customer data governance?
Governance is a critical part of the initiative. Key controls include:

- Contractually permitted usage only
- Region-aware storage and processing
- Internal R&D environments only
- Controlled access and retention policies

We treat governance as a first-class concern, not an afterthought.

#### Q9: How much synthetic vs. real data do you use?
Both are important and serve different purposes.

**Real data provides:**
- Operational realism
- True workflow patterns
- Real-world edge cases

**Synthetic and simulated data helps:**
- Expand coverage
- Generate rare scenarios
- Scale training safely

The combination allows us to balance realism and scalability.

### Tab: Human Expertise

#### Q10: How do you ingest expertise from SMEs?
We capture expertise through:

- Workflow walkthroughs
- Operational demonstrations
- Meeting transcripts
- Human feedback loops
- Evaluation reviews
- Trajectory correction

The goal is to convert tacit operational knowledge into reusable training and evaluation signals.

#### Q11: How do you capture tacit operational knowledge?
A large part of warehouse expertise is not documented explicitly. We learn this through:

- Observing operational decisions
- Comparing successful vs. unsuccessful workflows
- Capturing repeated expert patterns
- Feeding corrections back into the flywheel

Over time, the system accumulates operational knowledge and decision patterns.

#### Q12: What role do human operators still play?
Human expertise remains essential. SMEs provide:

- Workflow understanding
- Evaluation feedback
- Exception handling
- Operational policy guidance
- Validation of model behavior

The goal is augmentation and scalability of expertise, not removal of human oversight.

### Tab: Evaluation & Safety

#### Q15: How do you evaluate success?
We evaluate across multiple dimensions:

- Operational correctness
- Scenario completion
- Tool-use accuracy
- Consistency
- Latency
- Human evaluation
- Benchmark and regression suites

The focus is operational reliability, not just conversational quality.

#### Q16: How do you avoid overfitting to one warehouse or customer?
Generalization is a key design principle. We address this through:

- Diverse operational patterns
- Simulation variability
- Cross-environment evaluation
- Synthetic scenario expansion

The goal is reusable operational intelligence, not customer-specific memorization.

#### Q19: What happens when the model is wrong?
Enterprise AI systems require guardrails and controlled autonomy. Key mechanisms include:

- Scoped permissions
- Human escalation paths
- Confidence thresholds
- Auditability
- Evaluation gates
- Safe fallback behavior

The system is designed to operate safely within defined boundaries.

### Tab: Strategic Positioning

#### Q17: What makes Blue Yonder uniquely positioned for this?
Blue Yonder combines:

- Deep supply chain expertise
- Large operational customer footprint
- Real execution system integration
- Historical operational data
- Existing workflow understanding

This creates a strong foundation for operational AI systems.

#### Q18: What is the long-term moat?
The moat is not prompts or a single model. The moat comes from:

- Operational data flywheel
- Domain expertise
- Evaluation infrastructure
- Workflow integrations
- Simulation environments
- Continuous learning systems

This creates compounding advantages over time.

#### Q20: Why not just use OpenAI directly?
Frontier models provide strong general intelligence. Our differentiation comes from:

- Operational context
- Workflow orchestration
- Domain specialization
- Tool integrations
- Evaluation infrastructure
- Continuous operational learning

The value is in the system and flywheel around the model.
