# Primitive Conceptual Predicates

The purpose of this repository is to systematically identify and document Primitive Conceptual Predicates.

## What are Conceptual Predicates?

There can be many different concepts relating the same entities:
- John is the father of Sam.
- John is taller than Sam.
- John likes Sam.

Each entity has a different role in the concept. If we swap their roles, the meaning changes.
- Sam is the father of John.
- Sam is taller than John.
- Sam likes John.

> e.g. Lojban; in Lojban a Conceptual Predicate is a tanru or a gismu or a lujvo.
> Roles are places in Lojban gismu (but roles aren't necessarily assigned positionally).

Languages associate a Conceptual Predicate to a particular morphological word form (the letters/sound/symbol for the word, separate to any meaning) to provide vocabulary.
Conceptual Predicates are not specific to any language, so they do not include a morphological word form (although they may be given as examples or used to help communicate the concept).


## What are Primitive Conceptual Predicates?

A Conceptual Predicate is primitive if:
- It cannot be separated into more primitive concepts without loosing it's meaning
- It does not conflate orthogonal meanings
- Its meaning cannot be constructed by other existing Primitive Conceptual Predicates

> e.g. Lojban; in Lojban a Primitive Conceptual Predicate is a gismu.

For example, the concept "to give" involves a giver, a gift and a recipient.
None of these elements of the "to give" relationship can be removed without it loosing its meaning.
The reason for giving the gift (christmas, birthday, charity, etc.) does not need to be conflated with the "to give" relationship.

For example, the concept of "eat" or "ingest" or "consume" involves an eater, and food.
Saying something "is food" does not remove the role of the eater from the relationship (otherwise it isn't food anymore), it just leaves it unspecified.
It doesn't make sense to break down this relationship more.
Also, this relationship does not need more concepts conflated with it (e.g. conflate time into the word like "eating" vs "ate").

If a Conceptual Predicates conflates some orthogonal concepts, then it is difficult to communicate the individual concepts conflated together.

> e.g. Lojban `fenki`: I'd argue crazy/insane are the same, but are probably separate from frantic/frenzy.

Scalar variations (opposite/negation or variation of intensity/strength) are an example of things that can be constructed.

> e.g. Lojban `citno` vs `nalci'o` vs `tolci'o`:

> e.g. Lojban `gleki` vs `tolbadri`, `badri` vs `tolgleki`:

> e.g. Lojban `fenki` vs `tolracli`:

Lots of concepts can be explained with many words.

## Why do this?

Building an intended Conceptual Predicate to communicate some particular meaning is difficult if concepts are not separated atomically.
When orthogonal concepts are separate, they can each be added as appropriate.

Additionally, it would be inefficient to have a word for every combination of concepts.
If you have 5 atomic concepts, needing only 5 words.
If you wanted to assign words for each pair of concepts, there are 10 different pairs needing 10 words.
This grows exponentially. If you have 10 concepts, you have 45 pairs.

When complete, this set of Primitive Conceptual Predicates can provide a well documented vocabulary of concepts, ready to be mapped to morphological word forms.

## What is the method for doing this?

Systematically examine each Conceptual Predicate with a series of questions.
These answers form documentation defining and justifing each Primitive Conceptual Predicate.

[Questions](QUESTIONS.md)

## How to contribute

Contributions are welcome.

Please create a pull request with any changes.

By providing a contribution you are agreeing to license your work under the same license (CC-BY-SA-4.0).

## Can a logical language use Conceptual Predicates which are not primitive?

Yes. One could say "this concept is not atomic, it is composed of these other two concepts, but we decide it is important enough to be a first class anyway".

Can we say "lets have this word because it would be super convenient, despite it not being primitive".

## Is the choice of Primitives subjective?

Probably.

These choices should be resolved by consistently following some rules.
It is unclear what rules are needed at this point.

