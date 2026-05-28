# EX-02-Cross-Platform-Prompting-Evaluating-Diverse-Techniques-in-AI-Powered-Text-Summarization

## AIM
To evaluate and compare the effectiveness of prompting techniques (zero-shot, few-shot, chain-of-thought, role-based) across different AI platforms (e.g., ChatGPT, Gemini, Claude, Copilot) in a specific task: text summarization.

## SCENARIO:
You are part of a content curation team for an educational platform that delivers quick summaries of research papers to undergraduate students. Your task is to summarize a 500-word technical article on "The Basics of Blockchain Technology" using multiple AI platforms and prompting strategies.

Your goal is to determine which combination of prompting technique + platform provides the best summary in terms of:

Accuracy

Coherence

Simplicity

Speed

User experience

## OUTPUT
## Introduction

Prompt engineering is the process of designing effective inputs to obtain accurate and relevant responses from Generative AI systems. Different prompting techniques influence how AI models understand and generate outputs. In text summarization tasks, prompts can significantly affect summary quality, accuracy, coherence, and brevity. This experiment compares multiple prompting methods across popular AI platforms to identify the most effective approach for summarization.

## AI Platforms Used
ChatGPT
Gemini
Claude
Microsoft Copilot
Prompting Techniques
## 1. Zero-Shot Prompting

The AI is directly asked to perform summarization without examples.

Example Prompt

“Summarize the following article in 100 words.”

Characteristics
Simple and fast
No prior examples required
Performance depends on model understanding
## 2. Few-Shot Prompting

The AI is given one or more examples before the actual task.

Example Prompt

Example:
Input: “Artificial Intelligence improves automation.”
Output: “AI enhances automation efficiency.”

Now summarize:
[Article Text]

Characteristics
Improves consistency
Helps guide formatting and style
Requires additional prompt space
## 3. Chain-of-Thought Prompting

The AI is instructed to think step-by-step before generating the summary.

Example Prompt

“Read the article carefully, identify key points step-by-step, and then generate a concise summary.”

Characteristics
Produces detailed and logical summaries
Better handling of complex content
Slightly slower response generation
## 4. Role-Based Prompting

The AI is assigned a specific role before performing the task.

Example Prompt

“You are an expert news editor. Summarize the following article professionally in 100 words.”

Characteristics
Produces domain-specific summaries
Improves tone and readability
Useful for professional applications
## RESULT
The experiment demonstrated that prompting techniques significantly influence summarization quality in Generative AI systems. Among all methods, Chain-of-Thought and Role-Based prompting produced the most effective summaries in terms of clarity, context retention, and readability. Different AI platforms showed varying strengths, with ChatGPT and Claude providing highly coherent outputs, Gemini offering faster responses, and Copilot delivering concise structured summaries.
