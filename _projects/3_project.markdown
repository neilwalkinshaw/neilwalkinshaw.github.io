---
layout: page
title: Evidence-Based Reasoning
description: Decisions from uncertain data.
img: /assets/img/dodgyTruck.png
---
There are often situations in which it is necessary to arrive at some decision or assessment, even though the underlying evidence is uncertain or partial. This project has developed structured reasoning techniques that can accommodate this sort of information.

My interest in this area started in 2013, with the particular challenge of how to determine the "quality" of a software system when there are several factors (intrinsic to our characterisation of quality) that we simply cannot know about.

My work on this area is underpinned by Dempster-Shafer theory; the idea that you can reason probabilistically about beliefs, but without the Bayesian constraint that all of the probabilities have to sum to 1. In other words, there can be some beliefs for which you simply do not know the underlying probability, and this absence of knowledge is in and of itself quantified and explicitly factored into any subsequent reasoning.

My initial work on this area used a Dempster-Shafer based analysis technique called [Evidential Reasoning](https://ieeexplore.ieee.org/abstract/document/259681), which fed into a tool-set that was used as the basis for a technique to assess software quality (PROMISE 2013), a collaboration with Sunil Nair, Tim Kelly, and José de Vara to assess safety-arguments for safety-critical systems (SRS'14 and ISSRE'15), and some small funded projects involving [AWE](http://www.awe.co.uk/){:target="\_blank"}, [DSTL](https://www.gov.uk/government/organisations/defence-science-and-technology-laboratory){:target="\_blank"}, [Fraser-Nash Consulting](https://www.fnc.co.uk/){:target="\_blank"} and [Qinetiq](https://www.qinetiq.com/){:target="\_blank"} to develop more reliable information in sensing environments and with respect to autonomous vehicle communications (e.g. to accommodate sensor failures or data blackouts).

Since then I have moved on to using a different Dempster-Shafer based reasoning technique - [Subjective Logic](https://en.wikipedia.org/wiki/Subjective_logic). This is more flexible and allows evidential beliefs (or non-evidential beliefs) to be expressed and combined more flexibly. Together with Martin Shepperd we have looked at applying this approach to reason about uncertainty with respect to Empirical Software Engineering results (EASE'20).

<div class="img_row">
    <img class="col two left" src="{{ site.baseurl }}/assets/img/dodgyTruck.png" alt="" title="Screen shot 1"/>  <img class="col two right" src="{{ site.baseurl }}/assets/img/fusedPlot1.png" alt="" title="SL-fused"/>
</div>


### Funding

* 2016 - Evidential Reasoning for Radiological Detection,  AWE
* 2016 - Trustworthiness Level Determination and Aggregation for Operation of Autonomous Vehicles, DSTL ASUR programme, 	joint with Qinetiq and Fraser Nash Consulting
* 2015 - EVIRE (An Evidence-Driven Reasoning Framework to Support the Transparent Control, Verification, and Validation of 	Autonomous Systems), DSTL ASUR programme.


### Publications

Go to my Publications page for links to PDF copies of the papers.

* Reasoning about Uncertainty in Empirical Results, Walkinshaw, Neil, and Shepperd, Martin, In Proceedings of the 24th International Conference on Empirical Software Engineering (EASE’20) 2020
* An evidential reasoning approach for assessing confidence in safety evidence Nair, Sunil, Walkinshaw, Neil, Kelly, Tim, and Vara, Jose Luis In Software Reliability Engineering (ISSRE), 2015
* Quantifying Uncertainty in Safety Cases Using Evidential Reasoning Nair, Sunil, Walkinshaw, Neil, and Kelly, Tim In International Conference on Computer Safety, Reliability, and Security 2014
* Using evidential reasoning to make qualified predictions of software quality
 Walkinshaw, Neil In Proceedings of the 9th International Conference on Predictive Models in Software Engineering 2013 (PROMISE'13)
