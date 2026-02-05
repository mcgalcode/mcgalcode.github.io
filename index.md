---
layout: homepage
---

## About Me

I'm a PhD student in the Materials Science Department at University of California, Berkeley. My research is performed at Lawrence Berkeley National Laboratory, where I work on simulation development for advancing synthesis recipe design for solid-state materials. In my free time, I try to spend as much time outside as possible - on most days that means running on our wonderful trails in Tilden and Strawberry Canyon. I also love reading, playing piano, traveling around California, and going to the climbing gym.

## Research Interests

- **Solid-state Synthesis:** precursor selection, thermodynamics, kinetics, defects
- **Simulation Design:** chemical reaction networks, cellular automata, lattice modeling
- **First Principles Calculations:** density functional theory, molecular dynamics
- **Machine Learning:** materials discovery via informatics, machine learning potentials

## News

- **[Feb. 2026]** I am awarded the UC Berkeley Department of Materials Science "Didier de Fontaine Student Award in Theory and Computation"
- **[Oct. 2025]** Our paper on a novel synthesis method for high-entropy alloy nanoparticles is published in _Nature_
- **[Oct. 2025]** Our python package for composite designed is published in _JOSS_
- **[June. 2025]** I spend the month in Linkoping, SE investigating the behavior of silica melts under high pressure
- **[July. 2025]** The second version of our computational materials science workflow software, `atomate2` is published in _Digital Discovery_
- **[Jan. 2025]** I start an AI PhD Residency at (Google) X, the moonshot factory
- **[Dec. 2024]** Our paper presenting a database of AIMD trajectories for amorphous configurations is published in _npj Computational Materials_
- **[Dec. 2024]** I am awarded the Kavli ENSI Graduate Student Fellowship
- **[Nov. 2024]** ReactCA solid-state simulation paper published in _Chemistry of Materials_
- **[July. 2024]** Pre-print of my paper about simulation solid-state synthesis uploaded to the arXiv.
- **[Feb. 2024]** My paper on my lattice simulation software, pylattica, is accepted by the Journal of Open Source Software!

<h2 id="publications">Selected Publications</h2>

<p>
See all publications <a href="/publications">here!</a>
</p>
<div class="publications">
<ol class="bibliography">

{% for link in site.data.publications.main %}
{% if link.selected %} 

{% include single_publication.md pub=link %}

<br>
{% endif %}
{% endfor %}

</ol>
</div>

{% include_relative _includes/services.md %}
