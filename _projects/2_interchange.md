---
layout: page
title: Graph-based Interchange Management
description: A graph-based approach to manage the traffic near highway interchanges.
img: assets/img/projects/inter_change_point.jpg
importance: 5
category: CPS
---

To read the full paper, please visit <a href="https://kevinchang73.github.io/assets/pdf/interchange.pdf">here</a>. For the source code, please visit the <a href="https://github.com/kevinchang73/2021Fall_IntroVehicles_Final_Project">Github repo</a>.

The areas near interchanges are often the most congested parts of a highway. In this work, we formulate the interchange management problem as an scheduling, decision-making, and optimization problem. We convert the problem onto the graph domain and adopt simulated annealing to optimize. Experimental result shows that our algorithm outperforms the first-come-first-serve strategy in terms of the total time required for all the vehicles passing the interchange area.

<div class="row">
    <div class="col-sm-5 mt-3 mt-md-0">
        {% include figure.html path="assets/img/projects/inter_lane_changing.jpg" title="inter_lane_changing" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm-7 mt-3 mt-md-0">
        {% include figure.html path="assets/img/projects/inter_discrete_points.jpg" title="inter_discrete_point" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    The interchange management problem. Left: the interchange management scenario. Right: add discrete points and convert to a discrete problem.
</div>

<div class="row justify-content-md-center">
    <div class="col-sm-8 mt-3 mt-md-0">
        {% include figure.html path="assets/img/projects/inter_flow.jpg" title="inter_flow" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    Our algorithm flow.
</div>

<div class="row justify-content-md-center">
    <div class="col-sm-10 mt-3 mt-md-0">
        {% include figure.html path="assets/img/projects/inter_add_path_edge.jpg" title="inter_add_path_edge" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="w-100">
    </div>
    <div class="col-sm-5 mt-3 mt-md-0">
        {% include figure.html path="assets/img/projects/inter_ss_edge.jpg" title="inter_ss_edge.jpg" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm-3 mt-3 mt-md-0">
        {% include figure.html path="assets/img/projects/inter_cs_edge.jpg" title="inter_cs_edge.jpg" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm-4 mt-3 mt-md-0">
        {% include figure.html path="assets/img/projects/inter_priority_order.jpg" title="inter_priority_order" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    The construction of constraint graphs. Top: nodes (discrete points) and path edges (vehicle traveling time). Left-bottom: constraint edges for same-lane seperating time. Middle-bottom: constraint edges for cross-lane seperating time. Right-bottom: the priority order of vehicles.
</div>

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/projects/inter_change_point.jpg" title="inter_change_point" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    The solution path.
</div>
