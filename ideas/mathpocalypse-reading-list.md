# The “mathpocalypse”: AI-generated mathematics at scale

**Proposed by:** jheffer
**Suggested format:** discussion (with a short paper-reading element)

## Why interesting

On 6 October 2026 OpenAI posted several hundred AI-generated manuscripts claiming progress on hundreds of open problems, most produced by an unreleased model. Scott Aaronson’s label for the day, “Mathocalypse”, stuck (also written “mathpocalypse” and “mathspocalypse”). It is a live test of how a research community verifies, credits and responds to agent-produced results at a volume no human can read.

## Reading list

Priority 1 is the minimum for the session. Priority 3 is optional.

### Priority 1: what happened

1. [Is this the “mathocalypse”? Why OpenAI’s latest results dump has left mathematicians in shock](https://phys.org/news/2026-10-mathocalypse-openai-latest-results-dump.html) (phys.org). Best single overview found.
2. [Mathpocalypse](https://discourse.julialang.org/t/mathpocalypse/139898) (Julia Discourse). Working practitioners’ reaction; read for the links it collects.
3. [OpenAI uploads 722 AI math preprints; three pulled next day](https://aiweekly.co/alerts/openai-uploads-722-ai-math-preprints-three-pulled-next-day). Covers the withdrawn manuscripts, including the sign error that broke a proof and two that depended on it.

### Priority 2: reaction and critique

4. [Mathspocalypse now: has AI made maths pointless?](https://theweek.com/tech/mathspocalypse-now-has-ai-made-maths-pointless) (The Week). The “whole lost generation” argument.
5. [The ‘Mathocalypse’: Why AI’s maths breakthrough has experts worried](https://www.tbsnews.net/world/mathocalypse-why-ais-maths-breakthrough-has-experts-worried-1571111). Security, cryptography and verification concerns.
6. [Has OpenAI started the ‘mathpocalypse’?](https://tech.yahoo.com/ai/articles/openai-started-mathpocalypse-experts-ais-190500361.html) (Yahoo Tech). Expert views on long-run consequences.
7. [Why Mathematicians Are Furious at OpenAI’s 722 Proofs](https://capitalandcompute.net/md/why-mathematicians-are-furious-at-openai.md). Covers the Association for Human Mathematics statement urging mathematicians to stop working with OpenAI.
8. [OpenAI posted 722 AI-written math papers, kept the prompts](https://letsdatascience.com/blog/openai-posted-722-ai-written-math-papers-kept-the-prompts). Reproducibility: prompts and the model were not released.

### Priority 3: background and context

9. [OpenAI and Anthropic hiding math breakthroughs](https://www.mindstudio.ai/blog/openai-anthropic-hiding-math-breakthroughs). Summarises Aaronson’s September post speculating that labs were withholding results.
10. [Towards Autonomous Mathematics Research](https://arxiv.org/abs/2602.10177). Earlier paper already linked from this repo.
11. [Lean 4 theorem proving tutorial](https://leanprover.github.io/theorem_proving_in_lean4/). Needed to judge the Lean formalisations that accompany some of the manuscripts.
12. [AlphaGeometry](https://en.wikipedia.org/wiki/AlphaGeometry). Prior AI mathematics milestone, for comparison.
13. [Artificial Intelligence in Mathematics: A Brief Introduction](https://theaiscientist.substack.com/p/artificial-intelligence-in-mathematics). Primer for members new to the area.

## Notes

* Related repo material: [`mathematics-harmonic-aristotle.md`](mathematics-harmonic-aristotle.md) covers machine-checked proofs in Lean 4, which is the main answer to the verification problem.
* Sources disagree on the numbers (722 papers, 372 problem families, 719 headline results) and on how many results have been checked in Lean. Settle this from the primary release before the session.
* Reports disagree on Terence Tao’s role in the Association for Human Mathematics statement. One says he reposted it on his blog; others say he led it.
* None of the papers is reported to claim a Millennium Prize Problem. Some Riemann hypothesis claims are reported as still under scrutiny.
* This list was built from search results. The fetch tool could not reach the pages, so none of them has been read in full. The OpenAI repository, Aaronson’s blog post and Tao’s blog post are the primary sources to add once someone locates them.
* Discussion prompts to consider: who verifies 700 papers, what credit and authorship mean for unreleased models, whether Lean formalisation is sufficient, and what the response of the Association for Human Mathematics implies for researchers who use commercial AI.
