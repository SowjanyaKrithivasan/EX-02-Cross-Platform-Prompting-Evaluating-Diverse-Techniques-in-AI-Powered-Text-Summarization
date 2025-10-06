# EX-02-Cross-Platform-Prompting-Evaluating-Diverse-Techniques-in-AI-Powered-Text-Summarization

## AIM
To evaluate and compare the effectiveness of prompting techniques (zero-shot, few-shot, chain-of-thought, role-based) across different AI platforms (e.g., ChatGPT, Gemini, Claude, Copilot) in a specific task: text summarization.

## Scenario:
You are part of a content curation team for an educational platform that delivers quick summaries of research papers to undergraduate students. Your task is to summarize a 500-word technical article on "The Basics of Blockchain Technology" using multiple AI platforms and prompting strategies.

Your goal is to determine which combination of prompting technique + platform provides the best summary in terms of:

Accuracy

Coherence

Simplicity

Speed

User experience

## Algorithm

## Result
EVALUATION AND COMPARISON OF PROMPTING TECHNIQUES ACROSS AI PLATFORMS IN TEXT SUMMARIZATION
1. INTRODUCTION

Text summarization is a fundamental task in Natural Language Processing (NLP) that aims to condense lengthy text into concise summaries while preserving meaning and context.
The advancement of Large Language Models (LLMs) such as ChatGPT (OpenAI), Gemini (Google DeepMind), Claude (Anthropic), and GitHub Copilot (OpenAI/Microsoft) has made summarization more efficient and contextually aware.

However, the prompting technique used plays a crucial role in determining how effectively an AI model performs summarization. This study evaluates and compares four major prompting techniques — Zero-shot, Few-shot, Chain-of-Thought, and Role-based — across these AI platforms.



2. OBJECTIVES

To understand the effect of different prompting techniques on summarization.

To compare text summarization performance across AI platforms.

To evaluate the quality, coherence, and conciseness of generated summaries.

To identify which combination of model and prompt yields the best performance.




3. OVERVIEW OF PROMPTING TECHNIQUES
3.1 ZERO-SHOT PROMPTING

Definition: The model is given a direct task without prior examples or demonstrations.

Example Prompt:
“Summarize the following article in three sentences.”

Advantages: Simple, fast, and effective for general summarization.

Limitations: May lack depth or context understanding; misses domain-specific nuances.

3.2 FEW-SHOT PROMPTING

Definition: The model is provided with a few example input-output pairs before the actual task.

Example Prompt:

Example 1:
Text: The economy is recovering from inflation.
Summary: Economic recovery follows inflation.

Example 2:
Text: AI is improving healthcare systems globally.
Summary: AI enhances healthcare worldwide.

Now summarize the following text:
[Insert new text]


Advantages: Increases accuracy, consistency, and adapts tone based on examples.

Limitations: Requires well-selected examples; may be restricted by input size limits.

3.3 CHAIN-OF-THOUGHT (CoT) PROMPTING

Definition: The model is asked to reason step-by-step before producing the summary.

Example Prompt:
“Think step by step about the main ideas, then write a concise summary.”

Advantages: Produces logical, structured, and coherent summaries.

Limitations: May include verbose reasoning or intermediate thoughts.

3.4 ROLE-BASED PROMPTING

Definition: The model is assigned a role or persona that influences the tone and structure of the output.

Example Prompt:
“You are a professional researcher. Summarize this paper in a formal and objective manner.”

Advantages: Controls tone and perspective effectively for domain-specific summarization.

Limitations: May create bias or overly formal language if the role is too restrictive.


4. AI PLATFORMS EVALUATED
   
![WhatsApp Image 2025-10-06 at 08 31 13_8f175a10](https://github.com/user-attachments/assets/2e3a724b-c972-4d88-bd81-e1aa9c4c3596)



6. METHODOLOGY
DATASET USED

Five diverse text sources were selected for testing:

Academic research article

News report

Blog post

Government policy report

Technical documentation

EVALUATION PROCESS

Each document was summarized using all four prompting techniques on each AI platform.

EVALUATION METRICS

ROUGE Score: Measures overlap between generated and reference summaries.

Factual Accuracy: Checks correctness of retained facts.

Coherence: Evaluates logical structure and readability.

Conciseness: Measures how much information is conveyed briefly.

Relevance: Judges focus on key points of the text.


6. RESULTS AND ANALYSIS

TABLE 1: COMPARISON OF PROMPTING TECHNIQUES ACROSS PLATFORMS

![WhatsApp Image 2025-10-06 at 08 09 56_4eaf5071](https://github.com/user-attachments/assets/7eab31ce-3c14-48a2-9f7d-5a392444c080)


7. DISCUSSION

BEST PERFORMING TECHNIQUE:
Chain-of-Thought prompting generated the most accurate and logically coherent summaries, particularly in ChatGPT and Claude.

FEW-SHOT PROMPTING:
Improved contextual understanding and stylistic uniformity, especially on Gemini.

ROLE-BASED PROMPTING:
Produced consistent tone and professionalism—ideal for academic or business summaries.

ZERO-SHOT PROMPTING:
Efficient for general tasks but often missed deeper context and nuance.

PLATFORM COMPARISON:

ChatGPT: Best balance of fluency, reasoning, and style control.

Claude: Most structured and logical summaries.

Gemini: Best factual summarization.

Copilot: Suitable mainly for technical and structured text.


8. CHALLENGES OBSERVED

Variation in summary length between platforms.

Chain-of-Thought prompts occasionally generated excessive intermediate reasoning.

Role-based prompting sometimes led to overly formal tone.

Copilot lacked creativity for narrative or descriptive texts.


9. KEY FINDINGS

Prompting strategy significantly affects summary quality and coherence.

Chain-of-Thought and Role-based prompting deliver superior human-like outputs.

ChatGPT and Claude excel in reasoning-based summarization.

Gemini performs best in factual and domain-specific summarization.

Zero-shot is ideal for fast, generic summarization but lacks depth.


10. CONCLUSION

This comparative study concludes that prompting techniques directly influence summarization performance across AI platforms.

Chain-of-Thought prompting achieved the best overall results in coherence and accuracy.

Role-based prompting is highly effective for formal and academic writing.

Few-shot prompting improves contextual accuracy on structured tasks.

ChatGPT and Claude outperformed Gemini and Copilot overall in summarization quality.

In summary, prompt engineering must be strategically designed according to the model and target domain.
The right combination of model and prompt style produces summaries that are concise, factual, and contextually relevant.


