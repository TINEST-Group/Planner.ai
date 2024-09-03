# Planner.ai
## Dataset approach
To address the problem, we initially approached it by simulating and experimenting with a dataset that was gathered through research and synthetically created. Our focus was on analyzing employees
their tasks (such as the duration of each task), and various operational factors like the gate’s location, including entry points and areas within the premises.
We dynamically extracted information on employee locations, skills, and their automatic classification.
The primary objective of our approach is to minimize downtime and enhance the efficiency of work order scheduling.


![Capture d’écran 2024-08-25 000528](https://github.com/user-attachments/assets/26ad607a-bf03-409a-bb49-619c028ce4f5)



## AI database agent
The project involves utilizing an SQLite database to implement a Retrieval-Augmented Generation (RAG) pattern. In this approach, a generative AI will assist in translating natural language queries into SQL code, enabling a seamless interaction between users and the database. The outcome will be the development of a database agent that leverages AI to understand and convert user requests into precise SQL commands, making data retrieval more intuitive and accessible.
We did an exdperience where you ask hima about the distance and time

![WhatsApp Image 2024-08-29 à 09 55 03_2a315936](https://github.com/user-attachments/assets/d6a8cd54-e87e-49b1-945f-a7f3f7d96b34)

## NER
We also experimented with Named Entity Recognition (NER) to determine if it could effectively identify specific entities such as skills, equipment, tasks, and actions. This approach involves training an existing NER model to recognize and categorize these entities within text. The goal was to assess whether NER could accurately extract and label these components, allowing for a better understanding of the content and context, much like how it identifies names, organizations, or dates in traditional use cases.

![WhatsApp Image 2024-08-29 à 09 50 32_965fa6e4](https://github.com/user-attachments/assets/7a8c65b4-73e0-4299-9db2-4134c41031b9)


These labels could serve as input for various use cases, such as a web application or a more complex architecture. By extracting and categorizing entities like skills, equipment, tasks, and actions, you can model text into graphs known as knowledge graphs. These knowledge graphs enable the establishment of relationships between entities, such as linking specific skills to corresponding tasks or actions. This structured representation of information facilitates better data analysis, decision-making, and enhances the functionality of applications that require contextual understanding and complex reasoning.


"""" #GraphRAG is a novel approach to question-answering over private text corpora that scales with both the generality of user questions and the quantity of source text to be indexed. The #hierarchical approach has major benefits over traditional #RAG - it provides high quality relevant answers, creates a single source of truth, enables traceability and #ResponsibleAI.

The pipeline is somewhat like this:

Source Docs -> Text Chunks -> Entities & Relations -> Hierarchical Communities -> Community summaries -> Global answers

With a production-ready graph database like Neo4j this pattern can be implemented in production to improve #RAG systems.

Tomaz Bratanic has written a detailed example with code for this using #Graph #DataScience algorithms in #Neo4j. Excellent read: https://lnkd.in/dc-SZWve

The original GraphRAG paper from Microsoft: https://lnkd.in/dY45YQx6 """ Llaama

Or we can use Semantic Role Labeling

![WhatsApp Image 2024-09-02 à 15 10 36_c778e432](https://github.com/user-attachments/assets/514b2260-efe9-45f1-bab2-1d4a240959d8)
## Mathematical Modeling
To complete the mathematical modeling, we need to formulate equations and algorithms that will optimize the scheduling and allocation of tasks based on various parameters:
Objective Function: Minimize total downtime and maximize task efficiency.
Constraints: Employee availability, task dependencies, location constraints, and operational limitations.
Variables: Task durations, employee assignments, skill levels, and operational factors.
By employing techniques from operations research and optimization (e.g., linear programming, integer programming), we can solve for the optimal allocation and scheduling of tasks, minimizing delays and enhancing overall productivity.



## Resources
huggingface.com, meduim articles, github, deeplearning.ai 
for research papers : arxiv.com, researchgate.com, paperswithcode.com,nature.com


### There's always room for new orientations and improvements




