# Learning Log — Tech, AI & Systems

## AI changes what is worth learning

AI makes implementation cheaper, so the bottleneck shifts from:

> **“Can I code this?”**

toward:

> **“Is this worth building, and do I understand the problem well enough to design it correctly?”**

More valuable skills become:

* problem selection
* systems thinking
* decomposition
* architecture
* debugging
* verification
* evaluation
* understanding fundamentals
* knowing when an AI-generated solution is wrong

**Key question:**

> **Which problems become worth solving now that prototyping is cheap?**

---

## AI systems > AI features

“Add AI to an app” is less interesting than designing a system whose behavior changes because of AI.

A useful general pattern:

**observe → infer → decide → intervene → measure → adapt**

This appears in:

* adaptive learning
* AI assistants
* automation
* computer vision
* human-computer interaction

---

## Adaptive learning

An AI tutor shouldn't just answer questions.

Instead:

**learner → attempt → detect confusion → intervention → new attempt → adapt**

Possible interventions:

* question
* hint
* analogy
* visual explanation
* example
* simulation
* prerequisite
* harder/easier problem

The key question becomes:

> **“Given what this learner just did, what should the system do next?”**

---

## Confusion is not always bad

Some confusion is necessary for human learning.

If everything is immediately explained, the learner may lose opportunities to:

* struggle productively
* retrieve information
* make mistakes
* form their own mental model
* discover relationships

So the goal shouldn't be:

> **eliminate confusion**

but:

> **distinguish productive confusion from unproductive confusion.**

---

## AI as an engineered information container

If AI is deliberately designed as a separate container for **highly engineered and selective information**, it should not simply dump everything it knows.

Useful rules:

* only provide information relevant to the current objective
* don't overload the learner
* introduce prerequisites when necessary
* separate essential from optional information
* avoid unnecessary terminology
* preserve productive difficulty
* don't reveal the solution prematurely
* adapt information quantity to learner state
* periodically test whether the learner can work without the AI

**Goal:**

> **minimum unnecessary information + enough information/difficulty for learning**

---

## What makes a good hint?

Still an open problem for me.

A good hint isn't necessarily the most informative one.

It should ideally be:

> **the smallest intervention likely to get the learner unstuck without doing the cognitive work for them.**

The established baseline I can build from is **scaffolding / fading** and **graduated prompting**:

1. Let the learner attempt independently.
2. Give a small cue.
3. Increase specificity if necessary.
4. Give an example/partial solution if necessary.
5. Eventually provide the solution.
6. Remove the support and test independent performance.

The interesting AI problem is:

> **Can the AI choose the appropriate level of scaffolding from evidence about the learner?**

---

## AI-generated content ≠ useful content

AI can generate explanations, quizzes, exercises and summaries extremely cheaply.

But:

> **Generating information is easy. Generating the right information at the right time is harder.**

The system around the model matters.

---

## Verification becomes part of programming

If AI can write code quickly, knowing syntax becomes less differentiated.

I need to be able to determine:

* what the code does
* whether the architecture makes sense
* what assumptions it makes
* where it can fail
* how to test it
* whether it actually satisfies the requirement

**AI increases the value of verification, debugging, testing and system understanding.**

---

## AI limitations

A capable model does not automatically produce a reliable system.

Models don't guarantee:

* factual correctness
* causal understanding
* consistent reasoning
* appropriate context
* reliable evaluation

> **“The model can do it” ≠ “the system can reliably do it.”**

Engineering is partly about turning probabilistic capabilities into reliable behavior.

---

## Small projects can become research instruments

Instead of:

> “I built an AI tutor.”

I can ask:

> “Does graduated hinting improve independent problem solving?”

Then:

**question → prototype → experiment → measurement → conclusion**

The software becomes an **experimental instrument**, not just a portfolio demo.

---

## Projects don't need novel models

A project can become interesting through system design and integration.

For example:

**webcam + OpenCV + MediaPipe + inference + feedback + UI**

can create a new interaction system even though the individual technologies already exist.

Innovation can happen at the **system/integration layer**.

---

## Motion tracking as a general interaction system

My motion-tracking work can be abstracted as:

**movement → computer vision → interpretation → feedback**

Potential applications:

* educational games
* movement learning
* posture feedback
* rehabilitation-oriented systems
* gesture interfaces
* interactive learning

The reusable technology is the **motion-to-feedback pipeline**, not one application.

---

## AI is bigger than the model

A real AI application looks more like:

