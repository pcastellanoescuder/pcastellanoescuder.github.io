---
title: The Last Human Input
subtitle: When AI can answer anything, the scarce skill is knowing what to ask.
date: July 2026
---

There is a particular kind of problem that used to define a career. You picked it early, you circled it for a decade, and if you were lucky and stubborn you cracked open one small corner of it before you were done. The problem was hard, and its hardness was the whole point: it sorted the people who could from the people who couldn't, and it made expertise scarce enough to be worth something.

That kind of problem is about to become a prompt.

Not all of them, not tomorrow, and not cleanly. But the direction is unmistakable. The cost of solving hard things is collapsing, and it is collapsing fast. Tasks that once demanded a team, a grant, and three years of somebody's life are compressing into an afternoon. The analysis that took a postdoc a summer now takes a query. Whole categories of difficulty are being demoted from *achievement* to *procedure*: from the thing you build a reputation on to the thing you simply invoke. The frontier of what counts as hard keeps receding, and it is not coming back.

This is the part of the essay where I am supposed to reassure you that humans remain essential. I will, but not in the way you are expecting, and not for the reasons that usually get offered. The comfortable version says we stay relevant because we bring creativity, or empathy, or some ineffable spark the machine lacks. I don't believe that version. It is sentimental, and worse, it is fragile: every year the machine does another thing we swore it never could, and the spark gets smaller.

The honest version is stranger and, I think, more durable. It is about optimization, about the variables nobody wrote down, and beneath them, about the one move an optimizer can never make for itself.

## What optimization actually does

An optimizer is only ever as good as its objective function. Give a system a goal (maximize this, minimize that) and it will search the space of possibilities for the best available answer *to the question you actually asked*. This is the source of all its power and all its blindness. The machine does not optimize reality. It optimizes the model of reality you handed it, over exactly the variables you chose to include.

Everything you left out simply does not exist to it.

This sounds like a limitation to be engineered away, and partly it is: you can always add more variables. But there is a deeper issue hiding underneath, and biology, of all things, is where I learned to see it. Because life has been running the largest optimization process on Earth for four billion years, and it does not find optimal solutions. It never has. It finds *viable* ones.

## The lesson of the fitness landscape

Evolution is an optimizer with no foresight and no eraser. It cannot leap to the global peak of fitness; it can only climb whatever hill it currently stands on, one small viable step at a time. The result is a living world full of designs that no engineer would sign off on. The vertebrate eye is wired backwards, its photoreceptors facing away from the light. The recurrent laryngeal nerve loops absurdly down around the aorta and back up, a detour of inches in you and of many feet in a giraffe. The panda's "thumb" is a repurposed wrist bone, a clumsy fix that works. None of these is optimal. All of them are viable, given everything else that had already been decided.

That phrase, *given everything else*, is the entire argument.

Consider sickle cell. On its own, the allele looks like a straightforward defect: it deforms red blood cells, it causes suffering, it kills. Any optimizer minimizing disease burden would delete it without hesitation. But add one variable to the objective function, malaria, and the picture inverts. The same allele that harms in two copies protects in one, and in regions where malaria is endemic it is not a defect at all. It is a solution. The "suboptimal" choice was optimal the entire time; we just weren't counting the variable that made it so.

This is not a quirk of genetics. It is the general shape of the thing. **Optimality is always conditional on which variables you decide to count.** Change the set of variables and the optimum moves. The machine that finds the perfect answer has not found the perfect answer: it has found the perfect answer to a particular, bounded, radically simplified question, and it has no way of knowing what got left off the list. You can always hand it more of the list (another variable, another constraint) and it will keep getting better at the question you gave it. What it cannot do is choose which question that should be. Counting is its job. Deciding what counts was never on the table.

## Taste is not a preference. It is a compression.

Now bring this back to the thing I actually want to defend, which is human judgment, and the word I keep resisting, *taste*.

We tend to treat taste as the soft stuff. The garnish on top of the real work. Someone runs the numbers, finds the optimal answer, and then a human comes along and says *no, I don't like it*, and we file that under irrationality or ego or aesthetics. The machine was right; the human was being difficult.

I want to propose the opposite. When a person looks at the mathematically optimal solution and feels, against all the evidence, that it is *wrong*, that reaction is not noise. It is very often an objective function with hidden variables, running in a body, arriving at a verdict it cannot fully explain because the terms were never written down. The human is not failing to optimize. The human is optimizing over a far richer space than the one the machine was given: metabolic cost, social risk, disgust, status, memory, the felt weight of consequences, a few million years of priors about what tends to go wrong. We call the output "taste" because we have no access to the calculation. But there is a calculation.

Our palate is the cleanest proof of this. Bitterness aversion is not an arbitrary preference: it is an evolved poison detector, a classifier trained on every ancestor who tried the wrong berry and left no descendants. Sweetness, fat, salt: each preference is a compressed heuristic about survival, a variable folded so deep into the body that it arrives as a *feeling* rather than a thought. When you say a food is "not to your taste," you are running an objective function with terms in it that predate language. The optimum-for-a-spreadsheet (nutritionally perfect, maximally efficient) loses to the meal that moves you, and it loses for a *reason*, even when you can't name it.

But the same example cuts the other way. The palate tuned to a world of scarce sugar now craves the thing that kills us; the detector that once saved an ancestor from a bitter berry nags at me to finish a dessert I would be better off leaving. The calculation is real, and it is also, often, out of date. An evolved variable is not automatically a true one: it is a bet placed by an environment that may no longer exist. The feeling carries information. It cannot certify its own worth.

So when human preference diverges from the machine's optimum, there are only two possibilities. Either the human is genuinely in error (and this happens, and we should say so) or the human is carrying a variable the model never had. The hard part, the part that matters, is telling those two cases apart. That discrimination is the actual work of the coming era. Not computing the answer. Deciding which variables belong in the question.

