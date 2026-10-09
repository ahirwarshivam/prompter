# Prompter

## AI Tool Discovery and Smart Prompt Generation Platform

Prompter is an AI-powered platform designed to help users identify the most suitable AI tools for their specific tasks and generate optimized, tool-specific prompts.

Instead of requiring users to know which AI tool to use or how to formulate an effective prompt, Prompter understands the user's objective, analyzes the task, recommends suitable AI tools, explains the reasoning behind each recommendation, and generates a prompt tailored to the selected tool.

## How It Works

The core workflow of Prompter is:

User Problem  
→ Task Understanding  
→ AI Tool Matching  
→ Recommendation and Explanation  
→ Tool-Specific Prompt  
→ Copy / Open AI Tool

## Core Features

- Natural language task understanding
- User profile and context-based personalization
- AI tool recommendation
- Explanation of why a tool is suitable
- Tool-specific prompt generation
- Prompt copying and external tool access
- Feedback and recommendation evaluation
- Support for different domains and task types

## Example

### User Input

> I have a research paper and tomorrow I need a professional college presentation.

### Task Understanding

- Domain: Academic
- Task: Presentation Generation
- Input: Research Paper / PDF
- Output: Presentation
- User: Undergraduate
- Constraint: Free or low-cost preference

Prompter analyzes these requirements, identifies suitable AI tools, explains why they are appropriate, and generates a prompt optimized for the selected tool.

## Personalization

Prompter can use relevant user context to improve recommendations, including:

- User role
- Education or profession
- Field or industry
- Skills and experience
- Interests
- Goals
- Preferred language
- Task requirements and constraints

Only relevant profile information is used when it improves the recommendation.

## Technology Stack

### Frontend
- Next.js
- React
- Tailwind CSS

### Backend
- Python
- FastAPI
- Pydantic

### Database
- PostgreSQL

### AI
- Large Language Model APIs
- Structured outputs

### Future Technologies
- Embeddings
- Retrieval-Augmented Generation (RAG)
- AI tool integrations
- Agent workflows

## Development Roadmap

The project is being developed incrementally:

1. Product foundation and architecture
2. User, task, and AI tool data models
3. AI task-understanding engine
4. AI tool knowledge base
5. Recommendation engine
6. Tool-specific prompt generation
7. Backend API
8. Frontend web application
9. Authentication and personalization
10. Voice and file inputs
11. Feedback and evaluation
12. Production deployment
13. RAG and embeddings
14. Future AI integrations and agent workflows

## V1 Objective

The primary objective of V1 is to build a reliable end-to-end workflow:

**Understand → Recommend → Explain → Generate Prompt → Open AI**

The initial focus is on building and validating the intelligence engine before expanding the platform with advanced features. :chatgpt-content-reference{index="0"}

## Future Vision

The long-term goal is to evolve Prompter from an AI recommendation and prompt-generation platform into an intelligent AI workflow system:

**Understand → Plan → Select Tools → Execute → Verify → Return Outcome**

Future development may include direct AI-tool integrations, automated execution, multi-step workflows, agent orchestration, personalized recommendations, mobile applications, and team or enterprise workflows. :chatgpt-content-reference{index="1"}

## Project Status

Currently in development.

The initial development phase focuses on the Prompter Intelligence Engine, including task understanding, AI tool matching, recommendation generation, and tool-specific prompt generation.
