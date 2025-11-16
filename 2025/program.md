---
layout: template
title: Program
menu: true
---

*Preliminary program which is still subject to potential changes*

Each technical paper presentation is scheduled for 20 minutes, where 5 minutes are supposed to be reserved for QA and setup.

<br/>

#### Monday, Nov 24, 2025

<br/>

##### 12:50-13:00 &emsp; Welcome

<br/>

##### 13:00-14:00 &emsp; Invited Talk by [Johannes Fürnkranz](https://www.jku.at/en/institute-for-application-oriented-knowledge-processing/about-us/team/johannes-fuernkranz/)

**Towards Deep and Interpretable Rule Learning** \
Inductive rule learning is concerned with the learning of classification rules from data. Learned rules are inherently interpretable and easy to implement, so they are very suitable for formulating learned models in many domains. Nevertheless, current rule learning algorithms have several shortcomings. First, with respect to the current praxis of equating high interpretability with low complexity, we argue that while shorter rules are important for discrimination, longer rules are often more interpretable than shorter rules, and that the tendency of current rule learning algorithms to strive for short and concise rules should be replaced with alternative methods that allow for longer concept descriptions. Second, we think that the main impediment of current rule learning algorithms is that they are not able to learn deeply structured rule sets, unlike the successful deep learning techniques. Both points are currently under investigation in our group, and we will illustrate our progress with some results.

<br/>

##### 14:00-15:30 &emsp; Technical Session

Globally Interpretable Classifiers via Boolean Formulas with Dynamic Propositions \
_Reijo Jaakkola, Tomi Janhunen, Antti Kuusisto, Masood Feyzbakhsh Rankooh_

Bayesian Hyperparameter Optimization with ALASPO (Extended Abstract) \
_Dave Pfliegler, Tobias Geibinger, Thomas Eiter_

Answer-Set-Programming-based Abstractions for Reinforcement Learning \
_Rafael Bankosegger, Thomas Eiter, Johannes Oetsch_

viasp: A visualization tool for Answer Set Programming (Extended Abstract) \
_Javier Romero, Torsten Schaub, Stephan Zwicknagl, Luis Glaser_


<br/>

##### 15:30-16:00 &emsp; Break

<br/>

##### 16:00-17:00 &emsp; Tutorial by Giuseppe Mazzotta

**Tackling Grounding Bottleneck through Compilation-Based ASP Solving** \
The success of Answer Set Programming (ASP) arises from its highly expressive declarative language capable of modeling complex combinatorial problems and from the availability of efficient solvers that make ASP a practical tool for real-world applications.
However, standard ASP systems based on the Ground & Solve paradigm suffer from an intrinsic limitation known as the grounding bottleneck. To overcome this limitation, compilation-based ASP solving has been recently proposed and has proven to be very effective in tackling the grounding bottleneck problem. \
In this tutorial, we will provide an overview of compilation-based ASP solving, so that attendees will gain a comprehensive understanding of this technique and its potential for efficiently evaluating ASP programs. We first recall the standard methodology adopted by state-of-the-art ASP systems, highlighting both its strengths and limitations. Then, we present the main idea behind compilation-based ASP solving, which consists of compiling logical rules into dedicated propagators. Finally, we introduce ProASP, the first compilation-based ASP solver, discussing its internal working principles and illustrating how it enables the integration of the Ground & Solve and compilation-based approaches into a unified framework, capable of constructing problem-specific solvers tailored to the requirements of a given ASP program.

<br/>

##### 17:00-18:30 &emsp; Technical Session

Incremental Lazy Grounding (Work in Progress) \
_Sebastian Adam, Thomas Eiter_

Automated Hybrid Grounding Using Structural and Data-Driven Heuristics (Extended Abstract) \
_Alexander Beiser, Markus Hecher, Stefan Woltran_

Many-sorted Bound Founded Logic of Here-and-There: Work in Progress \
_Pedro Cabalar, Jorge Fandinno, Nicolas Rühling, Torsten Schaub, Sebastian Schellhorn, Philipp Wanko_

CompLogDL and its Implementation in Answer Set Programming (Extended Abstract) \
_Lucrezia Mosconi, Johannes Peter Wallner_

