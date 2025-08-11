---
layout: post  
title: AI in Education - For Teachers  
date: 2025-08-08 15:34:00 +0300  
categories: [blog, education]  
tags: [learning, teaching, AI in Education]  
# excerpt: A warm welcome to my corner of the internet — a space for learning, creating, reflecting, and growing across disciplines.  
# image: /assets/img/welcome.jpg  
---

This blog explores useful AI tools and solutions for teachers. I have focused on free, open-source, or freemium options where applicable.  

### 1. Planning / Documentation (Lesson plans/activities) 
To plan exclusively within a specific book's context or a source, choose [NotebookLM](https://notebooklm.google.com/), 
For general purposes, use [Magicschool.ai](http://magicschool.ai/) or any other Generative AI tool(refer to section 4).

### 2. Gamification 
[Curipod](http://www.curipod.com) (Curipod ppt lessons + kahoot like activities, + activity insights & reports for all students), 
[Blooket](http://www.blooket.com), 
[Quizziz](https://quizizz.com/), 
[Jeopardy Labs](https://jeopardylabs.com/), 
[Magicschool.ai](http://magicschool.ai/), 
[padlet](http://padlet.com), 
slido (a slide extension)

### 3.  Quiz/Assessments
[Exam Mate](http://www.exam-mate.com), 
[Humata](http://www.humata.ai), 
[Magicschool.ai](http://magicschool.ai/), 
[NotebookLM](https://notebooklm.google.com/), 
[Socrative](https://www.socrative.com/)

### 4. Generative AIs(for asking questions and getting responses)
[Claude](http://www.claude.ai),
[Gemini](https://gemini.google.com/), 
[Chatgpt](http://www.chatgpt.com), 
[Perplexity](http://www.perplexity.ai), 
[Copilot](https://gemini.google.com/app), 
[Grok](https://grok.com/)

### 5.  Preparing Presentations/apps/quiz apps
[Curipod](http://curipod.com), 
[Magicschool.ai](http://magicschool.ai/), 
[Gamma.app](https://gamma.app/), 
Slido(An extension for Microsoft PowerPoint and Google Docs), 
[Chalkie](https://chalkie.ai),
[NotebookLM](https://notebooklm.google.com/)(for creating ppt content restricted to your sources:textbook or curriculum specific, etc), 

### 6. All-in-one your own Resource repository (free website can be easily published/shared)
[Notion](http://notion.com/), 

### 7. For online classes : whiteboard
[Microsoft Whiteboard](http://notion.com/) Free Save-able Whiteboard (saves your whiteboard lifetime), 
[Excalidraw](https://excalidraw.com/) (Free open source) 

### 8. For recording classes : 
Free and easy video/lesson recording, [ShareX](https://getsharex.com/)

### 9. Mind Mapping/Visualizing Free Tool
[NotebookLM](https://notebooklm.google.com/)
[Draw.io](http://draw.io) 


### 10. Voice Typing notes
[Google Docs](https://docs.google.com/document) (new blank doc -> Tools -> Voice Typing) 
 
### 11. Audio to Text (Multi-lingual)
[Huggingface.co (Whisper ai)](https://huggingface.co/spaces/openai/whisper)

### 12. Events
[Canva](http://www.canva.com), 
[Text to Video: Synthesia](http://www.synthesia.io)

### 13. Search for all AI tools & Solutions
[There is an AI for that](https://theresanaiforthat.com/)

### 14. Flashcards 
[Quizlet](https://quizlet.com/sa),
[Canva](http://www.canva.com), 
[Flash Card Machine](http://flashcardmachine.com)

### 15. YouTube Video Summarizer
[Eightify](https://eightify.app/)

---

## Introduction to Prompt Engineering

If you’ve ever chatted with ChatGPT or asked an AI tool to create a picture, you’ve already dipped your toes into prompt engineering—even if you didn’t realize it! 
Prompt engineering sounds fancy, but it’s simply the skill of crafting clear and effective instructions (or “prompts”) to get the best possible responses from artificial intelligence (AI) systems.

---

## Prompting Techniques for Any Generative AI

When writing prompts for tools like Claude, Grok, ChatGPT, Gemini, always try to include these four components at the beginning of your prompt chat:

1.  **Role:** Define the role the AI should play (e.g., "You are a tech-savvy person and a history teacher...").
2.  **Goal:** State the specific task you want the AI to accomplish (e.g., "Give me a lesson plan...").
3.  **Context:** Provide the necessary background information for the question (e.g., "The students are 10th graders...").
4.  **Format:** Specify how you want the response to be structured (e.g., "Give me in an Excel format...").
5.  **Example (optional):** To show the pattern you want, you can say, "The pattern is:..."

**Key Rule:** Always start a new chat for a new topic to keep the context clean.

---

## Prompt Examples

* **Flashcard Prompt for EXCEL Format:**
If you need Flashcard in a certain format that you want, instead of copy pasting to do your bulk upload, you can ask the GenAI to create that format for you. Imagine this in any given scenario:
    * **Prompt:** `You are a tech savvy person and a <xyz subject Teacher>. create flashcard for flashcard machine website import option. here is the entire content of flashcards: “<paste your topic content here, inside the double quotes >”. Ensure the flashcards MUST be in EXCEL format. For example, the first term must be in row 1, column 1, and its definition in row 1, column 2.`

* **Lesson Plan Prompt for NoteBookLM (after uploading a textbook):**
    * **Prompt:** `Generate a lesson plan for chapter 1, for pages between 1 and 56: follow BLOOMS taxonomy. make sure to include enrichment activities.`

* **Quiz Worksheet Prompt for NoteBookLM (to extract questions from specific content):**
    * **Prompt:** `Generate 10 MCQ style questions from the attached book, chapter 1 between pages 1 and page 56: make sure to give answers only at the end.`
    
    
    
    
    
    
    🌿
