# Design Evolution Report

## Project: Genetic Clinic (Working Title)

> This document is a decision log rather than a Game Design Document. It
> records *why* ideas appeared, *why* they were challenged, and *why*
> they were kept or rejected. It is intended to become the long-term
> source of truth for future development.

------------------------------------------------------------------------

# 1. Original Premise

The earliest vision was a player acting as a doctor inside a genetic
clinic existing outside normal space and time.

Patients arrive from different periods of humanity's evolution.

Originally four broad eras were envisioned.

## Stage 1A

Normal humans. Cosmetic edits. Minor inherited diseases.

Purpose: Teach mechanics.

## Stage 1B

Genetic disorders.

Examples discussed: - Albinism - Down syndrome - Rare inherited diseases

Purpose: Increase diagnostic reasoning.

## Stage 2

Space-adapted humanity.

People voluntarily redesign themselves for survival.

Examples: - Radiation skin - Extra lungs - Twin hearts - Additional
limbs

Purpose: Increase biological complexity without changing core
interaction.

## Stage 3

External civilization capable of rewriting biology.

Patients appear with impossible mutations.

Main conflict becomes ethical rather than technical.

## Stage 4

Post-human evolution.

Entirely new body plans.

Important decision: No new core interaction should be introduced.
Difficulty must increase through biological rules rather than controls.

------------------------------------------------------------------------

# 2. First Design Question

Originally the discussion focused on:

"What is the genetic editing mechanic?"

This turned out to be the wrong question.

Because mechanics alone do not create interesting cases.

The better question became:

"What problem is the player solving?"

Later this evolved again into:

"What decision is the player responsible for?"

This shift changed the entire project direction.

------------------------------------------------------------------------

# 3. Launch Scope Decision

A major scope reduction was agreed.

Launch version should contain only:

-   Stage 1A
-   Stage 1B

Everything else becomes future content.

Reason:

The project becomes realistically shippable for a solo/small team.

------------------------------------------------------------------------

# 4. Gameplay Goals

The game must not become:

-   a children's dentist game,
-   an extremely realistic medical simulator,
-   a visual novel.

Desired characteristics:

-   Learn quickly.
-   Master slowly.
-   Reuse one interaction.
-   Produce new situations through context.

------------------------------------------------------------------------

# 5. Storytelling Evolution

Initial thought:

Story would appear between treatments.

Problem:

Gameplay becomes interrupted.

Decision:

Story happens during treatment.

Patients speak while the player continues interacting.

Conversation never pauses gameplay.

------------------------------------------------------------------------

# 6. Dialogue Evolution

Early concept:

Dialogue choices decide outcomes.

Problem:

Player solves dialogue instead of treatment.

Decision:

Dialogue reveals personality only.

Real decisions happen through physical treatment actions.

------------------------------------------------------------------------

# 7. Human-Centered Shift

This became the largest philosophical change.

The project moved from:

Game about genetics.

to

Game about medical decisions affecting different people.

Then further refined into:

Human beings are gameplay. Not the reward after gameplay.

Meaning:

Players should remember patients more than systems.

------------------------------------------------------------------------

# 8. Success Definition

Medical success is not equal to human success.

Possible outcomes include:

-   cured but regrets decision,
-   partially cured but satisfied,
-   refused treatment,
-   accepted risk,
-   long-term consequence.

Game Over was removed.

Instead the game records an entire career.

------------------------------------------------------------------------

# 9. Career Summary

Endings were replaced by legacy.

Career report may contain:

-   patients saved,
-   failed operations,
-   refused treatment,
-   unintended mutations,
-   people encountered again,
-   evolution influenced.

Every playthrough creates a unique history.

------------------------------------------------------------------------

# 10. Companion Characters

Recurring characters were introduced to connect centuries.

Ideas included:

-   one family across generations,
-   one child returning as an adult,
-   AI assistant,
-   recurring antagonist.

Purpose:

Players emotionally connect across time.

------------------------------------------------------------------------

