---
title: "Database privileges as a diagram"
author: craig
Discipline: Databases
ConceptualAdvantage: "Visualizes the relationships grant-to between users as a graph"
DrawsAttentionTo: "The relation on users by granting privileges, the fact that a privilege is owned by a user if there is a path from the DBA to the user"
Topic: Query languages (advanced)
Domain: Within-Database
Form: Visual representations
OriginSource: "Silberschatz, A., Korth, H. F., & Sudarshan, S. (2011). Database system concepts. McGraw-Hill Education."
image: "241.png"
Mapping:
  node :  user
  arc :  privilege granted
---
### Alternate Versions
<a href="/nms/Database_privileges_as_a_diagram.html" Database_privileges_as_a_diagram [Root]</a>
<a href="/nms/GRANT_and_REVOKE_process_as_a_diagram.html" GRANT_and_REVOKE_process_as_a_diagram </a>