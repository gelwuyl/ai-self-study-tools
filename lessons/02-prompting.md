# Module 2: How to Write Good Prompts

**Duration:** ~35 minutes  
**Goal:** Learn practical techniques to get much better answers from any AI tool, grounded in Google’s official Gemini Prompting Guide 101

---

## 🤔 Why Does Prompting Matter?

AI tools like Gemini, ChatGPT, or Claude are powerful — but they don’t automatically know what you need. The quality of what you get back depends almost entirely on the quality of what you ask.

> **Garbage in, garbage out.** A vague question gets a vague answer. A well-structured prompt gets a precise, useful response.

Prompting is a skill anyone can learn. You don’t need to be a "prompt engineer" — just follow a simple structure.

---

## Technique 1: Gemini Prompt 101 — The 4-Component Framework

Google’s Gemini Prompting Guide 101 identifies **4 key components** that make up an effective prompt. You don’t need all 4 every time, but using even 2 or 3 will dramatically improve your results.

### The 4 Components

| Component | What It Means | Colour in Google’s Guide |
|-----------|--------------|--------------------------|
| **Persona** | Who should the AI act as? | 🔵 Blue |
| **Task** | What do you want it to do? *(most important — always use a verb)* | 🩷 Pink |
| **Context** | What background information does it need? | 🟡 Yellow |
| **Format** | How should the response look? | 🟢 Green |

> 💡 **Key tip from the guide:** The **Task** is the most important component. Always include a clear verb or command — *summarise*, *draft*, *explain*, *compare*, *create*.

### Seeing It in Action

Google’s guide uses this example prompt with each component colour-coded:

> *"**You are a program manager in [industry].** **Draft an executive summary email to [persona]** **based on [details about relevant program docs].** **Limit to bullet points.**"*

Broken down:
- 🔵 **Persona:** "You are a program manager in [industry]."
- 🩷 **Task:** "Draft an executive summary email to [persona]"
- 🟡 **Context:** "based on [details about relevant program docs]"
- 🟢 **Format:** "Limit to bullet points."

### Applying It to Data Science Study

**❌ Weak prompt:**
```
Explain transformers.
```

**✅ Strong prompt (using all 4 components):**
```
You are a data science educator teaching adult learners with no technical background.
Explain what a Transformer is in simple terms using one everyday analogy.
I’ve just read about it in the "Attention Is All You Need" paper but found it confusing.
Keep your answer under 150 words and avoid equations.
```

### 🏋️ Practice

Rewrite this weak prompt using the 4-component framework:
```
Tell me about neural networks.
```

---

## Technique 2: Make It a Conversation (Prompt Iteration)

One of the most important tips in the Gemini guide is this:

> **"Fine-tune your prompts if the results don’t meet your expectations. Use follow-up prompts and an iterative process of review and refinement to yield better results."**

Most people give up after one prompt. The real power comes from **continuing the conversation**.

### How Prompt Iteration Works

Think of Gemini or any AI as a capable colleague who just needs more direction. Your first prompt gets the conversation started — your follow-up prompts shape the output.

**Step 1 — Start with your best prompt:**
```
You are a data science educator.
Explain the concept of "overfitting" to someone with a business background.
Use a business scenario as the analogy.
```

**Step 2 — Refine based on the response:**
```
That’s helpful. Now make it shorter — just 3 sentences.
```

**Step 3 — Ask for a different angle:**
```
Now give me a visual analogy instead of a business one.
```

**Step 4 — Request a format change:**
```
Turn this into a bullet-point summary I could share with a colleague.
```

Each follow-up shapes the response closer to exactly what you need.

### 🏋️ Practice

Use the "Attention Is All You Need" paper in NotebookLM from Module 1 — or try with Gemini. Start with one prompt, then write at least 2 follow-up prompts to refine the answer.

---

## Technique 3: Ask AI Who Is the Expert (Assign a Role)

The Gemini guide’s "Leveling up" section includes this powerful tip:

> **"Assign a role. To encourage creativity, assign a role. You can do this by starting your prompt with language like: ‘You are the head of a creative department for a leading advertising agency...’"**

This technique is surprisingly powerful because **different experts explain things differently**. A statistician, a science journalist, and a teacher will each approach the same concept from a completely different angle. You get to choose the lens.

### The Two-Step Method

**Step 1 — Ask the AI to identify the best expert type:**
```
Who would be the best type of expert to explain "bias in AI models" 
to someone with a social science background?
```

