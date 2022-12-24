---
title: "Prime Idea Factorization"
date: 2022-12-23
draft: false
author: Dan
tags: ["Ideas", "Novelty", "Factorization", "Literature"]
Params:
  ShowReadingTime: true
---

I've never had a truly original idea.

I had that realization around a month ago. It irked me at first. After some
thought, it's brought me a lot of peace, focus, and optimism. I'd like to share why.

Most people have never had original, novel ideas. This applies to people
that pride themselves on having great ideas. It also applies to people that *history*
prides on having great ideas. And let me be clear: I'm not making a semantic or
hand-wavey epistemic argument. Take any reasonable interpretation of the word
idea, and I'll tell you that people generally just don't have novel ones.

Perhaps ironically, I'm not the first person to say this. In a 1903 letter to
Helen Keller, Mark Twain remarked:
> The kernel, the soul — let us go further and say the substance, the bulk,
> the actual and valuable material of all human utterances — is plagiarism.

Twain's thoughts are well-explored in the literary and artistic domain. Take any
well-known novel or movie from the 21st century, and you can probably reduce it
to something done five hundred (or more) years ago; repeat ad nauseum until you've exhausted
the human historical record. As it turns out, there are fundamental
facets of the human experience that have remained unchanged over time and permeate our
artistic and literary expressions. We keep writing the same stories--painting the
same feats of heroism and depths of despair--over and over again. I suspect that's
what Twain was getting at. It's beautiful, if not a bit cynical. But it's not
*really* what I'm getting at.

I don't mean books, movies, or paintings. I mean "invention." I mean cutting-edge
research. The latest articles published in *Nature*, or the startup that just
raised $100m.[^1] Rather than trying to take pick apart specific instances, I think
it'd be more productive to explain the framework I've begun using to think
about ideas.[^2]

Are you familiar with the story of *Frankenstein*? Here's a one sentence summary:[^3]
> Frankenstein is a novel about a scientist [Dr. Frankenstein] who creates a monster out of body
> parts and brings it to life, but the creature becomes violent and wreaks havoc, leading the scientist to 
> regret his actions.

People overwhelmingly think a bit like Dr. Frankenstein (if you ignore the
grave robbing and wreaking havoc parts). They chop different parts off
of existing ideas--maybe articles they've read or companies they've heard of--and
combine them together. Maybe the resulting combination is novel, but none of the parts
are. You can often easily decompose these ideas into their parts.

I'm not knocking Frankenstein ideas. All of my ideas are Frankenstein ideas.
Cars are a Frankenstein idea. So were telephones. Pretty much *every* notable
machine learning paper of the past 20 years has been a Frankenstein idea or
remarkably close to it.[^4] Sometimes Frankenstein ideas consist of parts taken
from the same technical domain. Often, great Frankenstein ideas take parts
from other, seemingly unrelated areas of invention and research literature.[^5]

All this talk about parts and decompositions might give the mathematically
astute a bit of déjà vu. It feels like we're talking about numbers. Take any
number, and you can *uniquely* represent it as a product of prime numbers, up to
the power on each prime (often called a prime factorization or prime decomposition).
This is the Fundamental Theorem of Arithmetic, and it has surprisingly applicable
intuition for thinking about ideas.

Let's throw any mathematical formalisms out the window. Ideas are numbers now.
Instead of "1, 2, 3," we count "wheel, penicillin, indoor plumbing." Convinced?

There are infinitely many prime (novel) ideas, but they get less common as you
stray from zero. The overall proportion of composite (Frankenstein) ideas increases.
Composite ideas are all unique in their construction and can decomposed into a
product of prime ideas. Try it--take some of your best ideas and see if you
can perform a prime idea factorization. Maybe `car = wheel * engine * horse buggy`.
You could probably represent some forms of neural networks as `(logistic regression)^n`
for large `n` (and you can decompose logistic regression even further).
I think performing these decompositions (in a serious, thoughtful manner--not like the above) can
actually be a useful exercise for getting at the crux of what something really is.

Now, we're back in the real world. Numbers are back to being numbers--ah yes,
1, 2, 3. However, I hope the prime idea factorization intuition remains.

If anything, this should all serve to make highly motivated, perpetually
stressed out individuals breathe a sigh of relief. You don't have to be good at
coming up with novel things--pretty much nobody is! If that's what you're optimizing
for, you're probably wasting your time. Instead, focus on learning and deeply
understanding what you learn. Be curious--build hypothetical Frankenstein ideas
in your head whenever you can. Look to successful, innovative ideas and understand
where they drew inspiration from and how all of the parts came together. To me,
that sounds a whole lot more achievable than hoping you'll magically have
some utterly novel idea that nobody else has had.

[^1]: Maybe these things are solving the same *fundamental human problems*
(getting from point A to B, feeling connected to others, etc.),
but that falls back into the semantic argument of what an idea even is. I don't
want to do that. No, the ideas themselves aren't novel.

[^2]: I'm probably too much of a theorist (and too lazy) to pick apart specific
examples anyway.

[^3]: Courtesy of ChatGPT :)

[^4]: In fact, running into so many machine learning research papers that just
seemed to be lopping pieces of existing techniques together (and I'm guilty
of this too) is what initially inspired these thoughts.

[^5]: This is part of the reason why anybody that wants to create something
meaningful should have a variety of interests outside of their work or primary
area of thought. They should read voraciously. Complete specialization isn't
always a good thing, and I'll likely explore this in future content.