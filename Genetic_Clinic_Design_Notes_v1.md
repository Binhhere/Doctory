# Genetic Clinic Game Design Notes

> This document records the design evolution discussed so far. It
> intentionally preserves the reasoning process rather than only the
> final conclusions.

------------------------------------------------------------------------

# Initial Vision

The player is a genetic doctor working in a clinic outside space and
time. Patients arrive from different stages of humanity's evolution.

The launch scope is intentionally small.

**Launch v1** - Stage 1A - Stage 1B

Future updates may expand into later eras.

------------------------------------------------------------------------

# Evolution Stages

## Stage 1A -- Modern Humans

Purpose: - Teach gameplay. - Simple medical/genetic cases. - Cosmetic
and light genetic treatments.

Examples: - Mild inherited disorders. - Cosmetic edits. - Small
congenital defects.

------------------------------------------------------------------------

## Stage 1B -- Human Genetic Disorders

More complex diagnosis.

Examples: - Albinism. - Down syndrome. - Rare inherited diseases. -
Multi-cause symptoms.

Difficulty increases through ambiguity instead of new controls.

------------------------------------------------------------------------

## Stage 2 -- Adapted Space Humans

Humans modify themselves to survive beyond Earth.

Examples: - Radiation resistant skin. - Twin hearts. - Auxiliary
limbs. - Infrared vision. - Alien atmosphere lungs.

------------------------------------------------------------------------

## Stage 3 -- External Genetic Civilization

An advanced civilization rewrites biology.

Patients arrive with: - Unknown organs. - Unstable biology. - Artificial
evolution. - Forced mutations.

The player decides whether to preserve, reverse or accept these changes.

------------------------------------------------------------------------

## Stage 4 -- Post Humanity

Humanity branches into entirely new forms.

Examples: - Stone people. - Vacuum-adapted people. - Symbiotic
organisms. - Crystal biology.

No new verbs should be introduced. Existing mechanics should scale
through new biological rules.

------------------------------------------------------------------------

# Core Design Goal

The game should not become: - a dentist game, - a medical simulator, -
or a visual novel.

Target:

Easy to learn. Hard to master. Constantly interesting through new
situations instead of many mechanics.

------------------------------------------------------------------------

# Gameplay Philosophy Evolution

Initially the discussion focused on:

"What is the genetic editing mechanic?"

This later evolved into:

"What problem is the player solving?"

Finally it evolved into:

"What decision is the player responsible for?"

This became the true center of the design.

------------------------------------------------------------------------

# Human-Centered Philosophy

The biggest insight reached during the discussion:

> The game is not about genes.
>
> The game is about making medical decisions for different people.

Later refined into:

> Human beings are the gameplay.
>
> Not the reward after gameplay.

The player should remember patients more than mechanics.

------------------------------------------------------------------------

# Storytelling Philosophy

Story should never interrupt gameplay.

Patients speak while treatment continues.

Dialogue exists to reveal values, priorities and personality.

Dialogue should almost never become a dialogue choice screen.

Instead: actions performed during treatment become the decision.

------------------------------------------------------------------------

# Treatment Philosophy

Medical success and human satisfaction are different things.

Possible outcomes include: - medically successful but personally
regretted, - medically imperfect but accepted, - refused treatment, -
partial recovery, - long-term consequences.

The game avoids binary success/failure.

There is no traditional Game Over.

------------------------------------------------------------------------

# Final Career Summary

Instead of endings:

Career history records: - patients treated, - patients saved, - failed
operations, - refused treatments, - unintended mutations, - future
consequences, - evolution branches influenced.

Every player creates a different medical legacy.

------------------------------------------------------------------------

# Companion Characters

Long-term recurring characters were proposed.

Possible structures: - one family across generations, - one patient
returning throughout history, - an AI assistant, - recurring
troublemakers.

Goal:

Players remember people across time.

------------------------------------------------------------------------

