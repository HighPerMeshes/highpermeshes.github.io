---
title: OpenCL-based FPGA Design to Accelerate the Nodal Discontinuous Galerkin Method for Unstructured Meshes
doi: 10.1109/FCCM.2018.00037
ris-id: 1588
authors: T. Kenter, G. Mahale, S. Alhaddad, Y. Grynko, C. Schmitt, A. Afzal, F. Hannig, J. Förstner et al.
publin: "IEEE, 2018, pages 189–196. ISBN:978-1-5386-5523-8"
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
>The exploration of FPGAs as accelerators for scientific simulations has so far mostly been focused on small kernels of methods working on regular data structures, for example in the form of stencil computations for finite difference methods. In computational sciences, often more advanced methods are employed that promise better stability, convergence, locality and scaling. Unstructured meshes are shown to be more effective and more accurate, compared to regular grids, in representing computation domains of various shapes. Using unstructured meshes, the discontinuous Galerkin method preserves the ability to perform explicit local update operations for simulations in the time domain. In this work, we investigate FPGAs as target platform for an implementation of the nodal discontinuous Galerkin method to find time-domain solutions of Maxwell's equations in an unstructured mesh. When maximizing data reuse and fitting constant coefficients into suitably partitioned on-chip memory, high computational intensity allows us to implement and feed wide data paths with hundreds of floating point operators. By decoupling off-chip memory accesses from the computations, high memory bandwidth can be sustained, even for the irregular access pattern required by parts of the application. Using the Intel/Altera OpenCL SDK for FPGAs, we present different implementation variants for different polynomial orders of the method. In different phases of the algorithm, either computational or bandwidth limits of the Arria 10 platform are almost reached, thus outperforming a highly multithreaded CPU implementation by around 2x.

