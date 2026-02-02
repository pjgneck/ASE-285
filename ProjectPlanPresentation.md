# 📘 ASE-285 Project Plan Presentation  
## Chat GBT Clone

---

## 🧠 Project Overview

**Project Title:** Chat GBT Clone  
**Course:** ASE-285  
**Objective:**  
The Chat GBT Clone is a feature-rich conversational AI interface inspired by ChatGPT, with added **developer-focused tools** that provide transparency into **token usage** and **context window health**. The project aims to help users better understand how AI systems manage memory, prompts, and conversation limits while maintaining a familiar and intuitive chat experience.

---

## ❓ Problem Statement

Modern AI chat interfaces abstract away critical technical details such as token consumption and context limits. This lack of visibility makes it difficult for developers and advanced users to:

- Optimize prompts effectively  
- Prevent unexpected context loss  
- Understand model limitations  
- Debug prompt and memory-related issues  

**This project solves that problem** by offering real-time insight into how conversational AI systems manage tokens and context, all within a polished and familiar chat interface.

---

## 🎯 Project Goals

- Replicate the core ChatGPT user experience  
- Provide real-time transparency into token usage  
- Allow direct manipulation of system prompts  
- Support persistent, local-first conversations  
- Run seamlessly as both a web and desktop application  

---

## 🛠 Planned Features

### Core Chat Features
- Clean, ChatGPT-style conversational interface  
- Persistent chat history stored locally  
- Multi-conversation support  

### Developer-Focused Enhancements
- **Real-Time Token Counting**
  - Tracks input and output tokens per message  
- **Context Window Health Indicator**
  - Visual indicator showing remaining context capacity  
- **System Prompt Control**
  - Editable system prompt to modify AI behavior dynamically  

### Platform & Architecture
- **Hybrid Deployment**
  - Web Application (Browser-based)
  - Electron Desktop Application  
- **Local Persistence**
  - Chat history and settings stored locally  

---

## 📋 Project Requirements

### Functional Requirements
- Users can send and receive AI-generated messages  
- Conversations persist across sessions  
- Token usage updates in real-time  
- Context usage is visually displayed  
- Users can edit and apply system prompts  

### Non-Functional Requirements
- Responsive and intuitive UI  
- Low-latency message handling  
- Cross-platform desktop support  
- Local-first data storage (no cloud dependency required)  

### Technical Requirements
- JavaScript / TypeScript  
- Frontend framework (React or similar)  
- Electron for desktop deployment  
- API integration with a large language model  
- Local storage (IndexedDB / LocalStorage / filesystem)  

---

## 🧩 System Architecture (High-Level)

- **Frontend UI**
  - Chat interface
  - Token & context visualizers
- **Application Logic**
  - Message handling
  - Token calculation
  - Context tracking
- **Persistence Layer**
  - Local chat storage
  - User settings storage
- **Deployment Layer**
  - Web build
  - Electron wrapper  

---

## 🏃 Sprint Plan Overview

Development will follow an **Agile, sprint-based approach** with incremental feature delivery.

---

## 🚀 Sprint 1 Plan (Foundational Sprint)

### Sprint Goal
Establish the **core chat functionality** and application foundation.

### Sprint 1 Objectives
- Set up project structure and tooling  
- Build a basic chat UI  
- Enable message sending and receiving  
- Integrate AI API for responses  
- Implement basic local chat persistence  

### Sprint 1 Deliverables
- Functional chat interface  
- Ability to send prompts and receive responses  
- Conversations saved locally  
- Initial Electron or web deployment working  

### Sprint 1 Out of Scope
- Token counting  
- Context visualization  
- System prompt editing  

---

## 📅 Future Sprint Preview

- **Sprint 2:** Token counting + UI indicators  
- **Sprint 3:** Context window visualization  
- **Sprint 4:** System prompt controls  
- **Sprint 5:** Polishing, testing, and performance optimization  

---

## ✅ Success Criteria

- Stable chat experience across sessions  
- Accurate real-time token and context tracking  
- Intuitive UI suitable for both users and developers  
- Fully functional hybrid deployment  

---

## 📌 Conclusion

The Chat GBT Clone enhances traditional AI chat interfaces by exposing the mechanics behind conversational AI. By combining usability with transparency, this project delivers both an educational and practical tool for understanding modern AI systems.

---
