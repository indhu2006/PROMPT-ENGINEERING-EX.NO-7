# Exno.7-Develop a prompt-based application tailored to their personal needs, fostering creativity and practical problem-solving skills while leveraging the capabilities of large language models.

# Date:
# Register no.
# Aim: To develop a prompt-based application using ChatGPT - To demonstrate how to create a prompt-based application to organize daily tasks, showing the progression from simple to more advanced prompt designs and their corresponding outputs.

#AI Tools Required: 


# Explanation: 
Prompt:
"Design a personal productivity assistant that can help manage daily tasks, schedule reminders, suggest wellness tips, and answer general queries. The assistant should interact using natural language and be adaptable to the user’s changing preferences over time."
Procedure:
1. Define the core requirements of a personal productivity assistant.
2. Identify and construct appropriate prompts for each task using an LLM (e.g., ChatGPT).
3. Simulate natural user interaction through a simple interface or command-line system.
4. Collect feedback or inputs from users and adapt responses accordingly.
5. (Optional) Integrate basic memory to simulate preference adaptation.
EXPECTED OUTPUT: - (attached the drive link)
Output (Example Response by LLM):
Personal Productivity Assistant Features:
1. Daily Task Manager:
o Accept tasks via natural language (e.g., "Remind me to call mom at 6 PM").
o Organize tasks by priority and deadline.
o Provide daily summaries and pending items.
2. Smart Scheduler:
o Schedule events and set reminders using contextual understanding.
o Notify user of overlapping appointments or free time slots.
3. Wellness Tips Generator:
o Suggest daily wellness advice (hydration, exercise, screen-time breaks).
o Adapt suggestions based on past user preferences and responses.

# PROMPTS AND THEIR OUTPUTS:
## PROMPT1: Create a prompt based application for organizing daily tasks<BR>
**OUTPUT:** <BR> 
Below is a **complete prompt-based application design** specifically for **organizing daily tasks**, aligned with your earlier productivity assistant concept.
This focuses on **how prompts drive the application**, not just UI or code.

---

# 🧠 Prompt-Based Application for Organizing Daily Tasks

## 1. Application Overview

**App Name:** SmartDay Organizer
**Type:** Prompt-Driven AI Application
**Core Idea:**
Users interact with the system using **natural language**, and the system uses **carefully constructed prompts** to organize, prioritize, schedule, and improve daily tasks using LLMs (ChatGPT / Gemini / Perplexity).

---

## 2. Key Capabilities

✔ Natural language task input
✔ Automatic task extraction
✔ Priority & deadline assignment
✔ Daily task planning
✔ Smart rescheduling
✔ Feedback-based correction

---

## 3. Prompt-Based Workflow (High Level)

```
User Input (Natural Language)
        ↓
Task Understanding Prompt
        ↓
Task Structuring Prompt
        ↓
Daily Planning Prompt
        ↓
Task Schedule Output
        ↓
User Feedback Prompt
        ↓
Improved Task Planning
```

---

## 4. Core Prompt Modules

### 🔹 1. Task Understanding Prompt

**Purpose:** Extract tasks, deadlines, priorities from raw user input.

**System Prompt**

```
You are an intelligent task extraction assistant.
Identify tasks, deadlines, priorities, and recurrence.
If information is missing, make reasonable assumptions.
```

**User Input Example**

> “I need to finish my assignment tonight and attend a meeting tomorrow morning.”

**LLM Output**

```
Task 1: Finish assignment
Deadline: Today, 10 PM
Priority: High

Task 2: Attend meeting
Deadline: Tomorrow, 10 AM
Priority: Medium
```

---

### 🔹 2. Task Structuring Prompt

**Purpose:** Convert extracted tasks into a structured format.

**Prompt**

```
Convert the following tasks into a structured daily task list.
Include: task name, priority, estimated time, deadline.
```

**Output Format**

| Task | Priority | Estimated Time | Deadline |
| ---- | -------- | -------------- | -------- |

---

### 🔹 3. Daily Task Planning Prompt

**Purpose:** Organize tasks into a realistic daily schedule.

**Prompt**

```
You are a smart daily planner.
Organize the tasks into an optimized schedule based on:
- Priority
- Deadlines
- Estimated duration
- Work-life balance
```

**Output Example**

```
6:00 – 6:15 PM → Break
6:15 – 8:00 PM → Assignment work
8:00 – 8:15 PM → Relax
```