# Hidden Antagonists

Inspired by identity-checking games.

Examples: - fake records, - parasites, - infiltrators, - disguised
organisms.

The purpose is uncertainty rather than combat.

------------------------------------------------------------------------

# Gameplay Ratios

Approximate target:

60% treatment

25% observation and reasoning

15% dialogue

Dialogue should remain short but meaningful.

------------------------------------------------------------------------

# Earlier Node Graph Direction

A biological graph was proposed.

Genes → Proteins → Hormones → Symptoms.

Advantages: - scalable, - logical, - expandable.

Weakness discovered later:

Players eventually memorize the graph.

Gameplay risks becoming pattern recognition.

This direction was intentionally deprioritized.

------------------------------------------------------------------------

# Scientific Discovery Discussion

Another proposal:

Players gradually build medical knowledge.

Notebook records hypotheses.

Later patients reveal exceptions.

Important refinement:

Knowledge should expand by conditions instead of random contradiction.

Example:

A rule remains true except for patients with specific environmental
history.

Notebook should preserve incorrect assumptions instead of deleting them.

------------------------------------------------------------------------

# Concern Raised

Risk:

Players begin playing the notebook rather than patients.

This redirected the design toward human values instead of knowledge
collection.

------------------------------------------------------------------------

# Human Values

Patients do not share identical priorities.

Different people value: - family, - appearance, - career, - lifespan, -
freedom, - legacy.

These priorities should emerge naturally through dialogue rather than
visible numerical stats.

Backend may internally track values.

Frontend should not expose them.

------------------------------------------------------------------------

# Moral Decisions

Choices should happen through treatment itself.

Not through dialogue boxes.

Example:

Saving hand function versus cardiac stability.

Player physically performs the action instead of selecting A/B.

------------------------------------------------------------------------

# Vun Trồng Direction

Major insight:

The body should behave like an ecosystem rather than a machine.

This naturally provides: - delayed consequences, - contextual
reactions, - uncertainty, - experimentation.

------------------------------------------------------------------------

# Living Body Representation

Temporary name:

Sinh Mạch.

Later refinement:

It should become visually integrated into the patient's own body instead
of floating separately.

Visible through skin and anatomy.

The patient becomes the interface.

------------------------------------------------------------------------

# Hidden Biological System

Genes, proteins and hormones still exist.

However:

They become invisible simulation rules.

Players infer them visually instead of reading charts.

------------------------------------------------------------------------

# Single Input Verb

Entire game uses:

Hold → Drag → Release.

Meaning depends on context.

Examples:

Feed.

Prune.

Transfer.

No additional core verbs.

"Dung hòa" can emerge naturally by partially committing instead of
introducing another action.

------------------------------------------------------------------------

# Why Hold Matters

Hold duration naturally distinguishes:

Intentional commitment.

Versus accidental input.

No confirmation popups required.

------------------------------------------------------------------------

# Case Loop

Observe.

Optional deep inspection.

Cultivate.

Release.

Patient reacts.

No success screen.

------------------------------------------------------------------------

# Patient Is The UI

Major principle.

Feedback should appear through: - breathing, - facial expression, -
voice, - posture, - eye movement, - visible biological changes.

Not numbers.

Not HP bars.

Not stat popups.

------------------------------------------------------------------------

# Greybox Priority

Do not continue expanding design documents before testing.

Prototype only:

Hold.

Drag.

Release.

Visual biological response.

One complete patient case.

Question to answer:

Is the interaction enjoyable after several repeated cases?

------------------------------------------------------------------------

# Current Design Principles

1.  Human beings are gameplay.
2.  Story never interrupts treatment.
3.  Decisions happen through actions.
4.  Biology behaves like an ecosystem.
5.  One core interaction should scale throughout the game.
6.  New features must improve Hold → Drag → Release instead of adding
    complexity.
7.  Patients should be remembered more than mechanics.
