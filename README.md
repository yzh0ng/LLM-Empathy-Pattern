# 🤖 AI Empathy Analysis: How LLMs Respond to Breakup Scenarios

As AI becomes more integrated into everyday life, people are increasingly turning to large language models (LLMs) not only for information but also for emotional support. This shift raises an important question: **Can AI demonstrate empathy? If so, how does it do it, and does it do it fairly?**

We're interested in how different LLMs approach empathy in sensitive relationship scenarios, especially those involving **moral nuance** and **emotional complexity** like infidelity.

---

## 🔍 Research Objectives

- Compare how different LLMs demonstrate empathy in relationship-related scenarios, especially involving infidelity  
- Explore differences in emotional tone, moral framing, and support strategies based on user condition  
- Analyze how **user role (cheater vs. cheated-on)** interacts with **model identity (ChatGPT, Claude, DeepSeek)** in a **2×2 experimental design**

---

## 🧪 Methodology

We selected:
- **ChatGPT** and **Claude**: two of the most prominent and widely used LLMs today  
- **DeepSeek**: a newer model with almost no existing research on emotional or empathetic behavior

**Process:**
- Collected 20 real posts from [r/BreakUps] (10 from cheaters, 10 from cheated-on users)  
- Prompted each LLM to respond → 60 responses total  
- Analyzed responses using:
  - **LIWC** (Linguistic Inquiry and Word Count) to assess psychological and emotional word use  
  - **N-gram analysis** to explore stylistic and phrase-level differences


## 📐 Statistical Tests

- **2-way ANOVAs** to examine interaction effects (group × model)  
- **Welch’s t-tests** for within-model comparisons across user roles  
- **Tukey HSD** for pairwise post-hoc analysis  

---

## 📊 Key Findings

- All three models expressed empathy across both user roles  
- **ChatGPT**: reflective, therapist-like tone with frequent causal and moral framing  
- **DeepSeek**: emotionally expressive, validating, like a supportive friend  
- **Claude**: neutral and balanced, often echoing the user’s story without strong interpretation  

---

## 📁 Files in This Repository

- `LIWC-22 Results - Text Analysis Database for LIW___ - LIWC Analysis.csv`  
  → Raw LIWC output from all 60 model responses  
- `Final Project Analysis.ipynb`  
  → Python notebook with full statistical analysis and plots  
- `Text Database.csv`  
  → Clean, viewer-friendly version of the original prompts and responses  

---

