# EX-02-Cross-Platform-Prompting-Evaluating-Diverse-Techniques-in-AI-Powered-Text-Summarization

# AIM

To evaluate and compare the effectiveness of prompting techniques (Zero-shot, Few-shot, Chain-of-thought, Role-based) across multiple AI platforms (ChatGPT, Gemini, Claude, Copilot) in the task of text summarization.

## SCENARIO  

A 500-word article on **“The Basics of Blockchain Technology”** is provided.  

- **Step 1**: Summarize the article in 120–150 words for undergraduate students.  
- **Step 2**: Revise the summary to be even simpler and include at least two real-world applications of blockchain.  

### Why this matters:  
- Undergraduate learners often find technical concepts like blockchain difficult.  
- Prompt engineering strategies can greatly affect the clarity, accuracy, and simplicity of AI-generated summaries.  
- Comparing multiple AI platforms highlights trade-offs in speed, usability, and performance.  

## ALGORITHM  

1. **Input Preparation**  
   - Collect the blockchain article.  
   - Remove redundant formatting, ensure clarity.  

2. **Define Prompting Techniques**  
   - Zero-shot: Direct summarization without examples.  
   - Few-shot: Provide 1–2 sample article-summary pairs.  
   - Chain-of-thought: Ask AI to reason step-by-step before summarizing.  
   - Role-based: Assign the role of a teacher explaining to undergraduates.  

3. **Platform Execution**  
   - Use ChatGPT, Gemini, Claude, Copilot.  
   - Run the same article under each technique.  

4. **Data Collection**  
   - Store all summaries in a structured table.  
   - Note time taken for each output.  

5. **Evaluation**  
   - Assign scores (0–5) for Accuracy, Coherence, Simplicity, Speed, UX.  
   - Compute overall performance.  


# EVALUATION TABLE
<img width="1536" height="1024" alt="ChatGPT Image Aug 29, 2025, 03_48_48 PM" src="https://github.com/user-attachments/assets/7a7adcf2-ed94-4a7b-a1a5-71656c0fb8a6" />

## VISUAL REPRESENTATIONS
1. Process Flow Diagram:
<img width="1024" height="1536" alt="ChatGPT Image Aug 29, 2025, 03_35_02 PM" src="https://github.com/user-attachments/assets/0429e39a-75df-4a3e-aed7-20b405870177" />

2.Comparative Scores (Bar Chart Representation):
<img width="1600" height="1000" alt="bar_chart_simplicity" src="https://github.com/user-attachments/assets/e17cc08d-4dfd-4795-a162-3954de6fb9ec" />

3.Spider/Radar Chart – Overall Evaluation (Conceptual):
<img width="1400" height="1400" alt="radar_chart_evaluation" src="https://github.com/user-attachments/assets/7c60709e-425c-4ad8-a134-415618aaaf27" />

## RESULT  

### Step 1 – Initial Summary  
Blockchain is a distributed digital ledger that records transactions securely across multiple computers. Each block stores data with a cryptographic hash and links to the previous block, making changes very difficult. The system is decentralized, meaning no single party has full control. New records are verified by consensus methods such as Proof of Work or Proof of Stake. Smart contracts—programs that run automatically—extend blockchain’s functionality. Although blockchain provides transparency and trust, it faces issues like scalability, energy consumption, and regulation.  

### Step 2 – Revised Beginner-Friendly Summary  
A blockchain is like a shared notebook where everyone has the same copy. New entries are added in “blocks” that link together so old records cannot be changed. No one person controls it; instead, many participants agree on updates. Programs called smart contracts can also run automatically.  

Real-world uses include:  
1. **Bitcoin** – allows people to send money without banks.  
2. **Food supply tracking** – companies log each step to ensure safety.  

Blockchains build trust and transparency but can sometimes be slow or expensive.  

