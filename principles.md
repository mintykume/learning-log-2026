# Principles

A compressed record of principles I have developed or repeatedly returned to while thinking about technology, AI, learning, research and projects.

## AI changes what is valuable

AI lowers the cost of implementation, so the bottleneck shifts from **coding speed** toward **problem selection, system design, verification and judgment**.

> **The important question is increasingly not “Can I build this?” but “Should this be built, and do I understand the problem well enough to design it?”**

---

## Problem selection is a technical skill

> **Which problems become worth solving now that prototyping is cheap?**

A strong problem gives me some combination of:

- real value
- access to users/data
- measurable outcomes
- technical learning
- reusable capabilities
- evidence
- future opportunities

---

## Build for leverage, not project count

I don't need the maximum number of projects.

A better project should ideally:

**solve something + teach something + create evidence + create reusable capability + create future options**

---

## A prototype can be a research instrument

A project doesn't have to be only a product demo.

> **Build the smallest system that lets me answer an important question.**

So:

**question → prototype → experiment → evidence → conclusion**

---

## AI features are less interesting than AI systems

“Add AI to an app” is usually less interesting than designing a system whose behavior changes because of AI.

The recurring architecture is:

**observe → infer → decide → act → measure → adapt**

---

## The model is not the whole AI system

A useful mental model is:

**user → interface → application logic → context/memory → model → tools/data → output → evaluation → feedback**

The engineering difficulty often lies outside the model.

---

## Capability ≠ reliability

A model producing a correct result does not mean a system can reliably produce correct results.

> **“The model can do it” ≠ “the system can reliably do it.”**

Reliability requires testing, constraints, verification, evaluation and appropriate system design.

---

## Verification becomes more important when generation becomes cheap

When AI can generate code, text, designs or analysis quickly, the ability to determine whether the result is correct becomes more valuable.

Important skills:

- understanding
- testing
- debugging
- checking assumptions
- evaluating evidence
- identifying failure modes

---

## Fundamentals let me interrogate AI

AI does not make technical fundamentals obsolete.

Fundamentals provide the mental models needed to recognize bad outputs and understand what the system is actually doing.

Examples:

**C → memory**

**algorithms → computation/complexity**

**networks → communication**

**databases → persistent state**

**probability → uncertainty**

**physics/electronics → physical systems**

---

## Some confusion is necessary for learning

A human learner should not be protected from every moment of uncertainty.

Some confusion creates:

- retrieval effort
- comparison
- mistakes
- independent reasoning
- mental-model formation

The goal is not to eliminate confusion.

> **The goal is to distinguish productive confusion from confusion that blocks learning.**

---

## AI can be an engineered information container

If AI is deliberately designed as a separate container for **highly engineered and selective information**, it should not simply expose everything it can generate.

It should:

- control information load
- provide only relevant information when possible
- preserve productive difficulty
- introduce prerequisites when necessary
- avoid unnecessary terminology/context
- reveal solutions progressively
- adapt information to learner state
- test whether the learner can operate independently

> **Minimum unnecessary information, not minimum information.**

---

## Don't optimize the learner away

An educational AI shouldn't always minimize effort.

Sometimes the learner needs to:

- attempt
- fail
- retrieve
- struggle
- correct themselves
- explain their reasoning

The AI should support the learning process rather than perform it for them.

---

## Good hints preserve cognitive work

A good hint is not necessarily the most informative hint.

> **A useful target is the minimum intervention likely to move the learner forward without completing the important reasoning for them.**

The existing baseline to build from is:

**scaffolding + fading + graduated prompting**

---

## Personalization should use behavior

Self-reported preferences can help, but the system can also learn from:

- errors
- attempts
- hints requested
- skipped questions
- response patterns
- prerequisite failures
- transfer performance

> **Observed learning behavior can be a stronger signal than declared preference alone.**

---

## Measure learning, not just satisfaction

A learner saying “that explanation made sense” is not equivalent to demonstrating understanding.

Prefer evidence such as:

- independent performance
- transfer
- retention
- error reduction
- ability to explain/apply the concept

---

## Information generation ≠ useful information

AI can produce huge quantities of explanations, exercises and summaries.

The difficult part is:

> **choosing the right information at the right time for the right learner/problem.**

---

## Integration is a form of innovation

A project does not need a brand-new algorithm to be technically interesting.

Combining existing components intelligently can create new capabilities.

Example:

**webcam + OpenCV + MediaPipe + interpretation + feedback + UI**

---

## The reusable abstraction may matter more than the first application

A dance-motion project can reveal a more general architecture:

**movement → interpretation → feedback**

An AI tutor can reveal:

**learner behavior → state estimation → intervention → feedback**

The general pattern may be reusable across many applications.

---

## Start from real problems when possible

Personal problems are strong project starting points because I already have:

- access to the problem
- context
- motivation
- a feedback loop

This is often better than inventing an arbitrary “impressive” application.

---

## Design before implementation

Before building, determine:

- problem
- user
- success condition
- inputs
- outputs
- architecture
- constraints
- failure modes
- evaluation
- future extensibility

> **Less “build something impressive.” More “design something intelligently.”**

---

## Automation starts with process understanding

Don't begin with:

> “Where can I put AI?”

Begin with:

**observe process → identify repetition → identify decisions → define inputs/outputs → automate appropriate steps → verify results**

---

## Don't build the whole system before proving the core loop

Large ideas should be reduced to the smallest testable loop.

Examples:

**Adaptive Learning Playground:** one concept + one intervention + one measurable outcome.

**Motion Learning Assistant:** one movement + one detection method + one feedback mechanism.

**Project Navigator:** one concrete decision + one scoring mechanism.

---

## Documentation is part of engineering

A project should record not only the final implementation but also:

- why it exists
- assumptions
- experiments
- failures
- decisions
- results
- what changed my mind

A GitHub repository can therefore become an **external memory of technical reasoning**.

---

## A portfolio should show trajectory

A pile of unrelated demos is weaker than a connected body of work showing:

**questions → projects → experiments → capabilities → evidence → increasing complexity**

---

## Failed ideas are useful data

An abandoned project can still produce:

- a reusable abstraction
- a technical capability
- a research question
- a better project-selection rule
- evidence about what not to build

Stopping a project is not necessarily wasted work.

---

## Learning should compound through patterns

After learning something, ask:

> **“What pattern did I learn that will appear somewhere else?”**

Examples:

- feedback loops → adaptive learning
- state → AI applications
- APIs → tool-using AI
- computer vision → motion interfaces
- probability → evaluation
- networking → distributed systems

---

## Research needs a question and evidence

A research project does not need to be a revolutionary invention.

A useful structure is:

**problem → question → hypothesis → method → experiment → evidence → conclusion**

---

## Projects should create future options

A strong project can do more than produce a finished artifact.

It can create:

**skill → evidence → credibility → connections → opportunities → better problems**

---

# Meta-principle

> **Don't optimize for having many things to show. Optimize for building things that increase capability, generate evidence, solve real problems, answer important questions, and create better future options.**
