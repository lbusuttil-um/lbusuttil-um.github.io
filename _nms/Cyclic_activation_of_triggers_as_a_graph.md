---
title: "Cyclic activation of triggers as a graph"
author: "xiaoying-tu"
Discipline: Databases
ConceptualAdvantage: "Visualizes the interdependencies among multiple active rules (triggers), which is a \"necessary condition for non-termination\""
DrawsAttentionTo: "interdependencies among multiple active rules (triggers)"
Topic: Query languages (advanced)
Domain: 
Form: Visual Representation
OriginSource: "Lecture Notes"
image: "001.png"
Mapping:
  node :  active rule (i.e. trigger)
  directed edge :  when action of one active rule triggers another active rule
---