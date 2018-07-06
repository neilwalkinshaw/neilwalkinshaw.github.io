---
layout: page
title: Semi-Automated Software Remodularisation
description: Efficiently reorganising files within a software system to minimise disruption.
img: /assets/img/lattice.png
---
As software evolves, its module structure can deteriorate. Given such a system, it can be challenging to find an appropriate package structure. Although several automated approaches have been proposed, they tend to be too disruptive, and often fail to make sense from a domain perspective.

This project has been a collaboration with Mat Hall and Phil McMinn at the University of Sheffield, as well as Ali Khojaye, who worked on this as an MSc. student when I was at Leicester.

Our SUMO tool reads the current package of a structure and interacts with the user to enable them to indicate which files do and do not belong into the same module. In doing so it will continuously suggest improved modularisations.

<div class="img_row">
    <img class="col one left" src="{{ site.baseurl }}/assets/img/sumo-shot2.png" alt="" title="Screen shot 1" width="200px"/>
    <img class="col one left" src="{{ site.baseurl }}/assets/img/sumoui.png" alt="" title="Screen shot 2" width="200px"/>
    <img class="col one left" src="{{ site.baseurl }}/assets/img/lattice.png" alt="" title="Lattice" width="200px"/>
</div>

### Software

An implementation of the SUMO tool [is available](https://bitbucket.org/mathew_hall/sumo){:target="\_blank"} via Bitbucket. It is licensed under the 3-clause BSD license.

### Publications

Go to my Publications page for links to PDF copies of the papers.

* Effectively incorporating expert knowledge in automated software remodularisation Hall, Mathew, Walkinshaw, Neil, and McMinn, Phil,
IEEE Transactions on Software Engineering, 2018
* Establishing the source code disruption caused by automated remodularisation tools Hall, Mathew, Khojaye, Muhammad Ali, Walkinshaw, Neil, and McMinn, Phil,
International Conference on Software Maintenance and Evolution (ICSME) ESR track, 2014
* Supervised software modularisation Hall, Mathew, Walkinshaw, Neil, and McMinn, Phil,
International Conference on Software Maintenance (ICSM'12)
