---
title: "Visual representation of a simple equi-join as a diagram"
author: "xiaoying-tu"
Discipline: Databases
ConceptualAdvantage: "Visualizes the operations of a query involving joining two relations by an equality condition between two attributes in separate relations, which helps reader understand the logical process of such queries"
DrawsAttentionTo: "The relevant components in both relations and the checking conditions involved, particularly the equi-join condition linking records in separate relations"
Topic: Query languages (basic)
Domain: Within-Database
Form: Visual Representation
OriginSource: "Garcia-Molina, H., Ullman, J., & Widom, J. (2009). Database Systems: The Complete Book. 2 ed. Prentice Hall Press, Upper Saddle River, NJ, USA."
image: "135.png"
Mapping:
  rectangles :  tables / relations
  horizontal stripes :  rows
  circled portions within the stripes :  specific attribute values in those rows
  double-sided arrow :  equi-join condition
---