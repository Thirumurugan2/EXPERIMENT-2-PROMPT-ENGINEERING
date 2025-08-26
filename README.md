# EXP-2-PROMPT-ENGINEERING-  Comparative Analysis of different types of Prompting patterns and explain with Various Test Scenarios

## Aim: 
Comparative Analysis of different types of Prompting patterns and explain with Various Test Scenarios

Experiment:
Test and compare how different pattern models respond to various prompts (broad or unstructured) versus basic prompts (clearer and more refined) across multiple scenarios. 
Analyze the quality, accuracy, and depth of the generated responses.

## Algorithm:
Choose a test scenario (e.g., solving a math problem, generating a story, writing code, or summarizing text).

Apply different prompting patterns (zero-shot, few-shot, chain-of-thought, etc.).

Record model output for each prompt.

Compare responses in terms of accuracy, relevance, depth, and clarity.

Analyze which prompt type gives the best result for the scenario.

## Prompt:
Unstructured Prompt: “Factorial program.”

Output: Incomplete/unclear.

Zero-Shot Prompt: “Write Python program to find factorial of a number.”

Output: Provides correct code.

Few-Shot Prompt: “Example: Python program for Fibonacci series: … Now write factorial program.”

Output: Correct and contextual.

Chain-of-Thought Prompt: “Explain step by step and then give Python code for factorial.”

Output: Explanation + correct code.

Role-Based Prompt: “You are a Python tutor. Write and explain factorial program.”

Output: Clean code with beginner-friendly explanation.

## Output
The responses of the model varied depending on the prompting pattern. Unstructured prompts gave vague or incomplete answers, while zero-shot prompts provided correct but basic responses. Few-shot prompts improved creativity and context, chain-of-thought prompts gave step-by-step explanations with clarity, and role-based prompts delivered detailed, user-friendly answers.
## Result
From the analysis, it is observed that structured prompting patterns such as few-shot, chain-of-thought, and role-based give more accurate, clear, and well-organized results compared to unstructured or basic zero-shot prompts. Hence, prompt engineering plays an important role in improving the quality and depth of model responses.
