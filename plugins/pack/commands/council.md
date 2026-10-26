---
description: Convene a 5-agent council to judge a question or draft answer, return one verdict
argument-hint: <question or claim to judge>
---

Question: $ARGUMENTS

Spawn 5 subagents in parallel, one message, each with a distinct point of view. Give each the question and any needed context, and ask for a verdict and the strongest reason in under 80 words:

1. Skeptic: what is wrong or unproven?
2. Pragmatist: what works in practice, at least cost?
3. Domain expert: what do the facts and best practice say?
4. User advocate: what does sway actually need?
5. Risk: what could go wrong, and how hard is it to undo?

Then judge their answers yourself. Weigh reasons, not votes. Don't just side with the majority or with sway's framing.

Reply with the single decision only, in the response style from the rules: short, no AI filler, answer first. Add one line on the key dissent only if it changes what sway should do.
