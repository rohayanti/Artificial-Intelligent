 
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

*For Students:*
- **Think & Feel:** Students aim to create an efficient and balanced class schedule while achieving their academic goals. They may feel stressed and overwhelmed by the complexity of course scheduling.    
- **Hear:** They hear advice and tips from peers about managing course schedules. They may also receive guidance from academic advisors.
- **See:** Students see the course catalog with various class options, and they may encounter time clashes and fully registered classes.
- **Say & Do:** They may express frustration when they face class scheduling conflicts or long gaps between classes. They actively seek information on courses, class timings, and scheduling tools.
- **Pain:** The pain point for students is the challenge of coordinating class schedules efficiently and avoiding time clashes, which can disrupt their academic progress.

*For Faculty and Administrators:*
- **Think & Feel:** Faculty and administrators aim to efficiently manage courses and resources. They may feel the pressure to optimize course assignments and meet students' scheduling needs.
- **Hear:** They hear feedback and requests from students and academic advisors regarding course scheduling challenges.
- **See:** They see the need for a system that simplifies class scheduling, reduces time clashes, and improves resource allocation.
- **Say & Do:** They actively seek tools and solutions to streamline the course scheduling process and meet the diverse needs of students.
- **Pain:** The pain point for faculty and administrators is the complexity of course scheduling and the potential impact on students' academic experiences.

*For Academic Advisors:*
- **Think & Feel:** Academic advisors aim to provide guidance and support to students in their course selections. They may feel responsible for helping students make informed decisions.
- **Hear:** They hear about students' scheduling challenges and concerns about course choices.
- **See:** They see the need for a system that can offer real-time scheduling assistance and help students align their courses with academic goals.
- **Say & Do:** They actively seek tools to assist students in selecting courses that fit their academic plans and preferences.
- **Pain:** The pain point for academic advisors is the time and effort required to provide personalized scheduling guidance to a large number of students.


# Chapter 3: System Architecture with Knowledge Base and Inference System

## System Architecture Overview

The Faculty Course Scheduling Chatbot's architecture will consist of the following key components as illustrated in Figure 1.


## Figure 1: System Architecture Diagram

Must put diagram here




## Components and Their Descriptions

| Component                    | Description                                                                                       | Technology Recommendation               |
|------------------------------|---------------------------------------------------------------------------------------------------|-----------------------------------------|
| User Interface (UI)          | Front-end component for user interaction, collects scheduling preferences, and displays schedule options.   | - Web-based interface probablu use laravel            |
| Inference System             | Core component for processing student queries, generating class schedules, and offering real-time recommendations. | - Python with AI scheduling algorithms  |
| Knowledge Base               | Repository of course information, including class schedules, course prerequisites, instructor data, and room accessibility. | - Relational database for structured data           |
| Knowledge Base Update Mechanism | Ensures periodic updates of the Knowledge Base to reflect course changes and availability.|- Automated data import processes   |
| Notification System         | Sends alerts and reminders to students regarding class schedules, course availability, and exam details.  | - Email, SMS, or app notifications   |



## System Workflow

1. Students interact with the chatbot through the user interface, providing their course preferences and constraints.

2. The chatbot's inference system processes the student's input and queries the Knowledge Base for available courses.

3. The chatbot generates and presents multiple schedule options, considering student preferences, course prerequisites, and real-time course availability.

4. Students can choose a suitable class schedule or request adjustments.

5. The chatbot sends notifications and reminders to students for critical scheduling events.

## Benefits of the System

- **Personalization:** The chatbot tailors schedules to each student's academic needs and preferences.
- **Real-time Information :** Offers immediate access to course availability, instructor data, and room accessibility.
- **Efficiency:** Streamlines the course selection process, reducing scheduling conflicts and time spent planning.
- **Support for Stakeholders:** Helps faculty, advisors, and parents/guardians in ensuring students make informed scheduling decisions.
- **Timely Alerts:**Keeps students informed about class schedule changes, exams, and course openings.

The proposed Faculty Course Scheduling Chatbot, utilizing AI scheduling algorithms and a robust Knowledge Base, aims to assist students in managing their academic schedules effectively and enhancing their overall university experience.





