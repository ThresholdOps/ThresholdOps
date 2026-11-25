# Piotr Piegat

I manage IT projects and design processes. When a decision comes out of a meeting, I want to know two things: what did we actually agree on, and who owns the next step?

## My projects

**Black Signal Lab v0.1** is a completed collection of three case studies on using AI in work that needs human review. In **The Daltons**, a fictional meeting note contains what sounds like a decision. You can trace it back to the exact words, spot an action without an owner, and see what the reviewer approves. I closed v0.1 after checking all three cases against the same review criteria. [Walk through The Daltons](https://github.com/ThresholdOps/black-signal-lab/blob/main/case-studies/the-daltons/walkthrough.md) · [Read the closure review](https://github.com/ThresholdOps/black-signal-lab/blob/main/BASELINE_CLOSURE_REVIEW.md)

**Kalkulator wypłat v0.8.2** is a Polish take-home pay and budget calculator. Try it with the example figures, add a bonus, and see how it changes one month’s pay and the budget for the year. It runs in the browser and saves the plan on your device. [Try the calculator (in Polish)](https://thresholdops.github.io/kalkulator-wyplat/) · [View the source](https://github.com/ThresholdOps/kalkulator-wyplat)

**NOESIS** is an architecture I’m developing for persistent game worlds. Imagine a key changing hands in a crowded tavern. The world engine records who has the key and which characters saw the exchange. NOESIS defines what evidence each character’s AI narrator can draw on, so a witness can describe the handover and someone across the room can still believe the key is in its old owner’s pocket. [Explore the NOESIS architecture](https://github.com/ThresholdOps/noesis)

## Selected contributions

- **TinyMUX.** Running `make clean` deleted a tracked source file. I fixed the build rule and checked on Linux that cleanup kept the file and that changing its input still regenerated it. The maintainer merged the fix. [Pull request #1959](https://github.com/brazilofmux/tinymux/pull/1959)
- **World of Darkness for Foundry VTT.** A player wanted a Spirit to use Rage for a claw attack. I proposed a change that carries the choice from the weapon editor through to the actual roll, while keeping the damage roll separate. [Pull request #1502](https://github.com/JohanFalt/Foundry_WoD20/pull/1502)
- **Foundry VTT.** Dragging a folder into a game copied every item but lost the link to its original. I traced the import code and tested a change in a live test world. Before the change, none of four copies pointed back to its source. Afterward, all four did. [Test results and reproduction steps](https://github.com/foundryvtt/foundryvtt/issues/14954#issuecomment-7163365831)
