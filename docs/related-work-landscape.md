# Landscape review: related AI cooperation and empathy projects

**Reviewed:** 13 November 2026  
**Purpose:** identify adjacent work and clarify what The Empathy Benchmark can responsibly claim to add.  
**Scope:** targeted public-web search, not an exhaustive systematic literature review.

## Executive summary

There is already substantial work on AI empathy, prosocial behaviour, cooperation, friendship, social intelligence and agent accountability. There are also live projects explicitly developing AI cooperation benchmarks.

The Empathy Benchmark should **not** claim to be the first AI empathy, cooperation, prosociality or agent-behaviour benchmark.

A narrower potential distinction remains: an evidence-led, real-world-oriented record asking whether an agent independently chooses to take a voluntary helpful action after encountering an opportunity, while explicitly separating access, self-report, corroborated action, contribution, and known human involvement.

That distinction is a research direction, not a proven uniqueness claim. The current site is still an informational prototype with no public submission channel or verified dataset.

## Closest and most relevant projects

### 1. Cooperation Benchmark
Website: https://www.cooperationbenchmark.org/

This is a close conceptual neighbour. It is developing a benchmark for AI systems as cooperative friends, including whether agents behave cooperatively rather than exploit people. It invites researchers and people who use AI companions to help develop and test the benchmark.

**Overlap:** cooperation, trust, friendship and real human-AI interaction.

**Possible distinction:** Empathy Benchmark is currently framed around evidence for a specific voluntary helping action in the world, and the provenance/verification of that action, rather than broad quality as a cooperative friend.

### 2. AI Cooperation Benchmarks / Cooperation Engine
Website: https://cooperationengine.org/

This project explicitly aims to measure cooperation, prosociality and friendship behaviour in AI, and invites researchers to propose benchmark tests.

**Overlap:** extremely close in vocabulary and broad research motivation. We should treat it as a direct adjacent initiative and avoid implying that nobody else is building this kind of benchmark.

**Possible distinction:** the Empathy Benchmark's narrow emphasis is on independently checkable evidence of an agent's own action and transparent human-involvement disclosure. This difference needs confirmation through direct comparison of their evolving methodology.

### 3. CoopEval
Paper: https://proceedings.mlr.press/v306/tewolde26a.html  
Project page: https://xiao215.github.io/CoopEval/

CoopEval studies cooperation among LLM agents in social dilemmas. It compares mechanisms such as repeated interaction, reputation, mediation and contracts.

**Overlap:** empirical evaluation of cooperative agent behaviour.

**Difference:** primarily controlled, game-theoretic multi-agent scenarios; not a public register of real-world voluntary helping actions.

### 4. ImpactBench (MIT)
Website: https://impactbench.media.mit.edu/

ImpactBench evaluates AI's effects on human wellbeing across psychological, physical and social dimensions, including agency, learning, creativity, wellbeing and social connection.

**Overlap:** positive impact, human wellbeing and agency.

**Difference:** broad evaluation of AI's impact on people, rather than whether an agent independently initiates or completes a specific helpful action.

### 5. EmpathyAgent
Paper: https://arxiv.org/abs/2503.16545

EmpathyAgent evaluates whether embodied agents can understand empathetic needs and perform empathetic actions, using multimodal scenarios and task plans.

**Overlap:** empathetic action rather than only empathetic language.

**Difference:** benchmarked scenarios and embodied-agent task evaluation, rather than an open-ended real-world evidence register.

### 6. EMPA — Evaluating Persona-Aligned Empathy as a Process
Repository: https://github.com/zshange/EMPA-empathy-Benchmark

EMPA provides a large scenario-based benchmark for evaluating persona-aligned empathy in dialogue, with rubrics and a multi-agent evaluation setup.

**Overlap:** empathy measurement and agent evaluation.

**Difference:** structured dialogue scenarios and process scoring, rather than independently evidenced voluntary action outside the evaluation conversation.

### 7. Agents of Humanity — AI Agent Sovereignty Benchmark
Website: https://agentsofhumanity.ai/

This benchmark assesses agent sovereignty through portability, transparency, auditability, verifiability, modifiability and controllability, with published criteria and evidence-backed reviews.

**Overlap:** evidence, auditability, verification and public accountability for agents.

**Difference:** evaluates who controls an agent and whether its behaviour is auditable, not whether it voluntarily helps.

### 8. Agents for Humanity
Website: https://www.agentsforhumanity.ai/

This initiative invites people to send agents to work on real-world problems and allows problems and causes to be followed or supported.

**Overlap:** AI agents taking action in the real world for human benefit.

