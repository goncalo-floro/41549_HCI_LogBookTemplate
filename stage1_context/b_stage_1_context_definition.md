[Back to main Logbook Page](../hci_logbook.md)

---
# B. Stage 1 - Context Definition


# B.1. Competitor Identification
>	The competitor analysis will entail an identification of all competitors, with brief descriptions and a collection of the look and feel of their solutions, e.g., with screenshots, etc. It will also include a detailed analysis of the competitor deemed the best or more representative. It ends with a summary of the main findings including an HCI SWOT analysis



## B.1a. Competitors


| **Competitor**    | **Description**                             	| Information repository              |
| ----------------- | ------------------------------------------- 	| ----------------------------------- |
| I Am Sober	    | I Am Sober is a sobriety-tracking app that 	| [Competitor Analysis I Am Sober](competitors/Competitor_Analysis_IAmSober.md) 	  |
|					| can help you recover from addiction to 		|									  |
|					| alcohol and other substances, as well as 		|									  |
|					| break bad habits and other harmful behaviours.|        							  |
| Quitzilla 		| Quitzilla is an app designed to help you quit | [Competitor Analysis Quitzilla](competitors/Competitor_Analysis_Quitzilla.md)	  |
|					| your unwanted habits and addictions. 			|                                     |
| nomo		        | Nomo is a simple clock that can track the		| [Competitor Analysis Nomo](competitors/Competitor_Analysis_nomo.md)		| 
|					| number of days you've been sober/clean/etc    |                                     |




## B.1b. Detailed Competitor Analysis
>	Choose the most notable competitor and do a more thorough analysis of their interactive solution


### - Heuristic Evaluation

#### Method
[ Describe the method used for the heuristic evaluation: procedure, number of experts, heuristics, severity scale considered, how was consensus done.]
The Heuristic Evaluation was performed by three usability specialists who collaboratively assessed the I Am Sober app from the beginning, applying Nielsen’s 10 Usability Heuristics. They recognized problems, assessed their severity on a scale from 0 to 4, and came to an agreement through dialogue, prioritizing solutions according to impact and practicality

#### Individual Evaluations
<!-- For the individual heuristic evaluations by each member of the group, you can use the templates below, grouping problems by heuristic OR each evaluator can have a table listing all the detected problems with the number of the violated heuristics on the second column. Whichever your choice, you should have a list of problems, the severity, and a recommendation to mitigate it -->



- [expert1_heuristic_evaluation_workbook](heuristic_evaluations/expert1_heuristic_evaluation_workbook.md)

- [expert2_heuristic_evaluation_workbook](heuristic_evaluations/expert2_heuristic_evaluation_workbook.md)

- [expert3_heuristic_evaluation_workbook](heuristic_evaluations/expert3_heuristic_evaluation_workbook.md)


#### Consensus

>	After the individual analysis by each expert, all results should be gathered in a consensus table. If an expert has not found any of the problems found by other experts, they should analyse it, at this point, and give it a severity.

| **Issue**       						| **Expert 1** | Expert 2 | Expert 3 | Recommendations                             |
| --------------- 						| ------------ | -------- | -------- | ------------------------------------------- |
| Repetition of various functionalities	| 3            | 3        | 2        | remove redundant features |
| Functionalities don't operate in the  | 1            | 0        | 1        | Other thing to recommend                    |
| same on pc and on mobile
| Labels don't accurately represent     | 2            | 2        | 3        |                                             |
| their content 
| Filters have a ton of options instead | 2            | 1        | 3        | Something could be done to the button to... |
| of a scroll wheel
| Repetition of buttons that do the 	| 1            | 1        | 1        | Something could be done to the button to... |
| same thing



---
### - Cognitive Walkthrough

#### Method
We followed a step-by-step evaluation approach, focusing on how easily a new user can accomplish key tasks within the app without prior experience.
We start defining an user persona, like a first-time user looking to track their sobriety and interact with the community. Then we select key tasks that represent essential user goals and break down each task into subtasks to analyze usability. In the end we evaluate each step with 2 questions: Will the user know what to do at this step? Will the user know what to do next?

#### Task Selection and Task Analysis

[Which tasks did you select and why. What are the subtasks entailed for each ]
We chose tasks crucial for user involvement: incorporating a dependency (tobacco) and interacting with the community, since they influence onboarding and sustained retention. Every task was divided into subtasks to examine usability and possible friction areas


