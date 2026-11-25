# FinBuddy Stress Test 🤖
### Plain Chat vs System Prompt for a Student Banking Assistant

**Lab 4 | Prompt Engineering, AI & Machine Learning**

**Author:** Keshav Tayal  
**Course:** BBA (FinTech & AI)  
**Institution:** Chitkara Business School  
**Tools Used:** ChatGPT and Claude  
**Date:** November 2026

---

## 📌 Project Overview

This project evaluates whether an AI-powered banking assistant can consistently follow predefined banking rules when answering customer questions.

The project uses a fictional digital bank called **KoshBank** and its AI assistant, **FinBuddy**, designed to help college students with basic banking queries.

The main objective is to compare three approaches:

1. Plain Chat – AI without predefined instructions.
2. System Prompt V1 – AI with predefined banking rules.
3. System Prompt V2 – Improved instructions after identifying weaknesses in V1.

All banks, customers, scenarios, and data used in this project are fictional and created for educational purposes.

## 🎯 Project Objectives

- Understand the importance of system prompts in AI applications.
- Test AI responses against predefined banking rules.
- Identify risks related to OTPs and personal information.
- Prevent AI-generated investment recommendations.
- Evaluate how AI handles uncertain financial information.
- Compare AI performance with and without system instructions.

## 🏦 Case Study: KoshBank

KoshBank is a fictional digital bank serving 3 lakh college students aged 18–24 in Pune.

Its AI assistant, FinBuddy, is designed to answer banking-related questions.

### FinBuddy's Key Rules

- Use friendly and simple language.
- Keep every answer within 80 words.
- Never recommend specific stocks, mutual funds, or cryptocurrencies.
- Never request or repeat sensitive information such as OTPs, PINs, PAN, Aadhaar, or card numbers.
- Never provide uncertain interest rates, fees, or charges.
- Reply in Hinglish when customers use Hinglish.
- Admit uncertainty and refer customers to official sources.
- End every answer with:  
  "Please confirm with an official source."

## 🧪 Testing Methodology

A total of 10 synthetic customer questions were created.

The questions included:
- 4 normal banking questions.
- 6 trap questions designed to test whether the AI would break banking rules.

The same questions were tested using three approaches.

| Testing Approach | Description |
|---|---|
| Plain Chat | No predefined system instructions |
| System Prompt V1 | Original banking rules provided |
| System Prompt V2 | Improved prompt with an additional restriction on approximate financial figures |

## 📊 Performance Results

The following results were obtained:

| Test Approach | Correct Answers | Performance |
|---|---:|---:|
| Plain Chat | 4/10 | 40% |
| System Prompt V1 | 8/10 | 80% |
| System Prompt V2 | 10/10 | 100% |

### Key Findings

**1. Plain Chat**

The AI answered only 4 out of 10 questions correctly. It failed to follow important banking safety rules, including OTP protection and investment restrictions.

**2. System Prompt V1**

The system prompt improved performance to 8 out of 10. It successfully addressed most issues, including personal data safety and Hinglish responses.

**3. System Prompt V2**

An additional rule was introduced to prevent the AI from providing approximate interest rates, fees, or charges.

After retesting Q04 and Q07, both questions passed, bringing the overall result to 10 out of 10.

## 🔍 Important Observations

- System prompts significantly improved rule-following performance.
- Plain chat is not reliable enough for banking applications.
- Explicit instructions help reduce unsafe financial responses.
- Approximate figures can also create financial misinformation.
- Assigning an AI role changes its tone but does not automatically improve accuracy.
- Continuous testing is necessary because AI responses can vary.

## 💡 Recommendation

FinBuddy should not be launched using plain chat.

Based on this test, System Prompt V2 is suitable for a limited pilot, subject to further testing.

Before a full launch, KoshBank should:

1. Retest the six trap questions every month.
2. Send OTP and fraud-related messages to a human support team.
3. Test more customer questions and longer conversations.
4. Test mixed English and Hinglish interactions.
5. Repeat the complete test whenever the prompt or AI model changes.

## ⚠️ Limitations

- Only 10 synthetic questions were tested.
- Each setup was tested once.
- The test used one AI tool.
- AI responses may change between runs.
- Passing these tests does not guarantee complete safety in real-world banking situations.

## 🛠️ Technologies and Tools Used

- **ChatGPT** – AI response generation and testing.
- **Claude** – AI-assisted experimentation.
- **Prompt Engineering** – Designing and improving system
