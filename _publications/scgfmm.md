---
title: SYCL Code Generation for Multigrid Methods
doi: 10.1145/3323439.3323984
ris-id: 16223
authors: S. Groth, C. Schmitt, J. Teich and F. Hannig
publin: "ACM, May 2019, pages 41–44. ISBN: 978-1-4503-6762-2"
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
>Multigrid methods are fast and scalable numerical solvers for partial differential equations (PDEs) that possess a large design space for implementing their algorithmic components. Code generation approaches allow formulating multigrid methods on a higher level of abstraction that can then be used to derive a problem- and hardware-specific solutions. Since these problems have a considerable implementation variability, it is crucial to investigate a general mapping of core components in multigrid methods to the target software. With SYCL there exists a high-level C++ abstraction layer that is capable of targeting a multitude of architectures. We contribute a general way to map multigrid components to SYCL functionality and provide a performance evaluation for specific algorithmic component.
