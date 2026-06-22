# AI vs Machine Learning vs Deep Learning vs Generative AI

## Hierarchy

```text
AI ⊃ ML ⊃ Deep Learning ⊃ Generative AI
```

Meaning:

- **AI** is the biggest umbrella.
- **ML** is one way to build AI.
- **Deep Learning** is a powerful type of ML.
- **Generative AI** is a modern subset focused on creating new content.

---

# 1) What is AI?

## Artificial Intelligence

AI means making machines perform tasks that normally need human intelligence.

Examples:

- Playing chess
- Face recognition
- Voice assistants
- Route optimization
- Fraud detection

Examples in real life:

- Google Maps finding the best route
- Siri answering questions

AI does not necessarily “learn.”  
Some AI systems are rule-based.

Example:

```python
if fever > 102:
   alert_doctor()
```

This is simple AI logic, not ML.

---

# 2) What is Machine Learning?

## Machine Learning

ML is a subset of AI where machines learn patterns from data instead of being manually programmed.

Instead of manually writing:

```python
if spam_word:
   spam = True
```

We give data:

- Spam emails
- Non-spam emails

Then the model learns patterns itself.

Examples:

- Spam detection
- Recommendation systems
- Stock prediction
- Price prediction

Examples in real life:

- Netflix recommendations
- Amazon product recommendations

Basic idea:

```text
Input → Data
Output → Prediction
```

Examples:

- House size → Price
- Student marks → Pass/Fail

---

# 3) What is Generative AI?

## Generative Artificial Intelligence

Generative AI is AI that creates new things.

It can generate:

- Text
- Images
- Music
- Code
- Video

Examples:

- ChatGPT writes text
- Midjourney creates images
- GitHub Copilot writes code

Example prompt:

```text
Write a Python function for binary search.
```

Generative AI creates brand new output.

---

# Key Difference

Traditional ML mostly predicts.

Generative AI creates.

---

## Traditional ML

```text
Input → Prediction
```

Example:

```text
Image → Cat / Dog
```

Output can be:

- Classification
- Regression
- Recommendation

---

## Generative AI

```text
Input → Generate new content
```

Example:

```text
Prompt → Image/Text/Code
```

Output can be:

- Generated text
- Generated images
- Generated code

---

# Example

Suppose a company has customer data.

## ML Task

Predict:

```text
Will customer leave?
```

Output:

```text
Yes / No
```

## Generative AI Task

Generate:

```text
Write a personalized email to retain this customer.
```

Output:

```text
New email content
```

---

# Simple Analogy

```text
AI = Entire universe
ML = One important city
GenAI = Special area inside city
```

Or:

```text
AI = Big field
ML = Learning from data
GenAI = Creating new content
```

---

# Table Comparison

| Feature | AI | ML | GenAI |
|---|---|---|---|
| Scope | Broadest | Subset of AI | Subset of ML/Deep Learning |
| Learns from data? | Not always | Yes | Yes |
| Main task | Smart behavior | Prediction | Generation |
| Output | Decisions/actions | Predictions | New content |

---

# In One Line

```text
AI → Make machines intelligent
ML → Make machines learn from data
GenAI → Make machines create new content
```
