---
name: the-question-way
description: >-
  Use to make viewers watch a video to the end by structuring it as a chain of open and closed
  loops (questions). Run when the user says "people drop off halfway," "keep viewers watching,"
  "retention is bad," "open loops," "plot points," "how do I keep them to the end," or shares a
  retention graph with a cliff. Maps every question the script opens and closes, finds the
  moments where all loops are closed (the drop-off points), and rewrites so the next question
  is open before the current one is answered: two-question hooks, the twist that turns an
  obvious answer into a new question, the problem-creates-a-bigger-problem chain, real stakes,
  and an ending where the last loop closes on the CTA. Works on talking heads, tests, tutorials,
  and long form. For the opening line alone use hook-writer; for writing the full script use
  short-form-video-script; for on-camera delivery use talking-head-and-piece-to-camera.
metadata:
  version: 1.0.0
license: MIT
---

# The Question Way

A video is a chain of questions. The hook opens the first one, which is only level zero.
Viewers keep watching while a question they care about is open, and they start leaving **the
second it is answered with nothing else open.** Retention is not won in the first three
seconds; it is won at every point where a loop closes.

Two ideas run through everything here:

1. **Never let every loop close before the end.** Open the next question before the current
   one is answered, or in the same breath. Each answer should leave the viewer feeling progress
   (value delivered) but not finished.
2. **Loops must be honest.** Every question opened gets answered in this video, or is openly
   handed to the next episode. A loop that is never closed is bait, and the bounce that follows
   costs more than the watch time it bought.

## Step 0 — Read the foundation first

Load `brand-profile.md` and `voice.md` if they exist; the loops are spoken in the brand's
voice. Get the script, outline, or transcript the user wants to fix. If there is a retention
graph, ask for the drop-off timestamps (measurement: the platforms' native analytics).

## Step 1 — Map the loops

List every question the video opens, where it opens, and where it closes, using the loop map
in `references/recipes-and-templates.md`. Mark every **dead zone**: a stretch where all loops
are closed. Those are the predicted drop-off points. If a retention graph exists, line its
drops up with the closures; each cliff should sit on a loop that closed with nothing behind it.

## Step 2 — Fix the hook: two loops, one instant payoff

Open two questions in the hook and **answer the first one immediately.** The fast answer proves
the video is worth the time; the second question holds them. See the hook pattern in
`references/the-question-way-framework.md`.

## Step 3 — Chain the body

Rewrite each section with the tools in the framework file:

- **Twist the obvious answer** ("but it's not what you think," "but this is where everyone gets
  it wrong") so the explanation becomes a new question instead of a repeat.
- **Problem → solution → bigger problem:** each solution exposes the next, larger question.
- **Stakes:** a time limit, a cost, a risk. Small, everyday stakes work. They must be true
  for anything presented as real (tests, results, reviews).
- **Open the next loop before closing the current one** wherever the map shows a dead zone.

## Step 4 — Land the ending

Close the last loop and put the CTA in that same second, or leave one clearly-flagged loop
open as the reason to watch the next episode. Nothing after the final answer but the CTA.

## Step 5 — Hand over the plan

Deliver the rewritten script with the loop map under it, the dead zones it removed, and the
timestamps to check on the retention graph after publishing.

## Honest scope (never violate)

- The agent cannot see footage or analytics; it works from the script, transcript, and the
  numbers the user reads off native analytics.
- **Never invent stakes, results, or "proof" for content presented as real.** Fiction is fine
  only when the viewer can tell it's a skit.
- Never leave a loop unanswered without telling the viewer where the answer is.
- Creator claims about how algorithms reward retention are claims, not facts; treat any figure
  as **verify-quarterly**.

## Where this connects

- `hook-writer` — the opening line itself (this skill decides which two questions it opens).
- `short-form-video-script` — the full script; run this skill on its draft.
- `talking-head-and-piece-to-camera` — delivering the chain on camera.
- `youtube-long-form` — long-form packaging and retention; the same loops apply per chapter.
- `analytics-and-reporting` — reading the retention data that this skill diagnoses.

## Reference files

- `references/scope-and-connections.md` — what this skill owns and where it hands off.
- `references/the-question-way-framework.md` — the method, tool by tool.
- `references/creator-video-notes.md` — the source videos (Ross, with Reckless Ben), what they say and do.
- `references/recipes-and-templates.md` — loop map, hook patterns, chain recipes, review checklist.

## Definition of done

A script where every stretch has at least one open question until the final answer, the hook
opens two loops and pays the first, every loop opened is closed (or handed to the next
episode out loud), stakes are true, and the CTA lands on the last closure.