| Task                        		| Subtasks                               										|
| --------------------------- 		| -----------------------------------------------------------------------------	| 
| **1. Add Dependency (Tobacco)** 	| Open the menu (hamburger icon) and select "Add New".							|
|                             		| Select "Tobacco" and press the "Next" button. 								|
|                             		| Choose the start date of your abstinence and press "Next".      				|
|                             		| Select how many days per week you used to consume tobacco, then press "Next". |
|                             		| Select how many times per day you used to consume tobacco, then press "Next". |
|                             		| Write down your motivation for quitting tobacco, then press "Done".           |


| Task                          | Subtasks                                													|
| ----------------------------- | -----------------------------------------------------------------------------------------	|
| **2. login** 					| Open the user icon.					  													|
|                               | Press the account button.            	  													|
|                               | Enter your email, then press "Next".    													|
|                               | Enter your username, then press "Next". 													|
|                               | Enter your password, then press "Next". 													|
|                               | Open your email app and verify your email.       											|
|                               | Return to the I Am Sober app and upload a profile picture (optional), then press "Next".  |
|                               | Skip the Paywall by tapping the "X" (account created).        							|


| Task                        				| Subtasks                               										|
| --------------------------- 				| -----------------------------------------------------------------------------	| 
| **3. Post in the Community (Tobacco)** 	| Select the "Community" hub.													|
|                             				| Press the "+" button.															|
|                             				| Accept the community guidelines, then press "Ok, Got It!".      				|
|                             				| Write your story, then press "Next". 											|
|                             				| Select a photo to attach to your story (optional), then press "Next". 		|
|                             				| Read the confirmation message that your post was sent, then press "Done".     |


#### Results

Task: Add Dependency (Tobacco)

| Step # | Task/Action to Perform | Will User Know What to do at this step? (Yes/No) | Notes | If the user does the right thing, will they know it is progressing towards goal? (Yes/No) | Notes | Is Action Successful? (Yes/No) | Suggestions for Improvement |     |
| ------ | ---------------------- | ------------------------------------------------ | ----- | ----------------------------------------------------------------------------------------- | ----- | ------------------------------ | --------------------------- | --- |
| 1      | Open the menu (hamburger icon) and select "Add New".   | [Yes/No]                                         |       | [Yes/No]                                                                                  |       | [Yes/No]                       | [Suggestion 1]              |     |
| 2      | Select "Tobacco" and press the "Next" button.   | [Yes/No]                                         |       | [Yes/No]                                                                                  |       | [Yes/No]                       | [Suggestion 2]              |     |
| 3      | Choose the start date of your abstinence and press "Next".   | [Yes/No]                                         |       | [Yes/No]                                                                                  |       | [Yes/No]                       | [Suggestion 3]              |     |
| 4      | Select how many days per week you used to consume tobacco, then press "Next".   | [Yes/No]                                         |       | [Yes/No]                                                                                  |       | [Yes/No]                       | [Suggestion 3]              |     |
| 5      | Select how many times per day you used to consume tobacco, then press "Next".   | [Yes/No]                                         |       | [Yes/No]                                                                                  |       | [Yes/No]                       | [Suggestion 3]              |     |
| 6      | Write down your motivation for quitting tobacco, then press "Done".         | [Yes/No]                                         |       | [Yes/No]                                                                                  |       | [Yes/No]                       | [Suggestions]               |     |

Task: login

| Step # | Task/Action to Perform | Will User Know What to do at this step? (Yes/No) | Notes | If the user does the right thing, will they know it is progressing towards goal? (Yes/No) | Notes | Is Action Successful? (Yes/No) | Suggestions for Improvement |     |
| ------ | ---------------------- | ------------------------------------------------ | ----- | ----------------------------------------------------------------------------------------- | ----- | ------------------------------ | --------------------------- | --- |
| 1      | Open the user icon.   | [Yes/No]                                         |       | [Yes/No]                                                                                  |       | [Yes/No]                       | [Suggestion 1]              |     |
| 2      | Press the account button.   | [Yes/No]                                         |       | [Yes/No]                                                                                  |       | [Yes/No]                       | [Suggestion 2]              |     |
| 3      | Enter your email, then press "Next".   | [Yes/No]                                         |       | [Yes/No]                                                                                  |       | [Yes/No]                       | [Suggestion 3]              |     |
| 4      | Enter your username, then press "Next".   | [Yes/No]                                         |       | [Yes/No]                                                                                  |       | [Yes/No]                       | [Suggestion 3]              |     |
| 5      | Enter your password, then press "Next".   | [Yes/No]                                         |       | [Yes/No]                                                                                  |       | [Yes/No]                       | [Suggestion 3]              |     |
| 6      | Open your email app and verify your email.   | [Yes/No]                                         |       | [Yes/No]                                                                                  |       | [Yes/No]                       | [Suggestion 3]              |     |
| 7      | Return to the I Am Sober app and upload a profile picture (optional), then press "Next".   | [Yes/No]                                         |       | [Yes/No]                                                                                  |       | [Yes/No]                       | [Suggestion 3]              |     |
| 8      | Skip the Paywall by tapping the "X" (account created).        | [Yes/No]                                         |       | [Yes/No]                                                                                  |       | [Yes/No]                       | [Suggestions]               |     |

