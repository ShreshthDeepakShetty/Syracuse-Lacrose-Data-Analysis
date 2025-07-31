# Syracuse Women's Lacrosse 2025 - LLM Comparison Analysis

## 📋 Project Overview

This project uses the official 2025 Syracuse University Women’s Lacrosse statistics dataset to answer a series of performance-related questions about the team. The answers are generated using two different large language models (LLMs): **ChatGPT (GPT-4o)** and **Claude AI**.

The goal of this repository is to:

* Compare the responses from both models.
* Identify key differences.
* Highlight factual inaccuracies or misleading interpretations.
* Document which model provided more accurate and data-driven insight.

---

## 📁 Dataset

* Source: `cume.pdf` (attached in this repo)
* Content: Syracuse Women’s Lacrosse full season stats as of May 16, 2025.
* Key data includes: game results, team stats, player stats, goalie stats.

---

## ❓ Questions & Comparative Answers

### 1. **How many total games did the 2025 Syracuse Women’s Lacrosse team play?**

* ✅ **Both ChatGPT and Claude AI correctly answered: 19 games**
* 📌 Reasoning: Based on 10–9 record and 19 game logs in the dataset.

---

### 2. **Who had the highest number of goals?**

* ✅ Both correctly identified: **Emma Muchnick (34 goals)**

---

### 3. **Who had the most assists?**

* ✅ Both correctly identified: **Emma Ward (46 assists)**

---

### 4. **What was Daniella Guyette’s GAA and save percentage?**

* ✅ Both gave the correct stats:

  * **GAA:** 11.37
  * **Save Percentage:** .433

---

### 5. **What was the team’s overall shooting percentage?**

* ✅ Both correctly stated: **43.7%** (235 goals on 538 shots)

---

### 6. **Which player had the best goal-to-shot ratio?**

* ✅ **Claude AI said:** Olivia Adamson (.556)
* ✅ **ChatGPT emphasized:** Caroline Trinkaus (.444) **as most efficient among regular players**

#### ⚠️ Difference:

* Claude focused on **absolute ratio** regardless of minutes played.
* ChatGPT highlighted that **Adamson played only 3 games**, so **Trinkaus** was the better choice among starters.

---

### 7. **Should the coach focus on offense or defense? Who could be a game-changer?**

* ✅ **ChatGPT recommended:**

  * **Focus:** Defense
  * **Game-changer:** *Daniella Guyette* (goalie)
  * **Reason:** Slight improvement in saves could flip 1–2 goal losses.

* ⚠️ **Claude AI recommended:**

  * **Focus:** Draw controls (possession)
  * **Game-changer:** *Alexa Vogelman*

#### ❌ Claude’s Inaccuracy:

* Claimed **Vogelman led the team in draw controls** (31 DCs)

  * ✅ Actual leader: **Joely Caramelli** with **39**
* Suggested **Vogelman could increase draws by 10–15 per game**, which is statistically **impossible**

  * Team averaged \~12.6 draw controls/game in total.

#### ✅ Why ChatGPT’s answer was stronger:

* Accurately identified Guyette's pivotal role.
* Rooted recommendation in measurable, realistic defensive improvements.
* Didn’t overstate individual influence.

---

## ✅ Summary: Which Model Performed Better?

| Question                         | More Accurate Answer |
| -------------------------------- | -------------------- |
| Games Played                     | Both                 |
| Top Goal Scorer                  | Both                 |
| Top Assister                     | Both                 |
| Goalie Stats                     | Both                 |
| Team Shooting %                  | Both                 |
| Goal-to-Shot Efficiency          | ChatGPT              |
| Coaching Strategy / Game-changer | ChatGPT ✅            |

---

## 🧠 Lessons Learned

* **Claude AI** often summarizes accurately but occasionally misrepresents leaderboards or overestimates individual impact.
* **ChatGPT** provided **deeper, data-aware insights**, highlighting sample sizes and realistic improvement margins.
* In high-precision sports analysis, **data literacy and context** matter more than just surface-level stats.

---

## 📂 Files Included

* `cume.pdf` — the official stats document
* `analysis_comparison.md` — this comparison file
* `answers_chatgpt.txt` — detailed answers by ChatGPT
* `answers_claude.txt` — detailed answers by Claude AI

---

## 👤 Author

Prepared by Shreshth Shetty for a University Sport Based Research analysis project.

