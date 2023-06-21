---
layout: page
title: Projects
permalink: /projects/
description:
---

I am interested in several aspects of Software Engineering. I am particularly interested in devising ways to explore, test and re-engineer software systems. Much of my work is concerned with systems that pose particular problems - poorly documented legacy systems, black-box components, or resource-intensive processes that take a long time to execute and are hard to control.

A list of my main research themes is listed below (they are broadly in order of recent activity). I'm happy to discuss any of these topics, please feel free to get in touch. If I haven't published in an area for a while, it won't be because I have lost interest in it! I post some links to research papers below, but please see my publications page for a full list of publications.

## Causal inference for software testing

Causal Inference describes a family of statistical techniques that can establish causal relationships between events. They are powerful because they can, with the appropriate guidance, offer a way to work around the criticism of traditional associational statistics, that `correlation does not imply causation'. These techniques offer lots of potential in the context of software testing (e.g. to establish definitively that a particular input configuration causes a particular output, or to reliably establish the cause of a bug).

On this project, we are currently particularly interested in focussing on the challenge of testing computational models and digital twins. 

This work is being carried out on the EPSRC-funded CITCOM project, with [Rob Hierons](https://robhierons.github.io/), [Michael Foster](http://staffwww.dcs.shef.ac.uk/people/M.Foster/), [Andy Clark](https://github.com/AndrewC19), and [Richard Somers](https://richardsomers.dev/) along with [Nick Latimer](https://www.sheffield.ac.uk/scharr/people/staff/nicholas-latimer) in the Sheffield School for Health and Related Research (ScHaRR) and [David Wagg](https://www.sheffield.ac.uk/mecheng/people/academic/david-wagg) in the department for Mechanical Engineering. 

### Software

* The [CITCOM Causal Testing Framework](https://github.com/CITCOM-project/CausalTestingFramework)

### Funding

* 2021-2024 - Causal Inference for Testing Computational Models (CITCoM), PI, funded by EPSRC 


## Reverse engineering and testing models of software behaviour

Model based software testing is nice in theory, but problematic in practice because the required models are rarely produced to begin with. With the rapid improvement of Machine Learning techniques, it has become possible to take a sample of program executions and to infer models from these. Once a model exists, this can in turn be used to `test' (or at least explore) the behaviour of the system under test, and so a virtuous cycle emerges.

This idea isn't mine (it was possibly Elaine Weyuker's, who [published the idea](https://dl.acm.org/doi/pdf/10.1145/69575.357231) in 1983). It does however raise some important challenges. How does one infer a useful model from sets of traces, perhaps some of which lead to failures (or turn out to be infeasible)? How does one select suitable test cases from an inferred model? Etc.

On the model inference front, much of this has focussed on approaches to infer state machines for reactive systems (e.g. for [testing GUIs](https://eprints.whiterose.ac.uk/157156/8/AITest_2020_paper_21__2_.pdf), or [network protocols](http://opendl.ifip-tc6.org/db/conf/pts/ictss2010/WalkinshawBDP10.pdf)). I have developed several inference techniques, for [finite state machines with guards (EFSMs)](https://link.springer.com/article/10.1007/s10664-015-9367-7), and [variants of those that also include complete transition functions](https://eprints.whiterose.ac.uk/127869/1/ICSME2016FinalSubmission.pdf), inferred using Genetic Programming.

It hasn't all revolved around state machines and reactive systems though. I've been interested in automatically [testing non-interactive black-box programs](https://leicester.figshare.com/articles/conference_contribution/Black-Box_Test_Generation_from_Inferred_Models/10170242) that constitute simpler functions that take a set of parameters and return a value. My Ph.D. student Tom Gransden at Leicester also investigated the use of this technology to [automate proofs in Coq](https://arxiv.org/pdf/1505.07987.pdf). 

Aside from the specific question of how to infer a model, there is also the broader question of how to pick useful test cases once a model has been inferred. It is in this context that, together with Gordon Fraser, I have been investigating [uncertainty (in its various forms) as a basis for driving test selection](https://arxiv.org/pdf/1608.03181.pdf) and assessing test adequacy.

### Funding

* October 2012 – May 2013 BATS (Building Adequate Test Sets by Reverse Engineering), PI, funded by DSTL.
* July 2009 – June 2012	StaMInA (A Novel Competition to Drive the Comparative Evaluation of State Machines), Researcher Co-investigator, funded by EPSRC
* April 2009 – September 2012 REGI (Reverse Engineering State Machines by Grammar Inference), Researcher Co-investigator, funded by EPSRC


## Uncertainty (or doubt, or ignorance) in Software Engineering

Software engineers are often uncertain about the software they are developing or maintaining. This is unavoidable for any non-trivial system. I am particularly interested in the challenge of quantifying, communicating and managing this uncertainty. 

My interest in this started in 2013 when I tried to develop techniques to support the assessment of software systems in terms of their quality or safety. This requires the assessor to ultimately arrive at some assessment (e.g. to state that some safety process has been diligently followed during the construction of the system).  Of course, these statements are often subject to some inherent uncertainty. To address this, I adopted an uncertainty-based reasoning technique known as Evidential Reasoning, first to reason about [software quality](https://leicester.figshare.com/articles/conference_contribution/Using_Evidential_Reasoning_to_Make_Qualified_Predictions_of_Software_Quality/10155845), then specifically to support [safety arguments for safety-critical systems](https://ieeexplore.ieee.org/stamp/stamp.jsp?arnumber=7381846).

Recently, I have taken an interest in using these techniques to capture and reason about uncertainty in the context of empirical software engineering. Together with [Martin Shepperd](https://www.brunel.ac.uk/people/martin-shepperd) this involved [the use of Subjective Logic to capture the uncertainty associated with (replications of) empirical studies, to systematically reason about the uncertainty associated with their conclusions](https://dl.acm.org/doi/abs/10.1145/3383219.3383234). Having found Subjective Logic an especially interesting framework, I am currently working on its use as a basis in the context of software testing.

### Funding

* 2016 - Evidential Reasoning for Radiological Detection, AWE (PI)
* 2016 - Trustworthiness Level Determination and Aggregation for Operation of Autonomous Vehicles, DSTL ASUR programme (PI for Leicester), joint with Qinetiq and Fraser Nash Consulting
* 2015 - EVIRE (An Evidence-Driven Reasoning Framework to Support the Transparent Control, Verification, and Validation of 	Autonomous Systems), DSTL ASUR programme (PI for Leicester).