# 11. Knowledge System

A notebook system was proposed.

Purpose:

Players build scientific knowledge gradually.

Notebook stores hypotheses.

Later cases introduce exceptions.

Important refinement:

Exceptions extend knowledge.

They do not randomly invalidate previous discoveries.

------------------------------------------------------------------------

# 12. Notebook Criticism

A major criticism appeared.

Risk:

Players begin playing the notebook instead of patients.

Decision:

Notebook becomes secondary.

Human stories remain primary.

------------------------------------------------------------------------

# 13. Values Instead of Statistics

Patients have hidden priorities.

Examples:

Family.

Career.

Appearance.

Freedom.

Longevity.

Important decision:

Never expose these as visible stats.

Players infer them from dialogue.

Backend may internally model them.

Frontend should not.

------------------------------------------------------------------------

# 14. Node Graph Phase

Genes → Proteins → Hormones → Symptoms.

Advantages:

Logical.

Expandable.

Educational.

Weakness:

Eventually memorized.

Game risks becoming pattern matching.

Decision:

Hidden simulation only.

Never exposed directly.

------------------------------------------------------------------------

# 15. Ecosystem Insight

A major breakthrough occurred.

Instead of repairing machines...

Treat bodies as ecosystems.

Consequences naturally become:

-   delayed,
-   contextual,
-   interconnected,
-   imperfect.

This direction replaced explicit node solving.

------------------------------------------------------------------------

# 16. Cultivation (Vun Trồng)

Core metaphor:

The doctor cultivates living biology.

Not repairs machinery.

This better matches genetics.

------------------------------------------------------------------------

# 17. Living Biological Field

Working name:

Sinh Mạch.

Initially visualized as a floating biological structure.

Criticism:

Could become detached from patients.

Decision:

Integrate directly into anatomy.

Visible through skin.

Patient becomes the interface.

------------------------------------------------------------------------

# 18. Patient Is The UI

Major principle.

Feedback should appear through:

-   breathing,
-   posture,
-   facial expression,
-   trembling,
-   voice,
-   visible biological changes.

Avoid:

HP bars.

Numbers.

Floating statistics.

------------------------------------------------------------------------

# 19. Single Interaction

Core interaction:

Hold → Drag → Release.

Interpretation depends on context.

Feed.

Prune.

Transfer.

No additional verbs added.

Potential balancing behaviour such as partial commitment emerges
naturally from the same gesture.

------------------------------------------------------------------------

# 20. Intentional Commitment

Hold duration solves accidental input.

No confirmation popup.

Player commits by continuing to hold.

Natural rather than artificial confirmation.

------------------------------------------------------------------------

# 21. Greybox Priority

Further documentation should stop temporarily.

Prototype should answer only one question:

Does Hold → Drag → Release feel meaningful after repeated cases?

Everything else depends on this answer.

------------------------------------------------------------------------

# 22. Design Filters

Every future feature must pass these questions:

Does it help players understand the patient?

Does it strengthen Hold → Drag → Release?

Does it create meaningful responsibility?

If not, postpone it.

------------------------------------------------------------------------

# 23. Current Guiding Principles

1.  Human beings are gameplay.
2.  Story never interrupts treatment.
3.  Dialogue reveals people rather than presenting choices.
4.  Decisions happen through action.
5.  Bodies behave like ecosystems.
6.  Hidden systems are preferable to visible charts.
7.  The patient is the UI.
8.  One interaction should support the entire game.
9.  Difficulty grows through biological rules, not extra controls.
10. Prototype before expanding lore.

------------------------------------------------------------------------

# 24. Open Questions

These remain intentionally unresolved.

-   Exact visual style of the biological field.
-   Exact resource economy during cultivation.
-   How recurrence of patients is scheduled.
-   How medical uncertainty is communicated.
-   Final naming.
-   Audio language of biological feedback.
-   Tutorial structure.
-   Long-term content pacing.

These questions should be answered through prototypes instead of
documentation whenever possible.
