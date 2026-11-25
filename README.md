# Piotr Piegat

I manage IT projects and design processes. When a decision comes out of a meeting, I want to know two things: what did we actually agree on, and who owns the next step?

## Process governance in practice

**The Daltons** is a worked example from my Black Signal Lab. It starts with a fictional meeting note. You can follow one apparent decision back to the words that support it, see where an action has no owner, and check what a human reviewer approves before the summary goes out. [Walk through the example](https://github.com/ThresholdOps/black-signal-lab/blob/main/case-studies/the-daltons/walkthrough.md)

## Selected contributions

- **TinyMUX.** Running `make clean` deleted a tracked source file. I fixed the build rule and checked on Linux that cleanup kept the file and that changing its input still regenerated it. The maintainer merged the fix. [Pull request #1959](https://github.com/brazilofmux/tinymux/pull/1959)
- **World of Darkness for Foundry VTT.** A player wanted a Spirit to use Rage for a claw attack. I proposed a change that carries the choice from the weapon editor through to the actual roll, while keeping the damage roll separate. [Pull request #1502](https://github.com/JohanFalt/Foundry_WoD20/pull/1502)
- **Foundry VTT.** Dragging a folder into a game copied every item but lost the link to its original. I traced the import code and tested a change in a live test world. Before the change, none of four copies pointed back to its source. Afterward, all four did. [Test results and reproduction steps](https://github.com/foundryvtt/foundryvtt/issues/14954#issuecomment-7163365831)
