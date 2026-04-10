# Module 1: Google NotebookLM

**Duration:** ~35 minutes  
**Goal:** Use NotebookLM to read a real AI research paper without getting overwhelmed

---

## 🤔 Why NotebookLM?

Research papers are the primary way that discoveries in AI and data science are shared. But they're often dense, jargon-heavy, and hard to follow — even for experienced practitioners.

**NotebookLM** is a free AI tool from Google that lets you upload documents and then *talk to them*. Instead of reading every word, you can ask questions, get summaries, and even listen to a podcast-style audio overview — all grounded in the actual content of the paper.

> Think of it as having a very patient, very well-read study partner who has read the whole paper and is ready to explain any part of it to you.

---

## 📄 Our Example: "Attention Is All You Need"

We'll use the landmark 2017 paper that introduced the **Transformer** — the architecture behind ChatGPT, Gemini, and virtually every modern AI language model.

📎 **Paper link:** https://arxiv.org/pdf/1706.03762

You don't need to understand the math. The goal is to use NotebookLM to extract meaning from it.

---

## 🚀 Step-by-Step: Getting Started

### Step 1 — Open NotebookLM
1. Go to [notebooklm.google.com](https://notebooklm.google.com)
2. Sign in with your Google account
3. Click **"New Notebook"**

### Step 2 — Add the Paper as a Source
1. Click **"+ Add source"**
2. Choose **"Link"** and paste: `https://arxiv.org/pdf/1706.03762`  
   *(Or download the PDF and upload it directly)*
3. Wait a moment — NotebookLM will read and index the paper

### Step 3 — Generate the Notebook Guide
- On the right panel, click **"Notebook Guide"**
- This gives you an instant **summary**, **key topics**, and **suggested questions**
- Read it. This is your map of the paper.

---

## 🎧 Feature 1: Audio Overview

The Audio Overview turns the paper into a short, conversational **podcast episode** where two AI hosts discuss the key ideas.

**How to use it:**
1. In the Notebook Guide, click **"Generate"** under Audio Overview
2. Wait ~1 minute for it to generate
3. Press play 🎧

**While listening, note:**
- What problem were the researchers trying to solve?
- What is "attention" in plain English?
- Why did this paper matter?

---

## 💬 Feature 2: Chat / Q&A

You can ask the paper anything in plain English. NotebookLM answers using only what's in the paper — it won't make things up.

**Try these questions (copy and paste them):**

```
What problem does this paper solve?
```

```
What is "attention" and why is it useful? Explain it like I'm new to this field.
```

```
What were the key results? How did the Transformer compare to previous models?
```

```
What are the limitations of this approach mentioned in the paper?
```

**Pro tip:** If an answer is confusing, follow up with:
```
Can you give me a simple analogy to help me understand that?
```

---

## 🗺️ Feature 3: Mind Map

NotebookLM can generate a visual map of the paper's key concepts and how they connect.

1. In the Notebook Guide, look for **"Mind Map"**
2. Click to generate
3. Use it to understand the structure of the paper at a glance

---

## ✏️ Hands-On Practice (15 minutes)

Work through these on your own or in pairs:

**Task 1:** Generate the Audio Overview and listen for 5 minutes. Write down 2 things you learned.

**Task 2:** Ask at least 3 questions of your own — things you're genuinely curious or confused about.

**Task 3:** Ask NotebookLM:
```
If I'm a beginner in machine learning, what concepts do I need to understand before I can fully appreciate this paper?
```

---

## 💡 Tips for Using NotebookLM Well

- **Be specific in your questions.** "Explain Section 3.2" works better than "explain everything."
- **Ask for analogies.** "Give me an everyday analogy for this concept" often unlocks understanding.
- **Add multiple sources.** You can add lecture notes, articles, and papers together — then ask questions across all of them.
- **Use it for your coursework.** Any PDF, Google Doc, or webpage can be a source.

---

## 🔬 Exercise 2: Using the Research Feature — Learning Git & GitHub as a Beginner

**Duration:** ~20 minutes  
**Goal:** Use NotebookLM's Research feature to teach yourself a brand-new technical topic with scaffolded guidance

In your data science course, you'll need to use **Git** and **GitHub** — tools for saving and sharing your work. They're unfamiliar to most beginners. This exercise shows you how to use NotebookLM to research and understand any new technical topic before you're thrown into the deep end.

> 💡 **What is the Research feature?**  
> Instead of uploading a single document, you add **multiple web sources** on the same topic — official docs, beginner guides, tutorials — and then ask NotebookLM questions that draw on *all of them at once*. It becomes your personalised research assistant on that topic.

---

### Step 1 — Create a New Notebook

1. Go to [notebooklm.google.com](https://notebooklm.google.com)
2. Click **"New Notebook"** — give it the title: `Git & GitHub Basics`

---

### Step 2 — Add Your Research Sources

Click **"+ Add source"** → choose **"Website"** and add each of these links one at a time:

| Source | What It Covers |
|--------|---------------|
| `https://docs.github.com/en/get-started/start-your-journey/about-github-and-git` | What Git and GitHub are |
| `https://docs.github.com/en/get-started/start-your-journey/hello-world` | Your first repo, step by step |
| `https://docs.github.com/en/get-started/using-git/about-git` | How Git works under the hood |

> Wait for all 3 sources to load before continuing — you'll see a tick next to each when they're ready.

---

### Step 3 — Generate the Notebook Guide

Click **"Notebook Guide"** in the right panel. Read the summary. This gives you the lay of the land before you start asking questions.

---

### Step 4 — Scaffolded Research Questions

Work through these questions **in order**. Each level builds on the last. Copy and paste them into the chat.

---

#### 🟢 Level 1 — Foundation: What Are These Tools?

These questions establish the basics. Don't skip them even if they feel too simple.

```
What is Git, and what problem does it solve? Explain it as if I've never used it before.
```

```
What is GitHub, and how is it different from Git?
Use a simple analogy — for example, compare it to something I might already use in daily life.
```

```
What is a "repository"? Give me a real-world analogy.
```

---

#### 🟡 Level 2 — Core Concepts: The Building Blocks

These are the terms you'll hear constantly. Build a mental model for each one.

```
Explain what a "commit" is in plain English.
Why would I want to save my work this way instead of just pressing Ctrl+S?
```

```
What is a "branch" and why would someone use one?
Explain it using a story or scenario that a beginner could follow.
```

```
What is a "pull request"? Walk me through what actually happens when someone creates one.
```

```
I keep seeing the words "push" and "pull" in GitHub tutorials. 
What do they mean, and how are they different?
```

---

#### 🔵 Level 3 — The Workflow: How It All Fits Together

Now connect the concepts into a sequence you can remember.

```
Imagine I'm a student working on a data science project.
Walk me through the basic GitHub workflow from start to finish —
from creating a repository to sharing my work with a classmate.
Keep it simple and use the terms I've just learned.
```

```
What are the most common mistakes beginners make when using Git for the first time?
How can I avoid them?
```

---

#### 🟣 Level 4 — Reflection and Application

Check your understanding and connect it to your course.

```
Based on everything in these sources, what are the 5 most important things 
a complete beginner needs to understand about Git and GitHub?
Give me a numbered list with a one-sentence explanation for each.
```

```
Create a simple glossary of the 8 most important Git/GitHub terms for a beginner.
For each term: the word, a one-line plain-English definition, and one example of when you'd use it.
```

```
I'm going to start a data science course soon. 
Based on these sources, what should I do in GitHub this week to prepare?
Give me 3 concrete actions, each taking less than 10 minutes.
```

---

### Step 5 — Create Your Personal Study Notes

Use NotebookLM to generate a study guide you can keep:

```
Based on all the sources in this notebook, write me a one-page beginner's guide to Git and GitHub.
Format it as: (1) What it is in 2 sentences, (2) The 5 key concepts, (3) The basic workflow in 4 steps,
(4) 3 things to remember when you're stuck.
```

You can copy this into a Google Doc or Notion page for future reference.

---

### 🪜 Scaffolding Notes for Facilitators

*This section is for instructors — learners can skip it.*

The 4-level structure above is intentional:

- **Level 1 (Green)** removes the fear of blank-page confusion by giving learners immediate, simple wins. Even learners who "know" what Git is benefit from having it confirmed in their own words.
- **Level 2 (Yellow)** introduces vocabulary in context rather than as a glossary. The story/scenario prompts activate prior knowledge.
- **Level 3 (Blue)** forces synthesis — learners must connect individual concepts into a process. This is where real understanding forms.
- **Level 4 (Purple)** shifts from reception to production. Asking learners to summarise and plan activates metacognition.

If a learner gets stuck at any level, encourage them to ask NotebookLM: *"I don't understand your answer. Can you explain it differently using a different analogy?"*

---

## ✅ Module 1 Checklist

- [ ] Created a NotebookLM notebook for "Attention Is All You Need"
- [ ] Added the paper as a source
- [ ] Generated and read the Notebook Guide
- [ ] Listened to at least part of the Audio Overview
- [ ] Asked at least 3 questions in the chat
- [ ] Written down 2 things I learned
- [ ] Created a new notebook: "Git & GitHub Basics"
- [ ] Added all 3 web sources
- [ ] Worked through at least Levels 1 and 2 of the scaffolded questions
- [ ] Generated a personal study guide for Git/GitHub

---

**Next up → [Module 2: How to Write Good Prompts](02-prompting.md)**
