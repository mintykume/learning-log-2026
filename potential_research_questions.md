Potential Research Questions

Working document. These are questions I could eventually turn into experiments, projects, or a bachelor's thesis. They are intentionally broader than a final research question and will need narrowing.

1. Adaptive AI tutoring and hints

Core question

How can an AI tutor choose the minimum sufficient hint that helps a learner progress without taking over the cognitive work?

Related questions:

Can learner behavior predict the amount/type of help needed?

Can repeated mistakes identify missing prerequisites?

When should the system allow productive confusion to continue?

When should it intervene?

How should scaffolding fade as competence increases?

Can an AI detect that its own explanation failed?

Is a progressively stronger hint sequence better than direct explanation for independent problem solving?

Existing baseline to build from:
scaffolding + fading + graduated prompting

Basic intervention ladder:
attempt → small cue → stronger cue → example/partial solution → solution → independent re-attempt

Possible experiment

Compare direct answers, fixed hints, and adaptive graduated hints on the same learning task. Measure independent performance on a new problem, not just immediate correctness.

2. Productive confusion vs. unproductive confusion

Can an AI learning system distinguish productive struggle from confusion that is blocking learning?

Possible signals:

repeated incorrect attempts

long pauses / excessive delay

repeated requests for explanation

random guessing

same conceptual error across problems

successful self-correction after a hint

The goal would not be to eliminate confusion, but to identify when intervention is actually useful.

3. Controlled information load in AI learning systems

Does deliberately limiting AI-generated information improve learning compared with giving more complete explanations?

Compare:

full explanation

concise explanation

prerequisite-only intervention

question-first intervention

adaptive information load

Measure:

retention

transfer

independent problem solving

time to mastery

Core hypothesis:
Less information is not automatically better; the useful target is less unnecessary information while preserving what is necessary for learning.

4. Behavioral learner modeling

Can learner behavior provide a more useful personalization signal than self-reported learning preferences?

Possible inputs:

error patterns

hint requests

response time

skipped questions

prerequisite failures

successful transfer

number of attempts

Compare behavior-based adaptation against preference-based personalization.

5. Self-evaluation of AI explanations

Can an AI learning system reliably detect when its own explanation did not improve the learner's understanding?

Potential test:

AI gives explanation.

Learner solves a new problem.

System analyzes the error.

System decides whether to revise its explanation.

Important distinction:
“The learner said the explanation was clear” vs. “the learner can now apply the concept.”

6. AI systems as feedback-control systems

How useful is a feedback-control framing for designing adaptive educational AI?

Model:
hidden learner state → observable behavior → state estimate → intervention → new behavior → updated estimate

Could compare a simple fixed tutor with a stateful adaptive tutor.

7. AI-assisted learning and independence

At what point does AI support stop improving learning and start reducing independent problem-solving ability?

Questions:

Does frequent hinting create dependency?

Does fading support reduce this effect?

How often should independent tasks appear?

Should the tutor intentionally remove itself from the process?

8. Motion-based learning feedback

Can computer-vision-based movement feedback improve acquisition of a physical skill compared with conventional verbal/video instruction?

Possible platform:
webcam → pose estimation → movement interpretation → feedback → reattempt

Potential applications:

dance

gesture/sign-language learning

posture-oriented training

educational games

9. Motion feedback quality

What kind of feedback from a motion-learning system produces the greatest improvement: visual, auditory, textual, or multimodal feedback?

This connects directly to the Motion Learning Assistant idea.

10. AI-generated educational content quality

Does AI-generated educational material become more effective when constrained by a learner model and learning objective?

Compare:

generic AI-generated exercise

curriculum-constrained exercise

learner-state-conditioned exercise

11. Building prototypes as research instruments

Can small software prototypes provide useful evidence for human-learning or human-computer-interaction questions before a full research study is designed?

This is less a single experiment and more a research methodology question for my own work.

12. AI verification

What lightweight verification methods are most effective for detecting errors in AI-generated technical work?

Possible domains:

code

factual explanations

research summaries

structured decisions

Core distinction:
generation capability vs. system reliability

13. AI-assisted project selection

Can an AI system improve project selection by explicitly evaluating problem value, learning value, evidence potential, feasibility, and future leverage?

This could become part of the Project Navigator concept.

14. Personal problem → prototype → opportunity

Do projects built around recurring personal problems produce better learning and stronger portfolio evidence than projects chosen primarily for novelty?

Potential evaluation dimensions:

completion probability

iteration count

depth of learning

real-user feedback

reuse of components

opportunities generated

15. Main meta-question

What becomes worth building when AI makes prototyping dramatically cheaper?

Possible decomposition:

Which bottlenecks disappear?

Which new bottlenecks appear?

Does problem selection become more important?

Does system design become more important?

Does verification become more important?

Which personal problems become technically solvable?

Which projects create compounding capability rather than one-off output?

This is probably too broad for a single study, but it is a useful theme connecting the rest of my work.

Candidate questions to investigate first

Adaptive hints: Can graduated/adaptive hints improve independent transfer compared with direct answers or fixed hints?

Productive confusion: Can learner behavior distinguish productive struggle from confusion that requires intervention?

Information load: Does controlled AI information load improve retention and transfer?

Behavioral personalization: Can observed learning behavior outperform self-reported preferences for deciding interventions?

AI self-correction: Can an AI tutor detect that its own explanation failed and successfully choose a better intervention?

These five are closely connected and could potentially become one larger experimental platform: Adaptive Learning Playground.
