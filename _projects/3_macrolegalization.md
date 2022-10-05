---
layout: page
title: Macro Legalization
description: A constraint-graph based algorithm flow which combines iterative refinement and simulated annealing to solve the macro legalization problem.
img: assets/img/projects/macro_layout.png
importance: 5
category: EDA
---

To read the full paper, please visit <a href="https://kevinchang73.github.io/assets/pdf/macro.pdf">here</a>. For the source code, please visit the <a href="https://github.com/kevinchang73/2021Spring_PD_Final_Project">Github repo</a>.

This is the final project report of Physical Design for Nanometer ICs (Spring 2021). Macro legalization is an important step in today’s placement flow. In this work, a constraint-graph based macro legalization algorithm flow which combines iterative refinement and simulated annealing is applied to solve the macro legalization problem. Experimental result shows the flow could achieve a balance between cost and runtime.

<div class="row justify-content-md-center">
    <div class="col-sm-6 mt-3 mt-md-0">
        {% include figure.html path="assets/img/projects/macro_flow.jpg" title="macro_flow" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    Our algorithm flow.
</div>

<div class="row">
    <div class="col-sm-3 mt-3 mt-md-0">
        {% include figure.html path="assets/img/projects/macro_initial_placement.jpg" title="macro_initial_placement" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm-9 mt-3 mt-md-0">
        {% include figure.html path="assets/img/projects/macro_hcg.jpg" title="macro_hcg" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    An example of our constraint graph.
</div>

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/projects/macro_layout.png" title="macro_layout" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    An example layout of legalized placement. Left: initial placement. Right: output solution.
</div>
