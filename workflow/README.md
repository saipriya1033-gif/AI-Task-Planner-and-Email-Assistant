# AI Task Planner and Email Assistant

## Project Overview
An AI-powered task planning assistant built using n8n, an AI model, and external application integrations. The agent helps users organize projects by breaking them into smaller, manageable tasks and adding approved tasks to Todoist.

## Objectives
- Simplify project planning and task management.
- Convert project ideas into structured, actionable steps.
- Reduce manual effort in organizing daily tasks.
- Explore how AI agents interact with external applications using tools.

## Key Features

### 1. AI-Powered Task Planning
- Accepts project-related requests from users.
- Identifies the steps required to complete a project.
- Organizes the steps into a structured task plan.

### 2. Todoist Integration
- Connects the AI agent with Todoist through n8n.
- Adds tasks to the user's Todoist account when the user approves the plan.
- Helps users organize and track their activities.

### 3. Email Assistance
- Includes a Gmail-related email assistance workflow.
- Helps analyze received emails and provide useful email information.

## Technologies Used
- **n8n:** Workflow automation and AI agent development.
- **AI Model:** Alibaba Qwen 3.5.
- **Todoist:** Task management integration.
- **Gmail:** Email assistance integration.

## Workflow
1. The user provides a project idea or request.
2. The AI agent identifies the necessary steps.
3. The agent presents an organized task plan.
4. After user approval, the agent uses the Todoist integration to create tasks.
5. The user can manage and track the tasks in Todoist.

## Repository Structure
AI-Task-Planner-and-Email-Assistant/
├── workflow/
│   └── ai_agent_workflow.json
└── README.md

## Learning Outcomes
- Understood the fundamentals of AI agents.
- Explored connecting AI models with external tools.
- Learned workflow automation using n8n.
- Practiced integrating task management and email applications.

## Note
The workflow configuration shared in this repository is sanitized to avoid exposing personal account credentials. It is provided for project documentation and learning purposes.
