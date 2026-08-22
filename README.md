# Analyzing Identifier Naming and Code Understanding Using AI

##  Project Overview

This project investigates the impact of identifier naming on code readability and program comprehension.

The study explores how Large Language Models (LLMs), specifically ChatGPT-4o, can generate meaningful and descriptive variable and method names for Java code containing unclear identifiers.

The project evaluates AI-generated identifier names and compares them with meaningful human-written names.

---

##  Project Objectives

The main objectives of this project are:

- Investigate the impact of identifier naming on code readability.
- Evaluate the ability of ChatGPT-4o to generate meaningful identifier names.
- Compare AI-generated identifiers with human-written identifiers.
- Analyze the effect of code complexity on AI-generated naming quality.
- Investigate how different prompting strategies influence AI performance.

---

##  Dataset

The dataset contains 20 Java methods organized into four complexity levels:

| Complexity Level | Number of Methods |
|---|---:|
| Simple | 5 |
| Medium | 7 |
| Complex | 5 |
| Real-World | 3 |
| **Total** | **20** |

Each method was prepared in two versions:

- Version A: Unclear identifiers
- Version B: Meaningful identifiers

---

##  AI Model

The project uses:

**ChatGPT-4o**

The model was provided with Java code containing unclear identifiers and was asked to generate meaningful and descriptive names.

---

##  Prompt Design

Three structured prompting strategies were evaluated:

### Prompt 1 - Direct Instruction

> Analyze the following Java code and suggest meaningful variable and method names.

### Prompt 2 - Task-Specific

> Rename the unclear identifiers using descriptive names while keeping functionality.

### Prompt 3 - Explanation-Based

> Explain the purpose of this method and generate improved identifier names.

---

##  Evaluation Criteria

The generated identifier names were evaluated using four criteria:

| Criterion | Description |
|---|---|
| Clarity | How clear and understandable the identifier name is |
| Readability | Whether the identifier improves code readability |
| Accuracy | Whether the identifier correctly represents its purpose |
| Usefulness | Whether the identifier helps developers understand the code |

A five-point rating scale was used:

1. Very Poor  
2. Poor  
3. Fair  
4. Good  
5. Excellent  

---

##  Results

The overall evaluation produced the following scores:

| Evaluation Criterion | Score |
|---|---:|
| Clarity | 4.75/5 |
| Readability | 4.90/5 |
| Accuracy | 4.75/5 |
| Usefulness | 4.75/5 |
| **Overall** | **4.79/5** |

---

##  Prompt Comparison

The three prompting strategies achieved different results:

| Prompt | Score |
|---|---:|
| Direct Instruction | 4.30/5 |
| Task-Specific | 4.60/5 |
| Explanation-Based | 4.90/5 |

The explanation-based prompting strategy achieved the highest evaluation score.

---

##  Key Finding

The results indicate that AI-generated identifier names can provide useful and meaningful suggestions for improving code readability and understanding.

The explanation-based prompting strategy achieved the best overall performance, suggesting that providing additional context about the purpose of the code can improve AI-generated identifier naming.

---

##  Example

### Before

```java
int a = 85;
int b = 90;
int c = (a + b) / 2;

### After
int firstGrade = 85;
int secondGrade = 90;
int averageGrade = (firstGrade + secondGrade) / 2;
Meaningful identifiers make the purpose of variables easier to understand.
---
Technologies and Tools
Java
ChatGPT-4o
Large Language Models (LLMs)
Prompt Engineering
Artificial Intelligence
Software Engineering
GitHub
Empirical Evaluation
