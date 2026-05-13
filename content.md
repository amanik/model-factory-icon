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
- footer: ICON 2026

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

### Domain Fine-tuning to Address Failure Modes

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

### Competitive Positioning (internal)
When customers ask "why not Palantir / C3.ai / Accenture + GPT-4?": Blue Yonder is the only vendor that combines 30+ years of supply chain domain software, live integrations into the execution systems where work actually happens, a dedicated training pipeline that produces specialized models (not prompt-engineering on top of generic models), and a continuous learning flywheel where every operational interaction makes the system better. Consulting firms can prototype. Cloud providers can host. Only Blue Yonder has the operational data gravity, system integrations, and domain depth to build models that actually work in production warehouse environments.

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
Agent resolves allocation shorts: identifies recoverable inventory, executes yard move, tracks fulfillment via Live Activity

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

#### Q2: How is this different from simple RAG or chatbot systems?
RAG retrieves information from documents. Our approach goes significantly further — operational reasoning, multi-step planning, tool execution, workflow automation, and continuous improvement through evaluation loops. We are building specialized agents, not document chatbots.

### Tab: Technical Approach

#### Q3: How exactly do you train your models?
We use a layered training approach: frontier foundation models as base intelligence, domain adaptation using warehouse workflows, domain fine-tuning on operational procedures and reasoning patterns, preference alignment to ensure the model completes tasks the way Blue Yonder wants, and reinforcement learning using simulated training environments. The models continuously improve through evaluation feedback and operational learning loops.

#### Q4: Are you training foundation models from scratch?
No. We build on top of strong open-source foundation models and specialize them for supply chain and warehouse operations through domain fine-tuning, preference alignment, and reinforcement learning. This lets us leverage the massive investment already made in general-purpose intelligence while focusing on operational reasoning, workflow execution, and enterprise-specific capabilities.

#### Q5: What role does reinforcement learning play?
Reinforcement learning helps the model improve decision-making through simulation. Simulated training environments allow us to run scenarios safely, test many operational variations quickly, reward successful task execution, and improve agent behavior iteratively — all without impacting production systems.

#### Q6: What is preference alignment?
After domain fine-tuning gives the model basic operational competence, preference alignment teaches it to distinguish between good and bad approaches. Using pairs of example responses, the model learns which investigation strategies are more thorough, which recommendations are more actionable, and which communication styles are more appropriate for operational contexts. This ensures the model completes tasks the way Blue Yonder wants them completed.

#### Q7: Can you explain the architecture in a few sentences?
Three architecture patterns show how specialized and frontier models work together. In the Routing Model, a frontier model classifies intent and dispatches to the right specialized model for domain execution. In the Sub-Agent Model, a frontier model orchestrates high-level reasoning while a specialized sub-agent handles operational tasks. The long-term vision is a Foundational Supply Chain Model — one model trained end-to-end on routing, reasoning, and execution without needing a frontier model in the loop.

### Tab: Data & Privacy

#### Q8: Where does the training data come from?
Our agentic Operator models train with 100% synthetic data generated from simulated training environments that mirror warehouse operational workflows, transactional patterns, and diverse operational scenarios. This allows us to generate diverse scenarios, cover rare edge cases, and scale training safely — all without dependency on customer production data.

#### Q9: How do you handle privacy and customer data governance?
Privacy and customer data governance are treated as core design requirements for supported AI capabilities. Key controls include contractually permitted usage, data minimization, role-based and least-privilege access controls, region-aware storage and processing, retention controls, and restricted access to secure development, testing, and support environments. Blue Yonder avoids including PII in AI models unless it is necessary for the use case, permitted, and subject to appropriate privacy and security controls. Where appropriate, Blue Yonder also uses anonymization or de-identification for data used in development, testing, analytics, or support activities. AI capabilities are governed through Blue Yonder security, privacy, and Responsible AI processes.

### Tab: Human Expertise

#### Q10: How do you capture and use SME expertise?
We capture expertise through workflow walkthroughs, operational demonstrations, human feedback loops, evaluation reviews, and trajectory correction. Much of warehouse expertise is tacit — not explicitly documented — so we also learn by observing operational decisions, comparing successful vs. unsuccessful workflows, and feeding corrections back into training. Over time, the system accumulates operational knowledge and decision patterns as reusable training signals.

#### Q11: What role do human operators still play?
Human expertise remains essential. SMEs provide workflow understanding, evaluation feedback, exception handling, operational policy guidance, and validation of model behavior. The goal is augmentation and scalability of expertise, not removal of human oversight.

### Tab: Evaluation & Safety

