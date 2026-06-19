# Agency Reactor — Design Notes

## Core idea

Agency Reactor is a short reflective game about keeping human agency alive inside an automated system.

The player manages a symbolic “human agency reactor” inside an AI-mediated organization. The reactor depends on five forces:

- Automation
- Judgment
- Responsibility
- Care
- Rest

The player’s task is not to reject automation. The task is to keep automation in relationship with human judgment, responsibility, care and rest.

If the system becomes too hot, too exhausting or too unstable, the agency core collapses.

## Core metaphor

The reactor represents human agency under system pressure.

Agency does not collapse all at once. It weakens through many small shifts:

- too much automation without judgment
- too much responsibility without rest
- too much speed without care
- too much system pressure without human interpretation

The visual reactor collapse represents the point at which the system still functions, but human agency can no longer meaningfully guide it.

## Main question

Can you keep human agency alive inside an automated system?

## Dimensions

The game tracks five main dimensions.

### Agency

The capacity to act, decide and remain meaningfully involved rather than passively following the system.

Agency rises through judgment, responsibility, care and rest.

Agency decreases when automation becomes dominant or when the player relies too heavily on system relief.

### Clarity

The capacity to understand what is happening and what is at stake.

Clarity rises through judgment and rest.

Clarity decreases when automation is used without interpretation or when the system becomes too complex and fast.

### Responsibility

The capacity to remain answerable for decisions, consequences and human effects.

Responsibility rises when the player chooses to take responsibility.

Responsibility can also become dangerous if it accumulates without care or rest.

### Burnout Risk

The accumulated human cost of carrying responsibility, pressure and performance without recovery.

Burnout risk rises over time, especially when responsibility is high and rest is low.

Burnout risk decreases through rest and, to a smaller extent, care.

### Stability

The overall balance of the reactor.

Stability is calculated from the relationship between:

- agency
- clarity
- responsibility
- care
- rest
- heat
- burnout risk
- imbalance among energy fields

High stability means the system remains humanly governable.

Low stability means the agency core is close to collapse.

## Secondary value

### Heat

Heat represents system pressure, speed, automation intensity and unresolved friction.

Heat rises over time and when system events add pressure.

Heat decreases mainly through rest and sometimes through automation.

If heat reaches 100, the reactor collapses.

## Starting values

The game begins with:

- Time: 120 seconds
- Level: 1
- Score: 0
- Agency: 65
- Clarity: 60
- Responsibility: 55
- Burnout Risk: 30
- Heat: 30
- Stability: approximately 70
- Automation Energy: 50
- Judgment Energy: 50
- Responsibility Energy: 50
- Care Energy: 50
- Rest Energy: 50

## Player actions

The player can choose five actions.

### Automate

Meaning:

Use AI or system automation to relieve pressure quickly.

Effect:

- Agency decreases
- Clarity decreases
- Responsibility decreases slightly
- Burnout risk decreases slightly
- Heat decreases
- Automation energy rises
- Judgment energy decreases
- Care energy decreases
- Score rises modestly

Design meaning:

Automation is useful. It can reduce immediate pressure. But if used too often, it may move the centre of action away from human agency.

### Judge

Meaning:

Pause and apply human interpretation.

Effect:

- Agency increases
- Clarity increases
- Responsibility increases slightly
- Burnout risk increases slightly
- Heat increases slightly
- Judgment energy rises
- Automation energy decreases
- Score rises

Design meaning:

Judgment restores agency and clarity, but it requires effort. Human judgment is not free; it takes time, energy and responsibility.

### Take responsibility

Meaning:

Accept answerability for a decision, situation or consequence.

Effect:

- Agency increases
- Clarity increases slightly
- Responsibility increases strongly
- Burnout risk increases
- Heat increases
- Responsibility energy rises
- Rest energy decreases
- Score rises

Design meaning:

Responsibility is essential for human-centred AI, but responsibility without support becomes overload.

### Care

Meaning:

