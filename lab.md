# Prompt Engineering LAB

## Overview

A well-written prompt helps an AI understand exactly what you want. One simple framework is to break every prompt into **six parts**:

1. Persona
Defines who the AI should be, including its role, expertise, or perspective (e.g., teacher, software engineer, lawyer, copywriter). A clear persona helps shape the knowledge, vocabulary, and approach used in the response.
2. Context
Provides the background information the AI needs, such as the situation, goal, target audience, uploaded files, relevant history, or domain-specific details. Good context gives the AI enough information to understand why it's performing the task.
3. Task
Clearly states what you want the AI to do, using specific action verbs like write, summarize, compare, analyze, explain, or generate. The task should leave little room for ambiguity.
4. Constraints
Defines the rules the AI must follow, including tone (e.g., professional, persuasive, friendly), audience (e.g., executives, customers, students), length, reading level, things to include or avoid, citation requirements, and any other guardrails.
5. Examples
Shows the AI what a successful response looks like by providing sample inputs, outputs, templates, or reference documents. Examples help the AI mimic the desired style, structure, or level of detail.
6. Format
Specifies how the final response should be organized, such as a business proposal, email, report, table, JSON, bullet list, Markdown document, or presentation with specific headings or sections.

---

# The 6 Parts of a Great Prompt

## 1. Persona

**Question:** Who is the AI?

Give the AI a role or identity. This helps establish expertise and perspective.

Examples:
- A software engineer
- A history teacher
- A career coach
- A professional editor

> Think: "Who should the AI pretend to be?"

<details>
<summary>💡 Example</summary>

```
You are a senior software engineer with 10 years of experience mentoring junior developers.
```

</details>

---

## 2. Context

**Question:** What is the situation?

Provide the background information the AI needs to understand the problem.

Include:
- The goal
- Relevant information
- Audience
- Current situation

> Think: "What does the AI need to know before it starts?"

<details>
<summary>💡 Example</summary>

```
I'm preparing for a technical interview next week. I've been studying Python for six months and struggle with recursion.
```

</details>

---

## 3. Task

**Question:** What should the AI do?

State the job clearly and directly.

Good task verbs:
- Explain
- Write
- Summarize
- Compare
- Analyze
- Generate
- Improve

> Think: "What exactly do I want?"

<details>
<summary>💡 Example</summary>

```
Explain recursion in simple language and provide three practice problems.
```

</details>

---

## 4. Constraints

**Question:** What rules should the AI follow?

Constraints help narrow the response.

Examples:
- Tone
- Length
- Reading level
- Things to avoid
- Style

> Think: "What should the response look or sound like?"

<details>
<summary>💡 Example</summary>

```
Keep the explanation under 300 words.
Use beginner-friendly language.
Avoid advanced mathematical notation.
```

</details>

---

## 5. Examples

**Question:** Can you show the AI what you want?

Examples are one of the most powerful prompting techniques because they demonstrate the expected style or structure.

You can provide:
- Sample input/output
- Desired writing style
- Templates

> Think: "Can I show instead of just tell?"

<details>
<summary>💡 Example</summary>

```
Example:

Question:
What is a variable?

Answer:
A variable is like a labeled box where you can store information to use later in your program.
```

</details>

---

## 6. Format

**Question:** How should the answer be organized?

Specify how you want the output presented.

Examples:
- Bullet list
- Numbered steps
- Markdown
- Table
- JSON
- Essay
- Email

> Think: "What should the finished product look like?"

<details>
<summary>💡 Example</summary>

```
Return your answer as:

# Summary

## Key Ideas

- ...

## Practice Problems

1.
2.
3.
```

</details>

---

# Putting It All Together

A complete prompt combines all six parts.

<details>
<summary>💡 Complete Example Prompt</summary>

```
Persona:
You are an experienced Python instructor.

Context:
I'm preparing for my first programming interview and have been learning Python for six months.

Task:
Teach me recursion and give me practice exercises.

Constraints:
Keep the explanation beginner-friendly.
Limit it to about 500 words.
Avoid unnecessary jargon.

Examples:
Explain concepts using simple analogies.

Format:
Use Markdown with headings, bullet points, and a numbered list of exercises.
```

</details>

---

# Challenge

Try writing your own prompt using the framework before looking at the examples.

| Part | Your Answer |
|------|-------------|
| Persona | |
| Context | |
| Task | |
| Constraints | |
| Examples | |
| Format | |

Once you've finished, compare your answers with the hidden examples above.