#### Q12: How do you evaluate success?
We evaluate across multiple dimensions: operational correctness, scenario completion, tool-use accuracy, consistency, latency, human evaluation, and benchmark and regression suites. The focus is operational reliability, not just conversational quality.

#### Q13: How do you avoid overfitting to one warehouse or customer?
Generalization is a key design principle. We address this through diverse operational patterns, simulation variability, cross-environment evaluation, and synthetic scenario expansion. The goal is reusable operational intelligence, not customer-specific memorization.

#### Q14: What happens when the model is wrong?
Enterprise AI systems require guardrails and controlled autonomy. Key mechanisms include scoped permissions, human escalation paths, confidence thresholds, auditability, evaluation gates, and safe fallback behavior. The system operates safely within defined boundaries.

### Tab: Strategic Positioning

#### Q15: What makes Blue Yonder uniquely positioned for this?
Blue Yonder combines deep supply chain expertise, a large operational customer footprint, real execution system integration, historical operational data, and existing workflow understanding. This creates a strong foundation for specialized AI systems.

#### Q16: What is the long-term moat?
The moat is not prompts or a single model. It comes from the operational data flywheel, accumulated domain expertise, evaluation infrastructure, workflow integrations, simulated training environments, and continuous learning systems. Together, these create compounding advantages over time — the advantage is in the system and flywheel around the model.

#### Q17: Why not just use OpenAI directly?
Frontier models provide strong general intelligence, but our differentiation comes from operational context, workflow orchestration, domain specialization through fine-tuning and preference alignment, tool integrations, evaluation infrastructure, and continuous operational learning. The value is in the system and flywheel around the model.

#### Q18: What business impact does the Model Factory enable?
The Model Factory enables faster operational issue resolution, workflow automation, scalable operational expertise available 24/7 across all sites, continuous capability improvement where every interaction makes the system better, and reduced operational overhead through less manual investigation and more strategic decision-making.

#### Q19: What are the levels of AI autonomy in supply chain?
The Model Factory enables progression through five levels: Chat (Q&A), Copilots (assisted workflows), Workflow Execution (automated processes), Specialized Agents (where we are today), and ultimately Autonomous Operations. Each level builds on the capabilities established by the previous one.

#### Q20: How does continuous learning work?
The system continuously improves through a flywheel: operational scenarios generate trajectories, which are evaluated, used for fine-tuning, deployed, and then new interactions create more scenarios. Each cycle expands coverage and improves quality. The long-term advantage compounds from this system, not from any single model.

### Tab: Objection Handling (internal)

#### Q21: "We already have Copilot / ChatGPT Enterprise."
Those are general-purpose conversation tools. Ask: "Can Copilot investigate an allocation shortage across your WMS, TMS, and yard management systems, identify recoverable inventory, and recommend an action?" The answer is no. General AI answers questions. Our agents investigate and resolve operational problems.

#### Q22: "This sounds like vaporware. What's actually running?"
The Allocation Shorts Agent is real. It runs against live enterprise systems, executes structured investigations, and produces actionable recommendations. We can demo it. The factory process that built it is repeatable and already being applied to the next set of use cases.

#### Q23: "Why should I trust AI with operational decisions?"
You shouldn't, blindly. That's why we built evaluation infrastructure, human review gates, confidence thresholds, scoped permissions, and audit trails. The system is designed for controlled autonomy — it operates within defined boundaries and escalates when uncertain. Trust is earned through measurable performance, not claimed.

#### Q24: "Our data is sensitive. We can't share it for AI training."
You don't have to. We train with 100% synthetic data generated from simulated environments. No customer production data is used in model training. Your data governance stays exactly as it is.

---

## Simple Section 01: What We Are Building

### Intro
Your best warehouse operators carry years of knowledge in their heads — how to investigate shortages, which exceptions matter, what to check first. That expertise is hard to hire, impossible to scale, and walks out the door every time someone leaves. Blue Yonder is building AI that captures and scales that operational intelligence — purpose-built assistants that know how your warehouse works, can investigate problems, and take action, available 24/7 across every site.

### Agent Capabilities
These AI assistants are designed to:
- Know how your warehouse actually operates
- Investigate issues and find root causes
- Take action across your systems
- Work alongside your team, not replace them
- Get smarter over time from real-world feedback

### Callout
> This is owned intelligence, not rented. Blue Yonder's AI is trained specifically for supply chain work — it understands your operations, speaks your language, and gets better with every shift. Think of it as a training academy for AI specialists, where each graduate is purpose-built for your world.