## The move that complicates everything

I have to confront the strongest objection to my own argument, because it is real, and because dodging it would be exactly the kind of comfortable thinking I said I distrusted.

In 2016, in a Go match watched by millions, a machine played a move, the thirty-seventh of the second game, that every human expert initially read as a mistake. It violated centuries of accumulated taste about how the game is properly played. It looked ugly. And it was *better*. It won, and in winning it revealed that human taste about Go had been, in that instance, simply too small: a local optimum that generations of masters had mistaken for the peak. The machine's alien judgment was the truer one, and the humans came to admire it.

This is the counterexample to everything I have said, and I want to sit inside it rather than wave it off. Sometimes the "irrational" human preference is not a hidden variable at all. Sometimes it is just a wall: a limit of imagination we have decorated with the word *taste* to make it feel principled. The machine can be right and the whole tradition can be wrong, and no amount of appeal to embodied wisdom changes that.

So the argument cannot be that human taste is always the deeper truth. That would be a comforting lie, and Move 37 is its refutation.

The argument is narrower and, I think, harder to kill. It is this: *deciding which of the two cases you are in is not itself an optimization.* When the machine's answer offends your judgment, no calculation can tell you whether you are the master carrying an unwritten variable or the tradition about to be humbled. That call is a value judgment. The reason it stays ours is not that the machine is too weak to make it. Give it enough data and it may one day predict which ugly answers the experts will come to bless. The reason is deeper. What a problem is *for*, and what counts as success, are not facts about the world waiting to be computed. They are stances toward it: claims about what we want. And the machine wants nothing. It can search any space you define; it has no stake in which space is worth searching. That choice is upstream of optimization, and it is ours, not because we are smarter, but because we are the ones for whom the outcome matters, and someone with a stake in it has to say what we are optimizing for.

There is a sharper version of this objection, and it comes from the people who build these systems. Teaching a machine the objective is exactly what the field is now trying to do. Reinforcement learning from human feedback, reward modeling, inverse reinforcement learning: the whole program is to watch what people choose and infer the function behind it, hidden variables and all. The moat is closing, the argument goes. Even the objective will be learned.

Learned from whom, though. Every one of these methods is parasitic on us: it recovers the preferences we already have, it does not originate them. And it recovers what we *do* want, never what we *should*. That gap is not a shortage of data. It is the oldest wall in philosophy: you cannot derive an ought from an is, and no amount of watching us choose can tell the machine whether we are choosing well. So even a perfect preference-learner does not settle what to value. It only pushes the question back a step: *whose* preferences, and whether those are worth having. And there it hands the choice back to us, because it was never the one to answer it.

## What this looks like from where I sit

I build tools that do exactly what this essay describes. At Heureka we compress research that used to take months into days: hypothesis to analysis to manuscript, the whole arc, run through AI agents against empirical data. I have watched the tool surface a pattern across datasets that no human would have had the time or breadth to see. The acceleration is not theoretical to me. It is the product.

And here is what I have learned watching scientists use it. The tool is extraordinary at finding what is optimal *in the data it was given*. What it cannot do, in the moment, is know what the data left out. A target can be statistically pristine and biologically hopeless: untractable, toxic in ways the assay never measured, sitting in a pathway that behaves nothing like the model assumes. The experienced biologist rejects it, and if you ask why, the first answer is often just *it doesn't feel right*. That feeling is not mysticism. It is a lifetime of toxicity intuition and pathway context and hard-won failure, compressed into a verdict the researcher cannot fully unpack in the moment. It is a hidden variable, exactly as advertised.

But be careful how much weight that carries. The variable is hidden only until someone measures it. Feed the tool the toxicity data and the pathway context, and it will fold them in and out-judge the biologist on that axis too. That edge is real, and it is borrowed: it lasts exactly as long as the data stays uncollected.

But sometimes that same feeling is just conservatism. Sometimes the target that offends the biologist's taste is the Move 37, and the whole field's intuition is the wall. The tool's job is to surface the candidate anyway. The scientist's job is to make the call. And the *quality* of that call, the ability to tell a real hidden variable from a mere failure of nerve, is now the scarcest and most valuable thing a researcher owns. It is the one part of the work the acceleration makes *more* important, not less.

And underneath even that call sits the one the tool will never make, no matter how much data it is fed: not whether the target is real, but whether it is the one worth chasing, given everything the program is trying to become. The machine ranks the candidates. It cannot tell you what the search is for.

## The last input

Here is the double meaning I have been walking toward.

*The last human input* reads, at first, as an ending: the extraordinary things are still waiting on the other side of the right question, and the cost of asking is falling toward zero. Anyone can invoke the machine now. The hard problems are lining up to become procedures, and our share of the work shrinks with them.

But there is a second reading, and it is the one I mean. The one input the optimizer cannot generate for itself is the choice of what to optimize for. The machine will answer any question you pose, brilliantly, at a scale no human can match, but it will not tell you which question is worth posing, or which of its brilliant answers is worth wanting. Those choices are not the machine's to make. They are made of preference, and constraint, and the willingness to look at a perfectly optimal solution and say *not that one*, and then to know, with a judgment that is itself the whole game, whether you are seeing a variable the machine missed or a wall you have not yet climbed.

That judgment is not a consolation prize for being outmatched at arithmetic. It is the actual seat of leadership in a world where answers are cheap and the only scarcity left is knowing what to ask, and what to want, and what to count.

The machine will optimize whatever function we hand it. Deciding what belongs in the function: that was always the human part. It still is.

The last human input is not the answer. Someone still has to have the taste to ask.
