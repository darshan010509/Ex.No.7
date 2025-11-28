# Exno.7-Develop a prompt-based application tailored to their personal needs, fostering creativity and practical problem-solving skills while leveraging the capabilities of large language models.

# Date: 07.10.2025
# Register no.: 212222080013
# Aim: 
To develop a prompt-based application using ChatGPT - To demonstrate how to create a prompt-based application to organize daily tasks, showing the progression from simple to advanced prompt designs and their corresponding outputs.

#AI Tools Required: 

# Explanation: 
Prompt:
"Design a personal productivity assistant that can help manage daily tasks, schedule reminders, suggest wellness tips, and answer general queries. The assistant should interact using natural language and be adaptable to the user’s changing preferences over time."

1. Introduction

Prompt-based applications rely on structured instructions provided to a language model (ChatGPT) to generate useful outputs. In this experiment, we design a daily-task-organizing mini-application entirely through prompt engineering—starting from simple prompts and gradually moving to advanced, structured, and contextual prompts.

The experiment demonstrates how different prompting styles influence accuracy, clarity, and functionality of the task-management application.

2. Levels of Prompt Design

We implement the daily task organizer in four progressive prompt stages:

Basic Prompt

Structured Prompt

Role-Based Prompt

Multi-Step/Advanced Prompt (with constraints, reasoning, and formatting)

Each stage includes:
✔ Prompt used
✔ Expected Output
✔ Example used

We will use the images you suggested earlier as example tasks:

Task Example 1: “Take my brown dog to the park”

Task Example 2: “Make coffee with a sugar cube”

3. Experiment Steps and Outputs
3.1 Basic Prompting
Prompt:

“Help me plan my tasks for the day.”

Example Input Tasks:

Take my brown dog to the park

Make coffee with a sugar cube

Output:

ChatGPT responds in a simple to-do list format:

Output:

Take your brown dog to the park.

Make a cup of coffee and add a sugar cube.

Observation:

Minimal structure

No prioritization

No reasoning

3.2 Structured Prompting
Prompt:

“Create a structured to-do list using the tasks below. Categorize them into ‘Morning’, ‘Afternoon’, and ‘Evening’.
Tasks:

Take my brown dog to the park

Make coffee with a sugar cube”

Output:

Morning:

Make coffee with a sugar cube

Afternoon:

Take your brown dog to the park

Evening:

(No tasks)

Observation:

More clarity and organization

Better usability as a “daily planner app”

3.3 Role-Based Prompting
Prompt:

“You are my personal productivity assistant. Organize my daily tasks, assign priorities (High/Medium/Low), and estimate time required for each task.
Tasks:

Take my brown dog to the park

Make coffee with a sugar cube”

Output:

Task 1: Make coffee with a sugar cube

Priority: High

Estimated Time: 10 minutes

Task 2: Take your brown dog to the park

Priority: Medium

Estimated Time: 45 minutes

Observation:

More context-aware

Behaves like a productivity tool

Role assignment improves detail

3.4 Advanced Prompting (Multi-step + Constraints)
Prompt:

“You are an advanced task-management AI. Follow these steps:

Read the tasks.

Classify tasks into Personal / Household / Outdoor.

Add estimated time.

Arrange tasks into an optimized timeline based on shortest completion time first.

Output result in a table.

Tasks:

Take my brown dog to the park

Make coffee with a sugar cube”

# Result: 
The evolution from simple to advanced prompts clearly shows:

Improved structure
Increased clarity
Application-like behavior
Better reasoning and planning
Greater adaptability to user needs
Through prompt engineering alone, we built a functional daily task-organizing micro-application without writing any code.

# Conclusion:

This experiment demonstrates how prompt design significantly impacts the performance of a prompt-based application.
Starting from a basic instruction, we built a fully structured, organized, and optimized task planner using ChatGPT—highlighting the importance and power of advanced prompting techniques.
