---
title: A Runtime System for Finite Element Methods in a Partitioned Global Address Space
doi: DOI:10.1145/3387902.3392628
ris-id: 16852
authors: S. Groth, D. Grünewald, J. Teich and F. Hannig
publin: "Proc. Int. Conference on Computing Frontiers (CF). ACM, 11.–13. May 2020, pages 39–48. ISBN: 978-1-4503-7956-4."
layout: single
---
<!-- Leave as is, let Jekyll do the work. -->
{% capture doiurl %}https://doi.org/{{page.doi | remove_first: "DOI:"}}{% endcapture %}
{% capture risurl %}https://ris.uni-paderborn.de/record/{{page.ris-id}}{% endcapture %}

<html><p><b>{{ page.authors }}.</b> Published in: {{ page.publin }}</p></html>

## Information

* DOI: <a href="{{doiurl}}">{{doiurl}}</a>
* RIS: <a href="{{risurl}}">{{risurl}}</a>

<!-- Change abstract -->
## Abstract
>With approaching exascale performance, applications in the domain of high-performance computing (HPC) have to scale to an ever-increasing amount of compute nodes. The Global Address Space Programming Interface (GASPI) communication API promises to handle this challenge by providing a highly flexible and efficient programming model in a partitioned global address space (PGAS).
>
>Suitable applications targeting supercomputers include the domain of mesh-based solvers for partial differential equations (PDEs) due to their high computational intensity. The implementation of such solvers is highly interdisciplinary, which therefore requires an abstraction of hardware-specific parallelization techniques from developing numerical algorithms.
>
>We present an open-source run-time system (RTS) that distributes and parallelizes device-agnostic kernels, which define algorithms on unstructured grids. We describe how the RTS abstracts common parts of iterative solvers and further explain how to parallelize and distribute these components. We further show the efficiency of our approach for several microbenchmarks and an implementation of the discontinuous Galerkin method (DGM). The results show that we can almost completely hide all synchronization overhead and that the RTS only imposes a small computational cost.
