# Lokpra

Lokpra is a [conlang](https://en.wikipedia.org/wiki/Constructed_language) which
was primarily generated using LLMs as an experiment to assess the skills of
(reasoning) LLMs in constructing languages. More about LLM usage in [LLM
Usage](#llm-usage).

## Key Features
- **Limited Alphabet:** Words in Lokpra use a restricted subset of the Latin
  alphabet, consisting only of the letters *p, r, l, k, o, e, i and a*, with *i
  and a* being more rare. (**The alphabet was provided in the prompt**.)

- **Subject-Verb-Object (SVO) Word Order:** Lokpra follows a straightforward
  SVO sentence structure for clarity and ease of understanding. (**This
  decision was taken by the AI**.)

- **Analytic Grammar:** The language employs an analytic grammatical structure,
  relying heavily on word order and particles to convey meaning, rather than
  complex inflections. (**This decision was taken by the AI**.)

# Reference
This repository contains the reference, which is also [hosted
here](https://podikoglou.github.io/lokpra).

# Maintenance
I'm not planning on maintaining this.

# LLM Usage
Two LLMs were used for the creation of Lokpra:
1) Deepseek R1 (for the ideation of the language),
2) Gemini 2.0 Flash Thinking Experimental 01-21 (for coming up with ~70% of the dictionary (the other 30% was created by R1)).

## DeepSeek R1
### Prompt
```
come up with a general purpose language for modern society, which consists only of the following letters:
- p
- r
- l
- k
- o
- e

and the very rare occurrance of i and a
```
### Response
[^1]
```
Okay, so the user wants me to create a general-purpose language using only the
letters p, r, l, k, o, e, with i and a being very rare. Hmm, first I need to
figure out how to structure a language with such limited vowels. The vowels
available are o, e, i, and a, but i and a are rare. That might lead to a lot of
consonant clusters. Maybe I should start by outlining the phonotactics—how
syllables are formed. Let's see, maybe each syllable has a consonant followed
by a vowel. Since there are more consonants (p, r, l, k) than vowels, repeating
vowels might be necessary. But since i and a are rare, most syllables will use
o and e.

Next, the grammar. Should it be analytic or synthetic? Since the alphabet is
limited, an analytic structure with word order determining meaning might be
better. That way, we don't need many inflections which could require more
letters. For example, Subject-Verb-Object order. Then, how to create
vocabulary. Maybe roots are 2-3 letters. Let's assign meanings to consonant
roots. For instance, 'p' could relate to people, 'r' to movement, 'l' to place,
'k' to objects. Then vowels modify the meaning. O could be noun, e verb, i past
tense (rare), a future (also rare). So 'pro' could mean person moving (maybe
'traveler'), 'pre' would be the verb 'to move'.

But wait, the letters allowed are p, r, l, k, o, e, with i and a rare. Need to
make sure that words are formed using these. Also, considering that i and a are
rare, maybe they're used for grammatical markers, like tense or case. For
example, adding 'i' to a verb makes it past tense, but since i is rare, maybe
past tense isn't used as often, or is marked differently. Alternatively, use a
particle with i or a. But particles would need to be short, maybe 'ki' for
past, 'ka' for future, but since a is rare, maybe 'ka' is only used in specific
contexts.

Semantics: How to cover modern concepts with limited roots. Maybe compound
words. Like 'komputer' can't be used, but maybe combine 'k' (object) + 'r'
(communication) + 'e' (verb) to form a word for computer. Wait, but the letters
are limited. So 'kre' could be a verb for computing, and 'kro' the noun. But
need to make sure all words only use the allowed letters.

Writing system: Since it's using Latin letters, maybe just a straightforward
script. But maybe diacritics for the rare vowels? The user didn't mention
diacritics, so probably not. So i and a are just used sparingly in the script.

Examples: Let's try some basic sentences. "I eat food." Subject is 'I', verb
'eat', object 'food'. In this language, maybe 'po' is person (p + o), so 'po'
could mean I/me. 're' as eat (r + e). 'ko' as food (k + o). So sentence: "Po re
ko." But need to check if that's how the grammar works. If word order is SVO,
then yes.

Another example: "He runs quickly." 'He' could be another pronoun, maybe 'ro'
(if r is movement, but that might conflict). Wait, pronouns might need to be
derived from the person root 'p'. So 'po' is I, 'pe' is you (if e is second
person), 'pi' is he/she (using rare i). But i is rare, so maybe third person
pronouns are marked with i. So 'pi' for he/she. 'Run' could be a verb, maybe
'rle' (since r is movement, l might be legs? Not sure. Or 're' again, but that
was eat. Hmm, maybe need more roots. Maybe 'r' is action, 'l' is location.
Wait, this is getting complicated. Maybe each consonant has a category, and
vowels indicate part of speech. So p-people, r-actions, l-places, k-objects.
Then vowels: o-noun, e-verb, i-adjective (rare), a-adverb (rare). So 're' would
be the verb for an action, but which action? Maybe need to combine consonants.
Like 'pr' could be a specific action, 'rl' another. Wait, but the letters are
single consonants. So each root is a single consonant followed by a vowel. So
'pe' is the verb for person-related action, like 'to be'. 're' is a general
action verb. Maybe this is too vague. Alternatively, roots are two consonants.
Like 'pl', 'rk', etc., but the user specified only the letters p, r, l, k, o,
e, i, a. So words can have multiple consonants as long as they're from the
allowed set. So maybe syllables are C(C)V(C), but vowels are o, e, with i and a
rare.

Wait, the problem says the language consists only of the listed letters. So
words can have any combination of p, r, l, k, o, e, with i and a rarely. So a
word could be 'prok', 'ler', etc. So the structure is more flexible. Maybe
roots are combinations of consonants, and vowels are used for inflection or
derivation. For example, 'pr' could be a root meaning 'to go', and adding 'e'
makes it a verb: 'pre'. Adding 'o' makes it a noun: 'pro' (a journey). Then 'k'
could be an object root, 'kro' is a tool, 'kre' is to use a tool.

But how to cover modern society terms. Like 'internet' or 'government'. Maybe
'loko' for internet (lo-place, ko-object, combined?). Or 'prelo' for government
(action + place). This is getting a bit abstract. Need to ensure that the
vocabulary can be expanded systematically.

Also, considering that i and a are rare, maybe they're used for grammatical
markers. Like pluralization, tense, or case. For example, adding 'i' to a noun
makes it plural, but since i is rare, perhaps plurals are not always marked, or
only when necessary. Similarly, 'a' could indicate future tense, but used
sparingly.

In terms of phonetics, the language might have a lot of consonant clusters, but
since the allowed consonants are p, r, l, k, which are all plosives and
liquids, it's manageable. Words might look like 'krop', 'lerp', 'polk', etc.

Testing some basic words: Hello could be 'polero' (person + movement +
greeting?), but maybe that's too long. Maybe 'prelo' (action + place =
meeting). Thank you: 'krepo' (object + person = gift, then verb form).

Need to establish a core vocabulary with the allowed letters. Maybe start with
pronouns, basic verbs, nouns, then build up. Also, considering that this
language needs to be general-purpose, covering technology, society, etc., the
roots should be abstract enough to allow compounding.

Another angle: Since i and a are rare, perhaps they serve as function words.
For example, 'i' could be a possessive marker, 'a' a question marker. So "po i
ko" = "my food". "Pe re ko a?" = "Do you eat food?"

Overall, the key steps are: define phonotactics, assign semantic categories to
consonants, use vowels for grammatical functions, create a systematic way to
derive words, handle rare vowels for special cases, and ensure the language can
scale to modern concepts through compounding and derivation.
```
[^1]: text underwent minor edits (wrapping), for better readability

