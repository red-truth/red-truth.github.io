---
layout: post
title:  "Monty Hall"
date:   2020-09-18 12:12:12 +0200
categories: stats
---
{% raw %}

A friend of mine has no knowledge of probabilities. I presented her the Monty Hall problem and she immediately said that she'd switch doors. 

(Clearly, she's smarter than Paul Erdős who required a computer simulation to be convinced.)

(Well, her explanation was that she'd have a gut feeling that the host would be trying to tell her something by opening another door. It's not entirely absurd to think that when a problem has a weird twist, it must that the "obvious" answer is wrong. As there's only one alternative to the "obvious" answer, I suppose that it's a decent way to play the metagame.)

Apparently this problem is still controversial to this day, although I don't really understand why. I suppose I'll use this page to keep track of different approaches and generalisations.

## Simple solution

When choosing a door at the start of the game, you have a 1/3 chance of winning a car. Let's assume that you adopt the following strategy: **always swap**. You'll expect to win whenever your initial choice was incorrect (2/3 of the time) and expect to lose the remaining 1/3 of games.

Of course, if you adopt the strategy of **never swapping**, then your expected win rate becomes 1/3. 

So if you're indifferent to swapping and swap 50% of the time when given the choice, then $$ P(\text{Win} \vert \text{Indifferent}) = 0.5\times 2/3 + 0.5 \times 1/3 = 0.5$$.

So swapping is the preferable strategy. 

{% endraw %}