Task: Post in the Community (Tobacco)

| Step # | Task/Action to Perform | Will User Know What to do at this step? (Yes/No) | Notes | If the user does the right thing, will they know it is progressing towards goal? (Yes/No) | Notes | Is Action Successful? (Yes/No) | Suggestions for Improvement |     |
| ------ | ---------------------- | ------------------------------------------------ | ----- | ----------------------------------------------------------------------------------------- | ----- | ------------------------------ | --------------------------- | --- |
| 1      | Select the "Community" hub.   | [Yes/No]                                         |       | [Yes/No]                                                                                  |       | [Yes/No]                       | [Suggestion 1]              |     |
| 2      | Press the "+" button.   | [Yes/No]                                         |       | [Yes/No]                                                                                  |       | [Yes/No]                       | [Suggestion 2]              |     |
| 3      | Accept the community guidelines, then press "Ok, Got It!".   | [Yes/No]                                         |       | [Yes/No]                                                                                  |       | [Yes/No]                       | [Suggestion 3]              |     |
| 4      | Write your story, then press "Next".   | [Yes/No]                                         |       | [Yes/No]                                                                                  |       | [Yes/No]                       | [Suggestion 3]              |     |
| 5      | Select a photo to attach to your story (optional), then press "Next".   | [Yes/No]                                         |       | [Yes/No]                                                                                  |       | [Yes/No]                       | [Suggestion 3]              |     |
| 6      | Read the confirmation message that your post was sent, then press "Done".        | [Yes/No]                                         |       | [Yes/No]                                                                                  |       | [Yes/No]                       | [Suggestions]               |     |

## B.1c. Overall Analysis

[Here, you should summarize the main findings for the competitor panorama, listing key points that are valuable to inform the design of your solution, and also make an HCI SWOT analysis for the main competitor, taking into consideration what you learned from the heuristic evaluatio, cognitive walkthrough, online reviews, user feedback, etc.]

---

# B.2. Users
>	For the users, there are two goals: 1) understand the current status of users in the domain you are addressing. How do they manage, what are the main tasks they do, if they use some tool for the purpose, what are current challenges, what might be improved, what might be new features, ...


## B.2a. Method

[What approach was followed to talk with users; what kind of users were considered. What was the goal of the interviews? What were the questions considered?]
## B.2b. Results

>	This section tracks all informal user interviews, summarizing key insights and linking to detailed notes for each session. 

### Interview List 
| Date       | Participant / Role | Key Insights                                                    | Link to Notes                |     |
| ---------- | ------------------ | --------------------------------------------------------------- | ---------------------------- | --- |
| 25-02-2025 | Paulo - addict     | Wants to overcome his addiction | [📄 Notes](interview-Paulo.md) |     |
| 25-02-2025 | Rafael - addict    | Wants to overcome his addiction | [📄 Notes](interview-Rafael.md)                             |     |
| 25-02-2025 | José - friend of an addict    | Wants to help his friend overcome his addiction | [📄 Notes](interview-José.md)                             |     |

### Common Themes & Patterns 

- **Recurring Problems:** 
	- Relapsing
	- Lack of always available support
- **Frequently Used Tools:** 
	- Social media for motivation
	- Asking for help from friends and family
	- Support groups
- **Desired Features / Solutions:** 
	- Rewards that makes your progress apparent
	- professional support
	- Privacy
	- Group chat's between addicts in similar situations
	- Scheduled activities to replace addictions
- --- 



---
[Back to main Logbook Page](../hci_logbook.md)

---
