# Prompt Engineering LAB

## Overview

A well-written prompt helps an AI understand exactly what you want. One simple framework is to break every prompt into **six parts**:
In this lab, You will create a prompt that - along with the documents Provided to you - you will later use to Prompt Chat Gpt to create a Proposal to Improve Collaboration Between Sales and Marketing Teams. You will look into the individual parts and connect them to form your final prompt. you can access the examples but Try writing your own prompt using the framework before looking at the examples.



## 1. Persona

Defines who the AI should be, including its role, expertise, or perspective (e.g., teacher, software engineer, lawyer, copywriter). A clear persona helps shape the knowledge, vocabulary, and approach used in the response.


<details>
<summary>💡 Example</summary>

```
<persona>
You are a professional copywriter experienced in preparing business proposals for senior management.
</persona>
```

</details>

Note: the "< persona >" and "< /persona >" are called Delimiters. They are markers used to clearly separate different parts of a prompt, such as instructions, context, examples, or data. They help the AI distinguish between sections, reducing ambiguity and improving the accuracy of the response. Other than XML tags (< persona >) you can also use triple quotes ("""), and clearly labeled headings (=== Persona ===).

---

## 2. Context

Provides the background information the AI needs, such as the situation, goal, target audience, uploaded files, relevant history, or domain-specific details. Good context gives the AI enough information to understand why it's performing the task.

for this case your relevant data is within the files Marketing_Campaign_Results.pdf and Sales_Performance_Report_Q1_2026.pdf

[Sales_Performance_Report_Q1_2026.pdf](https://github.com/zoubidarezki-31/From-Prompting-Chaos-to-Consistency-The-6-Pillar-Framework-for-Scalable-AI-Outputs/edit/main/lab.md#:~:text=README.md-,Sales_Performance_Report_Q1_2026,-.pdf)

[Marketing_Campaign_Results.pdf](https://github.com/zoubidarezki-31/From-Prompting-Chaos-to-Consistency-The-6-Pillar-Framework-for-Scalable-AI-Outputs/edit/main/lab.md#:~:text=Marketing_Campaign_Results.-,pdf,-Proposal_%20Implementing%20a)


<details>
<summary>💡 Example</summary>

```
<Context>
Use the data from the uploaded reports "Marketing_Campaign_Results.pdf" and "Sales_Performance_Report_Q1_2026.pdf" as the primary source of information when preparing your proposal.
</Context>
```

</details>

---

## 3. Task

Clearly states what you want the AI to do, using specific action verbs like write, summarize, compare, analyze, explain, or generate. The task should leave little room for ambiguity.

Example task verbs:
- Explain
- Write
- Summarize
- Compare
- Analyze
- Generate
- Improve


<details>
<summary>💡 Example</summary>

```
<Task>
Write a proposal for senior management recommending ways to improve collaboration between the Sales and Marketing teams.
</Task>
```

</details>

---

## 4. Constraints

Defines the rules the AI must follow, including tone (e.g., professional, persuasive, friendly), audience (e.g., executives, customers, students), length, reading level, citation requirements, and any other guardrails.


<details>
<summary>💡 Example</summary>

```
<Constraints>
Use a Professional, objective, and persuasive tone. The proposal should: Identify the root causes of poor collaboration, Explain how these issues are affecting productivity; revenue; customer satisfaction; or other business outcomes, Support each major point with evidence from the uploaded files, Clearly cite which uploaded source each piece of evidence came from.
</Constraints>
```

</details>

---

## 5. Examples

Shows the AI what a successful response looks like by providing sample inputs, outputs, templates, or reference documents. Examples help the AI mimic the desired style, structure, or level of detail.


In this case you will Provide the example file "Proposal_Implementing_a_Company_Wide_Cybersecurity_Awareness_Training_Program.pdf" as an example of what you would want your output to look like. 
An example does not always have to be a file or text that you provide. You can also describe the style or format you want the AI to emulate by referencing something it is likely to recognize. For example, you could ask the AI to "write in the style of a formal business proposal" or "use clear, persuasive language similar to a TED Talk.", implement the same writing style such as that Martin Luther King. This allows you to guide the output even when you don't have a sample example.

[Proposal_Implementing_a_Company_Wide_Cybersecurity_Awareness_Training_Program.pdf](https://github.com/zoubidarezki-31/From-Prompting-Chaos-to-Consistency-The-6-Pillar-Framework-for-Scalable-AI-Outputs/edit/main/lab.md#:~:text=Proposal_%20Implementing%20a-,Company,-%2DWide%20Cybersecurity%20Awareness)

<details>
<summary>💡 Example</summary>

```
<Examples>
Use the uploaded file "Proposal_Implementing_a_Company_Wide_Cybersecurity_Awareness_Training_Program.pdf" only as an example of the desired writing style and overall proposal structure.
</Examples>
```

</details>

---

## 6. Format

Specifies how the final response should be organized, such as a business proposal, email, report, table, JSON, bullet list, Markdown document, or presentation with specific headings or sections.


<details>
<summary>💡 Example</summary>

```
<Format>
Format the proposal using the following sections:
Executive Summary
Current Challenges
Analysis
Recommendations
Expected Outcomes
Conclusion
</Format>
```

</details>

---

# Putting It All Together

A complete prompt combines all six parts.

<details>
<summary>💡 Complete Example Prompt</summary>

```
<persona>
You are a professional copywriter experienced in preparing business proposals for senior management.
</persona>

<Context>
Use the data from the uploaded reports "Marketing_Campaign_Results.pdf" and "Sales_Performance_Report_Q1_2026.pdf" as the primary source of information when preparing your proposal.
</Context>

<Task>
Write a proposal for senior management recommending ways to improve collaboration between the Sales and Marketing teams.
</Task>

<Constraints>
Use a Professional, objective, and persuasive tone. The proposal should: Identify the root causes of poor collaboration, Explain how these issues are affecting productivity; revenue; customer satisfaction; or other business outcomes, Support each major point with evidence from the uploaded files, Clearly cite which uploaded source each piece of evidence came from.
</Constraints>

<Examples>
Use the uploaded file "Proposal_Implementing_a_Company_Wide_Cybersecurity_Awareness_Training_Program.pdf" only as an example of the desired writing style and overall proposal structure.
</Examples>

<Format>
Format the proposal using the following sections:
Executive Summary
Current Challenges
Analysis
Recommendations
Expected Outcomes
Conclusion
</Format>
```

</details>


