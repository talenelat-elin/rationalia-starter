---
_id: 5f5c37ee1b5cdee568cfb108
title: Priors
href: https://www.lesswrong.com/tag/priors
slug: priors
type: tag
tags:
  - LessWrong
  - Concept
  - Tag
synchedAt: '2022-09-01T09:42:28.006Z'
status: todo
---

# Priors

In the context of [Bayes's Theorem](https://wiki.lesswrong.com/wiki/Bayes's_Theorem), **priors** refer generically to the beliefs an agent holds regarding a fact, hypothesis or consequence, before being presented with evidence. Upon being presented with new evidence, the agent can multiply their prior with a [likelihood distribution](https://wiki.lesswrong.com/wiki/likelihood_distribution) to calculate a new (posterior) probability for their belief.

## Examples

Suppose you had a barrel containing some number of red and white balls. You start with the belief that each ball was independently assigned red color (vs. white color) at some fixed probability. Furthermore, you start out ignorant of this fixed probability (the parameter could be anywhere between 0 and 1). Each red ball you see then makes it *more* likely that the next ball will be red, following a [Laplacian Rule of Succession](http://en.wikipedia.org/wiki/Rule_of_succession). For example, seeing 6 red balls out of 10 suggests that the initial probability used for assigning the balls a red color was .6, and that there's also a probability of .6 for the next ball being red.

On the other hand, if you start out with the prior belief that the barrel contains exactly 10 red balls and 10 white balls, then each red ball you see makes it *less* likely that the next ball will be red (because there are fewer red balls remaining).

Thus our prior affects how we interpret the evidence. The first prior is an inductive prior - things that happened before are predicted to happen again with greater probability. The second prior is anti-inductive - the more red balls we see, the fewer we expect to see in the future.

As a real life example, consider two leaders from different political parties. Each one has his own beliefs - priors - about social organization and the roles of people and government in society. These differences in priors can be attributed to a wide range of factors, ranging from their educational backgrounds to hereditary differences in personality. However, neither can show that his beliefs are better than those of the other, unless he can show that his priors were generated by sources which track reality better[^1^](#fn1).

Because carrying out any reasoning at all seems to require a prior of some kind, ideal Bayesians would need some sort of priors from the moment that they were born. The question of where an ideal Bayesian would get this prior from has occasionally been a matter of considerable controversy in the philosophy of probability.

## Updating Prior Probabilities

In informal discussion, people often talk about "updating" their priors. This is technically incorrect, as one does not change their prior probability, but rather uses it to calculate a posterior probability. However, as this posterior probability then becomes the prior probability for the next inference, talking about "updating one's priors" is often a convenient shorthand.

## References

## Blog Posts

- [Priors as Mathematical Objects](http://lesswrong.com/lw/hk/priors_as_mathematical_objects/)
- ["Inductive Bias"](http://lesswrong.com/lw/hg/inductive_bias/)
- [Probability is Subjectively Objective](http://lesswrong.com/lw/s6/probability_is_subjectively_objective/)
- [Bead Jar Guesses](http://lesswrong.com/lw/em/bead_jar_guesses/) by [Alicorn](https://wiki.lesswrong.com/wiki/Alicorn) \- Applied scenario about forming priors.

## See Also

- [[Evidence]] (`= [[Evidence]].status`)
- [[Inductive Bias|Inductive bias]] (`= [[Inductive Bias|Inductive bias]].status`)
- [[Belief Update|Belief update]] (`= [[Belief Update|Belief update]].status`)

## References

1. Robin Hanson (2006). "Uncommon Priors Require Origin Disputes". Theory and Decision 61 (4) 319–328. [http://hanson.gmu.edu/prior.pdf](http://hanson.gmu.edu/prior.pdf)[↩](#fnref1)


%%

% START
Basic (and reversed card)
What is **Priors**?
Back: {TODO}
Tags: LessWrong
END

%%
	
