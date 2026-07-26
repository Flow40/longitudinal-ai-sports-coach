# Long-Term Memory AI Sports Coach

## Overview

This project explores how a large language model can evolve from an episodic assistant into a persistent sports coach by using structured long-term memory.

Over more than one year, an AI assistant was used to adapt training recommendations based on:

- completed workouts and actual loads
- perceived exertion and pain
- injury history and medical constraints
- available equipment
- travel and recovery context
- evolving athletic goals
- user feedback after each session

The goal is not to claim that an LLM can replace a qualified coach, physiotherapist or physician. The project examines how persistent memory changes the quality, consistency and safety of personalized recommendations.

## Core Research Questions

1. How much does persistent memory improve personalization?
2. Can an LLM build a useful longitudinal model of an athlete?
3. Which information should be stored, summarized or forgotten?
4. How should recommendations be evaluated across weeks and months?
5. What safeguards are required for medical and injury-related context?
6. How should privacy be managed in long-term personal AI systems?

## Athlete Context

The case study includes:

- running, CrossFit and strength training
- evolving goals and training environments
- recurrent business travel
- changing equipment availability
- lumbar constraints
- recovery from a shoulder dislocation
- detailed workout feedback, including loads, repetitions, pain and RPE

## Conceptual Architecture

```text
Training history
Medical and movement constraints
Preferences and available equipment
                |
                v
        Structured athlete memory
                |
                v
     Session planning and adaptation
                |
                v
       Workout execution and feedback
                |
                v
          Memory update and review
```

## Repository Structure

```text
longitudinal-ai-sports-coach/
├── README.md
├── LICENSE
├── docs/
│   ├── architecture.md
│   ├── memory-model.md
│   ├── case-studies.md
│   ├── limitations-and-safety.md
│   └── research-questions.md
├── data/
│   ├── example-athlete-profile.json
│   ├── example-workout-log.csv
│   └── README.md
├── prompts/
│   ├── session-planning-prompt.md
│   ├── workout-review-prompt.md
│   └── memory-update-prompt.md
└── paper/
    └── outline.md
```

## Status

Exploratory personal project and work in progress.

## Safety

This project is not medical advice and does not replace a physician, physiotherapist or qualified sports coach.
