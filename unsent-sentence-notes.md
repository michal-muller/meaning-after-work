# The Unsent Sentence — Design Notes

## Core idea

The Unsent Sentence is a short reflective game about protecting a human sentence from becoming too efficient, too polished or too afraid.

The player does not write personal text. Instead, the game offers prepared sentence fragments. Each choice changes the emotional and existential quality of the sentence.

The game asks how easily human expression can be transformed by pressure, professionalism, fear, optimization and the desire to remain safe.

## Core metaphor

The sentence represents a human attempt to speak honestly.

It begins with:

**I wanted to tell you...**

As the game progresses, the sentence is shaped by competing forces:

* honesty
* warmth
* courage
* polish
* pressure

The sentence can become more human, more guarded or more optimized.

A sentence does not become less human only because it is short. It becomes less human when its truth, warmth or courage are edited out.

## Main question

Can a sentence stay human before it is optimized away?

## Player task

In each round, the player chooses one of three prepared fragments.

Each fragment has a different character:

* Human
* Guarded
* Optimized

The player must decide what kind of sentence they are willing to let survive.

The goal is not to write the perfect message. The goal is to notice how human expression changes under pressure.

## Dimensions

The game tracks five dimensions.

### Honesty

Honesty represents how much truth remains in the sentence.

Honesty rises when the player chooses direct, vulnerable and human fragments.

Honesty decreases when the player chooses fragments that hide the real meaning behind process language, abstraction or professional smoothness.

### Warmth

Warmth represents whether the sentence still carries relation, care and emotional presence.

Warmth rises when the sentence remains relational and open.

Warmth decreases when the sentence becomes too procedural, defensive or emotionally distant.

### Courage

Courage represents the willingness to say something that matters, even if it is uncomfortable.

Courage rises when the player chooses fragments that keep difficulty visible.

Courage decreases when the player avoids discomfort, hides need or makes the sentence too safe.

### Polish

Polish represents professional smoothness, clarity and social safety.

Polish is not bad by itself.

A sentence may need some polish in order to be sendable. But too much polish can erase the human being who wanted to speak.

### Pressure

Pressure represents the external and internal forces that try to make the sentence safer, shorter, more efficient or less vulnerable.

Pressure rises over time and through difficult human choices.

Pressure may decrease when the player chooses optimized fragments, but this often comes at the cost of honesty, warmth or courage.

## Starting values

The game begins with:

* Honesty: 55
* Warmth: 50
* Courage: 45
* Polish: 30
* Pressure: 35
* Score: 0
* Human fragments: 0
* Guarded fragments: 0
* Optimized fragments: 0
* Total rounds: 8
* Time per round: 18 seconds

## Fragment types

### Human fragments

Human fragments preserve vulnerability, relationality and truth.

Examples:

* “that I have been carrying more than I said”
* “and I did not know how to ask for help”
* “because I was afraid you would only see my usefulness”
* “and I missed being spoken to as a person”
* “I am not blaming you, I am trying to stay honest”
* “I still care about this, and maybe that is why it hurts”
* “I do not need you to fix it immediately, but I need you to hear it”
* “and I hope we can meet each other more truthfully next time”

Design meaning:

Human fragments keep the person visible.

They may increase pressure because truth can be difficult, but they strengthen honesty, warmth and courage.

### Guarded fragments

Guarded fragments preserve some truth, but protect the speaker from full exposure.

Examples:

* “that things have been busy lately”
* “and I probably should have communicated sooner”
* “because I was unsure how it would be received”
* “and I missed a different kind of conversation”
* “I hope this does not sound too negative”
* “I think this matters more than I expected”
* “I would be grateful if we could return to this later”
* “and I hope we can talk about it when there is space”

Design meaning:

Guarded fragments are not false.

They often represent a realistic compromise between honesty and safety.

However, if the sentence becomes too guarded, its most human part may remain hidden.

### Optimized fragments

Optimized fragments make the sentence smooth, professional and safe.

Examples:

* “that there have been minor capacity constraints”
* “and I will improve future communication flows”
* “because stakeholder expectations were unclear”
* “and I would appreciate improved communication quality”
* “I am sharing this as constructive feedback”
* “this remains relevant for future collaboration”
* “no immediate action is required at this stage”
* “and I look forward to further alignment”

Design meaning:

Optimized fragments reduce discomfort and may lower pressure.

But they often remove honesty, warmth and courage.

They show how human expression can become administratively acceptable and existentially empty.

## Pressure prompts

Each round introduces a pressure that tries to shape the sentence.

Examples:

* Make it efficient.
* Do not sound needy.
* Hide the feeling.
* Make it shorter.
* Sound professional.
* Do not make it personal.
* Avoid discomfort.
* End safely.

Design meaning:

The pressure prompts are not external commands only. They also represent internalized norms of professional communication.

The game asks whether the player can recognize these pressures before they erase the sentence.

## Round logic

The game has eight rounds.

In each round:

1. A pressure prompt appears.
2. Three possible fragments are shown.
3. The player chooses one fragment.
4. The chosen fragment is added to the sentence.
5. The player’s dimensions change.
6. The next round begins.

Each choice changes the sentence and the emotional profile of the result.

## Time logic

Each round has 18 seconds.

If the player does not choose in time, the system automatically selects a safer or more optimized fragment.

Design meaning:

When the human does not choose, the system chooses safety.

The timeout is not meant to punish the player. It represents the way pressure, delay and uncertainty often push human expression toward safer language.

## Collapse conditions

