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
