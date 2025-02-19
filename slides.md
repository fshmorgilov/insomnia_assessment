---
marp: true
class: invert
---
# FinanceBuddy - Conversational AI for Personal Finance Management

---

## **Presentation structure**

- Introduction
- Problem to be Solved
- Risk Management
- Managing Client Expectations & Communication
- MVP Features & Prioritization
- Project Planning & Resource Allocation
- Assumptions


---

## **1. Introduction**

### **Objective:**

Develop a conversational AI assistant, "FinanceBuddy," that helps users track expenses, create budgets, and receive personalized financial advice within **3 months**.

---

## **2. Problem to be Solved**

### **User Pain Points:**

- Clients want to track finances to have better control over their spending and financial goals.

### **How Customers currently solve this problem:**

- By downloading apps like CoinKeeper.
- By building manual Excel spreadsheets for tracking expenses.
 
---

## **3. Hypothesis**

Implementing an **AI assistant feature** will solve stated pain point. It will also make users stay within the app, increasing potential conversions to other financial services.

### **Success Metrics**

✅ Increase in average session time

✅ Higher conversion rate to other neobank products (e.g., loans, investments, crypto services)

---

## **5. Risk Management**

| Risk                    | Mitigation Strategy                             |
| ----------------------- | ----------------------------------------------- |
| Scope creep             | Define clear MVP, limit non-core features       |
| AI accuracy limitations | Human-in-the-loop approach, continuous training |
| Regulatory compliance   | Legal review & secure API usage                            |
| Financial advice risk   | Legal review and prompt user to agree on using the service |
| Tech dependencies       | Use established AI/finance APIs                 |

---

## **5. Managing Client Expectations & Communication**

### **Transparent Communication Plan:**

✅ **Kickoff Meeting** – Align on goals, scope, and KPIs

✅ **Weekly Updates** – Sprint reviews & feature progress

✅ **Bi-weekly Demos** – Client validation & adjustments

✅ **Risk Mitigation** – Realistic timeline & AI accuracy expectations


---
## **6. Prioritization**
### **Methods:**

- **RICE scoring (Reach, Impact, Confidence, Effort)**
- **Feature categorization - outlines improtance after alligning with stakeholders**
    - Must have – Essential features required for the product to function effectively.
    - Should have – Important features that enhance usability but are not critical for the MVP.
    - Delighter – Features that provide extra value and improve user experience but are not necessary.

---

### **MVP Features (3-month launch)**

| Feature                                      | Reach | Impact | Confidence | Effort | RICE Score | Category |
| -------------------------------------------- | ----- | ------ | ---------- | ------ | ---------- | ----------------- |
| Pre-set questions                            | 7     | 8      | 8          | 2      | 224        | Must have         |
| Conversational AI chatbot (text-based)       | 8     | 9      | 7          | 4      | 126        | Must have         |
| AI expense categorization & summaries        | 9     | 10     | 7          | 6      | 105        | Must have         |

---

**Pre-set Questions**:
- Provides users with frequently asked questions about their spending habits.
- Helps users quickly get insights without manually inputting text.

**Conversational AI Chatbot (Text-based)**
- Engages users in real-time conversations about their finances based on data available in neobank.
- Uses NLP to understand user queries and provide relevant financial insights.

**AI Expense Categorization & Summaries**
- Automatically classifies transactions into user set categories.
- Provides spending summaries to help users track and manage expenses.

---

### **Post-launch features - Agreed with stakeholders to postpone**

| Feature                                      | Reach | Impact | Confidence | Effort | RICE Score | Category           |
| -------------------------------------------- | ----- | ------ | ---------- | ------ | ---------- | ---------------- |
| Recommendations of partnered services        | 6     | 10     | 6          | 5      | 72         | Should have        |
| Voice interaction support                    | 5     | 7      | 6          | 7      | 30         | Should have      |
| Third-party API integrations (Plaid, Mint)   | 5     | 7      | 6          | 7      | 30         | Should have        |
| Gamification & rewards                       | 8     | 6      | 6          | 6      | 48         | Delighter        |

---


## **7. Project Planning & Resource Allocation**

### **Agile Execution Plan:**

- **Sprint-based delivery:** 6 sprints of 2 weeks each.
- **MVP-first approach:** Focus on core functionalities before expanding.
- **Cross-functional alignment:** Clear team roles and responsibilities:
    - Daily standup meetings to check statuses and solve operational problems
    - Weekly backlog grooming sessions and task decomposition
    - Monthly retrocpective to discuss the development process.
- **Stakeholder reporting** through weekly check-ins and sprint burn-down chart display
---


### **Project plan for MVP**
**Sprint 1-3**: Develop conversational AI chatbot and pre-set questions.

**Sprint 4-5**: Integrational testing.  Implement AI expense categorization & summaries. 

**Spring 6**: Bug fixes. Conduct initial user testing and feedback loops.


---

### **Resource Allocation:**

| Role              | Responsibility                      | Team Size |
| ----------------- | ----------------------------------- | --------- |
| AI/ML Engineers   | Train AI models on transactions     | 3         |
| Backend Engineers | Secure API & infrastructure         | 3         |
| Frontend/UI       | Mobile interface within the app     | 2-3       |
| QA                | Ensure the quality app is delivered | 4         |
| Compliance        | Regulatory & data security          | 1-2       |

---

## **8. Strategic Partnerships & Integrations**

- **Plaid API** – Secure banking data aggregation
- **DeepSeek/OpenAI/Gemini API** – Conversational AI 
- **Stripe/Tink APIs** – Transaction insights

---

## **9. Assumptions**

- Before the kickoff of the project, multiple interviews were conducted with users, confirming that the problem really exists.
- The feature is aimed to launch on mobile platforms only.
- UI design is ready before the kickoff.
- AI/ML models will achieve sufficient accuracy within the 3-month timeframe.
- The development team has the required expertise to execute the project.
- All required documentation has been gathered, requirements are full before the project initiated.
- No additional development is required from the adjacent neobank teams.
- Deployment is managed by the neobank's deployment team.

---

## **10. Next Steps**

1. **Validate assumptions with early user testing**
2. **Monitor chatbot performance and create feature adoption report**
3. **Educate L1 and L2 support teams**


