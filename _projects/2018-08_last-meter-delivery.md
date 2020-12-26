---
title: "Last Meter Delivery"
collection: projects
permalink: /projects/2018-08_last-meter-delivery
start_date: 2018-08-01
end_date: 2019-09-01
exec_summary: "The last mile delivery problem is the challenge of delivering 
goods from a central location to their final destination. Last _meter_ delivery 
refers to the subproblem of finding a non-obvious micro-location 
(e.g. a side entrance) when a street address is already known. In this project, I 
developed a method for automatically extracting relational landmark-based 
representations of space given route instructions written in natural language, 
with the end goal of developing a mobile app for couriers that automatically 
produced schematic maps."
academic_summary: "In this project, we extract relational landmark-based spatial 
representations from natural language route instructions by leveraging prior work with 
robotic navigation. Specifically, we expect route instructions (one or more sentences 
describing a path through space) as input, and extract both landmarks (noun phrases 
relating to physical entities in space) and the relations between them that define 
the path described in the route. We do this by decomposing the task into 
predicting states (landmarks) and actions (movements), as is common in the robotic 
navigation literature. To do so, we leverage a bidirectional LSTM to encode 
sentences and then apply an attention mechanism in conjunction with an RNN decoder to
predict both landmark phrases (i.e. phrases that define decision points) and 
one of a set of actions (e.g. 'turn', 'forward') until a goal is reached. In this way,
the model can be said to learn to attend to different parts of the instruction as it 
progresses through the described path. "
image_url: "/images/2018_cervantes_last-meter-diagram.png"
tech_used: [Python, NLTK, Tensorflow, Numpy, Matplotlib, Java for Android]
related_links: ["/patents_pubs/2020-01-24_patent-16-774315", 
"/talks_teach/2019-06-25_talk_last-meter-delivery",
"/files/cervantes_2019_route.pdf"]
---
