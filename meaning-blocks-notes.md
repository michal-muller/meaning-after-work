# Meaning Blocks v0.1 — Design Notes

Meaning Blocks is a reflective falling-block experience about AI, work, care, pressure and human meaning.

It is not a psychological test, diagnostic instrument, productivity assessment or therapeutic tool.

## Core metaphor

Meaning Blocks treats life and work as a composition of pressures, relationships, responsibilities and spaces of reflection.

The player does not simply manage isolated tasks. The player arranges forces that shape a life pattern.

The central idea is:

> Meaning does not depend only on what enters life, but on how different demands, relationships and responsibilities are arranged together.

## What the game tracks

The prototype tracks four reflective dimensions:

* **Pressure**
  The felt density of deadlines, system demands, usefulness and overload.

* **Meaning**
  The degree to which the arrangement remains connected to purpose, authorship and human significance.

* **Agency**
  The degree to which the player preserves judgment, choice and the capacity to rearrange the pattern.

* **Co-being**
  The degree to which the arrangement preserves relationship, care, shared burden and human presence.

## Starting values

The current starting values are:

* Pressure: 40
* Meaning: 50
* Agency: 50
* Co-being: 50

Scores are bounded between 0 and 100.

## Block families

Each block belongs to a conceptual family.

### System blocks

Examples:

* AI
* Work

System blocks represent technical, organizational or productivity structures.

They are not negative in themselves, but if they cluster without reflection, they tend to increase pressure and reduce agency or co-being.

### Pressure blocks

Examples:

* Deadline
* Ambition
* Silence

Pressure blocks represent compression, acceleration, expectation and unspoken tension.

They often raise pressure and may reduce meaning, agency or co-being.

### Human blocks

Examples:

* Care
* Relationship

Human blocks represent presence, interruption, mutuality and shared life.

They tend to strengthen meaning and co-being.

### Reflective blocks

Examples:

* Reflection
* Responsibility

Reflective blocks represent judgment, ethical attention and the capacity to ask what should remain human.

They tend to strengthen meaning and agency.

### Rest blocks

Examples:

* Rest

Rest blocks represent non-instrumental space.

They reduce pressure and reopen the possibility of meaning beyond usefulness.

## Basic scoring logic

Each block has its own basic effect when placed.

For example:

* AI may increase pressure while lowering agency if it is not accompanied by reflection.
* Care may slightly increase practical pressure but strongly increase co-being.
* Rest lowers pressure and protects space beyond usefulness.
* Responsibility increases meaning, agency and co-being, but may also add some pressure.
* Silence increases pressure and lowers meaning, agency and co-being.

## Neighbourhood logic

The game also reads the neighbourhood of blocks in the grid.

Only direct neighbours are currently checked:

* above
* below
* left
* right

Diagonal neighbours are not currently counted.

The meaning of a block depends not only on what it is, but on what it is placed next to.

## Pattern rules

### System next to system

Examples:

* AI next to Work
* AI next to AI
* Work next to Work

Interpretation:

System elements are clustering. Efficiency may grow, but pressure thickens and human space can narrow.

Effect:

* Pressure increases
* Meaning may decrease
* Agency may decrease
* Co-being may decrease

### Human next to human

Examples:

* Care next to Relationship
* Care next to Care
* Relationship next to Relationship

Interpretation:

Human elements are connecting. Meaning is strengthened not only by isolated care, but by relational patterns.

Effect:

* Pressure may decrease slightly
* Meaning increases
* Agency may increase slightly
* Co-being increases strongly

### Reflective next to system

Examples:

* Reflection next to AI
* Responsibility next to Work
* Reflection next to Work

Interpretation:

Technology and work are not the problem in themselves. The problem emerges when they are disconnected from judgment, responsibility and reflection.

Effect:

* Pressure decreases
* Meaning increases
* Agency increases
* Co-being may increase slightly

### Rest next to pressure

Examples:

* Rest next to Deadline
* Rest next to Ambition
* Rest next to Silence

Interpretation:

Rest is not escape. It is a counterweight to pressure and a condition for human judgment to return.

Effect:

* Pressure decreases significantly
* Meaning increases
* Agency increases
* Co-being may increase slightly

### Overloaded column

If one column becomes too crowded, the game interprets this as overload.

Interpretation:

A life pattern cannot carry everything in one place. When all demands accumulate in one column, pressure rises and the pattern becomes less humanly sustainable.

Effect:

* Pressure increases
* Meaning decreases
* Agency decreases
* Co-being decreases

## What the game evaluates

Meaning Blocks does not evaluate whether the player is right or wrong.

It evaluates:

1. What kinds of blocks enter the grid.
2. Where the player places them.
3. What neighbourhoods and clusters emerge.
4. Whether the pattern becomes overloaded, relational, reflective or pressured.

The game is therefore not about individual choices alone. It is about configuration.

## Core conceptual claim

The central philosophical claim of Meaning Blocks is:

> Life is not an optimization problem. It is a fragile composition of demands, relationships, responsibilities and spaces of reflection.

The game should help players notice whether their life pattern is becoming:

* too system-heavy,
* too pressure-driven,
* relationally supported,
* reflectively arranged,
* spacious enough for meaning,
* or overloaded by usefulness.

## Result profiles

The current profiles are:

### The Overloaded Grid

High pressure and lower meaning.

This profile suggests that work, speed or system demands may have taken up more space than meaning can sustain.

### The Relational Pattern

High co-being.

This profile suggests that care, relationship and shared responsibility have prevented the grid from becoming only a structure of output.

### The Reflective Arranger

High meaning and agency.

This profile suggests that the player creates pauses, boundaries and reflective arrangements where judgment can return.

### The Spacious Composer

Lower pressure and higher meaning.

This profile suggests that rest, reflection or care have created enough space to interrupt the pressure of usefulness.

### The Fragile Composition

Default profile.

This profile suggests that the pattern holds together, but remains fragile. The future of the grid depends on what is allowed to cluster.

## Important limitation

The scoring is interpretive and conceptual, not empirical.

It should not be presented as a validated assessment, psychological test, personality typology, diagnostic tool or mental health instrument.

Preferred language:

* reflective pattern
* current arrangement
* tendency
* invitation
* question
* profile

Avoid:

* diagnosis
* personality type
* score as measurement
* assessment result
* mental health interpretation

## Data ethics

The current version stores nothing, sends nothing and uses no database.

All choices remain in the visitor’s browser during the session only.

No personal data should be requested.

No sensitive, medical, workplace-confidential or third-party information should be entered into the tool.
