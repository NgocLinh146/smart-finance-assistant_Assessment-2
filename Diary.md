## Week 8 – Project Planning and CSV Review

**Artifact:**  
Evidence for this week is stored in the `AI-CONVERSATIONS/` folder. The relevant files are:

- `AI-CONVERSATIONS/Week 8_1.png`
- `AI-CONVERSATIONS/Week 8_2.png`
- `AI-CONVERSATIONS/Week 8_3.png`
- `AI-CONVERSATIONS/Week 8_4.png`
- `AI-CONVERSATIONS/Week 8_Planning`

**Context:**  
I used AI to check whether my Budget Buddy project idea was suitable for the Smart Finance Assistant assignment. I also wanted to confirm whether my sample transaction CSV file was appropriate for the app before I started coding.

**Reflection:**  
The AI interaction helped me confirm that Budget Buddy was a suitable direction because it can cover the main assignment requirements, including Chat, RAG, an Agent Tool, Gradio UI, and testing. It also helped me confirm that my CSV structure with Date, Description, Category, and Amount was suitable for analysing personal spending. From this, I was able to plan the project more clearly and break the work into logical parts. This gave me a more organised and practical plan before starting the notebook.

## Week 9 – Notebook Setup, Problem Understanding, and Pseudocode

### Artifact 1: Sample Transaction Data Setup  
Evidence for this part is stored in the `AI-CONVERSATIONS/` folder. The relevant files are:

- `AI-CONVERSATIONS/week 9_1.png`
- `AI-CONVERSATIONS/Week 9_2.png`
- `AI-CONVERSATIONS/week 9_3.png`

**Context:**  
I used AI to revise the “Sample Transaction Data Setup” section of my notebook based on my actual transaction CSV file. I also sent the starter notebook sample format so the AI response would stay close to the original notebook style instead of creating unrelated sample data.

---

### Artifact 2: Project Problem and Business Value  
Evidence for this part is stored in the `AI-CONVERSATIONS/` folder. The relevant files are:

- `AI-CONVERSATIONS/week 9_4.png`
- `AI-CONVERSATIONS/week 9_5.png`
- `AI-CONVERSATIONS/week 9_6.png`

**Context:**  
I asked AI to help brainstorm realistic personal finance problems that Budget Buddy could solve. I wanted the problem statement to be clearer about who the app helps and what value it provides.

---

### Artifact 3: Inputs, Outputs, and Manual Examples  
Evidence for this part is stored in the `AI-CONVERSATIONS/` folder. The relevant files are:

- `AI-CONVERSATIONS/week 9_7.png`
- `AI-CONVERSATIONS/week 9_8.png`
- `AI-CONVERSATIONS/week 9_9.png`
- `AI-CONVERSATIONS/week 9_10.png`
- `AI-CONVERSATIONS/week 9_11.png`
- `AI-CONVERSATIONS/week 9_12.png`

**Context:**  
I used AI to identify the most useful inputs and outputs for the app, such as CSV data, monthly budget, spending totals, refunds, highest spending category, and chatbot advice. I also asked AI to create manual examples from my actual CSV file so I could show how the calculations work before coding.

---

### Artifact 4: Pseudocode Review and Improvement  
Evidence for this part is stored in the `AI-CONVERSATIONS/` folder. The relevant files are:

- `AI-CONVERSATIONS/week 9_13.png`
- `AI-CONVERSATIONS/week 9_14.png`
- `AI-CONVERSATIONS/week 9_15.png`
- `AI-CONVERSATIONS/week 9_16.png`

**Context:**  
I asked AI to review my pseudocode for analysing spending data from a CSV file. I wanted to check whether I was missing any edge cases or business logic before converting the plan into Python code.

---

### Reflection  
This week, AI helped me move from a general project idea into a clearer notebook structure. I tried to make my prompts specific by explaining which starter notebook section I was working on, what starter notebook was already provided, and what parts I wanted the AI to complete or improve. I also shared the original starter notebook sample format so the AI would follow the assignment structure instead of giving unrelated code. This helped the AI suggestions fit my Budget Buddy project better.

