---
title: "A join query as a diagram"
author: "xiaoying-tu"
Discipline: Databases
ConceptualAdvantage: "Visualize the involved tables, their attributes, and put highlight the elements involved in the query"
DrawsAttentionTo: "attributes matched by join condition, elements involved in SELECT and WHERE clauses"
Topic: Query languages (basic)
Domain: Within-Database
Form: Visual Representation
OriginSource: "Hoffer, J. A., Ramesh, V., & Topi, H. (2015). Modern database management. 12 ed. Pearson."
image: "145.png"
Mapping:
  rectangles :  tables / relations
  horizontal stripes :  rows
  circled portions within the stripes :  attributes in the SELECT?
  single-sided arrow :  attributes involved in join condition
  rectangles containg query clauses are linked by arrows to the data portions they refer to
---
### Alternate Versions
<a href="/nms/Match_between_tuples_in_joins_as_links.html">Match_between_tuples_in_joins_as_links [Main]</a>
