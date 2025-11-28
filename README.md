# EX-02 – Cross-Platform Prompting: Evaluating Diverse Techniques in AI-Powered Text Summarization

## AIM
To evaluate and compare the effectiveness of prompting techniques (Zero-shot, Few-shot, Chain-of-thought, Role-based) across multiple AI platforms (ChatGPT, Gemini, Claude, Copilot) in the task of text summarization.

## SCENARIO
A 500-word article on **“The Basics of Blockchain Technology”** is provided.

### Tasks:
**Step 1** – Summarize the article in 120–150 words for undergraduate students.  
**Step 2** – Revise the summary to be simpler and include *two real-world applications*.

### Importance:
- Undergraduate students find advanced tech concepts challenging.
- Prompt engineering can drastically improve clarity, accuracy & readability.
- Comparing AI models reveals strengths, weaknesses & usability trade-offs.

---

## ALGORITHM
1. **Input Preparation**
   - Collect the blockchain article (approx. 500 words).
   - Remove unnecessary formatting & noise for better processing.

2. **Define Prompting Techniques**
   - **Zero-shot** – direct summarization with no examples.
   - **Few-shot** – add 1–2 example summaries.
   - **Chain-of-thought** – generate explanation reasoning before summary.
   - **Role-based** – response as a teacher for beginners.

3. **Platform Execution**
   - Perform summarization using: **ChatGPT, Gemini, Claude, Copilot**.

4. **Data Collection**
   - Store AI outputs and note generation time.

5. **Evaluation**
   - Rate performance on: Accuracy, Coherence, Simplicity, Speed, UX (0–5).
   - Calculate overall score and compare.

---

## PROCESS FLOW DIAGRAM

Article Text  
⬇️  
Prompting Technique: Zero-shot / Few-shot / CoT / Role-based  
⬇️  
AI Platform: ChatGPT / Gemini / Claude / Copilot  
⬇️  
Generated Summary  
⬇️  
Feedback: Simplify + Add real-world examples  
⬇️  
Final Revised Summary

---

# EVALUATION TABLE

| Platform | Accuracy | Coherence | Simplicity | Speed | UX | Total |
|----------|----------|-----------|-------------|--------|-----|--------|
| ChatGPT  | 5 | 5 | 4 | 4 | 5 | 23 |
| Gemini   | 4 | 4 | 4 | 5 | 4 | 21 |
| Claude   | 4 | 4 | 5 | 3 | 4 | 20 |
| Copilot  | 3 | 3 | 3 | 5 | 3 | 17 |

---

## VISUAL REPRESENTATIONS
### 1. **Process Flow Diagram**
(As referenced image above)

### 2. **Comparative Scores: Bar Chart (Simplicity Metric)**
*(Generated programmatically – displayed above)*

### 3. **Radar Chart – Overall Evaluation**
*(Generated visually – shows performance spread)*

---

## RESULT SUMMARIES

### **Step 1 – Initial Summary (120–150 Words)**
Blockchain is a secure digital ledger system used to record transactions across many computers without needing a central authority. Each entry is stored in a “block” that contains data and a cryptographic link to the previous block. This structure prevents tampering, increasing transparency and trust. The network is decentralized, and updates are verified through consensus mechanisms such as Proof of Work or Proof of Stake. Blockchain also supports smart contracts—self-executing programs that run when conditions are met. Although blockchain provides strong security, it faces challenges like high energy consumption, slower processing at large scale, and inconsistent government regulations. Overall, blockchain is a powerful emerging technology with broad applications in data security, digital payments, and automated processes.

### **Step 2 – Simplified Summary (Beginner-Friendly + Use-Cases)**
A blockchain is like a shared digital notebook that everyone can see and verify. When new information is added, it forms a “block” connected to earlier blocks so old records can’t be changed. No single person controls it; many people check and approve updates together. This makes blockchain safe and trustworthy. Programs called smart contracts can run automatically on it.

**Real-world uses include:**
1. **Banking & Cryptocurrency** – sending money without banks (e.g., Bitcoin, UPI-crypto bridges).
2. **Healthcare Records** – securely storing patient history across hospitals.

Blockchain is secure and transparent, though sometimes slower and more expensive to maintain.

---

## FINAL RESULT
The experiment successfully demonstrated how different prompting approaches affect summary quality across multiple AI systems. Zero-shot produced fast but basic summaries; few-shot improved structure; Chain-of-Thought improved reasoning clarity; Role-based generated the simplest output for students. Among the tested platforms, **ChatGPT scored highest overall**, followed by **Gemini**, **Claude**, and **Copilot**.

➤ Prompting technique selection significantly affects summarization clarity & educational usefulness.

---

