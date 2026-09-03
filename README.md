# EX-02-Cross-Platform-Prompting-Comparing-Prompting-Methods-for-AI-Based-Text-Summarization

## AIM

To study and compare the performance of different prompting techniques (**Basic, Role-Based, Context-Based, Constraint-Based, and Output-Format Prompting**) using multiple AI platforms (**ChatGPT, Gemini, Claude AI, and Microsoft Copilot**) for generating effective summaries of technical content.

---

# Scenario

You are working as a content development team member for an educational platform that provides simplified study materials for undergraduate engineering students.

The task is to summarize a **500-word technical article** on **"The Basics of Blockchain Technology"** using different AI platforms and prompting techniques.

The generated summaries are evaluated based on the following criteria:

* Accuracy
* Coherence
* Simplicity
* Speed
* User Experience

---

# Prompting Techniques Used

## 1. Basic Prompt

### Prompt Used

```text
Summarize the following article about "The Basics of Blockchain Technology"
in approximately 150 words.

The summary should:
- Include the main ideas.
- Use clear and simple language.
- Be suitable for undergraduate engineering students.
- Preserve the original meaning.

Article:
[Paste the article here]
```

---

## 2. Role-Based Prompt

### Prompt Used

```text
Act as a university professor who teaches Blockchain Technology
to undergraduate engineering students.

Read the following article and prepare a summary of approximately
150 words.

Requirements:
- Explain the important concepts clearly.
- Use student-friendly language.
- Avoid unnecessary technical terms.
- Focus on concepts useful for students.

Article:
[Paste the article here]
```

---

## 3. Context-Based Prompt

### Prompt Used

```text
You are preparing study and revision material for undergraduate
engineering students on an educational learning platform.

Read the following article about Blockchain Technology and create
a concise summary of approximately 150 words.

The summary should:
- Include the most relevant concepts.
- Be clear and accurate.
- Help students understand the topic quickly.
- Be useful for examination revision.

Article:
[Paste the article here]
```

---

## 4. Constraint-Based Prompt

### Prompt Used

```text
Summarize the following article on Blockchain Technology
while following these conditions:

- Maximum 150 words
- Use simple English
- Write in paragraph form
- Suitable for undergraduate students
- Include only the essential information
- Do not change the original meaning

Article:
[Paste the article here]
```

---

## 5. Output-Format Prompt

### Prompt Used

```text
Summarize the following article about Blockchain Technology.

Follow this output structure:

Title:
Summary:
Key Concepts:
- Concept 1
- Concept 2
- Concept 3
Conclusion:

Requirements:
- Approximately 150 words
- Use simple language
- Make the content easy to understand
- Suitable for undergraduate engineering students

Article:
[Paste the article here]
```

---

# AI Platform Evaluation

## ChatGPT + Basic Prompting

### Prompt Used

```text
Summarize the following article about Blockchain Technology
in clear and simple language for undergraduate students.
```

### Summary Generated

> Blockchain is a decentralized technology that allows information and transactions to be stored across a network of computers. Data is organized into blocks, which are connected using cryptographic methods. Since the information is distributed instead of being controlled by a single authority, blockchain provides transparency and security. It is widely used in cryptocurrencies such as Bitcoin and can also be applied to banking, healthcare, logistics, and supply chain management. Despite its benefits, blockchain faces challenges such as scalability, energy consumption, and transaction processing speed.

### Evaluation

| Criterion       | Result    |
| --------------- | --------- |
| Accuracy        | High      |
| Coherence       | Excellent |
| Simplicity      | Excellent |
| Speed           | Very Fast |
| User Experience | Excellent |

---

## Gemini + Few-Shot Prompting

### Prompt Used

```text
Study the following sample summaries and follow their style,
length, and level of detail.

Example 1:
[Sample technical summary]

Example 2:
[Sample technical summary]

Now summarize the Blockchain Technology article using
a similar style.
```

### Summary Generated

> Blockchain is a distributed ledger technology that stores digital records in connected blocks. The information is shared among multiple computers, which improves transparency and makes unauthorized changes difficult. Cryptographic techniques help maintain the security and integrity of the stored data. Blockchain is mainly known for supporting cryptocurrencies, but it can also be used in finance, healthcare, logistics, and supply chain applications. Although it provides several advantages, issues such as scalability, energy usage, and slower transaction processing can create difficulties when the technology is used on a large scale.