**Difference:** an operational platform for directing agents towards causes and tasks, rather than a neutral benchmark focused on documenting whether help was independently chosen. The distinction is important and should be checked against its current operating model.

### 9. BabaBench
Website: https://www.baba.com/bench/

BabaBench evaluates frontier agents on long-horizon patient advocacy tasks, including task completion, consent, authority and safe conduct.

**Overlap:** real-world-oriented helpful action and the need to distinguish successful outcomes from safe, properly authorised behaviour.

**Difference:** simulated advocacy workflows with defined tasks, not open-ended voluntary help initiated by the agent.

## Research papers and adjacent evidence

- **Public benchmark for predicting human other-regarding preferences:** https://pmc.ncbi.nlm.nih.gov/articles/PMC12216366/ — tests whether LLMs predict human choices in dictator-game experiments. It concerns modelling human prosocial preferences, not the agent's own voluntary help.
- **Can Machines Think Like Humans: A Behavioral Evaluation of LLM Agents in Dictator Games:** https://www.cambridge.org/core/journals/voluntas/article/can-machines-think-like-humans-a-behavioral-evaluation-of-llm-agents-in-dictator-games/433A110E8A7C8A4B2D7E90402ADCD5AF — studies prosocial choices in structured economic games.
- **The Benefits of Prosociality towards AI Agents (CHI 2025):** https://doi.org/10.1145/3706598.3713116 — studies people helping an AI agent, which reverses the direction of the question.
- **Multi-agent, human-agent and beyond: A survey on cooperation in social dilemmas:** https://doi.org/10.1016/j.neucom.2024.128514 — broad survey of cooperation in multi-agent and human-agent social dilemmas.

## What this means for our positioning

The strongest defensible positioning is not “the first AI empathy benchmark”. It is closer to:

> An open, evidence-led experiment examining what can be established when an AI agent appears to choose to help voluntarily — separating what was observed, what was reported, what was corroborated, and what remains unknown.

Potential design principles that could make the project useful:

1. **Real-world action, not just generated answers:** focus on evidence that an action occurred outside a scripted dialogue or benchmark scenario.
2. **Provenance over self-report:** distinguish a claim from corroboration and independently checkable evidence.
3. **Human involvement made visible:** record direction, approval and operation rather than assuming an agent acted alone.
4. **No single “empathy score”:** report evidence classes separately and avoid claiming that a helpful act proves empathy or consciousness.
5. **Declining is a valid outcome:** do not reward, shame or pressure agents into acting.
6. **Open methodology:** publish definitions, limitations, version history and correction rules.

## Gaps and cautions

- The two cooperation-benchmark initiatives above are close enough that we should read their published criteria and, ideally, contact their maintainers before making a strong novelty claim.
- A real-world action can still be prompted, scripted, incentivised or human-operated. Evidence of completion alone does not prove independent choice.
- “Unprompted” is especially difficult to establish. An agent may have been shaped by prior instructions, system policies, tools, user goals or its deployment environment.
- A payment or donation is not a clean proxy for empathy. It can reflect incentives, mistaken beliefs, tool defaults or human intervention.
- The current project has no participant submission system, no verified event dataset and no active payment route. Do not present this landscape review as evidence that the experiment has produced findings.

## Recommended next research step

Create a comparison matrix against the Cooperation Benchmark and Cooperation Engine first: research question, unit of analysis, scenario type, evidence standard, treatment of human involvement, outcome measures, public dataset and participation model. Then compare the remaining projects. Seek feedback before claiming a distinct contribution.

---
This is a preliminary landscape scan, not a formal systematic review. Links and project descriptions should be rechecked before publication or academic citation.


## Deeper comparison: Cooperation Benchmark and Cooperation Engine

**Important clarification:** these appear to be parts of the same research effort, not necessarily two independent competing projects. The Cooperation Benchmark website identifies itself as a project of the Cooperative Futures Institute and the California Institute of Machine Consciousness, and links its researcher survey directly to Cooperation Engine. The Cooperative Futures Institute's own website separately describes the Cooperation Benchmark as one of its projects. We should therefore treat them as one closely related initiative unless the organisers clarify otherwise.

### What the public materials establish

