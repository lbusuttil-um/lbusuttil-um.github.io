---
title: JSON as "schema on read"
author: daphne-miedema
Discipline: Databases
ConceptualAdvantage: "Draws parallels to processing as done in relational databases."
DrawsAttentionTo: "How reading from JSON is similar to RDBMS projection"
Topic: Data storage and indexing
Domain: Within-Database
Form: Database Analogies
OriginSource: "Textbook Hellerstein, J. M., & Stonebraker, M. (2005). Readings in Database Systems. 4 ed. MIT Press."
image: "206.png"
Mapping:
  JSON structure : schema
  defining what to see at runtime : projection operation
  "schema on read" : relational operation"  
---
### Text
<p>"JSON can be viewed in one of three ways. [...] As a mechanism for “schema on read”. In effect, the schema is very wide and very sparse, and essentially all users will want some projection of this schema. When reading from a wide, sparse schema, a user can say what he wants to see at run time. Conceptually, this is nothing but a projection operation. Hence, ’schema on read” is just a relational operation on JSON-encoded data.
In summary, JSON is a reasonable choice for sparse data. In this context, I expect it to have a fair amount of “legs”. On the other hand, it is a disaster in the making as a general hierarchical data format. I fully expect RDBMSs to subsume JSON as merely a data type (among many) in their systems."</p>
