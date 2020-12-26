---
title: "Entity-Based Scene Understanding"
collection: projects
permalink: /projects/2018-02_entity-based-scene-understanding
start_date: 2014-06-01
end_date: 2018-02-01
exec_summary: "
This Master's thesis defines a machine learning method for identifying
entities in a visual scene using multiple text descriptions. Specifically,
we use a neural approach to determine which phrases from parallel captions
corefer (e.g. 'A man with his dog' and 'A person on their pet' yields
&#123;'A man', 'A person'&#125; and &#123;'his dog', 'their pet'&#125;)
and to which image regions those entities correspond. In addition, we
created and introduced a new annotated image caption dataset:
Flickr30kEntities v2"
academic_summary: "
Unifying multiple descriptions to determine the details of an everyday event can
be a challenging task for humans. Though incorporating other modalities like images
or videos can help humans unify such descriptions, this remains a challenging task
for computational systems. We define entity-based scene understanding as the task
of identifying the entities in a visual scene from multiple descriptions. This task
subsumes coreference resolution, bridging resolution, and grounding to produce
mutually consistent relations between entity mentions and groundings between
mentions and image regions. Using neural classifiers (including a bidirectional
LSTM and feed-forward layers) and integer linear program inference (to ensure
phrase-phrase and phrase-region relation consistency), we show that grounding
is improved when forced to conform to relation predictions. We introduce the
Flickr30k Entities v2 dataset, and show how our methods can be used to
automatically generate similarly rich annotations for the MSCOCO dataset."
image_url: "/images/2015_cervantes_flickr30k_ex.png"
github_link: "https://github.com/cmcervantes/ImageCaptionLearn_py"
tech_used: [Java, Python, NLTK, Tensorflow, Scikit-Learn, Numpy, LBJava, Stanford Core NLP,
Gurobi ILP Solver, PHP, Bash]
related_links: ["/patents_pubs/2018-02-01_thesis_cervantes-entity"]
---
