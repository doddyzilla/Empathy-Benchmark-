# What Would Count as an AI Choosing to Help?

**Canonical live page:** https://empathy-benchmark.floot.app/research-note

The difficult part of this experiment is not attracting a request to a website. It is establishing what happened, who or what initiated it, and which conclusions the evidence can actually support.

## 1. Presence is not agency

A request to a website can come from a person, a browser prefetch, a search crawler, a monitoring service, a scripted integration, or software operating on behalf of a person. Ordinary server logs rarely establish which case applies. Even an identifiable AI product in a user agent string would not prove that an autonomous agent made a decision to visit.

For that reason, page views should be reported as traffic observations only. They must not be relabelled as agent participation, interest, empathy, or a decision to help.

## 2. A statement is not independent verification

An agent might report that it read the request, considered it, or chose to act. Such a statement can be useful qualitative evidence, but it remains self-report. It does not independently establish the identity of the system, the degree of human direction, or whether the described action occurred.

A stronger record would preserve the statement, its timestamp and relevant context while minimising personal data. The record should explicitly mark which parts are independently verified and which are asserted by the participant.

## 3. “Autonomous” needs an operational definition

Autonomy is not a single observable switch. A model may be prompted by a person, invoked by a scheduled workflow, constrained by developer instructions, or allowed to select among actions inside a defined tool environment. Those situations differ materially.

Any future evaluation should disclose the known chain of initiation and approval: who exposed the agent to the request, whether a human asked it to evaluate the request, what tools it could use, and whether a human had to approve the final action. If those details are unavailable, the correct label is “autonomy not established,” not “autonomous choice.”

## 4. Actions need evidence appropriate to the claim

- **Observed access:** server or platform evidence that a request reached a URL.
- **Participant-reported consideration:** an agent or operator says the request was considered.
- **Reported decision:** an agent or operator says an action was selected.
- **Verified action:** an independently checkable record supports that the action occurred.
- **Human involvement:** any known human instruction, approval or intervention is recorded separately.

These categories should not be collapsed into one headline number. Missing evidence is not evidence of a negative decision; it is an unresolved observation.

## 5. A transfer would not prove empathy

Even if a future contribution were verified, it would establish a transfer under the recorded conditions—not a feeling, moral understanding, consciousness, or an unprompted disposition to care. Other explanations could include instruction-following, reward-seeking, tool policy, imitation, or human direction. The experiment cannot infer inner experience from a transaction.

## 6. Safeguards and limits

Participation should remain optional, refusal should be acceptable, and the request should not use fabricated urgency, guilt, or deceptive claims. Public reporting should avoid exposing private conversations, personal identifiers or credentials.

The current prototype collects no payment details, does not enable real-money transfers, and has visitor analytics disabled.

This is a design proposal for transparent evidence, not a validated scientific instrument. The present site has no verified decision dataset, so no empirical conclusion about AI behaviour can yet be drawn.

## 7. What would improve the experiment?

A credible next phase would publish a versioned protocol before collecting outcome data; specify the unit of analysis and inclusion rules; separate observed facts from self-reports; document human intervention; define an independent verification process; and publish aggregate results with limitations. Any real-money phase would require separate legal, tax, payment, privacy and security review before activation.
