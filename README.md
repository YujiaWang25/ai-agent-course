[README.md](https://github.com/user-attachments/files/31588124/README.md)
# AI Learning Course: Zero-Basis AI Agent Development

> *A self-developed AI curriculum built with the assistance of Trae.*

## 1.0 Motivation

I’ve always been interested in AI, but as someone who didn’t come from a technical background, I found it really hard to get started. There’s so much information out there, but most courses are either too theoretical (all math and algorithms) or too superficial (just “how to use ChatGPT”). I wanted something practical—something that would teach me how to actually work with AI day-to-day.

That’s why I decided to build this course. At first, it was just for me—a way to organize what I was learning and make sense of this new field. But as I went along, I realized other people might benefit from it too. So this course serves two purposes: it’s my personal learning resource, and it’s something I can share with others who are in the same boat.

Here are the main things I wanted to figure out when I started:

First, what *actually* is AI? Like, how does it work under the hood? I didn’t want to just use tools blindly. Understanding that AI is basically a really advanced autocomplete—predicting what word comes next—helped me set realistic expectations. It’s not magic, and it’s not perfect. That realization changed how I interact with AI tools.

Second, how do you talk to AI effectively? I’d spend hours trying to get AI to do what I wanted, only to get frustrating results. Turns out, the problem was usually my prompts—they were too vague or lacked context. I wanted to learn the skill of asking good questions, setting constraints, and giving AI the right information to work with.

Third, how do you trust what AI says? It makes stuff up sometimes, and that’s a big problem if you’re using it for work or learning. I needed strategies to verify AI outputs—cross-checking, asking it to explain itself, that kind of thing. Most courses skip this, but I think it’s essential, especially for beginners.

Fourth, how do you go from playing around with AI to actually building something useful? It’s one thing to generate a demo, but another to make something reliable that you can actually use. I wanted to learn about deployment, monitoring, and error handling—skills that feel more like engineering than just “using AI.”

So this course is my way of working through these questions. I built it using Trae as a collaborator—sort of like having a study buddy who can help draft ideas and work through problems. The process of creating each lesson forced me to understand the material deeply, which is why I think this approach works so well for learning.

## 2.0 Tech Stack

- **Language**: Python 3.x
- **Framework**: None (focus on AI collaboration and agent engineering concepts rather than ML frameworks)
- **AI Assistant**: Trae (for content generation, code debugging, and curriculum design)

## 3.0 Course Structure

The course has four stages with 45 lessons total. It’s designed for people who have never coded before, and each lesson follows a similar pattern: lecture, hands-on practice, self-study, and assignments.

### Stage 1: Cognitive Foundation (5 lessons)

**Goal**: Understand what AI is and how to think about working with it.

This first stage is all about building the right mental models. When I started learning, I had so many misconceptions about AI—this stage helped me clear those up and develop a deeper sense of how LLMs actually work.

- **Lesson 1**: The Nature of Large Language Models—explains that AI predicts the next most probable word, using examples like phone keyboard autocomplete. We play around with token visualization and test what AI is good and bad at.
- **Lesson 2**: AI Collaboration Basics—covers how to ask precise questions, including why context, constraints, and format matter.
- **Lesson 3**: Prompt Engineering Fundamentals—goes into techniques like few-shot learning, role prompting, and chain-of-thought reasoning.
- **Lesson 4**: Requirement Description Practice—uses the Markdown-to-Word project as an example to teach how to turn vague ideas into clear tasks for AI.
- **Lesson 5**: AI Industry Overview—looks at the bigger picture: major models like GPT and Claude, the tools people use, and what kinds of jobs involve AI.

### Stage 2: Collaboration Essentials (8 lessons)

**Goal**: Develop practical skills for working with AI through hands-on projects.

Building on the first stage, this part focuses on applying what you’ve learned. I found that doing actual projects was the best way to solidify my understanding.

- **Lessons 6-8**: Core skills like generalization (finding patterns that work across different cases), output control (getting AI to follow specific formats), and debugging (figuring out why AI gave a bad answer and how to fix it).
- **Lesson 9**: Building the first rule-based agent—we create a simple agent using basic if-then logic to get a feel for how agents work.
- **Lessons 10-13**: The Markdown-to-Word project. This is the main project for this stage. We use AI to build a tool that converts Markdown files to Word documents, going through the whole process: defining what we need, setting up the environment, generating code, testing it, fixing problems, and iterating.

### Stage 3: Agent Engineering (18 lessons)

**Goal**: Learn engineering approaches for building more advanced AI agents.

This is the longest stage, covering more complex concepts and practices. As I got deeper into AI, I realized that building reliable agents requires more than just good prompts—it requires engineering practices.

- **Lessons 14-21**: Core engineering ideas like boundary engineering (deciding what AI should and shouldn’t handle), reasoning mechanisms (teaching AI to think step by step), self-iteration (letting AI review and improve its own work), tool calling (connecting AI to external tools like APIs), and workflow orchestration (designing sequences of tasks for agents).
- **Lessons 22-29**: More advanced topics including multimodal AI (working with text, images, and audio), RAG (retrieval-augmented generation, which lets AI look up information from documents), validation engineering (building systems to check AI outputs), agent frameworks like LangChain and LangGraph, and planning patterns like ReAct and Tree of Thought.
- **Lessons 30-31**: Project deepening—we take our Markdown-to-Word tool from something that works to something production-ready, focusing on code quality, documentation, and packaging.

### Stage 4: Practical Application (14 lessons)

**Goal**: Apply skills to real-world scenarios and prepare for using AI professionally.

The final stage wraps everything up with practical applications and career guidance. This is where we take everything we’ve learned and figure out how to use it in the real world.

- **Lessons 32-41**: Advanced topics like agent memory, how multiple agents can work together, low-code agent development, comprehensive project practice with code review, thinking about AI from a product perspective, and expanding features.
- **Lessons 42-45**: Deployment and career—moving agents from local development to the cloud, iterating based on user feedback, looking at real industry examples (education, healthcare, enterprise), and wrapping up with advice on AI-related careers.

## 4.0 Key Highlights

- Covers 45 complete lessons across AI cognition, prompt engineering, and agent development, each designed as a 40-minute teaching script.
- Uses the Markdown-to-Word project as a running example throughout the course, showing the full workflow from idea to deployed tool.
- Implements the “Four Beams and Eight Pillars” framework—a structured approach to developing AI collaboration skills across four areas: meta-cognition, decomposition, validation, and intuition.
- Focuses on real-world readiness with practical tools like deployment checklists, monitoring strategies, rollback plans, and cost control for AI applications.
- Designed for absolute beginners, emphasizing working with AI rather than writing code from scratch.
- Created as a personal learning resource by someone who was also new to the field.

## 5.0 Reflection

Building this course has been my way of teaching myself AI. The biggest lesson I learned is that “teaching” is the best way to learn. When you have to explain a concept clearly enough for someone else to understand, you realize how much you actually know—and how much you don’t. There were countless times when I thought I understood something, only to get stuck trying to write a lesson about it. That forced me to go back, do more research, and really figure it out.

Working with Trae was a huge part of this process. At first, I thought of AI as a tool to generate content quickly. But as I went along, I realized it’s more like a collaborator. Trae would help me brainstorm ideas, draft sections, and even point out gaps in my understanding. But here’s the thing: it wasn’t perfect. Sometimes it would generate content that sounded good but was actually wrong or too abstract. I had to learn to be critical of what it produced—to check facts, simplify explanations, and make sure the material was actually useful for beginners.

One of the most rewarding things was seeing how much I progressed. When I started, I could barely write a decent prompt. Now, I can design complex agent workflows and debug AI outputs systematically. That growth didn’t come from just reading books—it came from building this course, one lesson at a time.

For the future, I have a few goals. First, I want to keep expanding the course with more advanced content, especially around specific frameworks like LangGraph and LlamaIndex. Second, I’d like to add more hands-on projects so learners (including myself) can practice what they’ve learned. Third, I want to keep updating the course as AI evolves—new models and tools come out all the time, and I want this to stay relevant. Finally, I’d love to connect with other learners who are going through similar journeys—sharing notes and projects would make the learning process more fun and effective.

This course is my personal AI learning journey documented. It’s not perfect, and I’m still learning every day. But putting it all together has been one of the most valuable learning experiences I’ve had. My hope is that it helps others too—whether you’re a complete beginner or someone who wants to get better at working with AI.

---

*Built with Trae | 45 Lessons | Zero-Basis AI Agent Development*
