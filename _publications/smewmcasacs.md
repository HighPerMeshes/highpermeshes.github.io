---
title: "Solving Maxwell’s Equations with Modern C++ and SYCL: A Case Study"
doi: 10.1109/ASAP.2018.8445127
ris-id: 3588
authors: Afzal, C. Schmitt, S. Alhaddad, Y. Grynko, J. Teich, J. Förstner und F. Hannig
publin: "IEEE, July 2018, pages 49–56. ISBN: 978-1-5386-7479-6"
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
In scientific computing, unstructured meshes are a crucial foundation for the simulation of real-world physical phenomena. Compared to regular grids, they allow resembling the computational domain with a much higher accuracy, which in turn leads to more efficient computations.There exists a wealth of supporting libraries and frameworks that aid programmers with the implementation of applications working on such grids, each built on top of existing parallelization technologies. However, many approaches require the programmer to introduce a different programming paradigm into their application or provide different variants of the code. SYCL is a new programming standard providing a remedy to this dilemma by building on standard C ++17 with its so-called single-source approach: Programmers write standard C ++ code and expose parallelism using C++17 keywords. The application isthen transformed into a concrete implementation by the SYCL implementation. By encapsulating the OpenCL ecosystem, different SYCL implementations enable not only the programming of CPUs but also of heterogeneous platforms such as GPUs or other devices. For the first time, this paper showcases a SYCL-based solver for the nodal Discontinuous Galerkin method for Maxwell’s equations on unstructured meshes. We compare our solution to a previous C-based implementation with respect to programmability and performance on heterogeneous platforms.<br

