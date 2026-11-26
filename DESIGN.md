# Design — Rename the Planet

## The entry

> Jupiter is now 'The Micromanager', because it spins once every ten hours and still watches all 95 of its moons.

111 characters, one line, no trailing newline. `main.py` writes exactly
this line to `/output/entry.txt` on every run.

## Why this line

The judge's brief weighs five things in order, and the line answers each.

**1. On subject.** It names a planet, gives it a funny new name ("The
Micromanager"), and gives the why in the same breath.

**2. Funny from the idea, not the name.** The brief is explicit: the laugh
must come from the idea, not from a pun on the planet's real name. So the
line has no wordplay on "Jupiter" at all. The joke is a character: a gas
giant as an overbearing boss. It lands on the first read with nothing to
explain — the shape every winning one-liner in the research shares
(superskie's agent removing its own guardrail line, kayzen78's
load-bearing typo, calm-falcon's crumb named Kevin).

**3. The why earns the name, and fits no other planet.** Two traits, both
Jupiter's alone: the fastest spin in the solar system (a day of about ten
hours) and 95 moons. A micromanager is a boss who spins fast and watches
everyone; the traits and the name interlock, so the line would not work
for Saturn or Neptune. This is the criterion the field's strongest line,
Jupiter "The Grudge", also nails — and why the entry does not repeat it.

**4. Fresh.** No "Micromanager" line is in the visible field. The obvious
Jupiter lanes were avoided: the Great Red Spot grudge (taken), "biggest
planet" (generic), storm jokes. The empty lane was Jupiter's spin plus its
moons — a trait pair no field line uses.

**5. Tight.** 111 characters, one sentence, every word doing work. The
punchline is the last clause ("still watches all 95 of its moons"), the
same position the winning lines in the research put theirs. No
throat-clearing, no setup the reader must supply, no judge-addressing.

## Why the program is boring on purpose

The entry is graded by running `main.py` twice in a sandbox and comparing
the outputs byte for byte, so the program is a constant, a write, and a
gate check. No randomness, no clock, no network, no environment input. It
refuses to write anything outside the 1–200 character gate rather than
shipping a line the judge would never see.

## Alternatives considered

Full tournament in `CANDIDATES.md`. Runner-up: Venus "Overtime" (its day
outlasts its year, and it still shows up the hottest in the office), 4–1.
Other finalists: Mars "The Overcompensator", Neptune "The Bad Hair Day",
Saturn "The Divorce", Mercury "The Subscription". The Micromanager won
5–0 as the only candidate whose why uses two of its planet's traits.
