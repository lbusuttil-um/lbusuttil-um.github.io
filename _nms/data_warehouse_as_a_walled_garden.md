---
title: "data warehouse as a walled garden"
author: "daphne-miedema"
Discipline: Databases
ConceptualAdvantage: "Evokes a visual of how clean and curated the data is"
DrawsAttentionTo: "Highlights how clean data is important for traditional systems, but not for MapReduce systems."
Topic: Conceptual modeling
Domain: Anything else
Form: Database Analogies
OriginSource: "Hellerstein, J. M., & Stonebraker, M. (2005). Readings in Database Systems. 4 ed. MIT Press."
image: "213.png"
Mapping:
  traditional data warehouse systems: walled gardens - ingested data is pristine, curated, and has structure.
  MapReduce systems process: arbitrarily structured data, whether clean or dirty, curated or not. There is no loading step. This means users can store data first and consider what to do with it later.

---
### Text
<p>traditional data warehouse systems are walled gardens: ingested data is pristine, curated, and has structure. In contrast, MapReduce systems process arbitrarily structured data, whether clean or dirty, curated or not. There is no loading step. This means users can store data first and consider what to do with it later.</p>
