![GenI-Banner](https://github.com/genilab-fau/genial-fau.github.io/blob/8f1a2d3523f879e1082918c7bba19553cb6e7212/images/geni-lab-banner.png?raw=true)

# **Optimizing AI-Driven Hiring Decisions: A Multi-Technique Approach to Fair and Accurate Resume Screening**

## **1-Liner Description**
This research explores how advanced prompt engineering techniques—including Reverse Prompting, Multi-Persona Evaluation, Self-Consistency, and Tree of Thoughts can enhance AI resume screening accuracy, fairness, and efficiency.

---

## **Authors**
- Ben Jenkins
- **Academic Supervisor:** [Dr. Fernando Koch](http://www.fernandokoch.me)  

---

# **Research Question**
Can AI-powered hiring systems be improved through advanced **prompt engineering techniques** to ensure fairness, reduce bias, and enhance decision accuracy?  

---

## **Arguments**

### **What is Already Known?**
- AI-powered resume screening automates candidate evaluations but often assumes missing information, leading to **inaccurate or biased decisions**.  
- Traditional AI hiring models focus on **static decision-making**, limiting adaptability in **complex hiring scenarios**.  
- Human hiring managers evaluate candidates **from multiple perspectives**, but AI lacks this multi-dimensional approach.  
- **Structured reasoning** have been shown to improve AI decision-making in other domains.  

---

### **What This Research is Exploring**
- We **employ Reverse Prompting** to enable AI to ask hiring managers **clarifying questions** before finalizing evaluations.  
- We **are building a Multi-Persona AI framework** that evaluates candidates **from multiple perspectives** (Hiring Manager, Technical Lead, HR).  
- We **are exploring Self-Consistency techniques** to allow AI to **generate multiple reasoning paths** and select the most consistent answer.  
- We **leverage the Tree of Thoughts (ToT) approach** to break down hiring decisions into **structured evaluations across different criteria**.  
- We **integrate Context-Length Expansion techniques** to improve **long resume processing** and **career trajectory analysis**.  

---

### **Implications for Practice**
- **Fair Hiring Decisions** → AI asks for clarifications **before making assumptions**, reducing bias.  
- **Optimized AI Resume Screening** → AI evaluates candidates from **multiple perspectives** rather than a single viewpoint.  
- **Better Career Insights** → AI retains long-form resume context and **identifies hidden leadership skills**.  
- **Enhances AI-Human Collaboration** → Hiring managers can **co-create hiring decisions** with AI rather than relying solely on automation.  

---

# **Research Method**
**Methodology:**
- Implemented **Reverse Prompting, Multi-Persona Evaluation, Self-Consistency, and ToT reasoning** within an **AI hiring assistant** (LLM-based).  
- Conducted **experiments using real-world job descriptions & multi-page resumes** to test how well AI applies these techniques.  
- Compared AI hiring decisions **before and after applying prompt engineering techniques** to measure **accuracy, fairness, and decision confidence**.  
- Gathered **feedback from hiring managers and recruiters** on AI’s effectiveness in **dynamic decision-making**.  
- Evaluated **latency, consistency, and interpretability** of AI recommendations across different prompting techniques.  

---

# **Results**  

## **Test Case Performance Analysis**
| **Prompting Technique**      | **Execution Time (s)** | **Match Score (%)** | **Insights** |
|-----------------------------|-----------------|---------------|-----------|
| **Reverse Prompting**       | `29.2s`        | `78%`        | AI **asked clarification questions** before making a final decision, reducing bias. |
| **Multi-Persona Prompting**  | `63.3s`        | `85%`        | AI used **multiple perspectives (HR, Hiring Manager, Tech Lead)** to improve **decision transparency**. |
| **Tree of Thoughts (ToT)**   | `72.2s`        | `91%`        | AI evaluated **multiple reasoning paths**, leading to **high decision confidence**. |

**Key Findings:**  
- **Reverse Prompting** was the **fastest** and improved **hiring fairness** by ensuring AI asked for clarification before making decisions.  
- **Multi-Persona** improved **evaluation depth but increased response time** due to the multi-perspective approach.  
- **Tree of Thoughts (ToT)** resulted in **the highest accuracy**, but it was also the most computationally expensive.  

**Overall: Combining Reverse Prompting + ToT resulted in the best hiring decisions.**  

---

# **Further Research**  

- **Expand Reverse Prompting** in other AI-driven decision-making areas (e.g., **medical diagnosis, financial risk assessment**).  
- **Combine Self-Consistency with Multi-Persona Evaluations** for even stronger, well-rounded hiring decisions.  
- **Investigate Adaptive AI Models** that learn from **hiring manager responses** over time to improve future screenings.  
- **Evaluate the impact of prompt engineering** on reducing AI bias in hiring through **large-scale hiring datasets**.  

---

**Conclusion:** This research validates that **AI hiring decisions significantly improve** with advanced **prompt engineering techniques**. 

**Final Recommendation:** **Hybrid approaches combining Multi-Persona + Self-Consistency + Reverse Prompting offer the most balanced AI hiring solution.**  

---