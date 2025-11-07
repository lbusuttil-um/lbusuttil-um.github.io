---
title: "fact table as \"fat\" table"
author: "daphne-miedema"
Discipline: Databases
ConceptualAdvantage: "The concept of a 'fat table' conjures an anthropomorphic image"
DrawsAttentionTo: "How tables in a star schema can get bigger than our normal conception of 'big'."
Topic: Conceptual modeling
Domain: Anything else
Form: Analogies
OriginSource: "Hellerstein, J. M., & Stonebraker, M. (2005). Readings in Database Systems. 4 ed. MIT Press."
image: "211.png"
Mapping:
  fat - many columns
  long - many rows
---
### Text
<p>The key observation is that Fact tables [in the star schema] are generally “fat” and often contain a hundred or more attributes. Obviously, they also “long” since there are many, many facts to record.</p>
