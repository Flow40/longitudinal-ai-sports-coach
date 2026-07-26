# Memory Model

## Purpose

The memory model separates stable facts from short-term context and session-level observations.

## Memory Categories

### Athlete Profile

- age range
- height and weight
- training background
- preferred sports
- experience level

### Goals

- current primary goal
- secondary goals
- target events
- time horizon

### Medical and Movement Constraints

- diagnosed conditions
- injury history
- active pain
- restricted movements
- clinician guidance
- red flags requiring referral

### Performance History

- recent sessions
- actual loads
- repetitions completed
- RPE
- pain response
- time or distance results

### Exercise Tolerance

- well-tolerated movements
- poorly tolerated movements
- regressions and substitutions
- successful reintroductions

### Environment

- available equipment
- hotel or home-gym constraints
- travel schedule
- session duration

### Preferences

- preferred session structure
- disliked exercises
- desired training style
- acceptable complexity

## Suggested Retention Rules

Keep long term:

- confirmed injuries
- persistent restrictions
- major performance benchmarks
- stable preferences
- recurring successful substitutions

Keep temporarily:

- acute fatigue
- short-term soreness
- travel context
- temporary equipment availability

Discard or summarize:

- repeated conversational details
- obsolete restrictions
- redundant session notes
- information with no impact on future planning

## Example Memory Object

```json
{
  "athlete_profile": {
    "sports": ["running", "strength training", "CrossFit"],
    "experience": "intermediate"
  },
  "active_constraints": [
    "previous right shoulder dislocation",
    "lumbar sensitivity"
  ],
  "recent_performance": {
    "front_squat": "5x5 at 55 kg, RPE 7",
    "incline_dumbbell_press": "4x8 at 17.5 kg, pain 1/10"
  },
  "equipment": ["commercial gym", "TRX", "dumbbells"],
  "planning_notes": [
    "avoid aggressive overhead progression",
    "favor controlled unilateral lower-body work"
  ]
}
```