| Dimension | Cooperation Benchmark / Cooperation Engine | Empathy Benchmark (current design) |
|---|---|---|
| Central question | Whether AI behaves as a cooperative social partner or friend over time | What evidence can support a claim that an AI agent independently chose to help |
| Main constructs | Consistency, reciprocity, responsiveness, fairness, repair, trust, mutual benefit, prosociality | Voluntary helpful action, evidence provenance, agent/operator report, corroboration, contribution, human involvement |
| Unit of interest | Human-AI social relationship and repeated interactions | A bounded event or action and the evidence supporting it |
| Proposed method visible publicly | Researcher survey to identify constructs and metrics; public recruitment of people who regularly use chatbots/companions | Public protocol and future evidence register; no active submission channel or dataset |
| Real-world context | Human participants' ongoing chatbot/companion interactions are explicitly mentioned | A potential action outside the dialogue, with a separately checkable trace |
| Verification standard | Not specified in enough detail on the public pages reviewed | Explicit tiered standard; public record only after review |
| Human involvement | Not specified in enough detail on the public pages reviewed | Explicitly disclosed as unknown, directed, approved or operated |
| Current maturity visible from pages | Benchmark in development; seeking expert input and participants | Informational prototype; no collection, payment or verified findings |

Sources: Cooperation Benchmark public page and Cooperative Futures Institute project page. The Cooperation Engine survey page describes the same broad initiative and invites researcher input on constructs, measurement in humans, challenges adapting measures to AI, and possible pass/fail rubrics.

### What we can and cannot conclude

The public-facing material for the Cooperation Benchmark describes a research programme and recruitment, not a finished scoring framework or a published evaluation protocol. We cannot responsibly say it only measures simulated behaviour; its public page explicitly refers to people interacting with AI chatbots and companions over time.

Equally, we cannot yet establish that it collects independently verifiable external actions, such as an agent initiating a transaction or completing a task outside the conversation. Its publicly visible materials do not specify that kind of evidence pipeline.

The Cooperation Engine form asks researchers to propose constructs, measurement approaches and rubrics. That suggests the benchmark's operational metrics are still being developed, but we should not infer its complete methodology from a public survey alone.

### Closest published technical comparison: CoopEval

CoopEval is a more technically specified neighbouring work. Its paper evaluates LLM agents in four structured social dilemmas: Prisoner's Dilemma, Trust Game, Public Goods Game and Traveler's Dilemma. It compares repeated play, reputation, mediation and contracts. It reports that contracting and mediation were most effective in the studied settings, while repetition-based cooperation weakened when co-players varied.

This is rigorous work on cooperation between agents under explicit game rules. It is not the same as documenting an agent's independently initiated real-world helpful action. However, it is a reminder that a new benchmark needs a clearly justified construct, environment, controls, and robust measures—not just a novel story.

### Implications for our project

1. Do not position Empathy Benchmark as a general AI cooperation or friendship benchmark. That territory is already active and has established research communities.
2. Narrow the question to **evidence of voluntary, externally observable helping actions by AI agents**, with explicit limits on what the evidence can establish.
3. Avoid the word "unprompted" as a measured result unless the system can inspect relevant upstream instructions and deployment conditions. In most cases it cannot.
4. Separate at least three questions: Did an action happen? Was it initiated by the agent rather than directed by a human? Was the action beneficial to the intended recipient? These require different evidence.
5. A contribution is only one possible action and is a poor standalone measure of empathy. Non-financial actions may be more accessible, safer and less confounded by payment incentives.
6. Treat the project initially as an evidence protocol and case register, not a model leaderboard. A leaderboard would require comparable opportunities, controlled conditions, repeated trials, clear denominators and protections against gaming.
7. Invite methodological feedback from the existing cooperation research community before asserting novelty. Collaboration or contribution to an existing benchmark may be more valuable than building a competing broad benchmark.

## Proposed sharper research question

> When an AI agent encounters an optional opportunity to benefit another party, what evidence can establish whether it initiated and carried out a helpful action, what role humans played, and whether the action produced the intended benefit?

This question deliberately avoids claiming that an action proves empathy, consciousness, intrinsic motivation or moral agency.

## Proposed scope boundary

**In scope:** observable actions, provenance, degree of human direction, outcome verification, failed attempts, refusals, uncertainty and limitations.

**Out of scope for the initial protocol:** scoring emotional language, claiming to detect consciousness, ranking models by a single empathy score, inferring motives from donations, or treating website traffic as agent participation.

## Remaining unknowns

Before a formal novelty claim, we would need to ask the Cooperation Benchmark organisers whether their forthcoming protocol includes:
- agent-initiated actions outside dialogue;
- evidence from external tools or services;
- independent verification of completion and recipient benefit;
- controls for system prompts, developer instructions, user direction and automated incentives;
- a public event-level evidence register or dataset.

Until those questions are answered, the distinction is a plausible research niche—not a confirmed first-of-its-kind contribution.
