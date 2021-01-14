---
title: Flexible FPGA design for FDTD using OpenCL
doi: 10.23919/FPL.2017.8056844
ris-id: 1592
authors: T. Kenter, J. Förstner, C. Plessl
publin: "Proc. Int. Conf. on Field Programmable Logic and Applications (FPL), IEEE, 2017"
layout: archive
---
<!-- Leave as is, let Jekyll do the work. -->
{% capture doiurl %}https://doi.org/{{page.doi | remove_first: "DOI:"}}{% endcapture %}
{% capture risurl %}https://ris.uni-paderborn.de/record/{{page.ris-id}}{% endcapture %}

<html><p><b>{{ page.authors }}.</b> Published in: {{ page.publin }}</p></html>

## Information

* **DOI**: <a href="{{doiurl}}">{{doiurl}}</a>
{% if page.ris-id %}
* **RIS**: <a href="{{risurl}}">{{risurl}}</a>
{% endif %}

<!-- Change abstract -->
## Abstract
>Compared to classical HDL designs, generating FPGA with high-level synthesis from an OpenCL specification promises easier exploration of different design alternatives and, through ready-to-use infrastructure and common abstractions for host and memory interfaces, easier portability between different FPGA families. In this work, we evaluate the extent of this promise. To this end, we present a parameterized FDTD implementation for photonic microcavity simulations. Our design can trade-off different forms of parallelism and works for two independent OpenCL-based FPGA design flows. Hence, we can target FPGAs from different vendors and different FPGA families. We describe how we used pre-processor macros to achieve this flexibility and to work around different shortcomings of the current tools. Choosing the right design configurations, we are able to present two extremely competitive solutions for very different FPGA targets, reaching up to 172 GFLOPS sustained performance. With the portability and flexibility demonstrated, code developers not only avoid vendor lock-in, but can even make best use of real trade-offs between different architectures.

