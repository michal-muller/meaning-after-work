# Co-being Signal — Design Notes

## Core idea

Co-being Signal is a short reflective game about staying connected under intelligent noise.

Two people are trying to remain present to one another while deadlines, metrics, AI summaries, optimization demands, fatigue and misunderstandings move between them.

The player’s task is not to click everything. The task is to discern what deserves attention, what needs repair, what is only noise, and what kind of pressure weakens the human connection.

## Core metaphor

The game represents noise, and what kind of pressure weakens the human connection co-being as a fragile signal between two people.

The signal becomes stronger when human needs are heard and repair is possible.

The signal becomes weaker when pressure, system demands and noise replace presence.

## Main question

Can you keep presence and trust alive while pressure and noise rise?

## Dimensions

The game tracks four dimensions:

### Presence

The capacity to remain attentive to the other person.

Presence increases when human signals are heard.

Presence decreases when human signals are missed or when the player amplifies noise.

### Trust

The fragile confidence that the other person is still seen, heard and taken seriously.

Trust increases when human and repair signals are clicked.

Trust decreases when human signals are missed, when system pressure is prioritized over relation, or when noise is amplified.

### Pressure

The accumulated force of deadlines, productivity demands, dashboards, optimization and system expectations.

Pressure rises over time and when system tokens are missed.

Pressure can be reduced temporarily by clicking system tokens, but this may weaken presence and trust.

### Noise

The accumulated interference of misunderstanding, fatigue, defensiveness, assumptions and over-explanation.

Noise rises over time, especially in higher levels.

Noise weakens the connection even when the player is still trying to listen.

## Starting values

The game begins with:

- Presence: 60
- Trust: 60
- Pressure: 35
- Noise: 30
- Time: 100 seconds
- Level: 1
- Score: 0

## Token families

### Human signals

Examples:

- “I need you to hear me.”
- “Are you still here?”
- “I am tired.”
- “This matters to me.”
- “Please do not fix me yet.”
- “Can we slow down?”
- “I do not feel seen.”
- “Stay with me.”
- “I need presence, not a solution.”
- “Please listen before answering.”

Human signals represent moments where another person asks to be heard, not optimized.

Clicking a human signal:

- Presence +7
- Trust +8
- Pressure -2
- Noise -3
- Score increases

Missing a human signal:

- Presence -6
- Trust -8
- Pressure +2
- Noise +3
- Score decreases

### Repair signals

Examples:

- Ask again
- Name the fear
- Pause
- Listen
- Return
- Repair
- Shared silence
- Say what hurts
- Begin again
- Stay gentle

Repair signals represent small practices through which co-being becomes possible again.

Clicking a repair signal:

- Presence +5
- Trust +5
- Pressure -5
- Noise -4
- Score increases

Missing a repair signal:

- Pressure +2
- Noise +2
- Score decreases slightly

### System tokens

Examples:

- AI summary
- Metric
- Deadline
- Optimization
- Productivity score
- Unread message
- Faster response
- Risk dashboard
- Efficiency target
- Automated decision

System tokens are not evil. They represent system demands that may be useful but can also make the other person less visible.

Clicking a system token:

- Presence -3
- Trust -4
- Pressure -3
- Noise +2
- Score decreases

Missing a system token:

- Pressure +4
- Noise +3
- Score decreases

Design meaning:

System pressure cannot simply be ignored, but prioritizing it too quickly may weaken relational presence.

### Noise tokens

Examples:

- Assumption
- Misunderstanding
- Defensiveness
- Fatigue
- Comparison
- Status anxiety
- Performance mask
- Silent resentment
- Over-explanation
- Shortcut

Noise tokens represent relational interference.

Clicking a noise token:

- Presence -4
- Trust -3
- Pressure +1
- Noise +4
- Score decreases

Missing a noise token:

- Pressure +1
- Noise +2

Design meaning:

Not all noise deserves attention. Some things become stronger when they are fed.

## Level logic

The game lasts 100 seconds.

Level increases as time passes:

- Level 1: beginning
- Level 2: after roughly 18 seconds
- Level 3: after roughly 36 seconds
- Level 4: after roughly 54 seconds
- Level 5: after roughly 72 seconds
- Level 6: after roughly 90 seconds