### Model Architecture
We use different approaches depending on the complexity of the task. For simple requests, AI routes to the right specialist. For complex problems, a general AI coordinates while specialists handle the domain-specific work. Our long-term vision is a single AI that deeply understands all supply chain operations end-to-end.

**Routing Model**
Simple requests go directly to the right specialist AI — fast and efficient.

**Sub-Agent Model**
A general AI coordinates the big picture while specialist AI handles the warehouse-specific tasks.

**Foundational Supply Chain Model**
Our long-term vision: one AI that understands the entire supply chain from end to end.

---

## Simple Section 02: Why Generic AI Is Not Enough

### Intro
Frontier models from OpenAI, Anthropic, and others are impressive for general questions, but they weren't built for running a warehouse. Supply chain operations need AI that understands your systems, your terminology, and your priorities — not AI that gives plausible-sounding answers without real operational knowledge.

### Comparison: Generic AI vs Specialized AI

| Generic AI | Specialized AI (Model Factory) |
|---|---|
| Answers general questions well | Understands your specific operations |
| No memory of your workflows | Knows how your warehouse runs |
| Cannot access your systems | Works with your enterprise tools |
| Gives best-guess answers | Delivers accurate, actionable results |
| One-size-fits-all | Purpose-built for supply chain |
| No way to measure reliability | Tested against real operational outcomes |

### Callout
> General AI is like hiring a brilliant generalist who's never worked in a warehouse. Our specialized AI is like hiring an expert who's been trained on thousands of warehouse scenarios and knows exactly how to investigate and resolve issues.

### Where Frontier Models Fail

Even the best general AI tools struggle with real warehouse operations.

**They look right but aren't**
General AI can produce answers that sound correct but don't actually solve the operational problem — style over substance. In a warehouse, a plausible-sounding wrong answer wastes more time than no answer at all.

**They don't speak your language**
General AI misunderstands warehouse terms, confuses item codes, and suggests solutions that don't match real workflows.

**They lack operational instinct**
Without deep warehouse experience, general AI can't tell what's urgent, what's routine, or what matters most for your business.

**They forget between conversations**
Every conversation starts from scratch. There's no awareness of ongoing issues, shift priorities, or what was already tried.

### How We Train AI to Think Like Your Best Operators

We train our AI specifically on how warehouse operations work — not just the terminology, but the actual decision-making process, the workflows, and the business judgment that experienced operators use every day.

### What Specialized Training Produces

**Understands How Work Gets Done**
The AI learns the natural flow of warehouse operations — how investigations unfold, what depends on what, and what to check next.

**Makes Sense of Raw Data**
Rather than just showing system outputs, the AI interprets data in business terms — what's urgent, what's impacted, and what it means for operations.

**Knows When to Act and When to Ask**
The AI knows when it has enough information to recommend action, when to ask a clarifying question, and when to escalate to a human.

**Focuses on What Matters Most**
Not everything is equally important. The AI prioritizes based on business impact — critical shortages before routine inquiries.

**Solves Problems, Not Just Answers Questions**
The AI is focused on resolving the actual operational issue, not just giving a technically correct answer.

### Specialized Training Callout
> Our AI doesn't just know supply chain vocabulary — it understands how work is actually performed: which steps come first, what matters most, and how to turn raw data into clear business recommendations. This is owned intelligence that compounds over time.

---

## Simple Section 03: How the Model Factory Builds a Specialized SC Model

### Intro
Building specialized AI is a repeatable five-step process. Each step feeds the next, creating a continuous cycle of improvement — the AI gets smarter and more capable with every iteration. This is how Blue Yonder builds owned intelligence: a system that compounds in value the longer you use it.

### 1. Define the Job
First, we define exactly what the AI needs to do — which operational tasks, what success looks like, and how we'll measure quality. Clear goals before any training begins.

### 2. Generate Training Scenarios
We create realistic training scenarios that mirror real warehouse operations — thousands of them, covering normal operations, unusual situations, and rare edge cases. Importantly, we generate these scenarios entirely from simulation. No customer data is ever used in training — your data stays completely separate.

### 3. Train the AI
We teach the AI two things: how your operations work (the knowledge) and how Blue Yonder wants tasks completed (the quality standards). This ensures both accuracy and consistency.

### 4. Test and Deploy
Before deployment, the AI goes through rigorous testing — scenario replays, benchmark checks, and human expert review. It only goes live when it meets our quality bar.

### 5. Improve Continuously
Once deployed, every interaction creates data that makes the next version better. The AI continuously learns from real-world feedback and new scenarios — the system gets smarter the longer it runs.

