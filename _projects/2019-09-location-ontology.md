---
title: "Location Ontology"
collection: projects
permalink: /projects/2020-09-location-ontology
start_date: 2018-08-01
end_date: 2019-09-01
exec_summary: "While there were many resources at HERE for describing _where_ 
an entity is, there were comparatively few to understand _what_ an entity is and 
how it related to other entities. We created an ontology for locations 
(e.g. businesses, parks) leveraging internal data sources and 
external, publicly available data (e.g. Wikidata, Schema.org). We then developed 
machine learning methods that could automatically relate new data to our existing 
dataset and find previously unknown relationships between existing entities."
academic_summary: "As a first step in the development of an ontology for locations,
we combined proprietary data with publicly available knowledge bases using 
heuristic and learned methods. The resulting ontology's nodes represented physical 
or conceptual entities (e.g. 'Starbucks', 'coffee shop', 'eating establishment') 
and edges represented hierarchical membership relations (e.g. INSTANCE_OF, 
SUBCLASS_OF). In this way, graph proximity indicated conceptual proximity 
(e.g. a coffee shop is closer to a bakery than a hospital). We then developed methods 
for predicting relations between entities in this graph, and showed that training 
such a model on the ontology and incorporating external text sources allowed 
us to predict previously unknown relations from known entities."
tech_used: [Python, Tensorflow, Scikit-Learn, Numpy, NLTK, Neo4j]
related_links: ["/patents_pubs/2020-12-09_patent-17-116717", 
"/patents_pubs/2020-12-09_patent-17-116727", 
"/patents_pubs/2020-12-09_patent-17-116743", 
"/patents_pubs/2020-12-09_patent-17-116756"]
---