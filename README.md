# Arsh

I build and review software, with a focus on **evaluating AI systems and making them reliable**. I work with AI coding agents: I specify, review and test; the agents draft a lot of the code. Where something is hand-written or agent-written, I try to say so in the repo.

## What I've been working on

- **[AfterThought](https://github.com/dnarsh/AfterThought)**: a local evidence workspace that scores research answers against explicit rules and explores a real fruit-fly neuron-metadata snapshot. It checks structure, not truth, and the README says so. 64 tests, CI on every push.
- **[deep-research-bench](https://github.com/dnarsh/deep-research-bench)**: a small, dependency-free framework for scoring deep-research answers (regex, citation and length checks).
- **[einsteins-jump](https://github.com/dnarsh/einsteins-jump)**: a pre-registered notebook that tried to test whether AI judges can tell novelty from recombination. It ended with an honest negative result, which I published.
- **[racefree-filelock](https://github.com/dnarsh/racefree-filelock)** and **[evergreen-watchdog](https://github.com/dnarsh/evergreen-watchdog)**: a cross-process lock that fixes a check-then-write race, and a supervisor for long-running jobs.

## Team work

I contribute to an open team repo, [OctoKon/Splyce](https://github.com/OctoKon/Splyce): 21 pull requests authored (18 merged) and 22 formal reviews, mostly security and fail-closed fixes. Counts as of October 2026.

## What I'm working on getting better at

Computer-science and statistics fundamentals. Several of my past experiments used small samples (n = 6 and n = 10) and I'm replacing those habits with proper confidence intervals. I'm also learning to write core algorithms by hand instead of only reviewing them.

## How I try to work

- State what a project does **not** do.
- Publish negative results.
- Review changes against the exact commit, and run the tests.