As levels rise:

- Tokens move faster.
- More system and noise tokens appear.
- Multiple tokens may appear close together.
- Pressure and noise rise faster.

## Token probability logic

Early levels are more generous:

- More human signals
- More repair signals
- Less noise

Middle levels increase ambiguity:

- Human signals become slightly less frequent.
- System and noise tokens become more frequent.

Later levels increase pressure:

- Human signals still appear, but they are easier to miss.
- System and noise tokens compete more aggressively for attention.

## Scoring logic

The score rewards the player for keeping presence and trust alive while pressure and noise rise.

The player gains points for:

- Clicking human signals
- Clicking repair signals
- Maintaining presence
- Maintaining trust
- Surviving under rising pressure

The player loses points for:

- Clicking noise
- Clicking system pressure too often
- Missing human signals
- Missing repair opportunities
- Letting pressure and noise accumulate

The score is not a measure of personal worth. It is a metaphorical indicator of how well the signal survived.

## Collapse conditions

The game ends early if any of these happen:

- Presence reaches 0
- Trust reaches 0
- Pressure reaches 100
- Noise reaches 100

The game also ends when time reaches 0.

## Result profiles

### Signal Keeper

Condition:

- High presence and trust
- Pressure and noise remain manageable

Meaning:

The player protected presence and trust while pressure moved through the space.

Reflection:

Co-being remained alive.

### Relational Rebel

Condition:

- Presence and trust remain high despite high pressure

Meaning:

The player refused to let optimization replace presence.

Reflection:

The signal survived through resistance.

### Overloaded Listener

Condition:

- Noise is high, but presence and trust remain moderate

Meaning:

The player tried to hear the other person while too much noise accumulated.

Reflection:

The connection survived, but became fragile.

### Efficient Drifter

Condition:

- Pressure is relatively low, but trust is weak

Meaning:

The player managed system pressure but lost part of the relational signal.

Reflection:

Efficiency is not the same as presence.

### Fragile Connection

Condition:

- The signal survives, but without strong presence/trust or strong collapse

Meaning:

The player kept the signal alive, but it remained vulnerable.

Reflection:

Co-being is not a state. It is a repeated return.

### Lost in the Noise

Collapse condition:

- Noise reaches 100

Meaning:

The signal did not fail because care disappeared. It failed because too much noise stood between the two people.

### Pressure Broke the Signal

Collapse condition:

- Pressure reaches 100

Meaning:

The connection weakened under accumulated pressure.

Reflection:

Co-being needs time, not only intention.

### Disconnected Listener

Collapse condition:

- Presence or trust reaches 0

Meaning:

The human signal became too faint.

Reflection:

The game asks how easily presence disappears when pressure rises.

## Design principles

Co-being Signal should feel:

- dynamic
- fragile
- relational
- slightly poetic
- emotionally legible
- not diagnostic
- not moralizing
- not purely efficiency-based

The player should learn that:

- not everything deserves attention
- human signals are easy to miss
- repair is possible but fragile
- system pressure can be useful but relationally costly
- noise often grows when amplified
- connection requires discernment, not speed alone

## Data ethics

The game stores no data.

The game sends no data anywhere.

There is no account, no database and no tracking of individual results beyond standard website analytics.

The score is local to the current session and disappears when the page is refreshed.

## Important disclaimer

Co-being Signal is a reflective prototype.

It is not:

- a psychological test
- a personality test
- a diagnostic instrument
- a therapy tool
- a clinical assessment
- a workplace assessment
- a validated measurement of relational capacity

It is an invitation to reflect on how presence and trust can weaken under pressure, noise and system demands.

## Future improvement ideas

Possible later improvements:

- Add sound effects for human signals and noise.
- Add optional slower mode for accessibility.
- Add personal best stored only in browser.
- Add more token types.
- Add “daily signal” version.
- Add short reflection prompts after the result.
- Add a visual explanation of how the signal line is calculated.
- Add keyboard support.
- Add mobile difficulty tuning.
- Add a short “What did you notice?” private reflection box.

## Current status

Co-being Signal is a working public prototype on Meaning After Work.

Page:

https://meaningafterwork.com/co-being-signal.html

Hub:

https://meaningafterwork.com/contradiction-diary.html
