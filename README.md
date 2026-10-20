# "Window on Time": a startup case from problem to pitch

A one-day startup sprint (team of four) on a learning case: a corporate client wants CO₂
sensors with dashboards in 42 meeting rooms to fight stuffy air. The team's job was to
**check whether that is really the problem and what to build instead**: interviews, survey,
market sizing, solution choice, business model, a working prototype and a 3-minute pitch.
Documents are in Russian; the field data (6 interviews, a 230-person survey, market notes) is
synthetic course material and is not included.

## The result in one paragraph

The client's idea (a CO₂ dashboard) is **not supported by the data**: 71 % say a display would be
good, but only 22 % ever open the company portal (78 % visit it once a month or less) – people
are not short of numbers, they are short of a *moment*: meetings are back-to-back with five
minutes between them, opening a window during a meeting causes drafts, and nobody owns
ventilation. The proposed product, **"Window on Time"**, reads the room's CO₂ and the meeting
calendar and, one minute before the meeting ends, messages the organiser in the work messenger:
*"Baikal – please air the room"*; the organiser answers "Done". Subscription: 115 ₽ per room per
month (4,830 ₽/month for the client's 42 rooms). Unit economics: CAC ≈ 28,000 ₽, LTV ≈ 59,000 ₽
(ratio 2.1), explicitly flagged as assumptions to be validated by a pilot.

## What is in the repository

```
docs/problem.md                        pain hunting: interviews, observations, hidden assumption of the client
docs/research.md                       user portrait, empathy map, competitors, TAM / SAM / SOM
docs/solution_and_business_model.md   ideas (HMW, Crazy 8s, SCAMPER), value proposition, Lean Canvas, unit economics
docs/prototype.md, prototype_prompts.md   prototype route, scenario, system prompt and five test messages
assets/prototype/                      screenshots of the prototype dialogue (AI agent built in a no-code studio)
pitch/deck.pdf                         8-slide pitch deck
pitch/script.md                        3-minute script with timing, speaker split and answers to hard questions
```

## My part

Team role: **Visionary** – focus on the problem, strategy, value proposition and the pitch script
(solution & business model, pitch). The other roles were researcher (interviews, survey, empathy
map), prototype architect, and economist (market size, unit economics).

## Method notes

- Every claim carries a source marker – *(interview 3)*, *(survey, q. 5)* – and everything that is
  **not** in the data is labelled *(assumption)*; the pitch answers "where does this number come from?"
  with exactly that distinction.
- Honest gaps, stated in the documents: no corridor test with outside users has been run yet and
  no timed pitch rehearsal was recorded.
- Context: a team assignment from the School 21 (Moscow) intensive. Team member names were removed
  from the documents and from the last slide of the deck.
