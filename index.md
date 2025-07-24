---
layout: default
title: Home
---

## My Research

I develop techniques and tools to improve the trustworthiness and reliability of software and cyber-physical systems. I am particularly interested in finding ways to test "hard to test" systems, with long execution times, non-determinism, limited state observability, and large input / output spaces. 

My research has been funded by the EPSRC (CITCOM, REGI, and STAMINA projects), InnovateUK, DSTL, and the DfT.

I am currently joint PC-chair for the [International Conference on Software Testing (ICST'26)](https://conf.researchr.org/home/icst-2026). I am an associate editor for the [Journal of Automated Software Engineering](https://link.springer.com/journal/10515).

My research publications can be found on [Google Scholar](https://scholar.google.com/citations?hl=en&user=Qa8zO1EAAAAJ&view_op=list_works&sortby=pubdate). Some key publications are highlighted below.

### Causal Software Engineering

My research explores techniques to support testing in traditionally difficult domains, such as complex input spaces, 
            cyber-physical systems, and systems with long execution times. Much of my recent research has focused on the application of
            Causal Inference to test causal relationships between inputs and outputs in scientific software models (funded by the EPSRC CITCOM project).
            I have written up more details on this work in the [CITCOM project page](citcom.md).

### State Machine Inference and Analysis

I have a longstanding interest in techniques that help to understand the sequential behaviour of systems when a prior model is unavailable. Key contributions in this area include:

- Extended Finite State Machine (EFSM) inference — a technique to infer state machines with guards ([Journal of Empirical Software Engineering, 2016](https://link.springer.com/article/10.1007/s10664-015-9367-7)) and full computational EFSMs with state transition functions ([ICSME'16](https://eprints.whiterose.ac.uk/127869/1/ICSME2016FinalSubmission.pdf)).
- LTSDiff — an algorithm to graphically compare two state machines ([ACM Transactions on Software Engineering Methodology, 2013](https://www.cs.le.ac.uk/people/nwalkinshaw/Files/tosem2012.pdf)).
- Subjective Opinion State Machines — a generalisation of Probabilistic State Machines using Subjective Logic to model second-order uncertainty, improving accuracy in inferred state machines ([IEEE Transactions on Software Engineering, 2023](https://eprints.whiterose.ac.uk/196630/14/Subjective_Logic_State_Machines.pdf)).

### Second-order uncertainty in Software Engineering

Second-order uncertainty is concerned with quantifying the (un-)certainty surrounding a probability. This arises in many Software Engineering contexts - if not in most contexts where probabilistic reasoning takes place. There are various uncertainty logics out there that provide ways of reasoning about probabilities in this way. My initial forays into this area used an approach called Evidential Reasoning. I then adopted Subjective Logic, because it is more flexible and expressive. Anything you can do with a conventional probability can be extended to Subjective Logic, and thus incorporate second-order uncertainties. Key works in this area include:

- Using Evidential Reasoning to quantify second order uncertainty in Safety Arguments [ISSRE'15](https://figshare.le.ac.uk/articles/conference_contribution/An_Evidential_Reasoning_Approach_for_Assessing_Confidence_in_Safety_Evidence/10129847/1/files/18256145.pdf)
- Using Subjective Logic to reason about uncertainty in Empirical Software Engineering experiments [EASE'20](https://eprints.whiterose.ac.uk/156832/1/EASE2020_Uncertainty.pdf)
- The work mentioned above of using Subjective Logic to reason about uncertainty in state machines ([IEEE Transactions on Software Engineering, 2023](https://eprints.whiterose.ac.uk/196630/14/Subjective_Logic_State_Machines.pdf)).

---

## Teaching and Administration

### Teaching

I am very fortunate to teach topics that are proximate to my research interests. My current topics include:

- Software Reengineering (COM3523 / COM6523): A joint undergraduate and masters module, teaching students how to understand and re-engineer unfamiliar, legacy software systems. Delighted to be jointly teaching this with Donghwan Shin.
- The Computer Science Ambassadors module: A smaller 3rd year undergraduate module. This involves our 3rd year students engaging with local schools, to try to support and improve their Computer Science provision, with a view towards making Computer Science more inclusive. This is led by my colleague Andy Charlesworth.

### Administration

I am currently the school lead on inclusion in Computer Science. In a nutshell, this has a focus on attracting more diverse cohorts of students into Computer Science. This is a partial objective of the Computer Science Ambassador's module described above. We are also a node in the BCS Levelling Up scheme, where several of our undergraduate students tutor groups of school children to achieve the Maths A-Level (a key entry requirement for most Computer Science courses).

