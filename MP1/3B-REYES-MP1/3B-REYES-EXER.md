# CSST 101 Laboratory Activity 1
### Vanesse V. Reyes
### BSCS - 3B
## Advance Representation and Reasoning
### Introduction to Knowledge Representation
### Objective: Introduction to Knowledge Representation

[![IMAGE ALT TEXT HERE](https://i9.ytimg.com/vi/CtpX1CJUJx0/mq2.jpg?sqp=CNCaqbgG-oaymwEmCMACELQB8quKqQMa8AEB-AHUBoAC4AOKAgwIABABGCcgWih_MA8=&rs=AOn4CLC_mH7eq0OAxMIkWXzWaWd2jl1LnA)](https://youtu.be/CtpX1CJUJx0)

## **What is Artificial Intelligence (Ai)?**

- Artificial Intelligence (AI) encompasses a broad range of technologies and methodologies aimed at creating machines capable of performing tasks that typically require human intelligence. These tasks include learning from experience, reasoning through complex problems, understanding natural language, recognizing patterns, and making decisions.


### **The importance of Knowledge in Ai**
At the core of AI systems lies the concept of knowledge representation, which is vital for enabling machines to interpret, reason about, and manipulate information effectively. Knowledge representation serves as the backbone of intelligent behavior in AI systems, allowing them to understand context, make inferences, and learn from data. Without structured knowledge representation, AI systems would lack the ability to perform complex reasoning or adapt their behavior based on new information.

### The Overview of Knowledge Representation

- Knowledge representation refers to the methods used to encode information about the world into formats that AI systems can utilize. This process involves creating models that represent various entities, their attributes, and the relationships between them. Forms of Knowledge Representation includes, Semantic Networks, Frames, Ontologies and Logic-Based Representations.

- These various forms of knowledge representation empower AI systems to process information efficiently, reason through complex scenarios, and make informed decisions based on available data.

### **SemantiC Networks**

- One prominent form of knowledge representation is semantic networks, which use graphical structures to represent concepts as nodes and relationships as edges. This visual approach helps illustrate how different pieces of information are interconnected, making it easier for AI systems to navigate complex relationships


### **Frames**

- One prominent form of knowledge representation is semantic networks, which use graphical structures to represent concepts as nodes and relationships as edges. This visual approach helps illustrate how different pieces of information are interconnected, making it easier for AI systems to navigate complex relationships

# Finance - Real-Time Fraud Detection

### **Ontologies**

- it also play a significant role in knowledge representation by defining a set of concepts within a specific domain and specifying the relationships among those concepts. They facilitate interoperability among different AI systems by providing a shared vocabulary and structure, which is particularly useful in fields like healthcare and natural language processing.



### **Logic - Based Representations**
- This are another critical technique in knowledge representation. This approach employs formal logic systems, such as propositional logic and first-order logic, to represent knowledge in a precise and unambiguous manner. Propositional logic allows for the expression of simple statements that can be true or false, enabling AI systems to make logical inferences based on known facts. For example, an AI can store statements like "If it is a car, then it has wheels" and apply logical rules to derive new knowledge from these assertions.



## **Comparasion of Knowledge Representation**

- Semantic Networks are graphical representations that depict concepts as nodes and relationships as edges. This visual format makes it intuitive to understand how different pieces of information are interconnected. Semantic networks excel in illustrating relationships and can easily accommodate new information by adding nodes and links. However, they may become complex and less manageable as the number of concepts increases, leading to potential difficulties in reasoning.

- Frames, on the other hand, are data structures designed to represent stereotypical situations through slots (attributes) and fillers (values). They provide a structured way to organize knowledge about various entities or scenarios, making it easier for AI systems to retrieve relevant information. Frames are particularly effective for representing hierarchical relationships and default values. However, they may lack the flexibility needed for dynamic or complex relationships that do not fit neatly into predefined structures.

- Ontologies offer a more formalized approach to knowledge representation by defining a set of concepts within a specific domain along with the relationships among them. They facilitate interoperability between different AI systems by providing a shared vocabulary and structure. Ontologies are particularly useful in domains requiring detailed classifications and relationships, such as biomedical research or semantic web applications. However, creating comprehensive ontologies can be time-consuming and may require expert knowledge to ensure accuracy.
Logic-Based Representations utilize formal logic systems to represent knowledge in a precise manner. This approach allows for rigorous reasoning and inference capabilities, making it suitable for applications that require consistency and clarity in decision-making. Logic-based representations can express complex relationships through quantifiers and variables, enabling AI systems to derive new knowledge from existing facts. However, they can also be computationally intensive and may struggle with uncertainty or ambiguity inherent in real-world scenarios.



## **Case Study Review – Medical Diagnosis System**

- One compelling application of knowledge representation in AI is within medical diagnosis systems. These systems assist healthcare professionals by analyzing patient symptoms and suggesting potential diagnoses based on vast medical knowledge.

### **How Knowledge is Represented in Medical Diagnosis System**

- One compelling application of knowledge representation in AI is within medical diagnosis systems. These systems assist healthcare professionals by analyzing patient symptoms and suggesting potential diagnoses based on vast medical knowledge.

- Ontologies play a crucial role by structuring medical knowledge into categories such as diseases, symptoms, treatments, and their interrelationships.

- Semantic networks help visualize connections between symptoms and diseases, allowing practitioners to quickly identify potential conditions based on presented symptoms.

- The system may also utilize logic-based representations, enabling it to apply rules such as “If a patient has a fever and cough, then consider flu or cold.”

- This structured approach not only enhances diagnostic accuracy but also addresses challenges such as ambiguity in symptom presentation and the complexity of interrelations among various medical conditions.


## **Problem Statement**

- To illustrate knowledge representation in this context, let’s consider a straightforward problem: analyzing common symptoms to suggest possible diagnoses.

- Knowledge Representation Model

A semantic network can be created as follows:
Nodes:
Fever
Cough
Cold
Flu
Links:
Fever → Associated with → Cold
Cough → Associated with → Flu
Cold → Symptoms include → Fever



### **How it works?** 
- The Knowledge Representation Model is a structured framework that enables AI systems to organize and utilize information effectively.

- It starts with knowledge acquisition, where data is gathered from various sources. This data is then transformed into a structured format through knowledge representation, using methods like semantic networks, frames, or ontologies.

- Next, the model employs reasoning, allowing the AI to draw conclusions from the represented knowledge. For instance, if it knows that "All humans are mortal" and "Socrates is a human," it can infer that "Socrates is mortal."
After reasoning, the AI applies this knowledge in the knowledge utilization phase to perform tasks or solve problems, such as suggesting diagnoses in a medical system.

- Finally, there's a feedback loop for knowledge learning and refinement, where the AI updates its knowledge base based on new data and outcomes. This ongoing process ensures that the AI remains accurate and relevant over time.



### **Implementing in Healthcare**


1. Establish a Framework
Choose methods like ontologies and semantic networks to organize medical knowledge, defining concepts and relationships relevant to patient care.
2. Integrate Electronic Health Records (EHR)
Use EHR systems to collect and store patient data systematically, allowing real-time access to histories, diagnoses, and treatments.
3. Develop Clinical Decision Support Systems (CDSS)
Create CDSS that analyze patient data and provide evidence-based recommendations for diagnoses and treatments based on established guidelines.
4. Enhance Interoperability
Adopt standardized vocabularies (e.g., SNOMED-CT) to ensure seamless information sharing among different departments within the hospital.
5. Implement Continuous Learning
Set up feedback loops to regularly update clinical guidelines and improve recommendations based on new research and treatment outcomes.
6. Train Healthcare Professionals
Provide training for staff on using the knowledge representation systems effectively, ensuring they understand how to interpret data and utilize tools.
7. Monitor Outcomes
Continuously track patient outcomes and system performance, making adjustments as needed to enhance the effectiveness of the knowledge representation approach.

# **Summary**


- Knowledge representation is a critical framework within the health sector, whereby it helps to organize and use medical information for better clinical decision-making, thereby improving patient outcomes. Some of its major constituents include
Framework creation: It employs methodologies like ontologies and semantic networks to define medical concepts and relationships.

- EHR Integration: Patients' data gets collected systematically and stored by using EHRs that provide real-time access to all relevant information.

- Clinical Decision Support Systems: Install data analysis systems that allow data monitoring of individual patients to generate evidence-based diagnosis and appropriate treatment recommendations based on established clinical guidelines.
Improvement of Interoperability: Standardized vocabularies, for example, SNOMED-CT, to ensure the free flow of information amongst departments within the same hospital.

- Installation of Continuous Learning Capability Enabled by Feedback Loops: Updating of clinical guidelines and refinement of recommendations in view of new research findings and treatment outcomes.
Training of Healthcare Staff: A training service that should be offered to staff on knowledge representation. Knowledge representation trains staff to interpret data and use the tools effectively.
Outcome Monitoring: A process of constant follow-up of patient outcomes and system performance with necessary changes to make the knowledge representation approach more effective.

- These approaches can enable hospitals to exploit knowledge representation for smoother operations, support healthcare providers in decision-making, and thus ultimately a better care facility for patients.