The AI might respond: *"A data ethics researcher or AI fairness specialist who works with social scientists would be ideal."*

**Step 2 — Use that role in your next prompt:**
```
You are a data ethics researcher who specialises in explaining AI fairness 
to social scientists.
Explain how bias can enter an AI model using a social science research analogy.
Keep it to 3 short paragraphs.
```

### Why This Matters for Your Studies

When you’re studying data science with no technical background, getting the **right expert voice** can be the difference between understanding something and feeling more confused.

### 🏋️ Practice

Use this technique to get an explanation of **"training data"** tailored to your own background.

---

## Technique 4: Meta Prompt — Ask AI to Help You Prompt

A **Meta Prompt** is when you ask the AI to *help you write a better prompt* before you ask your actual question. The Gemini guide encourages this through the tip: *"Make Gemini your prompt assistant."*

### The Template

```
I want to ask an AI about [your topic].
Help me write a clear, detailed prompt that will get the best possible answer.
My goal is: [what you’re trying to achieve].
My background: [brief description of your level/context].
```

### Example

```
I want to ask an AI to help me understand the "Attention Is All You Need" paper.
Help me write a prompt that will get me a clear, beginner-friendly explanation.
My goal is to understand the core idea well enough to explain it to a classmate.
My background: I’m new to data science, no math or coding background.
```

The AI will generate a polished prompt for you. Then you **copy that prompt and use it**.

### 🏋️ Practice

Use the Meta Prompt technique to get help understanding any concept from Module 1 that still feels unclear.

---

## The 6 Quick Tips from Google’s Guide

These are directly from the Gemini Prompting Guide 101:

| # | Tip | What It Means |
|---|-----|--------------|
| 1 | **Use natural language** | Write as if speaking to a person. Full sentences work better than keywords. |
| 2 | **Be specific and iterate** | Tell Gemini exactly what to do. Use instructions *and* constraints. |
| 3 | **Be concise, avoid complexity** | Brief but specific. Avoid jargon in your prompt. |
| 4 | **Make it a conversation** | Follow up, refine, and build on responses. |
| 5 | **Use your documents** | Reference your own notes, papers, or files for personalised output. |
| 6 | **Make Gemini your prompt assistant** | Use Gemini to suggest and improve your own prompts. |

---

## Leveling Up: Advanced Tips

From the "Leveling up your prompt writing" section of the Gemini guide:

**Break it up** — If you need several things done, use separate prompts rather than one long one.

**Give constraints** — Add specifics like "in under 100 words" or "give me exactly 3 options."

**Ask for feedback** — Try: *"What questions do you have for me that would help you give a better answer?"*

**Consider tone** — Ask for outputs to be formal, casual, technical, or creative.

**Say it another way** — If the result isn’t quite right, rephrase rather than repeat.

---

## Putting It All Together

```
[Step 1 — Meta Prompt]
I want to understand why the Transformer architecture was such a big deal in AI.
Help me write a clear prompt to get a beginner-friendly explanation.
My background: adult learner, no technical background, just started a data science course.

[Step 2 — Using the 4 components + assigned role]
You are a science journalist who explains AI breakthroughs to general audiences.
Explain why the 2017 paper "Attention Is All You Need" was a turning point in AI.
I’m an adult learner with no math or coding background taking my first data science course.
Format as 3 short paragraphs: (1) the problem before, (2) the solution, (3) why it mattered.

[Step 3 — Iteration follow-up]
That’s great. Now give me one memorable analogy I could use to explain this to a friend.
```

---

## ✅ Module 2 Checklist

- [ ] Understand the 4 components: Persona, Task, Context, Format
- [ ] Rewrote a weak prompt using the framework
- [ ] Practised prompt iteration with at least 2 follow-up prompts
- [ ] Used "Assign a Role" to get a tailored explanation
- [ ] Used a Meta Prompt to generate a better question
- [ ] Applied the 6 quick tips in your own prompting

---

## 🔗 Further Reading

- [Google Gemini Prompting Guide 101](https://services.google.com/fh/files/misc/gemini_for_workspace_prompt_guide_october_2024_digital_final.pdf) ← the source for this module
- [Anthropic Prompt Engineering Guide](https://platform.claude.com/docs/en/build-with-claude/prompt-engineering/overview)
- [Prompt Templates →](../resources/prompt-templates.md)

---

**← [Back to Module 1](01-notebooklm.md) | [Back to Home](../README.md)**
