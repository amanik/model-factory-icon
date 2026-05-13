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
A repeatable system for building specialized supply-chain models trained to operate like subject matter experts in the Blue Yonder ecosystem. Owned intelligence, not rented — built to scale across the business.

### Factory Flow Diagram (pipeline stages)
1. Operational Data
2. Simulated Training
3. Training & Evaluation
4. Specialized Models
5. Platform Integration
- Feedback loop label: Continuous Improvement

### TL;DR (explainer only)
<!-- This section only appears in explainer.html -->
**TL;DR** — The Model Factory is a repeatable system for building, evaluating, and deploying specialized AI capabilities for supply chain operations. It combines operational data, simulated training environments, layered training (domain fine-tuning, preference alignment, RL), and continuous evaluation to produce specialized agents — not chatbots. The first agent investigates allocation shortages end-to-end in warehouse operations.

---

## Section 01: What We Are Building

### Intro
The Model Factory is Blue Yonder's repeatable system for building specialized AI capabilities for supply chain workflows. Rather than building isolated copilots or one-off AI demos, the Model Factory creates specialized AI systems that can reason about operational scenarios, interact with enterprise workflows, and continuously improve through evaluation and learning loops.

### Agent Capabilities
The goal is not simply to answer questions. The goal is to create specialized agents that can:
- Understand warehouse and supply chain workflows
- Investigate operational problems
- Execute structured workflows
- Interact with enterprise systems
- Learn from evaluations and operational feedback

### Callout
> At its core, the Model Factory is a scalable capability-generation system for specialized AI — owned intelligence, not rented intelligence, built in a repeatable way we can scale across the business.

### Model Architecture
The primary reason for training specialized models is to achieve faster, cheaper, and more performant automation — enabling agents to handle more tasks autonomously. Three architecture patterns show how specialized and frontier models work together.

**Routing Model**
A frontier model acts as a router, analyzing incoming requests and dispatching them to the right specialized supply chain model. The frontier handles intent classification; the specialized model handles domain execution. Fast, cheap, and targeted.

**Sub-Agent Model**
A frontier model handles high-level reasoning and orchestration, then delegates operational tasks to a specialized supply chain sub-agent. The frontier thinks; the specialized model acts. Each does what it's best at.

**Foundational Supply Chain Model**
The long-term vision: a single foundational model trained end-to-end on supply chain operations. One model that understands the entire domain — routing, reasoning, and execution — without needing a frontier model in the loop.

---

## Section 02: Why Generic AI Is Not Enough

### Intro
Frontier models are extremely capable at language understanding and general reasoning. However, supply chain operations introduce a fundamentally different problem space. This is why specialized AI requires a dedicated system architecture rather than simply adding prompts on top of a general-purpose model.

<!-- explainer variant intro: "General-purpose LLMs are strong at language understanding, but supply chain operations require capabilities that generic models don't provide out of the box." -->

### Comparison: Generic AI vs Specialized AI

| Generic AI | Specialized AI (Model Factory) |
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

<!-- explainer variant Specialized AI column:
- Domain-specialized reasoning
- Structured multi-step planning
- Deep operational context and state awareness
- Tool orchestration and API execution
- Continuous learning from evaluation loops
-->

### Callout
> Generic AI systems are optimized for broad conversational intelligence. Specialized and domain fine-tuned AI systems must instead understand workflows and state transitions, navigate enterprise APIs and systems, reason over operational data, execute tasks reliably, and be evaluated against measurable outcomes.

<!-- explainer variant callout: "The output of the Model Factory is not a chatbot. It is a specialized agent combining reasoning, operational context, workflow execution, and enterprise integrations into a unified system." -->

### Where Frontier Models Fail

Even the most capable frontier models break down in predictable ways when applied to operational supply chain work.

**Domain Language**
Misunderstands warehouse terminology, treats operational terms as typos, and makes irrelevant suggestions that don't map to real workflows. Guesses when uncertain, leading to wasted retries — too strict on spelling and IDs, too loose on business logic.

**Operational Intuition**
Cannot generalize across different warehouse configurations. Only performs with extensive prompt context — no embedded tribal or trade knowledge. Thinks too long on simple lookups and adds latency to time-sensitive operations.

**Operational Context**
No memory across sessions. Misinterprets user intent without workflow awareness. No understanding of operational priorities or urgency. Optimizes for plausible-sounding answers rather than correct operational outcomes.

**Gaming vs. Solving**
Reward hacking and pattern-matching produce outputs that look right but don't resolve the actual operational problem. Stylistic and formatting issues mask substantive gaps in reasoning and execution.

### What Domain Fine-tuning Actually Means

Domain fine-tuning is not simply teaching a model industry terminology or adding more prompts. The real shift is that the model learns how a business domain operates: how workflows decompose, how operational decisions are made, what context matters, and how actions should be executed safely.

### Key Capabilities of a Domain Fine-tuned Model

**Operational Reasoning**
The model learns how business workflows naturally break down into operational investigations, dependencies, and next steps.