<br/>

##### 19:00-22:00 &emsp; Social Dinner at Gasthaus Buchecker & Sohn 

<br/>
<br/>

#### Tuesday, Nov 25, 2025

<br/>

##### 09:00-10:00 &emsp; Invited Talk by [Katsumi Inoue](https://researchmap.jp/vivre/?lang=en)

**Towards end-to-end ASP computation** \
We propose an end-to-end approach for Answer Set Programming (ASP) and linear algebraically compute stable models satisfying given constraints.  The idea is to implement Lin-Zhao’s theorem together with constraints directly in vector spaces as numerical minimization of a cost function constructed from a matricized normal logic program, loop formulas in Lin-Zhao’s theorem and constraints, thereby no use of symbolic ASP or SAT solvers involved in our approach.  We also propose precomputation that shrinks the program size and heuristics for loop formulas to reduce computational difficulty.  We empirically test our approach with programming examples including the 3-coloring and Hamiltonian cycle problems. \
This is joint work with Taisuke Sato and Akihiro Takemura, and is to appear in Neurosymbolic Artificial Intelligence.

<br/>

##### 10:00-10:30 &emsp; Break

<br/>

##### 10:30-12:30 &emsp; Technical Session

Formalizing ASP-based Product Configuration: Work in Progress \
_Nicolas Rühling, Torsten Schaub, Philipp Wanko_

Preliminary Report: Improving Suboptimal Reduction-based Approaches for Multi-agent Pathfinding \
_Klaus Strauch_

A CASP-based Solution for Traffic Signal Optimisation - Extended Abstract \
_Alice Tarzariol, Marco Maratea, Mauro Vallati_

Reasoning over student-related study regulations hard and soft constraints in ASP \
_Henry Otunuya_

Solving Energy-Aware Double-Flexible Job Shop Scheduling with CP and ASP modulo CSP \
_Francesco Zuccato, Patrick Rodler, Gerhard Friedrich, Konstantin Schekotihin, Giray Havur, Richard Comploi-Taupe_

Investigating the Grounding Bottleneck for a Large-Scale Configuration Problem: Existing Tools and Constraint-Aware Guessing \
_Veronika Semmelrock, Gerhard Friedrich_

<br/>

##### 12:30-14:00 &emsp; Lunch Break

<br/>

##### 14:00-16:00 &emsp; Technical Session

Simple Guess-and-Check Programs: Strong and Uniform Equivalence Meet Again \
_Wolfgang Dvořák, Zeynep G. Saribatur, Stefan Woltran_

On Strong Equivalence Notions in Logic Programming and Abstract Argumentation \
_Giovanni Buraglio, Wolfgang Dvořák, Stefan Woltran_

ANTHEM 2.0: Automated Reasoning for Answer Set Programming (Extended Abstract) \
_Jorge Fandinno, Christoph Glinzer, Zachary Hansen, Jan Heuer, Yuliya Lierler, Vladimir Lifschitz, Torsten Schaub, Tobias Stolzmann_

Logic-based Languages For Solving Reversibility in Planning \
_Wolfgang Faber, Michael Morak_

An Argumentation Calculus for Equilibrium Logic \
_Tobias Geibinger, Thomas Eiter_

Effect of Abstraction on Understandability of ASP Explanations: Work in Progress \
_Zeynep G. Saribatur, Johannes Langer_


<br/>

##### 16:00-16:30 &emsp; Break

<br/>

##### 16:30-17:30 &emsp; Technical Session

Comparing SLTL<sup>x</sup>-based Synthesis and ASP for the Automated Composition of Data Analysis Workflows \
_Nikolas Bertrand, Mario Frank, Anna-Lena Lamprecht_

Towards Temporal Answer Set Programming with Preferences (Extended Abstract) \
_Javier Romero, Torsten Schaub, Hannah Mathilde Steinbach_

Brief Temporal Equilibrium Logic \
_Pedro Cabalar, Thomas Eiter, David Pearce, Davide Soldà_

<br/>

##### 17:30-17:40 &emsp; Closing

<br/>