Protect the human field around the system.

Effect:

- Agency increases slightly
- Clarity increases slightly
- Responsibility increases slightly
- Burnout risk decreases
- Heat increases slightly
- Care energy rises
- Automation energy decreases
- Score rises

Design meaning:

Care slows the system down, but protects the human world that the system affects.

### Rest

Meaning:

Cool the agency core and prevent collapse.

Effect:

- Agency increases slightly
- Clarity increases
- Responsibility decreases slightly
- Burnout risk decreases strongly
- Heat decreases strongly
- Rest energy rises
- Responsibility energy decreases
- Score rises

Design meaning:

Rest is not a luxury. It is a condition of sustained agency.

## System events

Every few seconds, a new system event appears.

Examples:

### AI recommends an immediate decision

The answer is fast, plausible and convenient. But no one has checked who carries the consequence.

### A dashboard asks for measurable output

The metric is clear. The human cost is not.

### A colleague asks who is accountable

The system supported the decision, but the answer cannot be delegated.

### Someone says: this process is harming people

The issue slows everything down, but ignoring it would make the system morally thinner.

### The team is tired but keeps performing

Nothing has collapsed yet. That is why the risk is easy to deny.

### The AI summary misses the nuance

The summary is efficient, but the important hesitation disappeared.

### People begin to wait for the system

The tool has become useful. It has also become a place to hide.

### Responsibility accumulates in one person

Everyone agrees the work matters. Nobody asks who can still carry it.

### A convenient shortcut appears

It would save time. It would also make discomfort disappear before it speaks.

### A human conversation is replaced by a summary

The information moves faster. The relationship does not.

## Event logic

Each event adds pressure to the system.

Events increase:

- heat
- burnout risk

The player must respond by choosing one of the five actions.

There is no single correct response. The meaning of each action depends on the current state of the reactor.

## Level logic

The game lasts 120 seconds.

Level increases as time passes:

- Level 1: beginning
- Level 2: after roughly 22 seconds
- Level 3: after roughly 44 seconds
- Level 4: after roughly 66 seconds
- Level 5: after roughly 88 seconds
- Level 6: after roughly 110 seconds

As level rises:

- heat rises faster
- burnout risk rises faster
- automation drift becomes more dangerous
- low rest becomes more costly
- the reactor becomes harder to stabilize

## Drift logic

The reactor changes even when the player does nothing.

Over time:

- heat rises
- burnout risk rises
- rest energy slowly decreases
- care energy slowly decreases
- automation energy slowly rises
- agency may drift down if automation exceeds judgment
- clarity may drift down if judgment energy becomes too low

Design meaning:

Systems do not remain neutral. Without active human effort, automated systems tend to drift toward speed, automation and overload.

## Stability logic

Stability is not a single value controlled directly by the player.

It is calculated from human strengths and system risks.

Stability rises when:

- agency is high
- clarity is high
- responsibility is present but not overloaded
- care is present
- rest is sufficient
- automation and judgment remain balanced

Stability falls when:

- heat is high
- burnout risk is high
- automation dominates judgment
- responsibility dominates rest
- care is too weak
- the energy fields become imbalanced

Design meaning:

Human agency depends on balance, not maximization.

## Collapse conditions

The game ends early if any of these happen:

- Agency reaches 0
- Clarity reaches 0
- Stability reaches 0
- Burnout Risk reaches 100
- Heat reaches 100

The game also ends when time reaches 0.

## Reactor collapse

If the game ends in failure, the reactor visually collapses or “bursts.”

This is not meant as a literal explosion. It is a metaphor for the moment when the system still appears to run, but human agency can no longer guide it.

The collapse should feel dramatic, but not like punishment. It should feel like a warning.

## Score logic

The player gains score by:

- preserving stability
- using judgment
- taking responsibility
- caring for the human field
- resting before collapse
- keeping the reactor alive over time

The player can also gain modest points from automation because automation can be useful.

