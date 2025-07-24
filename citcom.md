---
layout: default
title: Causal Inference for Testing Computational Models (CITCOM)
---

<img src="/assets/logo.png" alt="CITCOM logo" style="max-width: 150px; border-radius: 50%;" />

Computational models can be hard to test. They have large input spaces (often hundreds of parameters). A single execution can take hours days. They can be inherently non-deterministic. Thus, running large numbers of carefully controlled tests is not feasible. Furthermore, given that they are often used to explore behaviours of unfamiliar phenomena, there may be a lack of certainty around what constitutes a "correct" output.
        
Causal Inference offers promising solutions to these problems. It provides a framework to enable some lightweight domain-knowledge into the analysis process. This can enable the tester to answer questions about the (causal) relationships between inputs (or parameters) and outputs. These can be answered without the need for large numbers of controlled tests. 

This work has been funded by the EPSRC (CITCOM grant - 2020-2025)
        
## Research Contributions

The CITCOM project runs from 2020-2025. The core conceptual contributions are listed and linked to their relevant papers here. A more complete bibliography is provided below.

- [To show how causal tests can be characterised as a specific form of Metamorphic relationship. (ICST'23)](https://eprints.whiterose.ac.uk/195317/1/CITCOM_2022_ICST%20%284%29.pdf)
- [To enable metamorphic relationships to be established from test executions without the need to control inputs. (TOSEM'23)](https://dl.acm.org/doi/pdf/10.1145/3607184)
- [To provide a statistical test adequacy metric for causal test cases (ICST'24)](https://eprints.whiterose.ac.uk/208652/1/main.pdf)
- Illustrating how Causal Inference can test systems with hidden and interacting variables. (EASE'25 – awarded the best research paper award)
    
## Software: The CITCOM Causal Testing Framework
A tool implementing the CITCOM Causal Testing approach has been made available on GitHub under an MIT License.

- [CITCOM Causal Testing Framework GitHub Repository](https://github.com/CITCOM-project/CausalTestingFramework)
- [Accompanying link to Journal of Open Source Software paper (JOSS'25)](https://joss.theoj.org/papers/10.21105/joss.07739)

## Target Systems

Causal testing is quite a flexible approach and can be applied to a range of classes of systems. We are currently in a phase of the project where we are exploring its application to a range of types of systems. These include:
            
- Scientific software models (covered in our [TOSEM'23 paper](https://dl.acm.org/doi/pdf/10.1145/3607184))
  - The CovaSim COVID pandemic simulator. We showed how the effect of different Covid variants could be accurately established from uncontrolled data, despite the variation of a large number of parameters.
  - The Luo-Rudy Cardiac Action Potential model. We replicated a sensitivity analysis of the parameters, but without requiring large numbers of controlled inputs.
  - A Poisson Line Tessellation model. Highly stochastic behaviour makes this hard to test (using traditional techniques). We showed how this could be managed with causal techniques.

- Cyber-physical systems

  We have particularly focussed on Artificial Pancreas Systems. In these systems a diabetic user is fitted with a glucose-monitor, and an insulin pump. The dosage of insulin is moderated by a controller that monitors the glucose-levels. This presents an interesting testing challenge, because a lot of the behaviour depends on factors in the human body which cannot be controlled.

  Details on the testing problem itself and on a Digital Twin test harness to support testing this are available in Richard Somers' recent [STVR paper on the topic (STVR'25)](https://onlinelibrary.wiley.com/doi/pdf/10.1002/stvr.70000).

- Automated driving simulators

  Automated driving systems (ADSs) present a particular testing problem, because there are lots of factors that sit outside of control of the tester, and there are lots of hidden variables. We show how causal testing can be used to test ADSs in a forthcoming EASE'25 paper.