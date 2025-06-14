# Note
This repo is cloned from https://github.com/PatrickMassot/GlimpseOfLean/tree/master.

# A glimpse of Lean

This repository is an introduction to theorem proving in Lean for the impatient.
The goal is to get a feel for what proving in Lean looks like in 2 or 3 hours,
or maybe devote half a day or a full day.

There are two tracks. Both start with reading the `Introduction.lean` file.

Then the short track continues in the `Shorter.lean` file which is meant to give
you access to not completely empty mathematical proofs in two hours if you are
ready to move pretty fast.

If you have a bit more time, you should instead read explanations and do
exercises in the `Basics` folder, and then choose to work on one file from the
`Topics` folder. Of course, you can play with all files from that folder if you
have even more time.

To work using Lean, you either have to install Lean locally, or use a lean4web
server, or use Codespaces or use Gitpod.

## Online version, no registration

If you don’t want to install Lean and don’t want to create an account on any
website, you can use the [lean4web server](https://live.lean-lang.org/) hosted by the [Lean FRO](https://lean-fro.org/) as follows:

* read [the introduction file](https://live.lean-lang.org/#project=GlimpseOfLean&url=https%3A%2F%2Fraw.githubusercontent.com%2FPatrickMassot%2FGlimpseOfLean%2Frefs%2Fheads%2Fmaster%2FGlimpseOfLean%2FIntroduction.lean)
* then read and edit the [explanations and exercises file](https://live.lean-lang.org/#project=GlimpseOfLean&url=https%3A%2F%2Fraw.githubusercontent.com%2FPatrickMassot%2FGlimpseOfLean%2Frefs%2Fheads%2Fmaster%2FGlimpseOfLean%2FExercises%2FShorter.lean) of the shorter track.

If you want to do the longer track then the relevant links are:
* [01Rewriting](https://live.lean-lang.org/#project=GlimpseOfLean&url=https%3A%2F%2Fraw.githubusercontent.com%2FPatrickMassot%2FGlimpseOfLean%2Frefs%2Fheads%2Fmaster%2FGlimpseOfLean%2FExercises%2F01Rewriting.lean)
* [02Iff](https://live.lean-lang.org/#project=GlimpseOfLean&url=https%3A%2F%2Fraw.githubusercontent.com%2FPatrickMassot%2FGlimpseOfLean%2Frefs%2Fheads%2Fmaster%2FGlimpseOfLean%2FExercises%2F02Iff.lean)
* [03Forall](https://live.lean-lang.org/#project=GlimpseOfLean&url=https%3A%2F%2Fraw.githubusercontent.com%2FPatrickMassot%2FGlimpseOfLean%2Frefs%2Fheads%2Fmaster%2FGlimpseOfLean%2FExercises%2F03Forall.lean)
* [04Exists](https://live.lean-lang.org/#project=GlimpseOfLean&url=https%3A%2F%2Fraw.githubusercontent.com%2FPatrickMassot%2FGlimpseOfLean%2Frefs%2Fheads%2Fmaster%2FGlimpseOfLean%2FExercises%2F04Exists.lean)

for the basics. And then you can choose depending on your mathematical
interests:
* [SequenceLimits](https://live.lean-lang.org/#project=GlimpseOfLean&url=https%3A%2F%2Fraw.githubusercontent.com%2FPatrickMassot%2FGlimpseOfLean%2Frefs%2Fheads%2Fmaster%2FGlimpseOfLean%2FExercises%2FTopics%2FSequenceLimits.lean) for elementary properties of sequences of real numbers.
* [RingTheory](https://live.lean-lang.org/#project=GlimpseOfLean&url=https%3A%2F%2Fraw.githubusercontent.com%2FPatrickMassot%2FGlimpseOfLean%2Frefs%2Fheads%2Fmaster%2FGlimpseOfLean%2FExercises%2FTopics%2FRingTheory.lean) for some commutative algebra, up to the Chinese remainder theorem in commutatives rings.
* [Probability](https://live.lean-lang.org/#project=GlimpseOfLean&url=https%3A%2F%2Fraw.githubusercontent.com%2FPatrickMassot%2FGlimpseOfLean%2Frefs%2Fheads%2Fmaster%2FGlimpseOfLean%2FExercises%2FTopics%2FProbability.lean) for some probability theory.

* [GaloisAdjunctions](https://live.lean-lang.org/#project=GlimpseOfLean&url=https%3A%2F%2Fraw.githubusercontent.com%2FPatrickMassot%2FGlimpseOfLean%2Frefs%2Fheads%2Fmaster%2FGlimpseOfLean%2FExercises%2FTopics%2FGaloisAdjunctions.lean) for some elementary abstract non-sense (adjunctions between ordered sets with applications to group theory and topology).

* [ClassicalPropositionalLogic](https://live.lean-lang.org/#project=GlimpseOfLean&url=https%3A%2F%2Fraw.githubusercontent.com%2FPatrickMassot%2FGlimpseOfLean%2Frefs%2Fheads%2Fmaster%2FGlimpseOfLean%2FExercises%2FTopics%2FClassicalPropositionalLogic.lean) for some mathematical logic in a classical setting.
* [IntuitionisticPropositionalLogic](https://live.lean-lang.org/#project=GlimpseOfLean&url=https%3A%2F%2Fraw.githubusercontent.com%2FPatrickMassot%2FGlimpseOfLean%2Frefs%2Fheads%2Fmaster%2FGlimpseOfLean%2FExercises%2FTopics%2FIntuitionisticPropositionalLogic.lean) for some mathematical logic in an intuitionistic setting (don’t try this if you don’t know about the use of Heyting algebras in intuitionistic logic).

You can refer to the [tactics cheatsheet](tactics.pdf) while doing the
exercises. Tactics are explained in the Lean file, but the pdf can be more
convenient as a reference.

## Online version, with registration

There are also websites that are a bit more comfortable but require
creating a [GitHub](www.github.com) account.

* To use codespaces, make sure you’re logged in to GitHub, click the button below, select `4-core`, and then press `Create codespace`. After a few minutes an editor with Lean working will open in your browser.

    [![Open in GitHub Codespaces](https://github.com/codespaces/badge.svg)](https://codespaces.new/PatrickMassot/GlimpseOfLean)

* Gitpod is very similar to Codespaces, click the button below, press `Continue` and wait a few minutes.

    [![Open in Gitpod](https://gitpod.io/button/open-in-gitpod.svg)](https://gitpod.io/#https://github.com/PatrickMassot/GlimpseOfLean)

## Local installation

If you want the full luxury Lean experience, you should install it on your
computer.

For this you can follow the instructions [here](https://leanprover-community.github.io/get_started.html).

If you have a lot more time, you should read the book [Mathematics in Lean](https://leanprover-community.github.io/mathematics_in_lean/).
