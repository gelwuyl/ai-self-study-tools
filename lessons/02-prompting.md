# Module 2: How to Write Good Prompts

**Duration:** ~35 minutes  
**Goal:** Learn 3 practical techniques to get much better answers from any AI tool

---

## 🤔 Why Does Prompting Matter?

AI tools like Gemini, ChatGPT, or Claude are powerful — but they don't automatically know what you need. The quality of what you get back depends almost entirely on the quality of what you ask.

> **Garbage in, garbage out.** A vague question gets a vague answer. A well-structured prompt gets a precise, useful response.

This module gives you three techniques you can use immediately.

---

## Technique 1: Gemini Prompt 101

Google's Gemini team distilled prompting into a simple framework with **5 components**. You don't need all 5 every time — but using even 2 or 3 dramatically improves your results.

### The Framework: **PCTOF**

| Component | What It Means | Example |
|-----------|--------------|---------|
| **P — Persona** | Who should the AI act as? | *"Act as a data science instructor..."* |
| **C — Context** | What's the background situation? | *"...teaching adult learners with no coding background..."* |
| **T — Task** | What do you want it to do? | *"...explain what a neural network is..."* |
| **O — Output** | What format should the response be? | *"...in a short paragraph with one analogy..."* |
| **F — Format / Constraints** | Any rules or restrictions? | *"...avoid technical jargon. Max 150 words."* |

### Example — Weak vs. Strong Prompt

**❌ Weak:**
```
Explain neural networks.
```

**✅ Strong (using PCTOF):**
```
Act as a data science instructor for adult learners with no coding experience.
Explain what a neural network is in plain English using one real-world analogy.
Keep it under 150 words and avoid technical jargon.
```

### 🏋️ Practice

Try rewriting this weak prompt using PCTOF:
```
Tell me about transformers.
```

---

## Technique 2: Ask AI Who Is the Expert

This technique is surprisingly powerful. Instead of jumping straight to your question, you first **ask the AI to identify who the best person would be to answer it** — then ask it to respond as that person.

### Why It Works

Different experts explain things differently. A statistician, a software engineer, and a science communicator will each explain "machine learning" in a completely different way. This technique lets you choose the lens.

### The Template

```
Who would be the best type of expert to explain [topic] to [audience]?
Then respond as that expert.
```

### Example

**Step 1 — Ask who the expert is:**
```
Who would be the best type of expert to explain the concept of "overfitting in machine learning" 
to someone who is new to data science and comes from a business background?
```

**The AI might say:** *"A data science educator or applied ML practitioner who specialises in translating technical concepts for non-technical stakeholders."*

**Step 2 — Use that answer in your next prompt:**
```
Act as a data science educator who specialises in explaining ML concepts to business professionals.
Explain overfitting in a way that uses a business scenario as the analogy. Keep it concise.
```

### 🏋️ Practice

Use this technique to get an explanation of **"bias in AI models"** tailored for someone from a humanities background.

---

## Technique 3: Meta Prompt

A **Meta Prompt** is when you ask the AI to *help you write a better prompt* before you actually ask your real question.

This is especially useful when you're not sure how to phrase something, or when you want to unlock the best possible answer.

### The Template

```
I want to ask an AI about [your topic].
Help me write a clear, detailed prompt that will get the best possible answer.
My goal is: [what you're trying to achieve].
My background: [brief description of your level/context].
```

### Example

```
I want to ask an AI to help me understand a research paper about transformer models.
Help me write a prompt that will get me a clear, beginner-friendly explanation.
My goal is to understand the core idea well enough to explain it to a colleague.
My background: I'm new to data science and have no math or coding background.
```

The AI will generate a polished prompt for you. Then you **copy that prompt and use it**.

### 🏋️ Practice

Use the Meta Prompt technique to get help understanding any concept from the "Attention Is All You Need" paper that confused you in Module 1.

---

## Putting It All Together

These three techniques work well in combination. Here's a workflow:

1. **Start with Meta Prompt** → Ask AI to help you craft the best question
2. **Apply PCTOF** → Structure the prompt with persona, context, task, output, format
3. **Use "Who is the Expert?"** → Make sure the persona is the right one for your needs

### Full Example

```
[Meta Prompt]
I want to understand why the Transformer architecture was a breakthrough in AI.
Help me write a clear prompt to get a beginner-friendly explanation.
My background: adult learner, no technical background, taking a data science course.

[Then, using the result with PCTOF + Expert]
Act as a science communicator who explains AI research to general audiences.
I'm an adult learner with no technical background taking my first data science course.
Explain why the 2017 paper "Attention Is All You Need" was a breakthrough, using an everyday 
analogy. Format as 3 short paragraphs: the problem before, the solution, and why it mattered.
```

---

## ✅ Module 2 Checklist

- [ ] Understood the PCTOF framework and rewrote a weak prompt
- [ ] Used "Who is the Expert?" to get a tailored explanation of a concept
- [ ] Used Meta Prompt to generate a better question
- [ ] Combined all three techniques in one prompt

---

## 🔗 Further Reading

- [Google Gemini Prompting Guide 101](https://services.google.com/fh/files/misc/gemini-for-google-workspace-prompting-guide-101.pdf)
- [Anthropic Prompt Engineering Guide](https://docs.claude.ai/en/docs/build-with-claude/prompt-engineering/overview)
- [Prompt Templates →](../resources/prompt-templates.md)

---

**← [Back to Module 1](01-notebooklm.md) | [Back to Home](../README.md)**
