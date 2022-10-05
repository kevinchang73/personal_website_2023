---
layout: page
title: HDR and Low Light Enhancement
description: Implementation of HDR imaging and low light enhancement algorithms on a FPGA board.
img: assets/img/projects/hdr_comparison.jpg
importance: 5
category: others
---

To read the full paper, please visit <a href="https://kevinchang73.github.io/assets/pdf/hdr.pdf">here</a>. For the source code, please visit the <a href="https://github.com/ChienKaiMa/2020Fall-NTUEE-DCLAB/tree/master/final">Github repo</a>.

In this final project, we implement an High Dynamic Range (HDR) Imaging algorithm on DE2-115 board. In addition to HDR, our work also performs well for low light image enhancement. Moreover, the whole computation time for one HDR imaging process of our work is less than 1 second, which is tens times faster than running the similar algorithm on the software.

<div class="row justify-content-md-center">
    <div class="col-sm-6 mt-3 mt-md-0">
        {% include figure.html path="assets/img/projects/hdr_hardware flow.jpg" title="hdr_hardware flow" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    The hardware design.
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
    The result of low light enhancement. Left: input image. Right: output enhanced image.
</div>