The player loses indirectly when choices create imbalance, burnout, heat or agency loss.

The score is not a measure of personal worth. It is a metaphorical indicator of how long and how well the agency core remained alive.

## Result profiles

### Agency Keeper

Condition:

- High agency
- High stability
- Burnout risk remains manageable

Meaning:

The player kept automation in relation to judgment, responsibility, care and rest.

Reflection:

The core remained alive.

### Responsible Overloader

Condition:

- Responsibility is high
- Burnout risk is also high

Meaning:

The player protected accountability, but carried too much without enough rest.

Reflection:

Responsibility needs support.

### Careful Stabilizer

Condition:

- Care energy is high
- Stability is moderate or high

Meaning:

The player protected the human field around the system.

Reflection:

The reactor survived through care.

### Efficient Drift

Condition:

- Automation energy is high
- Agency is weakened

Meaning:

Automation helped the system move quickly, but human agency became thinner.

Reflection:

Speed is not the same as human control.

### Fragile Reactor

Condition:

- The reactor survives, but without strong agency or strong stability

Meaning:

The player kept the core alive, but the balance remained unstable.

Reflection:

Agency is a practice, not a setting.

### Reactor Rupture

Collapse condition:

- Heat reaches 100

Meaning:

The agency core overheated.

Reflection:

The system did not collapse from one bad decision, but from accumulated pressure.

### Burnout Spiral

Collapse condition:

- Burnout Risk reaches 100

Meaning:

The reactor was kept running by human effort until the human field could no longer carry it.

Reflection:

A system can appear productive while consuming the people who sustain it.

### Efficiently Captured

Collapse condition:

- Agency reaches 0

Meaning:

The system became fast, but agency disappeared.

Reflection:

Automation took the centre.

### Agency Collapse

Collapse condition:

- Clarity or stability reaches 0

Meaning:

Human judgment, care and rest could no longer balance system pressure.

Reflection:

The system became too unstable to remain humanly governable.

## Design principles

Agency Reactor should feel:

- dynamic
- systemic
- slightly tense
- visually powerful
- strategic rather than purely reactive
- metaphorical rather than diagnostic
- playful but serious
- connected to AI, management and burnout

The player should learn that:

- automation is useful but not neutral
- agency requires judgment
- responsibility can overload people
- rest protects agency
- care stabilizes systems
- heat accumulates slowly
- collapse often comes from imbalance, not one bad choice
- human-centred AI requires human energy, not only good principles

## Relationship to Co-being Signal

Co-being Signal focuses on relational pressure.

Agency Reactor focuses on systemic pressure.

Together they form a pair:

- Co-being Signal: Can you keep presence and trust alive under intelligent noise?
- Agency Reactor: Can you keep agency alive inside an automated system?

## Data ethics

The game stores no data.

The game sends no data anywhere.

There is no account, no database and no tracking of individual results beyond standard website analytics.

The score is local to the current session and disappears when the page is refreshed.

## Important disclaimer

Agency Reactor is a reflective prototype.

It is not:

- a psychological test
- a personality test
- a diagnostic instrument
- a therapy tool
- a clinical assessment
- a workplace assessment
- a productivity assessment
- a validated measurement of agency, burnout or responsibility

It is an invitation to reflect on how human agency can weaken under automation, pressure, responsibility and burnout risk.

## Future improvement ideas

Possible later improvements:

- Add optional slow mode.
- Add sound effects for reactor heating and collapse.
- Add personal best stored only in browser.
- Add more events.
- Add event-specific suggested actions.
- Add difficulty levels.
- Add “reflection after collapse” prompts.
- Add a visual explanation of stability.
- Add keyboard shortcuts.
- Add mobile difficulty tuning.
- Add a calmer version for teaching and workshops.

## Current status

Agency Reactor is a working public prototype on Meaning After Work.

Page:

https://meaningafterwork.com/agency-reactor.html

Hub:

https://meaningafterwork.com/contradiction-diary.html
