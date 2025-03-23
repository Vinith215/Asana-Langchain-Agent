# Asana-Langchain-Agent

# 🤖 AI-Powered Asana Task Manager  

A **Conversational AI Assistant** that integrates **Asana task management** with **LLMs (GPT-4o, Claude)** to automate and streamline task creation. Built with **LangChain, OpenAI, Anthropic, and Asana API**, this assistant helps users create and manage tasks effortlessly through natural language interactions.  

---

## 📌 Features  
✅ **AI-Driven Task Creation** – Automatically generates tasks in Asana based on user prompts.  
✅ **LLM-Powered Assistant** – Supports **GPT-4o and Claude** for intelligent task management.  
✅ **Asana API Integration** – Creates tasks with due dates and project assignments.  
✅ **Multi-Turn AI Conversations** – Handles contextual interactions for task updates.  
✅ **Tool-Calling Capabilities** – AI decides when to invoke Asana task creation tools.  

---

## 🛠️ Tech Stack  
- **Python** – Core programming language  
- **LangChain** – Framework for AI agent and tool orchestration  
- **OpenAI & Anthropic APIs** – LLM-based chatbot models  
- **Asana API** – Task management and automation  
- **dotenv** – Environment variable management  

---

## 🚀 Installation & Setup  
### 1. Install Dependencies  
```bash
pip install -r requirements.txt
```

### 2. Set Up Environment Variables  
Create a `.env` file and configure your **Asana API key** and LLM model:  
```env
OPENAI_API_KEY=your_openai_api_key
ASANA_ACCESS_TOKEN=your_asana_access_token
ASANA_PROJECT_ID=your_project_id
LLM_MODEL=gpt-4o
Anthropic_API_KEY=your_anthropic_api_key
```

### 4️⃣ Run the Chatbot  
```bash
python agents.py

## 📜 Usage  
1️⃣ Start the AI assistant and interact using natural language commands.  
2️⃣ The assistant processes requests and creates tasks in Asana.  
3️⃣ AI dynamically decides when to invoke the Asana API for task creation.  
4️⃣ Chat history is maintained to enhance context-aware task management.

Example Interaction:  
```
User: "Create a task for submitting the monthly report by March 30."
AI: "Task 'Submit monthly report' created in Asana with a due date of March 30." 
