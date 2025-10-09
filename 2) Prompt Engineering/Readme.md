# 🧠 Zero-Shot Task Toolkit

A simple **Zero-Shot & Few-Shot task toolkit** built on foundation models like **FLAN-T5**. This project demonstrates the power of **Prompt Engineering** to make models perform tasks they were not explicitly trained for.

---
## 🎯 Project Goal

Showcase the ability to use **foundation models** for multiple tasks just by changing prompts, without additional task-specific training.

---
## 📋 Tasks Implemented

1. **Sentiment Analysis**  
Classify a review as positive or negative.  
prompt = f"Is the following review positive or negative? Review: {review}"
sentiment = run_task(prompt)

2. **Text Summarization**  
Summarize a paragraph in one sentence.
prompt = f"Summarize the following text in one sentence: {text}"
summary = run_task(prompt)

3. **Question Answering** 
Answer questions based on a given context.
prompt = f"Based on the text, answer the question: {question} Text: {context}"
answer = run_task(prompt)

4. **Few-Shot Learning Example** 
Enhance accuracy with a few examples in the prompt.
prompt = f"{few_shot_examples}\nReview: {review}\nSentiment:"
sentiment = run_task(prompt)

---
🌟 Key Learnings:
Crafting effective prompts (Prompt Engineering)
Leveraging Zero-Shot and Few-Shot capabilities of foundation models
Understanding how models generalize knowledge without explicit task training