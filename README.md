# Video Cursor — Prompt → Explainer Video (WIP)

Video Cursor is a work-in-progress platform that takes a user’s learning prompt and turns it into a clear explainer video using AI + Manim.

I am currently building a basic version with two core pipelines:

### 1. Understanding Pipeline
- The user gives a prompt describing what they want to learn.  
- This is sent to an OpenAI model that deeply understands, expands, and structures the concept.  
- The output is a detailed explanation of what needs to be taught.

### 2. Manim Generation Pipeline
- The structured explanation is then passed to another model I'm developing.  
- This model generates Manim code to visually explain the concept.  
- The generated script will later be rendered into an animation/video.

---

## Future Possibilities
Things that can be added as the project grows:

- **RAG-powered document explainers** (upload a PDF/PPT → get a video explanation)  
- **Better visual styles**, alternative renderers  
- **Narration and voice generation**  
- **Improved prompt templates and learning modes**  
- **Multi-language video output**

---

## Current Focus
Setting up a reliable base workflow from **prompt → understood explanation → Manim code**.