### Callout
> This is the flywheel: operational scenarios create training data, which creates better AI, which handles more scenarios. The competitive advantage isn't a single model — it's a system that compounds in value over time. The longer it runs, the better it gets.

---

## Simple Section 04: First Agent — Allocation Shorts

### Intro
Our first AI assistant tackles one of the most common warehouse headaches: figuring out why orders can't be fully filled from available inventory. This is where the Model Factory moves from concept to proof.

### Tag
Warehouse Operations

### What the Agent Does
#### Allocation Shorts Investigation
When a warehouse can't fill an order completely, someone has to figure out why. Today, that means an experienced operator manually checking multiple systems, reviewing inventory, looking at order priorities, and tracking down the root cause. A typical investigation takes 30-60 minutes of skilled operator time and requires deep knowledge that's hard to find and harder to scale.

Our AI assistant automates this entire investigation — from identifying the problem to recommending a resolution — completing in minutes what previously required the better part of an hour. It works across shifts, never forgets a pattern, and gets smarter with every investigation.

### Image Caption
Agent resolves allocation shorts: identifies recoverable inventory, executes yard move, tracks fulfillment via Live Activity

### Agent Workflow Steps
1. User Request
2. Agent Reasoning
3. Tool / API Calls
4. Operational Analysis
5. Recommendation

### Additional Use Cases
- Short order investigation
- Yard management
- Inventory analysis
- Workflow optimization
- Operational exception handling

### Next Steps

**Ship the Allocation Shorts Agent**
Launch the first AI assistant for warehouse shortage investigation — automating a process that currently takes significant manual effort.

**Build the Next Wave of Agents**
The same factory process is already being applied to more supply chain workflows — yard management, demand analysis, and exception handling across the Blue Yonder product suite.

**Get Early Access**
Talk to your Blue Yonder account team to learn more about timelines and how AI-powered supply chain assistants fit your operations.

---

## Simple Section 05: Questions & Answers

### Tab: Top Questions

#### Q1: What exactly is a "Model Factory"?
A proven, repeatable process for building AI assistants that specialize in supply chain work. Rather than one-off projects, it's a production system that can create, test, and continuously improve AI capabilities at scale.

#### Q2: How is this different from simple RAG or chatbot systems?
Chatbots look up information and repeat it back. Our AI assistants can actually investigate problems, take actions across systems, follow multi-step workflows, and improve over time. They're operational assistants, not search engines.

#### Q8: Where does the training data come from?
We train entirely with generated scenarios — realistic simulations that mirror real warehouse operations, but created by us, not pulled from your systems. No customer production data is ever used in training. Your data stays completely separate.

#### Q9: How do you handle privacy and customer data governance?
Privacy is built into the design from day one. We use strict access controls, data minimization, region-aware processing, and avoid using personal information unless absolutely necessary and permitted. Everything is governed by Blue Yonder's security, privacy, and Responsible AI processes.

#### Q11: What role do human operators still play?
Humans are essential. Experts provide the knowledge, validate the AI's behavior, handle exceptions, and set operational policies. Our goal is to scale expertise — making your best operators' knowledge available across all shifts and sites — not to remove human oversight.

#### Q14: What happens when the model is wrong?
Safety is built in. The AI has clear boundaries for what it can and can't do, knows when to escalate to a human, tracks its confidence level, and maintains a full audit trail. If it's unsure, it asks rather than guesses.

#### Q17: Why not just use OpenAI or another general AI provider directly?
General AI models are the engine, but we're the team that knows warehouses. The model itself is maybe 10% of the value. The other 90% is operational context, workflow integration, quality evaluation, and continuous learning from real use. You can't prompt your way to that — it takes deep supply chain specialization and years of system integration.

#### Q18: What business impact does the Model Factory enable?
Faster problem resolution, automated investigations, expert-level support available 24/7 at every site, systems that get smarter over time, and less time spent on manual investigation — freeing your team for higher-value strategic work.

### Tab: Fundamentals

#### Q1: What exactly is a "Model Factory"?
A proven, repeatable process for building AI assistants that specialize in supply chain work. Rather than one-off projects, it's a production system that can create, test, and continuously improve AI capabilities at scale.

#### Q2: How is this different from simple RAG or chatbot systems?
Chatbots look up information and repeat it back. Our AI assistants can actually investigate problems, take actions across systems, follow multi-step workflows, and improve over time. They're operational assistants, not search engines.

### Tab: Technical Approach