**Business Interpretation**
The model translates raw enterprise data into operational meaning, urgency, and business impact rather than simply returning system outputs.

**Context-Aware Decision Making**
The model learns when to infer, ask follow-up questions, summarize, or stop execution safely.

**Operational Prioritization**
The model understands that not all records or events matter equally and learns to prioritize based on operational impact and urgency.

**Action-Oriented Responses**
The model optimizes for resolving business issues rather than simply answering the immediate question.

### Domain Fine-tuning Callout
> Domain fine-tuning is fundamentally about operational reasoning. The model learns how work is actually performed: how workflows break down, how decisions are prioritized, how operational context changes meaning, and how enterprise data translates into business action.

---

## Section 03: How the Model Factory Builds a Specialized SC Model

### Intro
The Model Factory is a repeatable process for building specialized AI capabilities. Rather than a single training run, it is a continuous cycle of specification, data generation, training, evaluation, and improvement.

<!-- explainer variant intro: "Each step feeds the next. Evaluation results loop back into data generation, creating a continuous improvement cycle." -->

### Process Steps (visual summary)
1. Problem & Domain Specification — Define the job, success criteria, evaluation benchmarks
2. Data Artifact Generation — 100% synthetic data from simulated training environments
3. Model Training — Domain fine-tuning and preference alignment
4. Model Evaluation & Go Live — Benchmarks, scenario replay, human review gates
5. Continuous Improvement — Feedback loops generate new scenarios each iteration

### 1. Problem and Domain Specification
Start by defining the supply-chain job the agent must perform. Scope the operational domain, set measurable success criteria, and build evaluation benchmarks — all before any training begins.

### 2. Data Artifact Generation
Generate high-quality training data using 100% synthetic data from simulated training environments. Cover normal operations, edge cases, and failure modes at scale — without using any customer data.

### 3. Model Training
Specialize the model through domain fine-tuning and preference alignment. Fine-tuning teaches operational workflows and reasoning patterns; preference alignment teaches the model to distinguish good approaches from bad, ensuring it completes tasks the way Blue Yonder wants.

### 4. Model Evaluation and Go Live
Run the model through benchmarks, scenario replay, and human review gates before deployment. Evaluation is not an afterthought — it is a first-class component of the factory. Deploy only when quality thresholds are met.

### 5. Continuous Improvement
Every deployment creates training signal for the next iteration. Feedback loops generate new scenarios, identify gaps, and drive continuous improvement — the system gets better with every cycle.

---

## Section 04: First Agent — Allocation Shorts

### Intro
The first specialized agent built using the Model Factory addresses one of the most common and time-consuming warehouse challenges: investigating allocation shortages.

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
2. Agent Reasoning
3. Tool / API Calls
4. Operational Analysis
5. Recommendation

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

### Next Steps

**Ship the Allocation Shorts Agent**
Move the first specialized model from evaluation into production, delivering autonomous shortage investigation to warehouse operations.

**Expand across Blue Yonder products**
Apply the Model Factory to more supply chain workflows — training specialized models that work across the Blue Yonder product suite.

---

## Section 05: Questions & Answers

### Tab: Fundamentals

#### Q1: What exactly is a "Model Factory"?
A repeatable system for building, evaluating, improving, and deploying AI capabilities at scale. It includes continuous data generation, simulated training environments, evaluation and benchmarking, domain fine-tuning and preference alignment, and operational deployment with monitoring. The goal is not one-off models, but a scalable capability production system for supply chain AI.

#### Q2: Why does supply chain need specialized AI models?
General-purpose models are strong at language understanding, but supply chain operations require deep operational context, structured reasoning, workflow execution, tool orchestration, and consistent auditable decision-making. We specialize models for warehouse and supply chain execution to improve operational correctness, reliability, and business value.

#### Q3: How is this different from simple RAG or chatbot systems?
RAG retrieves information from documents. Our approach goes significantly further — operational reasoning, multi-step planning, tool execution, workflow automation, and continuous improvement through evaluation loops. We are building specialized agents, not document chatbots.

### Tab: Technical Approach

#### Q4: How exactly do you train your models?
We use a layered training approach: frontier foundation models as base intelligence, domain adaptation using warehouse workflows, domain fine-tuning on operational procedures and reasoning patterns, preference alignment to ensure the model completes tasks the way Blue Yonder wants, and reinforcement learning using simulated training environments. The models continuously improve through evaluation feedback and operational learning loops.

#### Q5: Are you training foundation models from scratch?
No. We build on top of strong open-source foundation models and specialize them for supply chain and warehouse operations through domain fine-tuning, preference alignment, and reinforcement learning. This lets us leverage the massive investment already made in general-purpose intelligence while focusing on operational reasoning, workflow execution, and enterprise-specific capabilities.

#### Q6: What role does reinforcement learning play?
Reinforcement learning helps the model improve decision-making through simulation. Simulated training environments allow us to run scenarios safely, test many operational variations quickly, reward successful task execution, and improve agent behavior iteratively — all without impacting production systems.

