 
Draft Survey: https://docs.google.com/forms/d/1zODY0bT-1qsH8vpZSaydpDLwpcLI2FccN31mGKM23SA/viewform?edit_ 

Conflict Detection: Automatically identify and alert users to potential timetable conflicts, such as overlapping classes or exams. 

Real-time Updates: Offer real-time notifications for important events, such as class cancellations, room changes, and registration deadlines. 

Integration with University Systems: Connect the chatbot to UTM's systems to fetch real-time data, such as course availability, professor information, and academic calendars. 

Reminders and Notifications: Send timely reminders for class schedules, assignment due dates, and exam times. 

https://imgur.com/UAFxe3F 


# Assignment 1
## Proposal of AI Solution
### FC Schedule Chatbot

*By Group 2*
*Members:*
- MUHAMMAD RITZFARHAN ROSLI BIN RITZWA ROSLI
- MUHAMMAD FARHAN BIN AZMI 
- MOHAMAD NORFIRDAUS BIN MOHAMMAD SUKRI 

### Chapter 1 - The Overview of Problem Background

#### Introduction:
The academic journey of a university student is often challenging due to complex course scheduling. Students face difficulties in arranging their daily schedules, avoiding class time clashes, and selecting suitable classes that align with their existing commitments and preferences.

#### The Problem Background:
Students frequently encounter scheduling problems, including time conflicts between classes, long gaps between courses, and limited information to make informed decisions about course selection. These issues can lead to inefficiencies in academic planning and adversely affect the overall learning experience.

#### Significance of the Problem:
Efficient course scheduling is crucial for students to maximize their learning potential, balance academic and personal commitments, and graduate on time. A chatbot designed to address these scheduling challenges can significantly enhance the academic experience and contribute to student success.

#### The Need for an AI Solution:
To address the complexities and individualized nature of course scheduling, an artificial intelligence (AI) chatbot solution is essential. Such a chatbot can offer personalized, real-time scheduling assistance, help students make informed course choices, and streamline the academic planning process.

## Chapter 2: The Stakeholders and the Empathy Map

**Stakeholders/Users of the Existing Application:**
1. **Students:** The primary users of the chatbot, seeking assistance in creating and optimizing their class schedules.

2. **Faculty and Administrators:** Seeking tools to efficiently manage course assignments and resources.

3. **Academic Advisors:** Utilizing the chatbot to provide guidance and assist students in selecting courses aligned with their academic goals.


**Empathy Map from the Stakeholders' Perspective:**

*For Consumers:*
- **Think & Feel:** Consumers want to make healthy choices and feel confident about their dietary decisions. They may feel overwhelmed by the abundance of fruit-related information.
- **Hear:** They hear recommendations from peers, health experts, and online sources regarding the benefits of different fruits.
- **See:** Consumers see various fruits in supermarkets and online, often with conflicting information about their nutritional value and benefits.
- **Say & Do:** They may express frustration when they can't find clear, trustworthy information. They actively search for recipes, dietary advice, and fruit-related content.
- **Pain:** The pain point for consumers is the difficulty in sifting through vast amounts of information to make informed choices.

*For Nutritionists and Dietitians:*
- **Think & Feel:** They think about providing the best advice to their clients and feel the weight of responsibility.
- **Hear:** They hear from clients about the challenges they face in understanding fruit-related nutritional information.
- **See:** They see the need for a reliable resource that simplifies fruit-related data.
- **Say & Do:** They actively seek a tool that can provide comprehensive and accurate information to support their recommendations.
- **Pain:** The pain point for nutritionists is the time and effort required to find and present fruit-related data to clients.



# Chapter 3: System Architecture with Knowledge Base and Inference System

In this chapter, we present the system architecture for the AI-driven chatbot prototype designed to provide comprehensive information about fruits. The architecture leverages a Knowledge Base and an Inference System to enhance the chatbot's knowledge and responsiveness.

## System Architecture Overview

The proposed system architecture is designed to consist of the following key components as illustrated in Figure 1.


## Figure 1: System Architecture Diagram

Must put diagram here




## Components and Their Descriptions

| Component                    | Description                                                                                       | Technology Recommendation               |
|------------------------------|---------------------------------------------------------------------------------------------------|-----------------------------------------|
| User Interface (UI)          | Front-end component for user interaction, collects user input, and displays chatbot responses.   | - React (JavaScript library)            |
| Inference System             | Core component for processing user queries, drawing conclusions, and generating context-specific responses. | - Python with open-source NLP libraries (e.g., spaCy, NLTK)   |
| Knowledge Base               | Repository of structured information about fruits, serving as the foundation for chatbot responses. | - MySQL for structured data            |
| Knowledge Base Update Mechanism | Ensures periodic updates of the Knowledge Base, keeping it current with the latest fruit-related information. | - Python scripts for data scraping and updating   |
| API Layer (Optional)         | Facilitates external communication for data enrichment and integration with external resources.  | - Node.js with Express for building RESTful APIs   |



## System Workflow

1. A user interacts with the chatbot through the user interface, posing questions or seeking information about fruits.

2. The user interface forwards the query to the inference system.

3. The inference system processes the query, extracting relevant data from the Knowledge Base and applying inference rules.

4. Based on the extracted data and inference results, the inference system generates context-specific responses.

5. The user interface displays the responses to the user.

## Benefits of the System

- **Accuracy:** The Knowledge Base ensures that chatbot responses are based on reliable and up-to-date data.
- **Contextual Understanding:** The inference system allows the chatbot to comprehend the context of user queries and provide relevant responses.
- **Customization:** Rules and algorithms in the inference system can be tailored to cater to specific user needs.
- **Continuous Learning:** The Knowledge Base update mechanism ensures that the chatbot remains current with the latest information about fruits.

The proposed system architecture, integrating a Knowledge Base and an Inference System, equips the chatbot to provide precise, context-aware information about fruits, addressing the diverse needs of consumers, nutritionists, researchers, and more.
