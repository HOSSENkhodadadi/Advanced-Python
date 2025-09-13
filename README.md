# Advanced Python – Minimalist GPT-Driven Learning

This repository helps you learn advanced Python concepts in the shortest time possible — without searching on Google or watching long YouTube videos.

Instead of passive learning, this approach uses an interactive, feedback-based method powered by ChatGPT. You will actively ask and answer questions, which leads to faster and deeper understanding.

## Learning Methodology

1. Ask ChatGPT to explain the concept and provide a minimal implementation.
2. Ask ChatGPT to give you an example question related to the concept, along with the correct answer.
3. Ask ChatGPT to quiz you on the concept and verify your response.
4. Repeat step 3 until you fully understand the topic.

After learning the concept, do **not** look at the example code immediately. First try to implement it yourself, then compare your solution.

## What's in This Repository

Each file in this repository contains:

- A short description of a Python concept (e.g., decorators, metaclasses, context managers, etc.)
- A ready-to-copy GPT prompt to learn and practice the concept
- One example question with a verified answer
- A follow-up prompt to let GPT quiz and evaluate your understanding

This format ensures you spend less time reading and more time thinking and coding.

## Example Format (e.g., `generators.md`)

```markdown
## Concept: Generators

### GPT Prompt:
Explain what a generator is in Python, how it works, and provide a minimal implementation.

### Example Q&A:
Q: Write a generator that yields the square of numbers from 1 to 5.  
A:
```python
def square_gen():
    for i in range(1, 6):
        yield i ** 2