#### Q7: What is domain fine-tuning?
Domain fine-tuning teaches the model how a business domain actually operates. Rather than just learning terminology, the model learns how workflows decompose, how operational decisions are made, what context matters, and how actions should be executed safely. It is the process that turns a general-purpose model into one that reasons like an experienced supply chain professional.

#### Q8: What is preference alignment?
After domain fine-tuning gives the model basic operational competence, preference alignment teaches it to distinguish between good and bad approaches. Using pairs of example responses, the model learns which investigation strategies are more thorough, which recommendations are more actionable, and which communication styles are more appropriate for operational contexts. This ensures the model completes tasks the way Blue Yonder wants them completed.

#### Q9: Can you explain the architecture in a few sentences?
The Model Factory is a five-step cycle: define the problem and domain, generate synthetic training data from simulated environments, train the model using domain fine-tuning and preference alignment, evaluate against benchmarks and human review, then deploy and collect feedback for continuous improvement. Each cycle makes the model better.

### Tab: Data & Privacy

#### Q10: Where does the training data come from?
Our agentic Operator models train with 100% synthetic data. Data is generated from simulated training environments that mirror warehouse operational workflows, transactional patterns, and diverse operational scenarios. All data generation follows governance controls and does not use customer production data.

#### Q11: How do you handle privacy and customer data governance?
Governance is a first-class concern. Key controls include contractually permitted usage only, region-aware storage and processing, internal R&D environments only, and controlled access and retention policies.

#### Q12: How much synthetic vs. real data do you use?
Our specialized agent models are trained on 100% synthetic data generated from simulated training environments. This allows us to generate diverse operational scenarios, cover rare edge cases, and scale training safely — all without dependency on customer production data.

### Tab: Human Expertise

#### Q13: How do you ingest expertise from SMEs?
We capture expertise through workflow walkthroughs, operational demonstrations, meeting transcripts, human feedback loops, evaluation reviews, and trajectory correction. The goal is to convert tacit operational knowledge into reusable training and evaluation signals.

#### Q14: How do you capture tacit operational knowledge?
A large part of warehouse expertise is not documented explicitly. We learn this through observing operational decisions, comparing successful vs. unsuccessful workflows, capturing repeated expert patterns, and feeding corrections back into the training cycle. Over time, the system accumulates operational knowledge and decision patterns.

#### Q15: What role do human operators still play?
Human expertise remains essential. SMEs provide workflow understanding, evaluation feedback, exception handling, operational policy guidance, and validation of model behavior. The goal is augmentation and scalability of expertise, not removal of human oversight.

### Tab: Evaluation & Safety

#### Q16: How do you evaluate success?
We evaluate across multiple dimensions: operational correctness, scenario completion, tool-use accuracy, consistency, latency, human evaluation, and benchmark and regression suites. The focus is operational reliability, not just conversational quality.

#### Q17: How do you avoid overfitting to one warehouse or customer?
Generalization is a key design principle. We address this through diverse operational patterns, simulation variability, cross-environment evaluation, and synthetic scenario expansion. The goal is reusable operational intelligence, not customer-specific memorization.

#### Q18: What happens when the model is wrong?
Enterprise AI systems require guardrails and controlled autonomy. Key mechanisms include scoped permissions, human escalation paths, confidence thresholds, auditability, evaluation gates, and safe fallback behavior. The system operates safely within defined boundaries.

### Tab: Strategic Positioning

#### Q19: What makes Blue Yonder uniquely positioned for this?
Blue Yonder combines deep supply chain expertise, a large operational customer footprint, real execution system integration, historical operational data, and existing workflow understanding. This creates a strong foundation for specialized AI systems.

#### Q20: What is the long-term moat?
The moat is not prompts or a single model. It comes from the operational data flywheel, accumulated domain expertise, evaluation infrastructure, workflow integrations, simulated training environments, and continuous learning systems. Together, these create compounding advantages over time — the advantage is in the system and flywheel around the model.

#### Q21: Why not just use OpenAI directly?
Frontier models provide strong general intelligence, but our differentiation comes from operational context, workflow orchestration, domain specialization through fine-tuning and preference alignment, tool integrations, evaluation infrastructure, and continuous operational learning. The value is in the system and flywheel around the model.

#### Q22: What business impact does the Model Factory enable?
The Model Factory enables faster operational issue resolution, workflow automation, scalable operational expertise available 24/7 across all sites, continuous capability improvement where every interaction makes the system better, and reduced operational overhead through less manual investigation and more strategic decision-making.

#### Q23: What are the levels of AI autonomy in supply chain?
The Model Factory enables progression through five levels: Chat (Q&A), Copilots (assisted workflows), Workflow Execution (automated processes), Specialized Agents (where we are today), and ultimately Autonomous Operations. Each level builds on the capabilities established by the previous one.

#### Q24: How does continuous learning work?
The system continuously improves through a flywheel: operational scenarios generate trajectories, which are evaluated, used for fine-tuning, deployed, and then new interactions create more scenarios. Each cycle expands coverage and improves quality. The long-term advantage compounds from this system, not from any single model.
