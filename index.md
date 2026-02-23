# Kevin Chen
**Email:** kec050@ucsd.edu

**Section:** B16, Agentic Applications and Knowledge Graphs in Life Sciences  
**Mentors:** Abed El-Husseini, Balaji Veeramani

---

## Quarter 2 Project Proposal Brainstorming

**1. What is the most interesting topic covered in your domain this quarter?**

The most interesting topic covered in my domain this quarter has been the large variety of agentic frameworks options that are available. There are many tools and services available that allow developers and engineers to create agentic applications using these frameworks, such as LangChain and CrewAI. It's fascinating how these frameworks can be used to create agents using leading LLMs sucha as Claude and GPT that can complete tasks and work that people would normally have to manually complete. I've been exploring a ton with LangChain and Claude in my Quarter 1 project and have been gaining more experience in using this framework to create an agent and a workflow that can answer biomedical research questions through querying a database all through the agent.

**2. Describe a potential investigation you would like to pursue for your Quarter 2 Project.**


I'm interested to investigate developing an adaptive agentic AI system that serves as a personalized medical assistant throughout the entire patient process. This system would use large language models and retrieval-augmented generation to provide intelligent medical support before, during, and after doctor visits.
The AI agent would conduct an intelligent symptom intake, asking follow-up questions based on the patient's responses. It would help patient explain and understand their concerns more effectively and prepare relevant questions for their upcoming appointment.

The system would serve as a real-time companion, helping patients understand medical terms being used, tracking key information and recommendations from the doctor, and suggesting important follow up questions the patient might want to ask.

This project would combine  natural language processing, information retrieval, prompt engineering, and human-computer interaction and consider the ethical implications of AI in healthcare settings.

**3. What is a potential change you'd make to the approach taken in your current Quarter 1 Project?**

Based on my current Quarter 1 project, one significant improvement I would make is implementing interactive query refinement through multi-turn conversations rather than the current one-shot question-answering approach. Currently, when a user asks a question like "What genes are linked to diabetes?", the system returns all matching results in a single response. However, biomedical researchers usually work iteratively and refine their queries based on initial findings. 

The improved system would allow the agent to engage users conversationally by asking clarifying questions when results are too broad. For example, if the initial query returns 100 genes, the agent could respond: "I found 100 diabetes-related genes. Would you like to filter by diabetes type (Type 1 vs Type 2), confidence level, or specific chromosomes?" Based on the user's response, the agent would refine the Cypher query and narrow results progressively. This approach would better represent actual research workflows, makes the system more useful for exploratory analysis.


**4. What other techniques would you be interested in using in your project?**

I would be interested in adding capabilities that combines knowledge graphs with retrieval-augmented generation from scientific literature. Currently, the system only queries structured data in the Neo4j knowledge graph. By integrating RAG, the agent could search biomedical literature databases like PubMed to retrieve relevant research papers that provide context, evidence, and explanations for the relationships found in the graph.
