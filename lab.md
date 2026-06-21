# Prompt Engineering LAB



# Section 1

If you don't already have a ChatGPT account, start by creating one. Right-click the link below and open it in a new tab.

[Chat GPT](https://chatgpt.com/?utm_source=google&utm_medium=paid_search&utm_campaign=GOOG_C_SEM_GNB_Core-Thematic_CHT_BAU_ACQ_PER_BRD_ALL_NAMER_US_EN_112624&c_id=21957315043&c_agid=170788222069&c_crid=723092045958&c_kwid=kwd-1884437950226&c_ims=&c_pms=9193836&c_nw=g&c_dvc=c&gad_source=1&gad_campaignid=21957315043&gbraid=0AAAAA-I0E5esqLvkNwW4XkK-q1G93BEag&gclid=CjwKCAjw6MPRBhBTEiwAd-7Mr3YDGVJCzDlNlrkFn1v12jJqzMcoYlGbORweiaMdyEEItSD8dksqZhoC-HgQAvD_BwE)

Once the new tab opens, click the "Sign up for free" button in the top-right corner, as shown below.

<img width="3456" height="2172" alt="image" src="https://github.com/user-attachments/assets/9da6c679-1f19-40bb-8810-0c9959878711" />

You can sign up using your email address, Google account, Apple account, or phone number. Choose the option you're most comfortable with.

<img width="1728" height="1081" alt="image" src="https://github.com/user-attachments/assets/175d728c-8d4a-4204-a0f0-64956a07fa9c" />

Once you've signed up, you'll be taken to the ChatGPT interface.

# Section 2

## Overview

A well-written prompt helps an AI understand exactly what you want. One simple framework is to divide every prompt into six parts.

In this lab, you will create a prompt that—along with the provided documents—you will later use to ask ChatGPT to generate a proposal for improving collaboration between the Sales and Marketing teams.

Throughout the lab, you'll explore each part of the framework and then combine them into one complete prompt. Feel free to view the examples, but try writing your own version before looking at them.

As you work through the lab, paste each section into the "Ask Anything" text entry field. You'll submit the completed prompt at the end.

<img width="1728" height="991" alt="image" src="https://github.com/user-attachments/assets/2de381c9-2776-4e39-9225-26ccbbad7da5" />

## 1. Persona

The Persona defines who the AI should be, including its role, expertise, or perspective (for example, a teacher, software engineer, lawyer, or copywriter). A clear persona helps shape the AI's knowledge, vocabulary, and overall approach.

Click the 💡 Example dropdown below to see an example Persona section for this prompt.

<details>
<summary>💡 Example</summary>

```
<persona>
You are a professional copywriter experienced in preparing business proposals for senior management.
</persona>
```
</details>

<details>
<summary>Click here to see what your UI should look like</summary>
<img width="1865" height="916" alt="image" src="https://github.com/user-attachments/assets/e262c4ec-2bc5-4d45-a285-6470887860fe" />
</details>


**Note**: The < persona > and </ persona > tags are called delimiters. Delimiters are markers used to clearly separate different parts of a prompt, such as instructions, context, examples, or data. They help the AI distinguish between sections, reducing ambiguity and improving the accuracy of the response.

In addition to XML-style tags (such as < persona >), you can also use triple quotes (""") or clearly labeled headings (for example, === Persona ===).

---

## 2. Context

The Context provides the background information the AI needs, such as the situation, goal, target audience, uploaded files, relevant history, or other domain-specific details. Good context gives the AI enough information to understand why it is performing the task.


For this exercise, your relevant information is contained in the following files:  
  - [Sales_Performance_Report_Q1_2026.pdf](https://github.com/zoubidarezki-31/From-Prompting-Chaos-to-Consistency-The-6-Pillar-Framework-for-Scalable-AI-Outputs/blob/main/Sales_Performance_Report_Q1_2026.pdf)
    
  - [Marketing_Campaign_Results.pdf](https://github.com/zoubidarezki-31/From-Prompting-Chaos-to-Consistency-The-6-Pillar-Framework-for-Scalable-AI-Outputs/blob/main/Marketing_Campaign_Results.pdf)


To download each file:

  - Right-click the file link and select Open Link in New Tab.
  - In the new tab, click the Download raw file button (the downward-pointing arrow) in the upper-right corner, as shown below.
  <img width="1721" height="940" alt="image" src="https://github.com/user-attachments/assets/d45dd869-ca05-48a1-844b-a048983368ee" />

After downloading the files, upload them to ChatGPT by clicking the + button to the left of the "Ask Anything" text entry field.
<img width="3456" height="1982" alt="image" src="https://github.com/user-attachments/assets/ae448e78-a8d4-47f4-accf-1cf0047b4de7" />

Then select "Add photos and files."
<img width="1864" height="916" alt="image" src="https://github.com/user-attachments/assets/92a55137-bcdc-490d-9c05-2353f78150fe" />

Click the 💡 Example dropdown below to see an example Context section for this prompt.

<details>
<summary>💡 Example</summary>

```
<Context>
Use the data from the uploaded reports "Marketing_Campaign_Results.pdf" and "Sales_Performance_Report_Q1_2026.pdf" as the primary source of information when preparing your proposal.
</Context>
```

</details>
<details>
<summary>Click here to see what your UI should look like</summary>
<img width="1867" height="916" alt="image" src="https://github.com/user-attachments/assets/fb5e7052-f3a3-4ada-bfb4-1b772c01ccc4" />

</details>

---

## 3. Task

The Task clearly states what you want the AI to do. Use specific action verbs such as write, summarize, compare, analyze, explain, or generate. A well-defined task leaves little room for ambiguity.

Some example task verbs include:
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

<details>
<summary>Click here to see what your UI should look like</summary>
<img width="1922" height="993" alt="image" src="https://github.com/user-attachments/assets/462ea6c8-e13e-4863-8bd4-afc7df13255d" />
</details>


---

## 4. Constraints

The Constraints define the rules the AI must follow, including the tone (for example, professional, persuasive, or friendly), audience, length, reading level, citation requirements, and any other guidelines.


<details>
<summary>💡 Example</summary>

```
<Constraints>
Use a Professional, objective, and persuasive tone. The proposal should: Identify the root causes of poor collaboration, Explain how these issues are affecting productivity; revenue; customer satisfaction; or other business outcomes, Support each major point with evidence from the uploaded files, Clearly cite which uploaded source each piece of evidence came from.
</Constraints>
```

</details>
<details>
<summary>Click here to see what your UI should look like</summary>
<img width="1918" height="993" alt="image" src="https://github.com/user-attachments/assets/4386d60b-203c-4bad-9937-2a89e2c47d42" />

</details>

---

## 5. Examples

The Examples section shows the AI what a successful response should look like by providing sample inputs, outputs, templates, or reference documents. Examples help the AI mimic the desired style, structure, and level of detail.

For this exercise, use the file "Proposal_Implementing_a_Company_Wide_Cybersecurity_Awareness_Training_Program.pdf" as an example of the style and structure you want your proposal to follow.

An example does not always have to be a file. You can also describe the style or format you want the AI to emulate. For example, you might ask the AI to:

Write in the style of a formal business proposal.
Use clear, persuasive language similar to a TED Talk.
Write using the style of Martin Luther King Jr.

This allows you to guide the output even when you don't have a sample document.

Download and upload this file using the same process you used earlier.

[Proposal_Implementing_a_Company_Wide_Cybersecurity_Awareness_Training_Program.pdf](http://github.com/zoubidarezki-31/From-Prompting-Chaos-to-Consistency-The-6-Pillar-Framework-for-Scalable-AI-Outputs/blob/main/Proposal_%20Implementing%20a%20Company-Wide%20Cybersecurity%20Awareness%20Training%20Program.pdf)

<details>
<summary>💡 Example</summary>

```
<Examples>
Use the uploaded file "Proposal_Implementing_a_Company_Wide_Cybersecurity_Awareness_Training_Program.pdf" only as an example of the desired writing style and overall proposal structure.
</Examples>
```

</details>

<details>
<summary>Click here to see what your UI should look like</summary>
<img width="1916" height="992" alt="image" src="https://github.com/user-attachments/assets/f8f433fc-17c1-4023-960c-b582f8602bbe" />

</details>


---

## 6. Format

The Format specifies how you want the final response organized. Examples include a business proposal, email, report, table, JSON, bullet list, Markdown document, or presentation with specific headings or sections.

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
<details>
<summary>Click here to see what your UI should look like</summary>
<img width="1917" height="988" alt="image" src="https://github.com/user-attachments/assets/60565352-0425-440c-b96f-2b50f1535c3e" />

</details>

---

# Putting It All Together

A complete prompt combines all six components.
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

Once you've finished building your prompt, click the Submit button (the white arrow).
<img width="1917" height="988" alt="image" src="https://github.com/user-attachments/assets/aebc5cbc-dd82-496c-ae7f-61ee01bb01e3" />

After submitting, your conversation should look similar to this:
<img width="1918" height="991" alt="image" src="https://github.com/user-attachments/assets/c2bdd0a6-f649-49d5-bdfa-860abac8ed42" />

Below is an example of the response generated by the AI:
<img width="1918" height="990" alt="image" src="https://github.com/user-attachments/assets/5a097ca7-1d6f-4e05-b92b-2e7bfa6a5b16" />

Notice the four buttons located at the top of the generated document:

  - Edit (far left): Edit the generated document.
  - Copy: Copy the document to your clipboard.
  - Download: Download the document.
  - Expand: Open the document in an expanded view for easier reading.
<img width="1918" height="990" alt="image" src="https://github.com/user-attachments/assets/26e797a5-09f3-4b41-b540-996e9877beac" />

