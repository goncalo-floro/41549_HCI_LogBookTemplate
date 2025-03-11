[Back to main Logbook Page](../hci_logbook.md)

---
# C. Requirement Definition
>	Based on all the gathered context, including an understanding of current practices, competitors, and user feedback and expectations: 
>	- summarize the user characteristics, context, and motivations using Personas
>	- explain your vision for a novel solution that will target user motivations using Scenarios
>	- identify requirements

# Personas

## Persona: Alberto Fernandes 
### Summary 
| Attribute        | Details                                        |
| ---------------- | ---------------------------------------------  |
| **Photo**        | ![Alberto Fernandes](personas/persona_alberto.jpeg)     |
| **Name**         | Alberto Fernandes                              |
| **Age**          | 48                                             |
| **Occupation**   | Friend of an Addict                            |
| **Location**     | Trás-os-Montes, Portugal                       |
| **Goals**        | Help his friend recover from his addictions    |
| **Pain Points**  | Finding enough time to help his friend         |
| **Motivation**   | Seeing his friend get better at each step      |
| **Full Profile** | [📄 Read More](personas/persona_alberto.md)   |

---
## Persona: Jéssica Orlando 
### Summary 
| Attribute        | Details                                              |
| ---------------- | ---------------------------------------------------- |
| **Photo**        | ![Jéssica Orlando](personas/persona_jessica.jpeg)             |
| **Name**         | Jéssica Orlando                                      |
| **Age**          | 47                                                   |
| **Occupation**   | Caffeine Addiction                                   |
| **Location**     | Lisboa, Portugal                                     |
| **Goals**        | Get rid of her caffeine addiction                    |
| **Pain Points**  | Struggles to stop drinking coffee due to lack of time|
| **Motivation**   | whants feel more energized naturally                 |
| **Full Profile** | [📄 Read More](personas/persona_jessica.md)         |

---

## Persona: Sofia Almeida 
### Summary 
| Attribute        | Details                                        |
| ---------------- | ---------------------------------------------  |
| **Photo**        | ![Sofia Almeida](personas/persona_sofia.jpeg)  |
| **Name**         | Sofia Almeida                                  |
| **Age**          | 38                                             |
| **Occupation**   | Psychologist                                   |
| **Location**     | Porto, Portugal                                |
| **Goals**        | Help her clients when they need her            |
| **Pain Points**  | She can't keep track of her patients           |
| **Motivation**   | Her motivation is to keep her patients happy   |
| **Full Profile** | [📄 Read More](personas/persona_sofia.md)     |

---



# Scenarios


## Scenario 1: Alberto Fernandes wants to check how his friend is doing

Alberto is always worried about his friend, so he often textes him about his addictions, but when he does it, he thinks that he his putting too much pressure on his friend, so after seeing his **friends status**, he is a lot more relieved about his friend.

Sometimes he is occupied working and forgets to check on his friend, but he recieves a **warning notification** if somethings wrong with his friend happends. This happends if his friend got a relapse, or if he had a bad day.

---

## Scenario 2: Jéssica Orlando had a relapse and whants some motivation

Jéssica had a tough day and gave in to drinking too much coffee again. She opens the app and looks for motivational **posts** shared by other users who have faced similar challenges. She also receives positive reinforcement messages from the groups she follows, which helps her feel supported.

She also changed her **status** to a sad face so that her friends know that she needs motivation and support on this day. As a result, they receive a notification about her status and can reach out to her.

Because of her relapse, Jéssica also marks the day on her **calendar** to keep track of it. She doesn’t want constant reminders of her addiction, so the app only shows her how many days or hours she has stayed strong since her last relapse.

---

## Scenario 3: Sofia Almeida whant to see if her clients need her

Sofia goes to her page, and marks her **status** as available. This way, her clients can text her at any hour, and she can see if they need an apointment with her or if they just need a little motivation.

To **mark appointments**, Sofia goes to her calendar and marks the day and time she has available time for her clients. Like this, her clients can see the best times to make an appointment with her.

In her free time, Sofia also likes to **post** some motivation lines about quitting addictions. She can post it in the general feed, and if she wants, she can also post it with a specific tag, because the **app prioritizes posts by tag adequation**.

---


# Requirements





## C.1. Functional requirements

User Status Management

- The system shall allow users to update their personal status, depending on roles (available, unavailable, happy face, sad face, etc.).
- The system shall notify the user’s friends or support groups when the status indicates the user needs support (sad face status).

Friend Monitoring & Notifications

- The system needs to allow users to view their friends' status updates in real-time.
- The system shall send warning notifications if a user’s friend experiences a relapse or reports a bad day.

Motivational Content Sharing

- The system shall allow users and professionals to post motivational content (text, images, etc.).
- The system needs to support tagging posts with specific tags to target relevant audiences.
- The system needs to prioritize posts based on tag relevance to deliver them to the appropriate groups faster.

Calendar & Progress Tracking

- The system shall allow users to mark relapse days in a personal calendar.
- The system needs to calculate and display the number of days/hours since the last relapse without sending unnecessary reminders.
- The system shall allow professionals (e.g., Sofia) to manage their availability via a shared calendar.
- The system needs to enable clients to view available appointment slots and book appointments with professionals.

Communication & Messaging

- The system shall enable direct messaging between users and their friends or clients.
- The system needs to allow psychologists/professionals to receive and respond to client messages, and identify if they need motivation or an appointment.

## C.2. Non-functional requirements

Performance

- Notifications (status changes, relapse alerts) shall be delivered immediately to authorized users to ensure timely support.
- The system shall load feeds and update user statuses in real-time or with minimal delay, so everyone can communicate easily and without interruption.
- The system shall handle high volumes of users and interactions without significant slowdown, ensuring a smooth and responsive experience for all users.

Scalability

- The system shall support simultaneous status updates and notifications for thousands of users without performance degradation.
- The system architecture should allow adding new features (e.g., video posts, group chats) without significant rework.

Reliability

- The system shall provide continuous access, especially for users needing urgent support.
- The system shall queue and retry sending notifications if an initial delivery fails.

Security & Privacy

- Status updates, calendar entries, and personal messages need to be secure.
- Only authorized users shall be able to view private data like relapse dates and personal statuses.

Usability

- The system interface shall be simple and intuitive, requiring no more than three actions to update a status or schedule an appointment.
- The app shall provide accessibility features, including screen reader compatibility and high contrast modes.

---
[Back to main Logbook Page](hci_logbook.md)