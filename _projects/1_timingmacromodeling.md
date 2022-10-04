---
layout: page
title: Timing Macro Modeling with GNN
description: A graph-neural-network-based approach for timing macro modeling. The preliminary result is published in DAC 2022.
img: assets/img/tmm_gnn.jpg
importance: 10
category: EDA
---

For the full paper, please visit the <a href="https://dl.acm.org/doi/abs/10.1145/3489517.3530599">ACM digital library</a> or directly access the <a href="https://kevinchang73.github.io/assets/pdf/dac22_tmm.pdf">pdf file</a>.

Due to rapidly growing design complexity, timing macro modeling has been widely adopted to enable hierarchical and parallel timing analysis. The main challenge of timing macro modeling is to identify timing variant pins for achieving high timing accuracy while keeping a compact model size. To tackle this challenge, prior work applied ad-hoc techniques and threshold setting. In this work, we present a novel timing macro modeling approach based on graph neural networks (GNNs). A timing sensitivity metric is proposed to precisely evaluate the influence of each pin on the timing accuracy. Based on the timing sensitivity data and the circuit topology, the GNN model can effectively learn and capture timing variant pins. Experimental results show that our GNN-based framework reduces 10% model sizes while preserving the same timing accuracy as the state-of-the-art. Furthermore, taking common path pessimism removal (CPPR) as an example, the generality and applicability of our framework on various timing analysis models and modes are also validated empirically.

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/tmm_problem.jpg" title="tmm_problem" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    The timing macro modeling problem.
</div>

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/tmm_gnn.jpg" title="tmm_gnn" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    The relation between timing propagation and GNN aggregation.
</div>

<div class="row">
    <div class="col-sm-4 mt-3 mt-md-0">
        {% include figure.html path="assets/img/tmm_flow.jpg" title="tmm_flow" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm-8 mt-3 mt-md-0">
        {% include figure.html path="assets/img/tmm_ts_generation.jpg" title="tmm_ts_generation" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    Our algorithm flows. Left: the overall flow. Right: our timing sensitivity metric and the training data generation flow.
</div>