The most useful part was learning how to connect the assignment requirements with my actual CSV data. Instead of using random sample data, I revised the notebook around my real transaction file with the columns Date, Description, Category, and Amount. AI also helped me make the problem statement more specific by focusing on students and young adults with limited monthly budgets.

I also learned that AI responses still need checking. For example, when I asked for markdown tables, the dollar signs caused formatting issues in the notebook, so I had to ask how to fix the table format. This helped me understand that even small formatting details can affect the quality of the final notebook.

## Week 10 – Core Python Implementation and Financial Recommendations

### Artifact 1: Load and Clean Transaction Data  
Evidence for this part is stored in the `AI-CONVERSATIONS/` folder. The relevant files are:

- `AI-CONVERSATIONS/week 10_1.png`
- `AI-CONVERSATIONS/week 10_2.png`
- `AI-CONVERSATIONS/week 10_3.png`
- `AI-CONVERSATIONS/week 10_4.png`
- `AI-CONVERSATIONS/week 10_5.png`
- `AI-CONVERSATIONS/week 10_6.png`
- `AI-CONVERSATIONS/week 10_7.png`

**Context:**  
I used AI to complete the starter notebook function for loading and cleaning transaction data. The original starter notebook had an incomplete code section, so I asked AI to replace the placeholder with beginner-friendly Python code that followed my pseudocode and worked with my CSV transaction format.

---

### Artifact 2: Spending Pattern Analysis  
Evidence for this part is stored in the `AI-CONVERSATIONS/` folder. The relevant files are:

- `AI-CONVERSATIONS/week 10_8.png`
- `AI-CONVERSATIONS/week 10_9.png`
- `AI-CONVERSATIONS/week 10_10.png`
- `AI-CONVERSATIONS/week 10_11.png`
- `AI-CONVERSATIONS/week 10_12.png`
- `AI-CONVERSATIONS/week 10_13.png`
- `AI-CONVERSATIONS/week 10_14.png`
- `AI-CONVERSATIONS/week 10_15.png`
- `AI-CONVERSATIONS/week 10_16.png`
- `AI-CONVERSATIONS/week 10_17.png`

**Context:**  
I asked AI to create the `analyze_spending_patterns(df, monthly_budget)` function based on my pseudocode. This section focused on calculating total expenses, total refunds, net spending, spending by category, highest spending category, top categories, large transactions, and budget status.

---

### Artifact 3: Financial Recommendations Report  
Evidence for this part is stored in the `AI-CONVERSATIONS/` folder. The relevant files are:

- `AI-CONVERSATIONS/week 10_18.png`
- `AI-CONVERSATIONS/week 10_19.png`
- `AI-CONVERSATIONS/week 10_20.png`
- `AI-CONVERSATIONS/week 10_21.png`
- `AI-CONVERSATIONS/week 10_22.png`
- `AI-CONVERSATIONS/week 10_23.png`
- `AI-CONVERSATIONS/week 10_24.png`

**Context:**  
I used AI to complete the financial recommendations section from the starter notebook. I asked AI to create a function that used the analysis dictionary from `analyze_spending_patterns()` and turned the results into a clear, business-friendly report for the user.

---

### Reflection  
This week, AI helped me convert my planning and pseudocode into working Python functions for Budget Buddy. I focused on the core implementation parts of the notebook, especially the sections where the starter notebook had incomplete placeholder code. Instead of asking AI for general code, I tried to write clearer prompts that explained which notebook section I was working on, what the incomplete starter code was supposed to do, and how the new code should connect to my previous pseudocode and CSV file.

The most useful part was developing the data cleaning and spending analysis functions. AI helped me think about real-world CSV issues such as dollar signs, missing values, invalid amounts, empty files, and inconsistent category names. I also learned that it is important to separate expenses and refunds correctly, because refunds should reduce net spending but still need to be shown clearly to the user.

For the spending analysis section, AI helped me build business logic that goes beyond simple totals. This made the app more useful as a finance assistant because it gives the user meaningful insights instead of only showing raw numbers.

I also used AI to create a financial recommendations function that turns the analysis results into a user-friendly report. This helped connect the technical calculations to the business purpose of the app.
