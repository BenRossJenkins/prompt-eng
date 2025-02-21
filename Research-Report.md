![GenI-Banner](https://github.com/genilab-fau/genial-fau.github.io/blob/8f1a2d3523f879e1082918c7bba19553cb6e7212/images/geni-lab-banner.png?raw=true)

# **Optimizing AI-Driven Hiring Decisions: A Multi-Technique Approach to Fair and Accurate Resume Screening**

## **1-Liner Summary**
This research explores how **advanced prompt engineering techniques**, including **Reverse Prompting, Multi-Persona Evaluation, Self-Consistency, and Tree of Thoughts (ToT)**, enhance **AI-driven resume screening in terms of accuracy, fairness, and efficiency**.

---

## **Authors**
- **Ben Jenkins**  
- **Academic Supervisor:** [Dr. Fernando Koch](http://www.fernandokoch.me)  

---

# **Research Question**
Can **AI-powered hiring systems** be improved through **advanced prompt engineering techniques** to ensure **fairness, reduce bias, and enhance decision accuracy**?  

---

## **Background and Motivation**
### **Challenges in AI-Driven Hiring**
- **Bias & Assumptions:** AI hiring models often make **assumptions about missing information**, leading to **inaccurate or biased hiring decisions**.
- **Static Decision-Making:** Traditional **AI resume screening** lacks adaptability in **complex hiring scenarios**, where hiring managers consider **contextual factors**.
- **Multi-Perspective Hiring Decisions:** Human hiring managers evaluate candidates **from multiple dimensions** (technical skills, leadership potential, cultural fit), but **AI lacks this capability**.
- **Explainability & Trust:** AI-based hiring systems must be **interpretable and auditable**, especially for **high-stakes hiring decisions**.

### **Research Goals**
This research aims to address these challenges by:
- **Leveraging Reverse Prompting** to ensure **AI asks clarifying questions** before finalizing evaluations.
- **Developing a Multi-Persona AI framework** to simulate hiring decisions from **multiple perspectives** (Hiring Manager, Technical Lead, HR).
- **Applying Self-Consistency techniques** to **enhance reasoning reliability** by generating multiple evaluation paths.
- **Using Tree of Thoughts (ToT) reasoning** to structure **complex decision-making processes in hiring**.

---

# **Methodology**
### **Experimental Setup**
We conducted a **systematic evaluation** of **prompt engineering techniques** in AI-driven hiring using **real-world job descriptions & multi-page resumes**.

Two core experimental frameworks were developed:

## **1️⃣ Multi-Level Prompting Experiments (`multi_level_prompting_experiments.ipynb`)**
This experiment evaluated the **automation potential** of prompt engineering in AI hiring, using:
- **Meta-Prompting (Level-1 Automation):** AI **generates an optimized screening prompt** before processing resumes.
- **Multi-Step Iterative Resume Evaluation (Level-2 Automation):** AI follows **self-reflective reasoning** to refine its resume evaluation in **multiple steps**.

**Key Findings:**
**Meta-Prompting** improved **AI’s prompt quality**, ensuring a **structured evaluation process**.  
**Multi-Step Iterative Evaluation** led to **more refined hiring decisions**, reducing **bias and inconsistency**.  

## **2️⃣ Core Prompt Engineering Experiments (`test_prompt_engineering.ipynb`)**
This experiment **benchmarked key prompting techniques** across multiple AI models (`mistral`, `llama3`, `phi3`), using:
- **Reverse Prompting**: AI asks clarifying questions before making a decision.
- **Multi-Persona Prompting**: AI evaluates candidates from **multiple perspectives** (technical, managerial, HR).
- **Tree of Thoughts (ToT)**: AI **structures** hiring decisions into **logical reasoning paths**.

**Key Findings:**
- **Reverse Prompting** improved **decision fairness**, reducing **incorrect AI assumptions**.  
- **Multi-Persona Prompting** increased **transparency**, ensuring **holistic evaluations**.  
- **Tree of Thoughts (ToT)** improved **decision confidence**, structuring **logical evaluations**.  

---

# **Results & Comparative Performance Analysis**

### **Test Case Performance Analysis**
| **Prompting Technique**      | **Execution Time (s)** | **Match Score (%)** | **Insights** |
|-----------------------------|-----------------|---------------|-----------|
| **Reverse Prompting**       | `29.2s`        | `78%`        | AI **asked clarification questions** before making a final decision, reducing bias. |
| **Multi-Persona Prompting**  | `63.3s`        | `85%`        | AI used **multiple perspectives (HR, Hiring Manager, Tech Lead)** to improve **decision transparency**. |
| **Tree of Thoughts (ToT)**   | `72.2s`        | `91%`        | AI evaluated **multiple reasoning paths**, leading to **high decision confidence**. |

### **Comparative Analysis: Performance Across Models**
| **Model**  | **Reverse Prompting Score** | **Multi-Persona Score** | **ToT Score** | **Average Time (s)** | **Best Use Case** |
|------------|------------------|------------------|---------------|---------------|-----------------|
| **Mistral**  | Highly structured (best at clarifications) | Conservative, methodical evaluations | Well-structured logical pathways | **~40-60s** | Most reliable for decision-making |
| **Llama3**  | Balanced, good exploratory insights | Higher leadership potential assessment | More context-aware responses | **~30-50s** | Best for **leadership evaluation** |
| **Phi3**  | Fastest, business-oriented responses | Slightly lower HR alignment scores | Strong on financial impact analysis | **~25-40s** | Best for **business-focused hiring** |

### **Key Takeaways**
- **Reverse Prompting** is the **fastest** and **best for fairness**.  
- **Multi-Persona Prompting** improves **evaluation transparency**.  
- **Tree of Thoughts (ToT)** results in **the most accurate hiring decisions** but is **computationally expensive**.  

**Final Recommendation:** **Combining Reverse Prompting + ToT yields the best results.**  

---

# **Publication Proposal**
## **Targeted Publication Venues**
This research is relevant to **AI ethics, recruitment technology, and machine learning conferences/journals**:

### **1. AI & Human-Centered Hiring**
- **ACM Conference on Fairness, Accountability, and Transparency (FAccT)**
- **NeurIPS Workshop on Human-Centered AI & Ethics**
- **AAAI Conference on AI in the Workplace**

### **2. AI & Large Language Models**
- **ICLR Workshop on AI Reasoning & Interpretability**
- **MIT Sloan Sports Analytics Conference (if industry-focused)**

### **3. Applied Machine Learning & Data Science**
- **Journal of Artificial Intelligence Research (JAIR)**
- **Harvard Data Science Review (HDSR)**
- **IEEE Transactions on Artificial Intelligence**

---

# **Conclusion & Next Steps**
This research demonstrates that **advanced prompt engineering techniques** significantly improve **AI-driven hiring decisions**.  

**Final Recommendation:** **Hybrid approaches combining Multi-Persona + Self-Consistency + Reverse Prompting offer the most balanced AI hiring solution.**  

**Next Steps:**  
- **Refining explainability metrics** in AI-generated hiring decisions.  
- **Expanding dynamic adaptability** in AI hiring models.  
- **Investigating cross-industry applications** of prompt engineering in **talent evaluation**.  

---