---

### 🔹 4. Smart Rescheduling Prompt

**Purpose:** Handle missed or delayed tasks.

**Prompt**

```
Reschedule the unfinished tasks intelligently.
Avoid overload and respect deadlines.
```

---

### 🔹 5. Feedback & Correction Prompt

**Purpose:** Learn from user corrections.

**User Feedback Example**

> “This schedule is too packed.”

**Prompt**

```
The user says the schedule is too packed.
Adjust future schedules by reducing workload density.
Update user preferences accordingly.
```

---

## 5. Prompt Templates Used in the Application

### 📌 Universal Prompt Template

```
Role:
Task:
Context:
Constraints:
Preferred Output Format:
```

---

## 6. Example End-to-End Interaction

### User

> “Plan my tasks for today: study for 3 hours, gym, call my friend.”

### Prompt 1 – Task Extraction

```
Extract tasks, duration, and priorities.
```

### Prompt 2 – Structuring

```
Organize tasks into a table with estimated times.
```

### Prompt 3 – Planning

```
Create a balanced daily schedule.
```

### Final Output

| Time           | Activity    |
| -------------- | ----------- |
| 7:00 – 8:30 PM | Study       |
| 8:30 – 9:00 PM | Gym         |
| 9:00 – 9:30 PM | Call friend |

---

## 7. Adaptability Using Feedback

### User Feedback

> “I prefer studying in the morning.”

### Learning Prompt

```
Update user preferences to schedule study-related tasks in the morning by default.
```

### Future Impact

* Study tasks automatically moved to morning slots
* Reduced need for manual correction

---

## 8. LLM Selection Logic (Optional)

| Task                  | Preferred LLM |
| --------------------- | ------------- |
| Task extraction       | ChatGPT       |
| Schedule optimization | Gemini        |
| Productivity tips     | ChatGPT       |
| Research queries      | Perplexity    |

---

## 9. Why This Prompt-Based Design Works ✅

* No hard-coded rules
* Highly flexible
* Natural user interaction
* Easy to extend
* Learns from behavior
* Works across multiple LLMs

---

## 10. Academic & Practical Use

✔ Final year project
✔ Prompt engineering case study
✔ AI productivity tool
✔ System design demonstration

---

## PROMPT 2: CREATE A PROMPT BASED APPLICATION FOR ORGANIZING DAILY TASKS LIKE BY GIVEING A POWERFUL PROMPTS THAT GENERATES THE POWERFUL SCHEDULAR FOR THE AUTOMATING THE USERS TASKS AND MANAGING HIS TIME<BR> 
**OUTPUT:** <BR> 
Below is a **clear, exam-ready and implementation-ready PROMPT-BASED APPLICATION** that focuses **only on powerful prompts** to build an **AI scheduler that automates daily tasks and manages user time intelligently**.

This answer is written so you can **directly use it in a project report, viva, or prompt-engineering assignment**.

---

# 🧠 Prompt-Based Application

## AI Daily Task Organizer & Smart Scheduler

---

## 1. Application Concept

**Goal:**
Design a **prompt-driven AI application** that:

* Accepts natural language task input
* Automatically organizes, prioritizes, and schedules tasks
* Optimizes time usage
* Learns from user behavior and feedback

**Core Idea:**
👉 *The intelligence of the system comes from carefully engineered prompts, not hard-coded rules.*

---

## 2. Prompt-Based Architecture

```
User Input
   ↓
Task Extraction Prompt
   ↓
Priority & Time Estimation Prompt
   ↓
Smart Scheduling Prompt
   ↓
Daily Schedule Output
   ↓
Feedback Optimization Prompt
```

---

## 3. Powerful Prompt Set (Core of the Application)

---

## 🔥 PROMPT 1: MASTER TASK EXTRACTION PROMPT

### Purpose

Convert **raw user thoughts** into structured tasks.

### Prompt

```
You are an advanced AI task management assistant.

Analyze the user's input and extract:
1. All tasks
2. Deadlines (explicit or implied)
3. Estimated duration
4. Priority level (High / Medium / Low)
5. Task type (Work, Personal, Health, Social)

If any detail is missing, infer intelligently based on context.

User input:
{USER_INPUT}

Output format (JSON):
- Task Name
- Deadline
- Duration
- Priority
- Task Type
```

