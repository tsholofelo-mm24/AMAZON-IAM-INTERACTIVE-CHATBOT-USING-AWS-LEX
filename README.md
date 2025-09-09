# AMAZON IAM INTERACTIVE CHATBOT USING AWS LEX



<img width="512" height="512" alt="image" src="https://github.com/user-attachments/assets/2e497489-437e-4977-bfa5-5a20109c41eb" />


**Amazon Lex** is _an AWS service for building conversational interfaces for applications using voice and text._


# Amazon Lex Core Capabilities

1. Automatic Speech Recognition (Voice) - _Converts Speech to Text_.
2. Natural Language Understanding (Text & Voice) - _Interprets User Intent and Extracts Data_.
3. Multi-turn Conversations (Text & Voice) - _Manages Complex Dialogs_.
4. Slot Filling (Text & Voice) - _Prompts for Missing Info_.
5. Lambda Integration (Text & Voice) - _Runs Backend Logic_.
6. Omnichannel Deployment (Text & Voice) - _Supports Text and Voice Platforms_.
7. Monitoring & Logging (Text & Voice) - _Tracks Usage and Performance_.




# BUSINESS SCENARIO

**Client Requirements:**

Our client **Cloud2Cloud Inc Learners** decided to approach us to teach their learners from Grade 11 and 12 who are studying **CAT (Computer Applications Technology)** about **Cloud Computing** with **AWS**  since on their Syllabus they have been covering the Topics under **Information Management and Security** which aligns with it. We developed an **Educational Chatbot** that provides an Interactive Quiz experience for the Learners. 


# Solution Overview:

How we built the Quiz bot:
Quiz’s Structure:







**Step 1**

<img width="624" height="267" alt="image" src="https://github.com/user-attachments/assets/972f86f4-6fb6-44f3-b831-302ec36ac3f5" />
















**Step 2**

<img width="624" height="266" alt="image" src="https://github.com/user-attachments/assets/85d2f3b9-00cb-4386-9678-724790503199" />














**Step 3**

<img width="624" height="262" alt="image" src="https://github.com/user-attachments/assets/81265f1b-7380-473b-9316-297629eeddfa" />















**Step 4**

<img width="624" height="265" alt="image" src="https://github.com/user-attachments/assets/55bb38b3-9cbd-4175-b448-05ed5aafcd28" />














**Step 5**

**Created an IAMQuiz Intent**


<img width="624" height="270" alt="image" src="https://github.com/user-attachments/assets/5703f252-22d2-43ed-817f-6301d5d614a1" />












**Step 6**

**Added Utterances**

<img width="624" height="264" alt="image" src="https://github.com/user-attachments/assets/f2748f18-1202-4331-bc12-f3fbf5691a75" />











<img width="624" height="265" alt="image" src="https://github.com/user-attachments/assets/a83d8acf-0ca2-4252-b17a-cda9fbb13991" />









<img width="624" height="264" alt="image" src="https://github.com/user-attachments/assets/6132ce04-cd73-486a-b3e5-327322fa4150" />













**Step 7**

**Added InputField Slot Type**

<img width="624" height="265" alt="image" src="https://github.com/user-attachments/assets/788ce73c-9d44-4f13-b888-99e8e0319611" />










<img width="624" height="266" alt="image" src="https://github.com/user-attachments/assets/04b0ec22-0fe5-41dc-a8a1-2d9d63f95ea7" />








<img width="624" height="264" alt="image" src="https://github.com/user-attachments/assets/6852c918-da48-4c16-b109-de927fe5cf7d" />











**Step 8**

**Added QuestionField Slot Type**

<img width="624" height="266" alt="image" src="https://github.com/user-attachments/assets/02797502-7f10-4749-99bf-fa12f1212941" />








<img width="624" height="268" alt="image" src="https://github.com/user-attachments/assets/ebd4d965-03fd-43d9-96e4-709ce6cbd718" />











**Step 9**

**Added Prompts for (InputField and QuestionField Slot Types)**

<img width="624" height="258" alt="image" src="https://github.com/user-attachments/assets/98c115bb-173e-403b-bf5c-e3d0ca3598d0" />







<img width="624" height="271" alt="image" src="https://github.com/user-attachments/assets/8c4bd96e-c18a-42e6-8770-bcc9a0282e22" />







<img width="624" height="271" alt="image" src="https://github.com/user-attachments/assets/f1133df5-4976-4397-937b-6a38ece625df" />






<img width="624" height="271" alt="image" src="https://github.com/user-attachments/assets/153a0c56-59c6-40ee-a907-6d4ba965e31a" />







<img width="624" height="268" alt="image" src="https://github.com/user-attachments/assets/90e350e2-1c2c-460b-8e2f-6fa7a136f2ca" />












**Step 10**

**Conditional Branching (InputField Slot Type)**



<img width="624" height="254" alt="image" src="https://github.com/user-attachments/assets/7ca26d5c-6bee-4152-a589-5ce235d415f7" />






**Step 11**

