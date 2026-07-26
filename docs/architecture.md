# Architecture

## Objective

The system aims to preserve useful athlete context across sessions so that recommendations are based on history rather than on a single prompt.

## Conceptual Flow

```text
User profile
Training history
Medical and movement constraints
Current goals
Available equipment
Recovery and travel context
        |
        v
Structured athlete memory
        |
        v
Session planning
        |
        v
Workout execution
        |
        v
User feedback
        |
        v
Memory review and update
        |
        v
Next session
```

## Main Components

### 1. Input Layer

Captures:

- workout requests
- completed sessions
- actual loads and repetitions
- pain and RPE
- recovery and fatigue
- equipment constraints
- schedule and travel context

### 2. Memory Layer

Stores and summarizes:

- stable profile information
- active injuries and restrictions
- recent training history
- exercise tolerance
- progression markers
- preferences and recurring constraints

### 3. Planning Layer

Uses memory to:

- select exercises
- adapt volume and intensity
- preserve the intended training stimulus
- avoid known contraindications
- propose realistic loads

### 4. Feedback Layer

Compares prescribed and completed work, then decides what should be retained, updated or discarded.

## Design Principle

The system should not remember everything. It should retain information that changes future recommendations.
