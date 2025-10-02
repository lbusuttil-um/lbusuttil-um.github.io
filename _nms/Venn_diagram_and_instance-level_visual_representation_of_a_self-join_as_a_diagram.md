---
title: "Venn diagram and instance-level visual representation of a self-join as a diagram"
author: "xiaoying-tu"
Discipline: Databases
ConceptualAdvantage: "Helps readers visualize the mechanism of self-join both in terms of sets and in terms of linking actual tuples"
DrawsAttentionTo: "The nature of self-joins: joining two \"copies\" of the same table; the \"overlapping\" (\"linkage\") between the two Employees \"copies\""
Topic: Query languages (basic)
Domain: Within-Database
Form: Visual Representation
OriginSource: "Hoffer, J. A., Ramesh, V., & Topi, H. (2015). Modern database management. 12 ed. Pearson."
image: "185.png"
Mapping:
  circle,set :  table/relation
  set intersection :  matching instances/tuples
  arrows :  tuples satisfying the join condition
---