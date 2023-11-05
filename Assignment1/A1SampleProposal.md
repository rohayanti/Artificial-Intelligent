# Assignment 1
## Proposal of AI Solution
### Fruit Chatbot

*By Group A*
*Members:*
- Mr. Tom
- Miss Sara
- Mr. John

### Chapter 1 - The Overview of Problem Background

#### Introduction:
In the ever-evolving landscape of information technology, the development of an AI-driven chatbot prototype focused on providing information about fruits represents a cutting-edge endeavor.

#### The Problem Background:
The modern world is characterized by an abundance of information, with access to knowledge at our fingertips. However, when it comes to obtaining accurate and accessible information about fruits, we often encounter significant challenges. The existing resources, although numerous, can be fragmented, inconsistent, and overwhelming, making it difficult for individuals to find relevant and reliable data. This inconsistency and lack of a centralized, user-friendly source of information regarding fruits can pose obstacles for consumers, nutritionists, researchers, and the general populace.

#### Significance of the Problem:
Understanding the importance of this problem is crucial. Access to accurate and reliable information about fruits is essential for various reasons. For individuals, it aids in making informed dietary choices, promoting healthier lifestyles. Nutritionists and healthcare professionals rely on precise fruit information to provide personalized dietary guidance. Additionally, researchers exploring the realms of agriculture, nutrition, and sustainable food production require reliable data for their work. Therefore, the significance of resolving the problem at hand extends beyond the individual level and encompasses broader implications for society's well-being and progress.

#### The Need for an AI Solution:
Given the complexities and multifaceted nature of this challenge, a robust and efficient solution is required. This is where artificial intelligence (AI) steps in as a transformative force. Leveraging AI, we can create a chatbot prototype that not only centralizes and organizes the vast troves of information but also makes it easily accessible and user-friendly. With AI's ability to understand natural language and provide context-specific responses, the chatbot can serve as a reliable source of information on fruits.


## Chapter 2: The Stakeholders and the Empathy Map

**Stakeholders/Users of the Existing Application:**
1. **Consumers:** The primary users of the application are individuals who seek information about fruits for dietary, health, or culinary purposes. They range from health-conscious individuals looking for nutritional information to amateur chefs seeking fruit-related recipes and recommendations.

2. **Nutritionists and Dietitians:** These professionals rely on the application for accurate and up-to-date information on fruits to provide tailored dietary guidance to their clients. They use the app to access nutritional data, recommended daily intake, and health benefits associated with specific fruits.

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
