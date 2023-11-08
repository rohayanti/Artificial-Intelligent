
# Assignment 1
## Proposal of AI Solution
### Chatbot of Student Activities and Events

*By Group 4*
*Members:*
- MOHAMMED UMAIR KHYAM
- MUHAMMAD AKMAL BIN MOHAMAD NIZAM
- MOHUMMAD SYAZWI BIN SHAHARAN AKBAR
- OMAR AHMED MOHAMED ABDELMONEIM

### Chapter 1 - The Overview of Problem Background

#### Introduction:
In today's rapidly evolving educational landscape, fostering a vibrant and engaging campus life is essential for student success and satisfaction. We recognize that modern students require dynamic and efficient tools to stay connected with their peers and stay informed about the plethora of events and activities offered by our institution. With this in mind, we are excited to introduce our project proposal for the development of the "Student Activities and Events Chatbot."

#### The Problem Background:
Students often face challenges related to accessing and engaging with student activities and events on campus. These challenges include information overload due to the vast array of activities, limited awareness about available opportunities, complex event registration processes, lack of personalized recommendations, and organizational difficulties for event hosts. These issues collectively contribute to reduced student engagement and participation, limiting the vibrant campus experience our institution aims to provide. Addressing these challenges is crucial to enhancing the quality of student life, improving student retention and success, fostering inclusivity and diversity, streamlining resource utilization, gaining a competitive edge in the higher education landscape, and harnessing valuable data insights to inform future decisions and provide a holistic education beyond the classroom.

#### Significance of the Problem:
Efficient and accessible engagement with student activities and events is essential for students to enrich their campus experience, build meaningful connections, and develop holistically. The implementation of an AI-driven Chatbot to address these challenges holds significant importance, as it can provide students with a user-centric, personalized, and 24/7 accessible platform to connect with the diverse array of activities on campus. This solution not only enhances the quality of student life but also contributes to improved student retention, academic success, inclusivity, and diversity. By streamlining event management and providing data insights, the Chatbot empowers administrators to make informed decisions, ensuring efficient resource utilization and maintaining the institution's competitive edge. It aligns with the institution's mission to nurture well-rounded, engaged graduates, making it a pivotal element of the holistic campus experience

#### The Need for an AI Solution:
To navigate the multifaceted challenges of student engagement in campus activities and events effectively, an artificial intelligence (AI) chatbot solution is imperative. This AI-driven chatbot can provide personalized recommendations and real-time assistance, delivering information that caters to individual preferences and schedules. By offering instant access and guidance 24/7, it ensures that students can engage with the rich tapestry of campus offerings at their convenience. Furthermore, the AI chatbot streamlines event management and data insights, making it an indispensable tool for event organizers and administrators to optimize resource utilization and decision-making. The need for such an AI solution aligns with our commitment to creating a more vibrant, inclusive, and efficient campus community, meeting the ever-evolving needs of modern students and reinforcing our competitive edge in the higher education landscape.

## Chapter 2: The Stakeholders and the Empathy Map

**Stakeholders/Users of the Existing Application:**
1. **Students:** The primary users of the chatbot, seeking assistance for various activities and events that are held.

2. **Faculty and Student Clubs:** Uploading various activities that are currently being held and provide assistance in planning the event.


**Empathy Map from the Stakeholders' Perspective:**

*For Students:*
- **Think & Feel:** Students often feel overwhelmed and stressed by the sheer volume of campus activities and events, making them unsure about what to attending. They feel the need for a solution that can simplify their engagement, ensuring they don't miss out on the opportunities that genuinely interest them.    
- **Hear:** They hear about exciting events from peers, but sometimes they miss out on these due to scheduling conflicts or not knowing where to find detailed information.
- **See:** They see posters, emails, and social media posts about events, but the abundance of information can be confusing and hard to manage.
- **Say & Do:** They might say things like, "I wish there was an easier way to keep track of all these events," or "I don't know how to find activities that match my interests". As a result, students might struggle to participate in events or join clubs, which affects their campus experience.
- **Pain:** The pain point for students is the frustration of missing out on opportunities and feeling disconnected from the vibrant campus life they desire.

*For Faculty and Administrators:*
- **Think & Feel:** Faculty and student club leaders often think about how to efficiently promote their events and maximize participation.They feel the need for a tool that simplifies event management, streamlines communication, and provides insights into student engagement.
- **Hear:** They hear about successful events and activities but may not have access to the right resources to replicate that success.
- **See:** They see the potential for more organized and well-attended events but are hindered by the lack of an efficient platform.
- **Say & Do:** They might say things like, "We need a better way to manage event registrations and promotion," or "It's challenging to reach our target audience effectively". As a result, faculty and club leaders may find themselves spending excessive time on administrative tasks rather than focusing on creating engaging events.
- **Pain:** The pain point for faculty and club leaders is the resource drain and the feeling that they could do more to enrich campus life if they had the right tools.

# Chapter 3: System Architecture with Knowledge Base and Inference System

## System Architecture Overview

The Chatbot of Student Activities and Events architecture will consist of the following key components as illustrated in Figure 1.


## Figure 1: System Architecture Diagram

Must put diagram here




## Components and Their Descriptions

| Component                    | Description                                                                                       | Technology Recommendation               |
|------------------------------|---------------------------------------------------------------------------------------------------|-----------------------------------------|
| User Interface (UI)          | Front-end component for user interaction, collects scheduling preferences, and displays schedule options.   | - Web-based interface probablu use laravel            |
| Inference System             | the core component responsible for processing student queries and offering real-time recommendations for events and activities is the cornerstone of the project. | - Natural Language Processing (NLP)  |
| Knowledge Base               | Repository of events, including faculty activities, location of the event, a description of the event, | - Database Management System (RDBMS)           |
| Knowledge Base Update Mechanism | Ensures periodic updates of the Knowledge Base to reflect event changes and new events added.|- Automated data import processes   |




## System Workflow

- Students access the survey through the user interface, where they provide feedback and information about their interests in student activities and events.
- The survey engine processes the survey responses, collects the data, and stores it in the data storage repository.
- The data analysis component performs statistical analysis and generates reports based on the survey data. 
- The user interface displays survey results and reports to students, event organizers, and administrators.



## Benefits of the System

- Data-Driven Decision-Making: The survey system provides valuable data to administrators, enabling them to make informed decisions about campus activities and resource allocation.
- Enhanced Student Engagement: Students gain access to a comprehensive source of information about campus events, fostering greater engagement and participation. 
- Efficient Event Planning: Event organizers benefit from structured feedback and insights, allowing them to plan and execute successful events.
- Continuous Improvement: The system's data analysis component enables ongoing refinement of campus activities and events based on student feedback.
- The proposed system architecture, integrating a Survey Engine and Data Analysis components, equips the survey to gather meaningful insights about student activities and events, enhancing the overall campus experience and administrative decision-making.







