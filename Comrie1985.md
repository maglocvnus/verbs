# Bernard Comrie (1985) *Tense*

Every finite verb form in English has either present tense or past tense. 

Here are some present tense forms:
- *Kate **dances**.*
- *Kate **is** dancing.*
- *Kate **will** dance.*
- *Kate **will** be dancing.*
- *Kate **has** danced.*
- *Kate **has** been dancing.*
- *Kate **will** have been dancing.*

Here are the corresponding past tense forms:
- *Kate **danced**.*
- *Kate **was** dancing.*
- *Kate **would** dance.*
- *Kate **would** be dancing.*
- *Kate **had** danced.*
- *Kate **had** been dancing.*
- *Kate **would** have been dancing.*

For Comrie:
- When a finite verb is in the present tense, this means that the situation (event, process or state) described by the verb (and its dependents) is true at the moment of utterance.
- When a finite verb is in the past tense, this means that the situation described by the verb (and its dependents) is true at some moment that precedes the moment of utterance.

## Simple tenses

Let’s start with the so-called ‘simple tense’ examples:
- *Kate **dances**.*
- *Kate **danced**.*

The lexical verb here is *dance*, which intrinsically describes a **process** (rather than an event or state). Simply put:
- Processes and events are *dynamic*, whereas states are not.
- Events are *bounded*, whereas processes and states are not. 

```
∀x. dancing(x) → process(x)
∀x. process(x) → situation(x) ∧ dynamic(x) ∧ ¬bounded(x)
∀x. event(x) → situation(x) ∧ dynamic(x) ∧ bounded(x)
∀x. state(x) → situation(x) ∧ ¬dynamic(x) ∧ ¬bounded(x)
```


A process like dancing can be thought of as a non-bounded repetition of individual events – dancing is an aggregate of step patterns, in the same what that sand (or uncooked rice) is an aggregate of grains.

Kate dance graph? FOL

```
∃x. dancing(x) ∧ sbj(x,Kate) ∧ at(x,now)
∃x. dancing(x) ∧ sbj(x,Kate) ∧ before(x,now)
```

In the simple present example *Kate dances*, the present tense suffix -s has been appended to the process verb *dance*.

graph? FOL

Most other European languages, this would mean the single process that holds right now, but not in English!

A process verb in the present simple forces habitual meaning for some reason.


Here the present tense suffix *-s* is attached to the verb *sing*, which is a **process verb**. This means that, intrinsically, the situation described by *sing* is a **process** – it consists of a non-bounded series of actions on the part of the swimmer, viewed from a time perspective that lies within the process itself.

perfective / imperfective

might also be true at other moments as well!


different for event verbs, process verbs and state verbs? swim is an activity/process verb, non-bounded non-culminating, doesn't change the world.


