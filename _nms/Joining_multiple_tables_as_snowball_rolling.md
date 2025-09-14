---
title: Joining multiple tables as snowball rolling
author: xiaoying-tu
Discipline: Databases
ConceptualAdvantage: "Helps readers understand the mechanism of joining more than two tables"
DrawsAttentionTo: "The fact that each additional table is joined with the intermediate resulting table, just like the snowball gets bigger when rolling down the hill."
Topic: Data storage and indexing
Domain: Within-Database
Form: Database Analogies
OriginSource: "Textbook Beaulieu, A. (2009). Learning SQL. 2 ed. O'Reilly."
image: "026.png"
Mapping:
  snowball : the "intermediate table" after joining each additional table
 
---
### Text
<p>One way to think of a query that uses three or more tables is as a snowball rolling down
a hill. The first two tables get the ball rolling, and each subsequent table gets tacked on
to the snowball as it heads downhill. You can think of the snowball as the intermediate
result set, which is picking up more and more columns as subsequent tables are joined.</p>
