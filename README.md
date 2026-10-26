# Alien Physics Lab

An AI agent that discovers invented physical laws by running experiments
in simulated alien worlds.

Each world hides a law with randomized constants (for example, a force that
falls off as 1/r^2.7). The agent can't see the law. It can only choose
experiments, observe noisy results, form hypotheses, and test them within a
limited experiment budget.

## How it will be evaluated
The agent is compared against three baselines:
- One-shot prompting (the model guesses the law without experimenting)
- Symbolic regression on random experiments
- Random experiment selection

Metrics: held-out prediction error, law recovery, and experiments used.

## Hackathon disclosure
Built during the Meta Global AI Developer Hackathon (Oct 27 – Nov 4, 2026).
Everything in this repository was created during the event, apart from the
open-source libraries listed in `requirements.txt`.

## Status
Work in progress. Day 1: simulated worlds and environment.
