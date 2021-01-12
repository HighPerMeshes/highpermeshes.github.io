---
title: C++ Data Layout Abstractions through Proxy Types
doi: DOI:10.1109/IPDPSW.2019.00126
ris-id: 
authors: F. Wende
publin: "Proc. International Parallel and Distributed Processing Symposium Workshops (IPDPSW), Int. Workshop on Automatic Performance Tunings (iWAPT). 2019, pages 758–766"
layout: single
---
<!-- Leave as is, let Jekyll do the work. -->
{% capture doiurl %}https://doi.org/{{page.doi | remove_first: "DOI:"}}{% endcapture %}
{% capture risurl %}https://ris.uni-paderborn.de/record/{{page.ris-id}}{% endcapture %}

<html><p><b>{{ page.authors }}.</b> Published in: {{ page.publin }}</p></html>

## Information

* DOI: <a href="{{doiurl}}">{{doiurl}}</a>
{% if page.ris-id %}
* RIS: <a href="{{risurl}}">{{risurl}}</a>
{% endif %}
<!-- Change abstract -->
## Abstract
>Programs that process linearly indexed fields with structured element types in a data-parallel way usually suffer from the fact that compilers fail to generate efficient code if the selected data layout appears inappropriate for the chosen target architecture. If their internal heuristics cannot proof a performance gain from a data-parallel execution, compilers may fall back to scalar code generation. Data access through proxy types together with a customized container is one means to assist the compiler in generating efficient machine code in these cases without changing the user code. We present an automated proxy-type generator (using Clang's LibTooling) and a configurable multidimensional C++ container type that supports different data layouts in a transparent way. We present an automated proxy-type generator (using Clang's LibTooling) and a configurable C++ container that supports different data layouts in a transparent way.