#### Q3: How exactly do you train your models?
We start with powerful general-purpose AI and specialize it for supply chain work through multiple training stages — teaching it operational knowledge, quality standards, and decision-making through simulated warehouse scenarios. The models improve continuously from real-world feedback.

#### Q4: Are you training AI models from scratch?
No. We take existing, proven AI models and specialize them for supply chain work. This gives us the best of both worlds — the power of the best available AI plus deep supply chain expertise built over decades.

#### Q5: How does the AI learn to handle new situations?
We use simulation to let the AI practice thousands of warehouse scenarios safely — learning what works, what doesn't, and how to handle unusual situations — all without any risk to your real operations.

#### Q6: How do you ensure the AI meets Blue Yonder's quality standards?
After teaching the AI how operations work, we train it on quality standards — which approaches are more thorough, which recommendations are more useful, and how Blue Yonder expects tasks to be completed. This ensures the AI completes tasks the way you'd want your best operator to complete them.

#### Q7: Can you explain the architecture in a few sentences?
We use different setups depending on the task complexity. For simple tasks, AI routes requests to the right specialist. For complex problems, a general AI coordinates while a supply chain specialist does the detailed work. Our long-term vision is a single AI model that handles everything end-to-end.

### Tab: Data & Privacy

#### Q8: Where does the training data come from?
We train entirely with generated scenarios — realistic simulations that mirror real warehouse operations, but created by us, not pulled from your systems. No customer production data is ever used in training. Your data stays completely separate.

#### Q9: How do you handle privacy and customer data governance?
Privacy is built into the design from day one. We use strict access controls, data minimization, region-aware processing, and avoid using personal information unless absolutely necessary and permitted. Where appropriate, we also use anonymization techniques. Everything is governed by Blue Yonder's security, privacy, and Responsible AI processes.

### Tab: Human Expertise

#### Q10: How do you capture and use SME expertise?
We work closely with warehouse experts through walkthroughs, demonstrations, and feedback sessions. A lot of warehouse knowledge is instinctive — it's never been written down — so we learn by observing expert decisions and feeding that wisdom into the AI's training.

#### Q11: What role do human operators still play?
Humans are essential. Experts provide the knowledge, validate the AI's behavior, handle exceptions, and set operational policies. Our goal is to scale expertise — making your best operators' knowledge available across all shifts and sites — not to remove human oversight.

### Tab: Evaluation & Safety

#### Q12: How do you evaluate success?
We test across multiple dimensions: Does it get the right answer? Does it complete the full workflow? Does it use tools correctly? Is it consistent? Is it fast enough? And critically — does it meet the standards human experts set? The focus is operational reliability.

#### Q13: How do you avoid overfitting to one warehouse or customer?
We specifically design for variety — training on diverse warehouse configurations, different operational patterns, and many scenario types. The goal is AI that works across different environments, not AI that only works in one specific warehouse.

#### Q14: What happens when the model is wrong?
Safety is built in. The AI has clear boundaries for what it can and can't do, knows when to escalate to a human, tracks its confidence level, and maintains a full audit trail. If it's unsure, it asks rather than guesses.

### Tab: Strategic Positioning

#### Q15: What makes Blue Yonder uniquely positioned for this?
Blue Yonder has decades of supply chain expertise, a large customer base running real operations, deep system integrations, and extensive operational data. Nobody else combines this domain knowledge with AI capabilities at this scale.

#### Q16: What is the long-term moat?
The competitive advantage isn't a single AI model — it's the entire system. Operational data feeds better training, which creates better AI, which generates more operational insights. This flywheel gets stronger over time, and competitors can't replicate the accumulated domain knowledge.

#### Q17: Why not just use OpenAI or another general AI provider directly?
General AI models are the engine, but we're the team that knows warehouses. The model itself is maybe 10% of the value. The other 90% is operational context, workflow integration, quality evaluation, and continuous learning from real use. You can't prompt your way to that — it takes deep supply chain specialization and years of system integration. The AI model is one piece. The system around it is what delivers results.

#### Q18: What business impact does the Model Factory enable?
Faster problem resolution, automated investigations, expert-level support available 24/7 at every site, systems that get smarter over time, and less time spent on manual investigation — freeing your team for higher-value strategic work.

#### Q19: What are the levels of AI autonomy in supply chain?
We're progressing through five levels: basic Q&A, assisted workflows (copilots), automated processes, specialized agents (where we are today), and ultimately autonomous operations. Each level builds on the last.

#### Q20: How does continuous learning work?
Every interaction makes the system better. Real operational scenarios feed back into training, which creates better AI, which handles more scenarios. This virtuous cycle means the system improves continuously — the longer it runs, the better it gets.