The game can end early if:

* Honesty reaches 0
* Warmth reaches 0
* Courage reaches 0
* Pressure reaches 100

The sentence also ends after the eighth round.

## Score logic

The score rewards fragments that keep the sentence human.

The player gains points for:

* choosing human fragments
* preserving honesty
* preserving warmth
* preserving courage
* allowing the sentence to remain emotionally alive

The player gains fewer points for guarded fragments.

Optimized fragments usually give low score because they often reduce the human quality of the sentence.

The score is not a measure of communication skill or personal worth.

It is a metaphorical indicator of how much of the human sentence survived.

## Result profiles

### Your Sentence Survived

Condition:

* Many human fragments
* High honesty
* Strong warmth

Meaning:

The sentence became vulnerable, warm and clear enough to remain human.

Reflection:

It did not become perfect. It became alive.

### Beautiful Avoidance

Condition:

* High polish
* Lower honesty

Meaning:

The sentence became elegant and safe, but some of its truth was edited out.

Reflection:

A beautiful sentence can still avoid the person who needed to speak.

### Brave Fragment

Condition:

* High courage
* High pressure

Meaning:

The sentence stayed human even while pressure tried to make it smaller.

Reflection:

Courage is not loudness. Sometimes it is one honest fragment that remains.

### Careful Distance

Condition:

* Many guarded fragments
* Few human fragments

Meaning:

The sentence did not lie, but it kept its most human part behind a door.

Reflection:

Safety protected the speaker, but also kept the truth at a distance.

### Gentle Truth

Condition:

* High warmth

Meaning:

The sentence found a way to be honest without becoming harsh.

Reflection:

A sentence can be true and still care for the relation.

### Unfinished Honesty

Condition:

* The sentence survives without a dominant pattern

Meaning:

The sentence survived in fragments.

Reflection:

It may not be ready, but it is no longer empty.

### The Sentence Was Pressured Away

Collapse condition:

* Pressure reaches 100

Meaning:

The sentence did not disappear because it was false. It disappeared because pressure became louder than truth.

### Protected Silence

Collapse condition:

* Courage, warmth or expression collapses

Meaning:

The sentence tried to stay safe.

Reflection:

It survived as silence, but not yet as speech.

## Design principles

The Unsent Sentence should feel:

* intimate but safe
* reflective
* emotionally recognizable
* short
* shareable
* poetic but not sentimental
* serious but playable
* non-diagnostic
* non-therapeutic
* not dependent on the user typing personal data

The player should learn that:

* language can remain useful and still lose its truth
* professionalism can protect but also hide
* efficiency can erase vulnerability
* not every human sentence should be optimized
* guarded language is sometimes necessary but has a cost
* honesty needs warmth
* courage needs care
* a sentence can survive as a fragment

## Viral potential

The game has stronger sharing potential than some other reflective games because it produces a final sentence.

The result is not only a score or a profile. It is a short, human, copyable sentence.

Possible shareable format:

**The Unsent Sentence — Your Sentence Survived**

“I wanted to tell you that I have been carrying more than I said and I did not know how to ask for help...”

This creates a small emotional artifact.

The game should encourage reflection without pressuring users to share anything personal.

## Safety and privacy design

The game uses only prepared fragments.

The player does not type private, personal or sensitive text.

The game stores no data.

The game sends no data anywhere.

There is no account, no database and no tracking of individual results beyond standard website analytics.

The final sentence exists only in the current browser session unless the user chooses to copy it.

## Important disclaimer

The Unsent Sentence is a reflective prototype.

It is not:

* a therapy tool
* a mental health tool
* a diagnostic instrument
* a communication assessment
* a personality test
* a clinical assessment
* a relationship test
* a validated psychological scale

It is an invitation to reflect on how human expression can become over-polished, guarded or erased under pressure.

## Relationship to EHCAI

The Unsent Sentence connects to EHCAI through the question of human expression under intelligent and organizational systems.

Many AI-mediated environments encourage:

* summarization
* optimization
* professional tone
* risk reduction
* emotional smoothing
* efficient communication

The game asks what happens when these pressures reshape not only communication, but the human being who tries to speak.

In EHCAI terms, the game explores:

* agency in expression
* responsibility in language
* co-being through speech
* meaning in unfinished communication
* the human cost of over-optimization

## Relationship to other games

The Unsent Sentence complements the other reflective games:

* Co-being Signal focuses on relational presence under intelligent noise.
* Agency Reactor focuses on agency inside automated systems.
* The Human Minute focuses on small moments of presence during a crowded day.
* The Last Human Desk focuses on arranging work, AI, care and meaning.
* The Unsent Sentence focuses on protecting human expression from optimization and fear.

Together, these games form a reflective laboratory for Meaning After Work.

## Possible future improvements

Possible later improvements:

* Add more sentence paths.
* Add different opening sentences.
* Add a “work version,” “friendship version,” and “leadership version.”
* Add optional slow mode.
* Add a no-timer reflective mode.
* Add sound or typewriter effects.
* Add a final shareable card with no personal data.
* Add a “rewrite with more warmth” button.
* Add a “make it less optimized” reflection mode.
* Add teaching notes for workshops.
* Add a short explanation of how professional language can hide responsibility.
* Add a Czech version.
* Add multilingual versions for public talks.

## Current status

The Unsent Sentence is a working public prototype on Meaning After Work.

Page:

https://meaningafterwork.com/unsent-sentence.html

Hub:

https://meaningafterwork.com/contradiction-diary.html
