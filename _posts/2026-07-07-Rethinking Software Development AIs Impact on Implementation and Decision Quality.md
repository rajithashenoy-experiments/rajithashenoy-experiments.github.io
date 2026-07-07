---
title: "Rethinking Software Development: AI's Impact on Implementation and Decision Quality"
date: 2026-07-07
---

## Rethinking Product Development in the Age of AI

### A discussion paper

---

## 1. Why I started thinking about this

Not long ago, we measured engineering productivity largely by our ability to implement software. Every improvement in tooling—better IDEs, frameworks, CI/CD, cloud infrastructure—was ultimately about reducing the cost of implementation.

Generative AI changes that equation.

Today, implementation itself is becoming dramatically cheaper.

Developers can generate code, tests, documentation and even design artefacts in minutes. Product Managers can draft comprehensive PRDs with AI. Designers can explore multiple UX directions almost instantly.

Our own team is already experiencing this shift.

Yet, despite this change, our Software Development Lifecycle remains largely unchanged.

We still move work sequentially through Product, Design, Engineering and QA.

That made me wonder:

**If implementation is no longer the expensive part of software development, why is our SDLC still optimized around it?**

## 2. The SDLC we have today

The traditional SDLC exists for good reasons.

When implementation was expensive, each stage reduced risk before engineering invested significant effort.

Requirements reduced ambiguity. Design reduced UX mistakes. Architecture reduced technical risk.

Testing reduced production failures.

The lifecycle optimised for protecting implementation effort. It worked well because implementation was the bottleneck.

Today, that assumption is changing.

## 3. AI changed the economics of software development

One observation has become increasingly obvious. AI has not eliminated engineering work.

It has dramatically reduced the cost of implementation. Writing code is becoming cheaper.

Generating tests is becoming cheaper. Creating documentation is becoming cheaper.

Even creating first-pass designs is becoming cheaper. The constraint is moving elsewhere.

Instead of asking

> "Can we build this?"

we increasingly ask

> "Should we build this?"

and

> "Are we building it the right way?"

The bottleneck is no longer implementation.

It is decision quality.

## 4. The hidden cost we rarely measure

One thing stood out while thinking through our current process. Almost every team translates the same customer intent into a different artefact.

Customers describe a problem. Product translates it into a PRD. Design translates it into mockups.

Engineering translates it into architecture and implementation. QA translates it into test scenarios.

Documentation translates it into release notes. Each translation is valuable.

But each translation also introduces:

- assumptions
- interpretation
- context loss
- rework
- coordination overhead

AI can accelerate every translation.

But acceleration alone does not remove the underlying cost.

## 5. What actually changes?

Initially, I thought AI would remove handoffs. I no longer believe that's true. Large organisations still need ownership.

Product should continue owning customer outcomes. Design should continue owning user experience.

Engineering should continue owning architecture. QA should continue owning quality.

Those responsibilities don't disappear. Instead, I think something else changes.

Execution becomes dramatically cheaper. Ownership remains. Judgment remains.

Implementation increasingly becomes delegated.

## 6. A different way to think about Agentic Engineering

Most conversations about Agentic Engineering focus on autonomous coding agents.

I think that is only part of the story. The more important shift is organisational.

Today, humans own both **decisions and execution**.

Tomorrow, humans continue owning **decisions**, while autonomous systems increasingly own execution.

That distinction matters.

The value of experienced engineers has never been typing code.

Their value has always been making good technical decisions.

AI simply exposes that reality.

## 7. Decisions become the new unit of work

This was probably the biggest realisation for me. Today we organise software delivery around artefacts.

PRDs.

Designs.

Architecture documents.

Source code.

Test plans.

Each artefact captures a set of decisions.

Perhaps we should optimise for the decisions themselves rather than the artefacts they produce.

For a typical feature, there are only a handful of decisions that truly require human expertise.

Product decides whether the problem is worth solving.

Design decides what experience customers should have.

Engineering decides how the system should evolve.

QA decides whether the feature is trustworthy enough to release.

Everything between those decisions increasingly becomes execution.

Execution can be delegated.

Judgment cannot.

## 8. What this means for engineering

This does not reduce the importance of engineers. If anything, it increases it.

Implementation becomes less valuable. Architecture becomes more valuable.

Verification becomes more valuable. Technical judgment becomes more valuable.

The Staff Engineer of the future may write less code than today.

But they will have dramatically more leverage.

Instead of implementing features directly, they will increasingly define architecture, create engineering guardrails, review AI-generated solutions and improve the systems that produce software.

## 9. Risks we should take seriously

This shift is not without risks.

One concern I have is AI acceptance bias.

As implementation becomes easier, there is a temptation to accept AI-generated solutions without sufficiently questioning them.

Another concern is skill degradation.

If engineers stop reasoning about systems because AI writes the code, our long-term engineering capability could decline.

I also worry about role ambiguity.

As AI performs more execution, organisations must become even clearer about ownership and accountability.

None of these concerns argue against AI.

They argue for stronger engineering discipline.

## 10. Some principles that might guide us

Rather than prescribing a new SDLC, I think there are a few principles worth exploring.

**Implementation is no longer the bottleneck.**

**Judgment cannot be delegated.**

**Execution should be automated wherever possible.**

**Every AI-generated output must be independently verifiable.**

**Architecture should precede implementation.**

**Organisations should optimise for decision quality rather than implementation speed.**

## 11. Questions worth discussing

I don't believe I have all the answers.

But I think these questions are increasingly important.

How should Product, Design and Engineering evolve together?

How should architecture reviews change in an AI-native world?

What new skills should Staff Engineers develop?

How should we measure engineering productivity when implementation is no longer scarce?

What does a high-performing AI-native product organization actually look like?

## Closing thoughts

This paper is not about adopting more AI tools.

Our team is already doing that.

Instead, it is about recognising that AI has fundamentally changed the economics of software development.

Whenever the economics of an industry change, its operating model eventually changes too.

The question is no longer whether AI will become part of software development.

It already has.

The more interesting question is whether our Software Development Lifecycle should evolve to reflect that reality.

I don't yet know what the final answer looks like.

But I believe it starts by asking a different question:

> **If implementation is no longer the most expensive part of software development, what should our SDLC optimise for instead?**

---

*Originally published on [Confluence](https://autodesk.atlassian.net/wiki/spaces/~shenoyr/blog/2026/07/07/942541981/Rethinking+Software+Development+AI+s+Impact+on+Implementation+and+Decision+Quality).*