### Why it’s powerful

✔ Handles messy input
✔ Infers missing details
✔ Converts thoughts into data

---

## 🔥 PROMPT 2: PRIORITY & TIME OPTIMIZATION PROMPT

### Purpose

Decide **what matters most** and **how long it should take**.

### Prompt

```
You are a time-management expert.

Given the following tasks:
{STRUCTURED_TASK_LIST}

Optimize task priorities based on:
- Urgency
- Importance
- Mental energy required
- Deadline proximity

Adjust estimated durations if necessary to make the schedule realistic.

Output a refined task list sorted by execution order.
```

### Why it’s powerful

✔ Prevents unrealistic schedules
✔ Automatically balances urgency vs importance

---

## 🔥 PROMPT 3: POWERFUL SMART SCHEDULER PROMPT (CORE PROMPT)

### Purpose

Generate a **fully automated daily schedule**.

### Prompt

```
You are an elite AI productivity scheduler.

Create an optimized daily schedule using the following constraints:
- Total available time: {AVAILABLE_HOURS}
- User productivity preference: {MORNING / EVENING / FLEXIBLE}
- Include short breaks after long tasks
- Avoid task overload
- Balance work, health, and personal life

Tasks:
{OPTIMIZED_TASK_LIST}

Rules:
1. High-priority tasks first
2. Energy-intensive tasks during peak productivity hours
3. Insert recovery breaks
4. Ensure deadlines are met

Output format:
Time Slot → Task
```

### Example Output

```
7:00 – 8:30 AM → Deep Work: Assignment
8:30 – 8:45 AM → Break
9:00 – 10:00 AM → Gym
10:30 – 11:00 AM → Emails
```

### Why it’s powerful

🔥 Automates time planning
🔥 Mimics human productivity logic
🔥 Prevents burnout

---

## 🔥 PROMPT 4: MISSED TASK AUTO-RESCHEDULING PROMPT

### Purpose

Handle **unfinished or skipped tasks** intelligently.

### Prompt

```
You are a recovery-focused AI scheduler.

The following tasks were not completed:
{MISSED_TASKS}

Reschedule them by:
- Minimizing stress
- Respecting deadlines
- Avoiding overload
- Preserving user well-being

Generate a revised schedule.
```

### Why it’s powerful

✔ Prevents guilt-based overload
✔ Encourages consistency

---

## 🔥 PROMPT 5: FEEDBACK-DRIVEN IMPROVEMENT PROMPT

### Purpose

Make the system **learn and adapt**.

### User Feedback Example

> “This schedule is too packed and stressful.”

### Prompt

```
The user reports that the schedule feels too packed.

Update scheduling behavior by:
- Increasing buffer time
- Reducing back-to-back tasks
- Prioritizing mental wellness

Apply these changes to future schedules.
```

### Why it’s powerful

✔ Creates personalization
✔ Enables continuous improvement

---

## 4. Example End-to-End Interaction

### User Input

> “I have to study for 3 hours, go to the gym, finish a report by tonight, and call my parents.”

### System Flow

1. Task Extraction Prompt ✔
2. Priority Optimization Prompt ✔
3. Smart Scheduler Prompt ✔

### Final Output

```
6:00 – 7:30 PM → Report (High Priority)
7:30 – 7:45 PM → Break
7:45 – 8:45 PM → Study
9:00 – 9:30 PM → Gym
9:45 – 10:00 PM → Call Parents
```

---

## 5. Why This Prompt-Based Application Is Effective ✅

| Feature              | Benefit            |
| -------------------- | ------------------ |
| Prompt-driven        | No rigid rules     |
| Automated scheduling | Saves time         |
| Adaptive             | Learns preferences |
| Natural language     | Easy to use        |
| Scalable             | Works with any LLM |

---

## 6. Academic Value (Very Important)

This design demonstrates:

* Prompt Engineering
* AI-based automation
* Human-centered scheduling
* Feedback-driven learning
* Real-world applicability

Perfect for:
✔ Final year project
✔ AI / NLP assignment
✔ Prompt engineering lab
✔ System design exam

---

## 7. One-Line Summary (For Viva)

> *“This is a prompt-based AI application where carefully engineered prompts act as the intelligence layer to automatically extract, prioritize, and schedule daily tasks while adapting to user behavior over time.”*