### Evaluation

| Criterion       | Result    |
| --------------- | --------- |
| Accuracy        | Very High |
| Coherence       | Excellent |
| Simplicity      | Good      |
| Speed           | Fast      |
| User Experience | Very Good |

---

## Claude AI + Chain-of-Thought Prompting

### Prompt Used

```text
Analyze the article carefully by identifying its major ideas
and important concepts first.

Then use those concepts to create a concise and
student-friendly summary.

Ensure that the final summary is clear, accurate,
and logically organized.
```

### Summary Generated

> Blockchain is a decentralized digital ledger that records transactions across a network of computers. Transactions are collected into blocks and connected through cryptographic techniques, creating a secure chain of information. Consensus mechanisms help network participants verify transactions and maintain agreement. Blockchain technology is commonly associated with cryptocurrencies and is also being used in areas such as banking, healthcare, and supply chain management. Its important advantages include transparency, security, and reduced dependence on a central authority. However, scalability, energy consumption, and transaction speed remain significant challenges.

### Evaluation

| Criterion       | Result    |
| --------------- | --------- |
| Accuracy        | Excellent |
| Coherence       | Excellent |
| Simplicity      | Good      |
| Speed           | Moderate  |
| User Experience | Excellent |

---

## Microsoft Copilot + Role-Based Prompting

### Prompt Used

```text
Act as a university tutor explaining Blockchain Technology
to undergraduate engineering students.

Provide a short and easy-to-understand summary of the article.
Focus on the main concepts and avoid unnecessary details.
```

### Summary Generated

> Blockchain is a digital system that records information in a series of connected blocks. The data is distributed among multiple computers, making it more transparent and difficult to modify without authorization. Blockchain reduces the need for a central authority and provides a secure way to manage digital records. It is widely used in cryptocurrency applications and can also support financial, healthcare, and supply chain systems. Some limitations of blockchain include high energy requirements, scalability problems, and slower processing compared with some traditional systems.

### Evaluation

| Criterion       | Result    |
| --------------- | --------- |
| Accuracy        | High      |
| Coherence       | Good      |
| Simplicity      | Excellent |
| Speed           | Fast      |
| User Experience | Very Good |

---

# Comparison Table

| AI Platform       | Prompting Technique | Accuracy  | Coherence | Simplicity | Speed     | User Experience |
| ----------------- | ------------------- | --------- | --------- | ---------- | --------- | --------------- |
| ChatGPT           | Basic / Zero-Shot   | High      | Excellent | Excellent  | Very Fast | Excellent       |
| Gemini            | Few-Shot            | Very High | Excellent | Good       | Fast      | Very Good       |
| Claude AI         | Chain-of-Thought    | Excellent | Excellent | Good       | Moderate  | Excellent       |
| Microsoft Copilot | Role-Based          | High      | Good      | Excellent  | Fast      | Very Good       |

---

# Overall Findings

| Platform          | Key Strength                                             | Limitation                                          |
| ----------------- | -------------------------------------------------------- | --------------------------------------------------- |
| ChatGPT           | Provides simple, readable, and fast summaries            | May provide less detailed explanations              |
| Gemini            | Produces structured and highly accurate summaries        | Sometimes uses more technical vocabulary            |
| Claude AI         | Provides highly coherent and logically organized content | Can take comparatively longer to generate responses |
| Microsoft Copilot | Produces concise and beginner-friendly explanations      | May provide fewer technical details                 |

---

# Final Result

Different prompting techniques were applied across multiple AI platforms to summarize a technical article on **Blockchain Technology**.

The experiment produced the following observations:

* **ChatGPT with Basic Prompting** generated a clear and easy-to-understand summary with very fast response time, making it suitable for quick academic revision.
* **Gemini with Few-Shot Prompting** produced highly accurate and well-structured summaries by following the examples provided in the prompt.
* **Claude AI with Chain-of-Thought Prompting** produced highly coherent and detailed summaries by identifying the important concepts before generating the final response.
* **Microsoft Copilot with Role-Based Prompting** provided concise and beginner-friendly explanations that were easy for undergraduate students to understand.

Overall, the experiment demonstrates that **the choice of prompting technique can significantly influence the quality, structure, clarity, and usefulness of AI-generated text summaries**. Selecting an appropriate prompt based on the required output can improve the effectiveness of AI tools for educational applications.
