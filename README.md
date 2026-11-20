# ChillarPay AI Support: From Zero-shot to Few-shot Prompting


**A FinTech case study on when a simple prompt is enough and when AI needs examples.**


Author: [Your Name] · BBA (FinTech), Chitkara Business School · Tool: [ChatGPT / Claude] · [Month Year]


## The case
**ChillarPay** (fictional) is a UPI payments app in Jaipur with 8 lakh users. It receives about 2,000 support messages a day in English and Hinglish, and urgent fraud cases get lost among simple questions. As a Business Analyst, I tested whether AI can sort messages, set priority and draft replies, and what kind of prompt it needs.


## The data
12 synthetic customer messages created with AI (8 English, 4 Hinglish, 3 deliberately tricky). I wrote the correct answers myself before testing.


## Approach
| Step | Prompt type | Task |
|---|---|---|
| 1 | Zero-shot | One-line summary of each message |
| 2 | Zero-shot | Category + priority + reply |
| 3 | Few-shot (3 examples) | Same task as Step 2 |


## Results
| Metric | Zero-shot | Few-shot |
|---|---|---|
| Correct category (/12) | __ | __ |
| Correct priority (/12) | __ | __ |
| Reply follows ChillarPay tone (/12) | __ | __ |
| Table format followed (/12) | __ | __ |


## Key learnings
1. **Zero-shot is enough for simple tasks:** [your finding]
2. **Few-shot teaches company-specific rules:** [message IDs it fixed]
3. **Hinglish and tricky messages:** [what changed]
4. **Limitation:** [one thing few-shot still got wrong]


## My recommendation to ChillarPay
[2–3 lines: which prompt ChillarPay should use for daily support, and why]


## Skills shown
Prompt engineering · Zero-shot and few-shot prompting · Synthetic data creation · AI output evaluation · Customer-support operations · FinTech domain knowledge


## What I learned
- Zero-shot prompting (instructions only) works well for simple, common tasks like summarising.
- Few-shot prompting (instructions + solved examples) teaches AI a company's own rules, tone and format.
- Start with the simplest prompt, and add examples only when the output misses the rules.
- How to create a realistic synthetic dataset with AI, without using real customer data.
- Why the answer key must be written before testing, so AI output is judged fairly.
- How to measure AI quality with a scorecard instead of gut feeling.
- AI output must always be checked by a human before business use.


*ChillarPay and all data in this project are fictional and created for learning.*