**user → interface → application logic → model → context/data → tools → state/memory → evaluation → feedback**

The model is only one component.

This makes software engineering, APIs, networking, databases, testing and system design increasingly important for AI.

---

## Fundamentals matter more, not less

AI makes it easier to skip fundamentals, but fundamentals let me **interrogate and verify the AI**.

Examples:

* C → memory
* algorithms → complexity
* OS → processes/resources
* networks → communication
* databases → state/data
* ML → models/evaluation

Fundamentals provide the mental models needed to use AI intelligently.

---

## Learning should compound through patterns

Instead of memorizing individual technologies, ask:

> **“What pattern did I just learn that will appear somewhere else?”**

Examples:

* feedback loops → adaptive learning
* state → AI applications
* APIs → tool-using AI
* computer vision → motion interfaces
* testing → AI verification
* data → personalization
* networking → distributed applications

Goal:

> **build a knowledge graph, not a collection of tutorials.**

---

## Research

A meaningful project doesn't necessarily need to invent something completely new.

A useful sequence:

**problem → question → hypothesis → method → experiment → evidence → conclusion**

A small experiment with a clear question can be more valuable than a huge project with no evaluation.

---

## Thesis as a forcing function

Instead of treating the bachelor's thesis as separate university work:

**existing interest → prototype → measurable question → experiment → thesis**

This could make academic work contribute directly to research and portfolio development.

---

## Automation

Automation isn't only:

> “Make this faster.”

A better question is:

> **“What repeated process can become a reliable system?”**

Typical structure:

**input → processing → decision → output**

AI can be one component rather than the entire solution.

---

## Good engineering starts before implementation

Before building:

* What problem?
* For whom?
* What does success mean?
* What data is needed?
* What architecture?
* What can be reused?
* How will it be evaluated?
* What happens when it fails?
* How could it evolve?

**Less “build something impressive.”
More “design something intelligently.”**

---

# Current Projects / Prototypes

## Adaptive Learning Playground

Web learning environment with:

* visual explanations
* mini simulations
* quizzes
* AI hints
* progress tracking
* adaptive interventions

Main question:

> **What should an educational system do next given what the learner just did?**

---

## Learning Systems Lab

GitHub public lab notebook containing:

* learning experiments
* AI-assisted learning tools
* educational prototypes
* coding/technical notes
* study methods
* failed experiments
* observations
* research questions

Not random notes → **documented experimentation and development of a way of thinking.**

---

## Motion Learning Assistant

**webcam → body movement → interpretation → feedback**

Exploring:

* OpenCV
* MediaPipe
* motion tracking
* interactive feedback
* educational applications

---

## AI Tutor / Personalized Learning System

A practical testbed for:

* learner-specific context
* adaptive explanations
* different difficulty levels
* hints
* feedback
* progress tracking

Goal:

**content + explanation + difficulty + interaction + feedback → adapted to the learner**

---

## Nutrition / Personal Planning Systems

Another recurring direction: using software and AI to solve real problems in my own environment rather than inventing arbitrary demos.

Examples include:

* micronutrient/meal planning
* structured decision systems
* automation
* information aggregation

This reinforces:

> **Personal problems can be useful starting points for technical projects because the feedback loop already exists.**

---

# Common architecture

I'm starting to see the same structure underneath many of these projects:

**observe → infer state → choose intervention → act → measure → update**

### Learning

student behavior → estimate understanding → choose hint → new attempt → evaluate

### Motion

movement → estimate state → feedback → movement changes → observe again

### AI workflow

problem → infer need → choose tool/action → observe result → adapt

The reusable skill may therefore be **designing feedback-driven systems**, rather than learning one particular framework.

---

# Open Questions

* How can AI distinguish productive vs. unproductive confusion?
* How can it estimate what a learner understands?
* What makes one hint better than another?
* How can it choose the **minimum sufficient hint**?
* When should it stop helping?
* How can it detect that its own explanation failed?
* How should scaffolding fade?
* Can mistakes reveal missing prerequisites?
* How much personalization actually helps?
* How should adaptive learning systems be evaluated?
* Can this feedback-loop architecture generalize beyond education?

---

# Main Takeaway

AI is lowering the cost of making things.

Therefore my advantage shouldn't be trying to compete with AI at raw implementation speed.

It should come from combining:

**technical fundamentals + systems thinking + problem selection + experimentation + domain understanding + building + evaluation**

The question I want to keep asking is:

> **What becomes possible now, what is actually worth building, and how can I design the smallest system that lets me find out?**
