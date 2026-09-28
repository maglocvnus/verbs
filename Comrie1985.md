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

We can formalise this as follows:

```
∀x. dancing(x) → process(x)
∀x. process(x) → situation(x) ∧ dynamic(x) ∧ ¬bounded(x)
∀x. event(x) → situation(x) ∧ dynamic(x) ∧ bounded(x)
∀x. state(x) → situation(x) ∧ ¬dynamic(x) ∧ ¬bounded(x)
```

In the simple present example *Kate dances*, the present tense suffix *-s* has been appended to the process verb *dance*.

Given Comrie’s characterisation of present tense meaning above, it would be expected that the meaning of *Kate dances* would be this:

```
∃x. dancing(x) ∧ sbj(x,Kate) ∧ at(x,now)
```

In other words, there is a process involving Kate dancing which is true right now, at the moment the sentence is being uttered by the speaker.

However, for some reason, and unlike in most other familiar languages, the simple present in English doesn’t work like that with process and event verbs.

Rather, the unmarked meaning of *Kate dances* is the description of a current habit, rather than simply a current process.


```
∃x. habit(x) ∧ at(x,now) ∧ dancing(y) ∧ sbj(y,Kate) 
```




Kate dance graph? FOL

```
∃x. dancing(x) ∧ sbj(x,Kate) ∧ at(x,now)
∃x. dancing(x) ∧ sbj(x,Kate) ∧ before(x,now)
```



graph? FOL

Most other European languages, this would mean the single process that holds right now, but not in English!

A process verb in the present simple forces habitual meaning for some reason.


Here the present tense suffix *-s* is attached to the verb *sing*, which is a **process verb**. This means that, intrinsically, the situation described by *sing* is a **process** – it consists of a non-bounded series of actions on the part of the swimmer, viewed from a time perspective that lies within the process itself.

perfective / imperfective

might also be true at other moments as well!


different for event verbs, process verbs and state verbs? swim is an activity/process verb, non-bounded non-culminating, doesn't change the world.


