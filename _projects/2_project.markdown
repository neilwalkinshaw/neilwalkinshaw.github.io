---
layout: page
title: (E)FSM Inference
description: Inferring state based software models.
img: /assets/img/process-small.png
---
State-based models of software behaviour can be very useful. There are many testing and verification approaches that can take advantage of such models. Unfortunately, they require a lot of knowledge and skill to develop by hand, and are rarely (if ever) included in real software development projects.

This project has been ongoing since 2006, and aims to develop techniques that are capable of reverse-engineering state machines from sequences of observed events. This is achieved by adapting and enhancing standard state machine inference (or regular grammar inference) Machine Learning techniques.

In recent years this has involved the development of state machines that have guards (Extended Finite State Machines), and even limited state transition computations, with the help of Genetic Programming.

This work has, over the past decade, involved collaborations with Kirill Bogdanov, John Derrick, Shaukat Ali, Sarah Salahuddin, Mike Holcombe, Ken Johnson, Ramsay Taylor and Mat Hall at the University of Sheffield, Tom Gransden at Leicester, as well as Pierre Dupont, Bernard Lambeau, and Christophe Damas at the University Catholique de Louvain.

<div class="img_row">
    <img class="col two left" src="{{ site.baseurl }}/assets/img/process-small.png" alt="" title="Screen shot 1"/>
</div>

### Software

Implementations of the various state machine inference approaches [are available](https://github.com/neilwalkinshaw/mintframework){:target="\_blank"} as part of the Mint Framework via Github. It is licensed under the 3-clause BSD license (because it includes WEKA, which is GPL-3).

### Funding

* October 2012 – May 2013 BATS (Building Adequate Test Sets by Reverse Engineering, DSTL.
* July 2009 – June 2012	StaMInA (A Novel Competition to Drive the Comparative Evaluation of State Machines), EPSRC
* April 2009 – September 2012 REGI (Reverse Engineering State Machines by Grammar 	Inference), EPSRC

### Publications

Go to my Publications page for links to PDF copies of the papers.

* Improving Automated GUI Testing by Learning to Avoid Infeasible Tests Walkinshaw, Neil In Proceedings of the Second IEEE International Conference on Artificial Intelligence Testing (AITEST’20) 2020
* Inferring extended finite state machine models from software executions Walkinshaw, Neil, Taylor, Ramsay, and Derrick, John Empirical Software Engineering 2016
* Inferring computational state machine models from program executions Walkinshaw, Neil, and Hall, Mathew In Software Maintenance and Evolution (ICSME), 2016 IEEE International Conference on 2016
* SEPIA: search for proofs using inferred automata Gransden, Thomas, Walkinshaw, Neil, and Raman, Rajeev In International Conference on Automated Deduction 2015
* Mining state-based models from proof corpora Gransden, Thomas, Walkinshaw, Neil, and Raman, Rajeev 2014
* STAMINA: a competition to encourage the development and assessment of software model inference techniques Walkinshaw, Neil, Lambeau, Bernard, Damas, Christophe, Bogdanov, Kirill, and Dupont, Pierre Empirical software engineering 2013
* Automated comparison of state-based software models in terms of their language and structure Walkinshaw, Neil, and Bogdanov, Kirill ACM Transactions on Software Engineering and Methodology (TOSEM) 2013
* Adapting grammar inference techniques to mine state machines Walkinshaw, Neil, and Bogdanov, Kirill Mining Software Specifications: Methodologies and Applicationss, Chapman & Hall/CRC Data Mining and Knowledge Discovery Series 2011
* Superstate identification for state machines using search-based clustering Hall, Mathew, McMinn, Phil, and Walkinshaw, Neil In Proceedings of the 12th annual conference on Genetic and evolutionary computation 2010
* A framework for the competitive evaluation of model inference techniques Walkinshaw, Neil, Bogdanov, Kirill, Damas, Christophe, Lambeau, Bernard, and Dupont, Pierre In Proceedings of the First International Workshop on Model Inference In Testing 2010
* Computing the structural difference between state-based models Bogdanov, Kirill, and Walkinshaw, Neil In Reverse Engineering, 2009. WCRE’09. 16th Working Conference on 2009
* Inferring finite-state models with temporal constraints Walkinshaw, Neil, and Bogdanov, Kirill In Proceedings of the 2008 23rd IEEE/ACM International Conference on Automated Software Engineering 2008
* Improving dynamic software analysis by applying grammar inference principles * Walkinshaw, Neil, Bogdanov, Kirill, Holcombe, Mike, and Salahuddin, Sarah Journal of Software Maintenance and Evolution: Research and Practice 2008
* Automated discovery of state transitions and their functions in source code Walkinshaw, Neil, Bogdanov, Kirill, Ali, Shaukat, and Holcombe, Mike Software Testing, Verification and Reliability 2008
* Evaluation and comparison of inferred regular grammars Walkinshaw, Neil, Bogdanov, Kirill, and Johnson, Ken Grammatical Inference: Algorithms and Applications 2008
* Reverse engineering state machines by interactive grammar inference Walkinshaw, Neil, Bogdanov, Kirill, Holcombe, Mike, and Salahuddin, Sarah In Reverse Engineering, 2007. WCRE 2007. 14th Working Conference on 2007
* Applying grammar inference principles to dynamic analysis Walkinshaw, Neil, and Bogdanov, Kirill Program Comprehension through Dynamic Analysis 2007
* Identifying state transitions and their functions in source code Walkinshaw, Neil, Bogdanov, Kirill, and Holcombe, Mike In Testing: Academic and Industrial Conference-Practice And Research Techniques, 2006. TAIC PART 2006. Proceedings 2006
