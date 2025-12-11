---
layout: template
title: Program
menu: true
---

Each technical paper presentation is scheduled for 20 minutes, where 5 minutes are supposed to be reserved for QA and setup.

<br/>

#### Monday, Nov 24, 2025

Room: [TU Wien Main Building, Ground floor, Sitzungszimmer AD EG](https://maps.tuwien.ac.at/?q=ADEG19)

<br/>

##### 13:30-13:40 &emsp; Welcome

<br/>

##### 13:40-14:40 &emsp; Invited Talk by [Johannes Fürnkranz](https://www.jku.at/en/institute-for-application-oriented-knowledge-processing/about-us/team/johannes-fuernkranz/)

**[Towards Deep and Interpretable Rule Learning](assets/invited_talk_fuernkranz.pdf)** \
Inductive rule learning is concerned with the learning of classification rules from data. Learned rules are inherently interpretable and easy to implement, so they are very suitable for formulating learned models in many domains. Nevertheless, current rule learning algorithms have several shortcomings. First, with respect to the current praxis of equating high interpretability with low complexity, we argue that while shorter rules are important for discrimination, longer rules are often more interpretable than shorter rules, and that the tendency of current rule learning algorithms to strive for short and concise rules should be replaced with alternative methods that allow for longer concept descriptions. Second, we think that the main impediment of current rule learning algorithms is that they are not able to learn deeply structured rule sets, unlike the successful deep learning techniques. Both points are currently under investigation in our group, and we will illustrate our progress with some results.

<br/>

##### 14:40-15:40 &emsp; Technical Session

[Effect of Abstraction on Understandability of ASP Explanations: Work in Progress](/assets/paper/4_Effect_of_Abstraction_on_Und.pdf) \
_Zeynep G. Saribatur, Johannes Langer, Ute Schmid_

[Globally Interpretable Classifiers via Boolean Formulas with Dynamic Propositions](/assets/paper/24_Globally_Interpretable_Clas.pdf) \
_Reijo Jaakkola, Tomi Janhunen, Antti Kuusisto, Masood Feyzbakhsh Rankooh_


[Answer-Set-Programming-based Abstractions for Reinforcement Learning](/assets/paper/10_Answer_Set_Programming_base.pdf) \
_Rafael Bankosegger, Thomas Eiter, Johannes Oetsch_


<br/>

##### 15:40-16:10 &emsp; Break

<br/>

##### 16:10-17:10 &emsp; Tutorial by Giuseppe Mazzotta

**Tackling Grounding Bottleneck through Compilation-Based ASP Solving** \
The success of Answer Set Programming (ASP) arises from its highly expressive declarative language capable of modeling complex combinatorial problems and from the availability of efficient solvers that make ASP a practical tool for real-world applications.
However, standard ASP systems based on the Ground & Solve paradigm suffer from an intrinsic limitation known as the grounding bottleneck. To overcome this limitation, compilation-based ASP solving has been recently proposed and has proven to be very effective in tackling the grounding bottleneck problem. \
In this tutorial, we will provide an overview of compilation-based ASP solving, so that attendees will gain a comprehensive understanding of this technique and its potential for efficiently evaluating ASP programs. We first recall the standard methodology adopted by state-of-the-art ASP systems, highlighting both its strengths and limitations. Then, we present the main idea behind compilation-based ASP solving, which consists of compiling logical rules into dedicated propagators. Finally, we introduce ProASP, the first compilation-based ASP solver, discussing its internal working principles and illustrating how it enables the integration of the Ground & Solve and compilation-based approaches into a unified framework, capable of constructing problem-specific solvers tailored to the requirements of a given ASP program.

<br/>

##### 17:10-18:40 &emsp; Technical Session

[Incremental Lazy Grounding (Work in Progress)](/assets/paper/3_Incremental_Lazy_Grounding_W.pdf) \
_Sebastian Adam, Thomas Eiter_

[Automated Hybrid Grounding Using Structural and Data-Driven Heuristics (Extended Abstract)](/assets/paper/6_Automated_Hybrid_Grounding_U.pdf) \
_Alexander Beiser, Markus Hecher, Stefan Woltran_

[Many-sorted Bound Founded Logic of Here-and-There: Work in Progress](/assets/paper/2_Many_sorted_Bound_Founded_Lo.pdf) \
_Pedro Cabalar, Jorge Fandinno, Nicolas Rühling, Torsten Schaub, Sebastian Schellhorn, Philipp Wanko_

[CompLogDL and its Implementation in Answer Set Programming (Extended Abstract)](/assets/paper/14_CompLogDL_and_its_Implement.pdf) \
_Lucrezia Mosconi, Johannes Peter Wallner_

<br/>

##### 19:00-22:00 &emsp; Social Dinner at [Salm Bräu](https://salmbraeu.com/en/salm-braeu/) 

<br/>
<br/>

#### Tuesday, Nov 25, 2025

Room:\
[TU Wien Theresianumgasse, 1. Floor, HS 1](https://maps.tuwien.ac.at/?q=QA0101) (09:00 - 12:30) \
[TU Wien EI Building, 1. Floor, Seminarraum 363](https://maps.tuwien.ac.at/?q=CA0138) (14:00 - 17:40)


<br/>

##### 09:00-10:00 &emsp; Invited Talk by [Katsumi Inoue](https://researchmap.jp/vivre/?lang=en)

**[Towards end-to-end ASP computation](assets/invited_talk_inoue.pdf)** \
We propose an end-to-end approach for Answer Set Programming (ASP) and linear algebraically compute stable models satisfying given constraints.  The idea is to implement Lin-Zhao’s theorem together with constraints directly in vector spaces as numerical minimization of a cost function constructed from a matricized normal logic program, loop formulas in Lin-Zhao’s theorem and constraints, thereby no use of symbolic ASP or SAT solvers involved in our approach.  We also propose precomputation that shrinks the program size and heuristics for loop formulas to reduce computational difficulty.  We empirically test our approach with programming examples including the 3-coloring and Hamiltonian cycle problems. \
This is joint work with Taisuke Sato and Akihiro Takemura, and is to appear in Neurosymbolic Artificial Intelligence.

<br/>

##### 10:00-10:30 &emsp; Break

<br/>

##### 10:30-12:30 &emsp; Technical Session

[Formalizing ASP-based Product Configuration: Work in Progress](/assets/paper/1_Formalizing_ASP_based_Produc.pdf) \
_Nicolas Rühling, Torsten Schaub, Philipp Wanko_

[Preliminary Report: Improving Suboptimal Reduction-based Approaches for Multi-agent Pathfinding](/assets/paper/7_Preliminary_Report_Improving.pdf) \
_Klaus Strauch_

[A CASP-based Solution for Traffic Signal Optimisation - Extended Abstract](/assets/paper/11_A_CASP_based_Solution_for_T.pdf) \
_Alice Tarzariol, Marco Maratea, Mauro Vallati_

[Reasoning over student-related study regulations hard and soft constraints in ASP](/assets/paper/15_Reasoning_over_student_rela.pdf) \
_Henry Otunuya_

[Solving Energy-Aware Double-Flexible Job Shop Scheduling with CP and ASP modulo CSP](/assets/paper/22_Solving_Energy_Aware_Double.pdf) \
_Francesco Zuccato, Patrick Rodler, Gerhard Friedrich, Konstantin Schekotihin, Giray Havur, Richard Comploi-Taupe_

[Investigating the Grounding Bottleneck for a Large-Scale Configuration Problem: Existing Tools and Constraint-Aware Guessing](/assets/paper/21_Investigating_the_Grounding.pdf) \
_Veronika Semmelrock, Gerhard Friedrich_

<br/>

##### 12:30-14:00 &emsp; Lunch Break

<br/>

##### 14:00-16:00 &emsp; Technical Session

[Simple Guess-and-Check Programs: Strong and Uniform Equivalence Meet Again](/assets/paper/16_Simple_Guess_and_Check_Prog.pdf) \
_Wolfgang Dvořák, Zeynep G. Saribatur, Stefan Woltran_

[On Strong Equivalence Notions in Logic Programming and Abstract Argumentation](/assets/paper/18_On_Strong_Equivalence_Notio.pdf) \
_Giovanni Buraglio, Wolfgang Dvořák, Stefan Woltran_

[An Argumentation Calculus for Equilibrium Logic](/assets/paper/23_An_Argumentation_Calculus_f.pdf) \
_Tobias Geibinger, Thomas Eiter_

[Bayesian Hyperparameter Optimization with ALASPO (Extended Abstract)](/assets/paper/5_Bayesian_Hyperparameter_Opti.pdf) \
_Dave Pfliegler, Tobias Geibinger, Thomas Eiter_

[viasp: A visualization tool for Answer Set Programming (Extended Abstract)](/assets/paper/13_viasp_A_visualization_tool_.pdf) \
_Javier Romero, Torsten Schaub, Stephan Zwicknagl, Luis Glaser_

[Logic-based Languages For Solving Reversibility in Planning](/assets/paper/19_Logic_based_Languages_For_S.pdf) \
_Wolfgang Faber, Michael Morak_

<br/>

##### 16:00-16:30 &emsp; Break

<br/>

##### 16:30-17:30 &emsp; Technical Session

[Comparing SLTL<sup>x</sup>-based Synthesis and ASP for the Automated Composition of Data Analysis Workflows (Extended Abstract)](/assets/paper/20_Comparing_SLTL_x_based_Synt.pdf) \
_Nikolas Bertrand, Mario Frank, Anna-Lena Lamprecht_

[Towards Temporal Answer Set Programming with Preferences (Extended Abstract)](/assets/paper/12_Towards_Temporal_Answer_Set.pdf) \
_Javier Romero, Torsten Schaub, Hannah Mathilde Steinbach_

[Brief Temporal Equilibrium Logic](/assets/paper/8_Brief_Temporal_Equilibrium_L.pdf) \
_Pedro Cabalar, Thomas Eiter, David Pearce, Davide Soldà_

<br/>

##### 17:30-17:40 &emsp; Closing

<br/>

