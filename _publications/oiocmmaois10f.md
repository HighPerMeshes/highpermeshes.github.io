---
title: OpenCL Implementation of Cannon's Matrix Multiplication Algorithm on Intel Stratix 10 FPGAs
doi: 10.1109/ICFPT47387.2019.00020
ris-id: 15478
authors: P. Gorlani, T. Kenter and C. Plessl
publin: "Proc. Int. Conf. on Field Programmable Technology (ICFPT). IEEE Computer Society, Dec. 2019, pages 99–107."
layout: archive
---
<!-- Leave as is, let Jekyll do the work. -->
{% capture doiurl %}https://doi.org/{{page.doi | remove_first: "DOI:"}}{% endcapture %}
{% capture risurl %}https://ris.uni-paderborn.de/record/{{page.ris-id}}{% endcapture %}

<html><p><b>{{ page.authors }}.</b> Published in: {{ page.publin }}</p></html>

## Information

* **DOI**: <a href="{{doiurl}}">{{doiurl}}</a>
* **RIS**: <a href="{{risurl}}">{{risurl}}</a>

<!-- Change abstract -->
## Abstract
>Stratix 10 FPGA cards have a good potential for the acceleration of HPC workloads since the Stratix 10 product line introduces devices with a large number of DSP and memory blocks. The high level synthesis of OpenCL codes can play a fundamental role for FPGAs in HPC, because it allows to implement different designs with lower development effort compared to hand optimized HDL. However, Stratix 10 cards are still hard to fully exploit using the Intel FPGA SDK for OpenCL. The implementation of designs with thousands of concurrent arithmetic operations often suffers from place and route problems that limit the maximum frequency or entirely prevent a successful synthesis. In order to overcome these issues for the implementation of the matrix multiplication, we formulate Cannon's matrix multiplication algorithm with regard to its efficient synthesis within the FPGA logic. We obtain a two-level block algorithm, where the lower level sub-matrices are multiplied using our Cannon's algorithm implementation. Following this design approach with multiple compute units, we are able to get maximum frequencies close to and above 300 MHz with high utilization of DSP and memory blocks. This allows for performance results above 1 TeraFLOPS.
