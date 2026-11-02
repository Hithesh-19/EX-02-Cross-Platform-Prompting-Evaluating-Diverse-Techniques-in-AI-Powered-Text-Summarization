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

\
\


## Algorithm
<img width="1280" height="720" alt="image" src="https://github.com/user-attachments/assets/22e22b74-ded9-4104-919d-7a50e71c4d27" />
Step 1: Define the Task
Select a technical article of approximately 500 words on "The Basics of Blockchain Technology."
Identify the target audience as undergraduate engineering students.
Define the summarization requirements:
Preserve important technical information.
Use simple and understandable language.
Avoid unnecessary technical terms.
Maintain the original meaning.
Generate a concise summary.

\
Step 2: Select AI Platforms

Choose the following AI platforms for comparison:

ChatGPT
Google Gemini
Claude
Microsoft Copilot

\
Step 3: Apply Different Prompting Techniques

Use the same blockchain article with four different prompting techniques.

3.1 Zero-Shot Prompting

Give a direct instruction without providing examples.

Example prompt:

Summarize the following article about blockchain technology in 150 words using simple English. Highlight its key concepts, working process, advantages, and applications.

3.2 Few-Shot Prompting

Provide a few examples of the expected summary format before giving the actual article.

Example prompt:

Example 1: Input: Artificial Intelligence is a technology that enables machines to perform intelligent tasks. Output: AI allows machines to perform tasks that normally require human intelligence.

Example 2: Input: Cloud computing provides computing services over the internet. Output: Cloud computing allows users to access storage and computing resources through the internet.

Now summarize the given article about blockchain technology in the same style using simple English.

3.3 Chain-of-Thought Prompting

Ask the AI to organize the important concepts before producing the final summary.

Example prompt:

Analyze the blockchain article by identifying its main concepts, working mechanism, advantages, and applications. Organize the key information and provide a clear, accurate summary in 150 words using simple English.

3.4 Role-Based Prompting

Assign a specific role to the AI to improve the quality and suitability of the response.

Example prompt:

Act as an experienced computer science professor. Summarize the given article about blockchain technology for undergraduate engineering students. Explain the important concepts in simple English and include the key points in approximately 150 words.

Step 4: Execute Prompts Across Platforms
Open each selected AI platform.
Enter the same blockchain article.
Apply each of the four prompting techniques.
Generate summaries using each technique.
Record the generated outputs.
Note the time taken to generate each summary.

This produces 16 outputs (4 platforms × 4 prompting techniques).

Step 5: Evaluate the Generated Summaries

Evaluate each summary using the following criteria:

Criteria	Description
Accuracy	Checks whether the summary correctly represents the original article.
Coherence	Evaluates the logical flow and clarity of sentences.
Simplicity	Checks whether undergraduate students can easily understand the summary.
Speed	Measures the time taken to generate the summary.
User Experience	Evaluates readability, formatting, usefulness, and ease of interaction.
Step 6: Assign Scores

Assign scores from 1 to 5 for each evaluation criterion.

Score	Performance
5	Excellent
4	Very Good
3	Good
2	Average
1	Poor

For speed, a higher score represents faster response time.

Step 7: Compare and Identify the Best Platform
Compare the scores obtained by all four AI platforms.
Identify which prompting technique produces the most accurate summary.
Compare the clarity and simplicity of the generated content.
Identify the fastest platform.
Calculate the overall average score.
Select the best platform and prompting technique combination.

Overall Score Formula:

Overall Score = (Accuracy + Coherence + Simplicity + Speed Score + User Experience) / 5

Step 8: Record Observations

Prepare a comparison table containing the scores of all platforms and prompting techniques.

Use the observations to identify the strengths and weaknesses of each combination.


\
\
## Result
Cross-Platform-Prompting-Evaluating-Diverse-Techniques-in-AI-Powered-Text-Summarization