**Selecting Option A**

<img width="624" height="277" alt="image" src="https://github.com/user-attachments/assets/e05f1282-6dfd-4121-bd38-de4a4f570ba9" />








<img width="624" height="274" alt="image" src="https://github.com/user-attachments/assets/47e8cd0b-85d4-4167-8bba-e91fd0174f34" />




**Step 11**

**Selecting Option B**

<img width="624" height="276" alt="image" src="https://github.com/user-attachments/assets/8ef8b86c-d5e1-4287-bb27-e4b855030987" />






<img width="624" height="275" alt="image" src="https://github.com/user-attachments/assets/2ea41a59-6fa9-4825-a99d-01d6c693b6ba" />





**Step 12**

**Selecting Option C**

<img width="624" height="276" alt="image" src="https://github.com/user-attachments/assets/2c0f7b58-c8b0-40f7-b912-c8f76b03526f" />








<img width="624" height="276" alt="image" src="https://github.com/user-attachments/assets/2c4d0d91-afad-4608-9bfe-ff67f6340507" />




**Step 13**

**Selecting Option D**

<img width="624" height="276" alt="image" src="https://github.com/user-attachments/assets/5c67c580-ead9-4e79-b139-cf949e7e947b" />







<img width="624" height="273" alt="image" src="https://github.com/user-attachments/assets/ee5a08d9-7b93-49e9-b304-1fbe5b9599a0" />






**Step 14**

**Conditional Branching (QuestionField Slot Type)**

<img width="624" height="277" alt="image" src="https://github.com/user-attachments/assets/dcc9e9f1-b41c-40c2-818e-0b73cd2494d3" />





**Step 15**

**Selecting Option Yes**

<img width="624" height="276" alt="image" src="https://github.com/user-attachments/assets/69b8b48e-2bc9-465a-a97d-0ba694df7be9" />




**Step 16**

**Selecting Option Yes**

<img width="624" height="278" alt="image" src="https://github.com/user-attachments/assets/d5a069da-a8e1-43ac-bf74-47030533b8c2" />








<img width="624" height="277" alt="image" src="https://github.com/user-attachments/assets/3d8d4f73-af8f-4509-b088-0ef0b0610bc6" />







<img width="624" height="279" alt="image" src="https://github.com/user-attachments/assets/02a85675-f326-420a-93a5-a6dcdace3544" />








**Closing Response**

<img width="624" height="266" alt="image" src="https://github.com/user-attachments/assets/3e416e5f-b60a-4fb7-ba08-cc3646686efa" />









# How the Chatbot maintains a **User-Friendly Flow, User Interactions**  and **Feedback** for _Correct and Incorrect_ **Answers**. 


**QUIZ CONVERSATION FLOW**

**Correct Answers**


<img width="382" height="586" alt="image" src="https://github.com/user-attachments/assets/a2ba04b6-d8b8-4231-8415-184f231d84d3" />









<img width="363" height="583" alt="image" src="https://github.com/user-attachments/assets/465b697a-044f-4c84-900a-4e2fc3fcc5e9" />








<img width="367" height="585" alt="image" src="https://github.com/user-attachments/assets/685c939f-45ea-49e5-8698-23329d60b66a" />







<img width="366" height="586" alt="image" src="https://github.com/user-attachments/assets/db1b63c2-832c-4566-b366-e6834d785b40" />






**Incorrect Answers**





<img width="364" height="583" alt="image" src="https://github.com/user-attachments/assets/d131daf5-7bbc-4929-b11d-59ea0cb7dee1" />









<img width="372" height="587" alt="image" src="https://github.com/user-attachments/assets/f13aa092-1144-4c2b-a40f-31f0df272a74" />









<img width="373" height="588" alt="image" src="https://github.com/user-attachments/assets/1e0a6020-4caa-4047-8412-224bffadb850" />







<img width="369" height="590" alt="image" src="https://github.com/user-attachments/assets/da430d00-928f-45f8-b5d4-f6c0126b47ca" />














# Technical Approach:

* The Structure of the Quiz is built for the Learners to use only the Text Technique. The first thing they will do is When they start the Quiz, they type a message greeting for **Example(Hello, Hi, Hey, Quiz Me)** which is an **Utterance** we give learners a cool Welcome, then the quiz begins.
* An **Intent** was added to name the Quiz. In the Intent we added **Slot Types**. One for the Question Field where the learner chooses their answer from Four **opions(A,B,C or D)**.
* Another **Slot Type** was added to prompt the learner to if they want to continue to the next Question they select **option(Yes or No)**.
* **Conditional Branching** was used to Validate if the Learner has selected the **Correct or Incorrect Answer**. The Response Message will show. After the message, Depending on the selection option. It will either asks if the learner wants to **Proceed**, **move to the next Question**, or **Close the Quiz**.









Our goal to our clients is that we Strive to prepare them for a _Technologically Advanced Future_ by Equipping them with _In-Demand Digital Skills_ and _Fostering Collaboration and Accessibility_ in Learning.