---
# PROMPTS COMPARISION: 
### PROMPT: COMPARE THE ABOVE TWO PROMPTS IN TERMS OF THE OUTPUT THEY GIVE<BR>
### OUTPUT: 
Below is a **clear, structured comparison of the TWO KEY PROMPTS** used in the prompt-based daily task organizer, **based strictly on the OUTPUT they generate**.

We compare:

* **Prompt A:** Master Task Extraction Prompt
* **Prompt B:** Powerful Smart Scheduler Prompt

---

# 📊 Comparison of the Two Prompts Based on Output

| Aspect                             | **Prompt A: Task Extraction Prompt** | **Prompt B: Smart Scheduler Prompt**        |
| ---------------------------------- | ------------------------------------ | ------------------------------------------- |
| **Primary Output Type**            | Structured task data                 | Fully organized time-based schedule         |
| **Nature of Output**               | Analytical and descriptive           | Actionable and prescriptive                 |
| **Output Format**                  | JSON / Table (tasks & attributes)    | Timeline / Time slots                       |
| **Level of Abstraction**           | Low-level (raw task understanding)   | High-level (complete daily plan)            |
| **Main Focus**                     | *What needs to be done*              | *When and how tasks should be done*         |
| **Task Granularity**               | Individual tasks                     | Task sequences with breaks                  |
| **Time Allocation**                | Estimated duration only              | Exact start and end times                   |
| **Decision Making**                | Minimal (classification & inference) | Strong (optimization & prioritization)      |
| **User Readability**               | More technical / structured          | Very user-friendly                          |
| **Automation Level**               | Partial automation                   | Full automation                             |
| **Adaptability Visible in Output** | Limited                              | High (reflects preferences & energy levels) |
| **Cognitive Intelligence**         | Understanding user intent            | Simulating human productivity planning      |

---

## 🧠 Output Illustration (Side-by-Side)

### 🔹 Output of Prompt A (Task Extraction)

```
Task: Finish report
Deadline: Today, 10 PM
Duration: 2 hours
Priority: High
Task Type: Work
```

✔ Converts natural language into **machine-understandable structure**

---

### 🔹 Output of Prompt B (Smart Scheduler)

```
6:00 – 7:30 PM → Finish report
7:30 – 7:45 PM → Break
7:45 – 8:45 PM → Study
9:00 – 9:30 PM → Gym
```

✔ Converts structured tasks into a **realistic daily routine**

---

## 🔍 Output Quality Comparison

| Quality Dimension         | Task Extraction Prompt | Smart Scheduler Prompt |
| ------------------------- | ---------------------- | ---------------------- |
| Accuracy                  | High (fact extraction) | High (time realism)    |
| Practical Usefulness      | Medium                 | Very High              |
| Cognitive Load on User    | Higher                 | Lower                  |
| Readiness for Execution   | Low                    | Immediate              |
| Impact on Time Management | Indirect               | Direct                 |

---

## 🔗 Relationship Between the Outputs

> **Prompt A’s output becomes the INPUT for Prompt B**

```
Unstructured User Input
   ↓
[Prompt A Output → Structured Tasks]
   ↓
[Prompt B Output → Executable Schedule]
```

They **do not compete**, they **complement** each other.

---

## 🎯 Key Insight (Important for Exams & Viva)

* **Prompt A output answers:**
  👉 *“What are the tasks and their attributes?”*

* **Prompt B output answers:**
  👉 *“How should the user spend their time today?”*

---

## 🧪 Final Verdict

| Criterion                 | Better Prompt |
| ------------------------- | ------------- |
| Understanding user intent | Prompt A      |
| Automating daily life     | Prompt B      |
| Time optimization         | Prompt B      |
| Data structuring          | Prompt A      |
| End-user satisfaction     | Prompt B      |

---

### ✅ One-Line Conclusion (Viva-Ready)

> *“The task extraction prompt produces structured task intelligence, while the smart scheduler prompt transforms that intelligence into a real-time, executable daily schedule, making it far more impactful for end users.”*

---

# Result: 
The lab exercise resulted in the creation of a prototype concept for a personal assistant powered by large language models. Students were able to:
 Understand how to tailor LLM prompts to real-life applications.
 Foster creativity by designing features suited to their personal or academic lives.
 Learn prompt engineering techniques for optimal interaction with AI tools.
 Experience the versatility and utility of generative AI in solving everyday problems.
