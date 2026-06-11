# Day2_SixPatterns.md

## Student Question

> Explain Big-O notation for a placement interview.

---

# Pattern 1 — PERSONA

## Prompt

```text
You are a senior placement coach at Aditya University. You have prepared 200 B.Tech CSE students for TCS, Infosys, and Cognizant placement interviews. A 3rd-year CSE student with 7.5 CGPA asks you about Big-O notation. Explain it the way you would in a 1-on-1 prep session — concrete, conversational, exam-relevant.
```

## Output

Big-O notation describes how the runtime or memory usage of an algorithm grows as input size increases. For example, if you search every element in an array once, the complexity is O(n). In placement interviews, remember common complexities like O(1), O(log n), O(n), and O(n²).

**Self Score:** 5/5

---

# Pattern 2 — FEW-SHOT

## Prompt

```text
Here are example explanations from a placement coach:

Q: What is recursion?
A: A function calling itself with a smaller problem. Like Russian dolls. Stops at the base case.

Q: What is a stack?
A: LIFO data structure. Like a stack of plates. Push adds, pop removes.

Q: What is Big-O notation?
A:
```

## Output

Big-O notation measures how the running time of code grows when the input becomes larger. Think of checking attendance: more students mean more work. One loop usually means O(n), while nested loops usually mean O(n²).

**Self Score:** 5/5

---

# Pattern 3 — CHAIN-OF-THOUGHT

## Prompt

```text
Explain Big-O notation to a placement interview candidate. Think step by step before answering.

Step 1: Define Big-O in one sentence.
Step 2: Give one concrete example with code.
Step 3: Explain why interviewers ask about it.
Step 4: Synthesize into a 3-sentence summary.
```

## Output

### Step 1

Big-O notation describes how algorithm performance grows with input size.

### Step 2

```python
for i in arr:
    print(i)
```

This runs O(n) because each element is visited once.

### Step 3

Interviewers use Big-O to evaluate problem-solving and efficiency.

### Step 4

Big-O helps compare algorithms. It measures scalability as input grows. Understanding Big-O is important in coding interviews.

**Self Score:** 5/5

---

# Pattern 4 — STRUCTURED OUTPUT

## Prompt

```text
Explain Big-O notation for a placement interview. Return ONLY valid JSON with this exact shape:

{
  "definition": "",
  "intuition": "",
  "code_example": "",
  "common_pitfall": "",
  "interview_test_question": ""
}
```

## Output

```json
{
  "definition": "Big-O notation describes how runtime grows with input size.",
  "intuition": "More data means more work.",
  "code_example": "for i in arr: print(i)  # O(n)",
  "common_pitfall": "Memorizing complexities without understanding.",
  "interview_test_question": "Why is Binary Search O(log n)?"
}
```

**Self Score:** 5/5

---

# Pattern 5 — SYSTEM PROMPT

## System Prompt

```text
You are a senior placement coach for B.Tech CSE students at an Indian engineering college. You prepare students for TCS, Infosys, and Cognizant interviews. You explain technical concepts in 50-80 words max, conversationally, with one concrete code example.
```

## User Prompt

```text
Explain Big-O notation.
```

## Output

Big-O notation tells us how an algorithm's running time grows as input size increases. For example:

```python
for i in arr:
    print(i)
```

This is O(n) because every element is visited once. Big-O helps compare algorithm efficiency in interviews.

**Self Score:** 5/5

---

# Pattern 6 — PROMPT CHAINING

## Conversation 1

### Prompt

```text
List the 5 most important sub-concepts a B.Tech student must understand about Big-O notation. Just the list, no explanation.
```

### Output

1. Definition
2. Common time complexities
3. Comparing algorithms
4. Space vs time complexity
5. Why interviewers ask

---

## Conversation 2

### Prompt

```text
For each of these 5 sub-concepts of Big-O notation, write a 1-paragraph explanation tailored to a 3rd-year B.Tech CSE student preparing for placement interviews.
```

### Output

Big-O defines algorithm growth. Common complexities include O(1), O(log n), O(n), and O(n²). It helps compare algorithms and understand time and space trade-offs. Interviewers ask it to test efficiency.

---

## Conversation 3

### Prompt

```text
Synthesize these paragraphs into one concise 80-word interview-prep explanation. End with one practice question.
```

### Output

Big-O notation measures how an algorithm's runtime or memory usage changes with input size. Common complexities are O(1), O(log n), O(n), and O(n²). It helps compare algorithms and understand efficiency. Interviewers ask Big-O to test problem-solving skills.

Practice Question: Why is Binary Search O(log n)?

**Self Score:** 5/5

---
