---
title: "Publications"
permalink: /publications/
layout: single
---

To reference the HighPermeshes Framework please use the following reference:

* S. Alhaddad, J. Förstner, S. Groth, D. Grünewald, Y. Grynko, F. Hannig, T. Kenter, F.Pfreundt et al  **HighPerMeshes – A Domain-Specific Language for Numerical Algorithms  on  Unstructured  Grids**.  In: Proc.  Int.  Workshop  on  Algorithms,  Models  and Tools  for  Parallel  Computing  on  Heterogeneous  Platforms  (HeteroPar)  in  Euro-Par2020: Parallel Processing Workshops. Lecture Notes in Computer Science (LNCS). Springer, 2020

Additionally, selected aspects of our work have been published in the following papers:

<html>
<ul>
{% for pub in site.publications %}
	<li>
	<div>
	<h4>
		<a href="{{ pub.url }}">{{ pub.title }}
	</a>
	</h4>
	{{ pub.authors }}
	</div>
	</li>
{% endfor %}
</ul>
</html>
