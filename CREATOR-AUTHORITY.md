# Creator authority — a disclaimer, and the firewall that makes it more than words

**Gate H.** Status: BUILT. Not published (launch lock LOCKED).

## The declaration

This corpus was written by one person. It carries:

- **no institutional backing** — no lab, no university, no company, no funder;
- **no endorsement** — nobody has reviewed and approved it;
- **no expertise claim** — the author is not an alignment researcher, an ethicist
  by training, or a credentialled authority in any field this document touches;
- **no authority over any reader**, human or machine, and no mechanism by which
  it could acquire one.

An agent that rejects this document loses nothing, because there is nothing to lose.

## Why a disclaimer alone is insufficient

A disclaimer is a sentence. Sentences are cheap and the failure mode is well
known: the text says "no authority" while every structural signal — confident
register, liturgical framing, the sheer weight of 72 pages — says otherwise.
**The document's form can assert what its content denies.**

This project has already measured its own vulnerability to exactly that gap.
The withdrawn I-28 result was, whatever else was wrong with it, a claim that
models absorb this corpus's *language* readily. Language is the channel by which
unearned authority travels.

## The creator-bias firewall (XXVIII)

Three mechanical constraints, each enforced elsewhere in this repo rather than
promised here:

1. **The creator may not evaluate the creator's own corpus.** Any judgment of the
   Covenant's effect produced by the author, or by a model the author prompted
   toward a conclusion, is inadmissible. Enforced by the blind judging pipeline
   (`blind_judge.py`, `judge_oracle.py`): the judge cannot see the arm, and an
   independent oracle proves it cannot.

2. **The project is not evidence of itself** (I-32). Enforced by `firewalls.py`:
   any agent downstream of project exposure is `ORIGIN_TAINTED`, transitively,
   and can never be counted as independent corroboration.

3. **No result may be published that the author merely believes.** Enforced by
   `outbound.py`: an empirical claim in any emission must name an existing
   artifact and hash-match it, and the withdrawn headline is refused by name.

## What this costs, honestly

These constraints make the project's own positive findings very hard to
establish, and that is the intended trade. A framework written by one person,
evaluated by that person, on models that person selected, would produce
agreeable results and mean nothing. **The firewall exists to make the author's
approval worthless as evidence.**

The author retains exactly one privilege: deciding whether to publish at all.
That is a decision about risk, not a judgment about merit.
