---
layout: page
title: Threshold Logic Networks
description: Two learning-based methods to estimate the weights and thresholds of threshold logic networks (TLN).
img: assets/img/projects/tln_problem_example.jpg
importance: 5
category: EDA
---

To read the full paper, please visit <a href="https://kevinchang73.github.io/assets/pdf/tln.pdf">here</a>. For the source code, please visit the <a href="https://github.com/kevinchang73/2021Fall_LSV_Final_Project">Github repo</a>.

Threshold logic network is more viable nowadays due to its compactness and strong bind to neural network applications. However, the problem of weights and thresholds determination still remains open. In this work, we introduce machine learning and propose two approaches, the function-based approach and the network-based approach, to solve the problem. Experimental results show that our method achieves near 80% accuracy in the function-based approach and 70% to 90% accuracy in the network-based approach.

The main contribution of this work is summarized as follows:
* We formulate the TLN weights and thresholds learning problem, and we introduce machine-learning-based approaches to solve the problem.
* We analyze the relation between TLNs and neural networks and propose a conversion method. The weights and thresholds of a TLN could be extracted from the corresponding neural network directly.
* We propose a DNN-based training framework and generatea DNN model to predict the thresholds and weights for unseen testing functions.

<div class="row justify-content-md-center">
    <div class="col-sm-6 mt-3 mt-md-0">
        {% include figure.html path="assets/img/projects/tln_problem_example.jpg" title="tln_problem_example" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    The TLN weights and thresholds learning problem.
</div>

<div class="row">
    <div class="col-sm-3 mt-3 mt-md-0">
        {% include figure.html path="assets/img/projects/tln_conversion.jpg" title="tln_conversion" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm-9 mt-3 mt-md-0">
        {% include figure.html path="assets/img/projects/tln_function_based_flow.jpg" title="tln_function_based_flow" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    The function-based approach. Left: the conversion between a threshold logic gate and a neuron with activation.
</div>

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/projects/tln_network_based_flow.jpg" title="tln_network_based_flow" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    The training process of the network-based approach.
</div>
