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
I asked AI to help complete the spending pattern analysis section based on my pseudocode and the incomplete starter notebook code. This section focused on calculating total expenses, total refunds, net spending, spending by category, highest spending category, top categories, large transactions, and budget status.

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
I used AI to complete the financial recommendations section for my Budget Buddy project. I asked AI to create a function that used the spending analysis results and turned them into a clear, business-friendly report for the user.

---

### Reflection  
This week, AI helped me convert my planning and pseudocode into working Python functions for Budget Buddy. I focused on the core implementation parts of the notebook, especially the sections where the starter notebook had incomplete placeholder code. Instead of asking AI for general code, I tried to write clearer prompts that explained which notebook section I was working on, what the incomplete starter code was supposed to do, and how the new code should connect to my previous pseudocode and CSV file.

The most useful part was developing the data cleaning and spending analysis functions. AI helped me think about real-world CSV issues such as dollar signs, missing values, invalid amounts, empty files, and inconsistent category names. I also learned that it is important to separate expenses and refunds correctly, because refunds should reduce net spending but still need to be shown clearly to the user.

I also used AI to create a financial recommendations function that turns the analysis results into a user-friendly report. This helped connect the technical calculations to the business purpose of the app.

## Week 11 – Chatbot, RAG System, and Custom Financial Tools

### Artifact 1: Chat Interface Integration  
Evidence for this part is stored in the `AI-CONVERSATIONS/` folder. The relevant files are:

- `AI-CONVERSATIONS/week 11_1.png`
- `AI-CONVERSATIONS/week 11_2.png`
- `AI-CONVERSATIONS/week 11_3.png`
- `AI-CONVERSATIONS/week 11_4.png`

**Context:**  
I used AI to complete the Chat Interface Integration section for Budget Buddy. AI helped create a finance chatbot that uses spending analysis results to provide personalised budgeting and spending advice for users.

---

### Artifact 2: RAG System for Financial Documents  
Evidence for this part is stored in the `AI-CONVERSATIONS/` folder. The relevant files are:

- `AI-CONVERSATIONS/week 11_5.png`
- `AI-CONVERSATIONS/week 11_6.png`
- `AI-CONVERSATIONS/week 11_7.png`
- `AI-CONVERSATIONS/week 11_8.png`

**Context:**  
I used AI to create a simple RAG-style feature for Budget Buddy. This section retrieves relevant finance guidance from stored documents and provides helpful budgeting and spending advice to users.

---

### Artifact 3: Debugging the RAG System  
Evidence for this part is stored in the `AI-CONVERSATIONS/` folder. The relevant files are:

- `AI-CONVERSATIONS/week 11_9.png`
- `AI-CONVERSATIONS/week 11_10.png`
- `AI-CONVERSATIONS/week 11_11.png`
- `AI-CONVERSATIONS/week 11_12.png`
- `AI-CONVERSATIONS/week 11_13.png`

**Context:**  
After running the first RAG code, I found an error because `rag.create()` and `rag.ask()` were not available. I asked AI to fix the code while keeping the same Budget Buddy RAG idea. AI rewrote the section using normal beginner-friendly Python, storing finance documents in a dictionary, retrieving relevant text using keyword matching, and returning a clear answer based on the retrieved context.

---

### Artifact 4: Custom Financial Tool Development  
Evidence for this part is stored in the `AI-CONVERSATIONS/` folder. The relevant files are:

- `AI-CONVERSATIONS/week 11_14.png`
- `AI-CONVERSATIONS/week 11_15.png`
- `AI-CONVERSATIONS/week 11_16.png`
- `AI-CONVERSATIONS/week 11_17.png`
- `AI-CONVERSATIONS/week 11_18.png`

**Context:**  
I used AI to complete the Custom Financial Tools section for Budget Buddy. AI helped create a savings goal calculator that estimates how long it will take a user to reach a target savings amount based on their current savings and monthly contributions.

---

### Reflection  
This week, AI helped me extend Budget Buddy beyond basic data analysis by adding chatbot, retrieval, and custom tool features. I focused on making the project feel more like a personal finance assistant instead of only a notebook that calculates spending totals.

In terms of creating the chat interface, AI helped me build a Budget Buddy chatbot function that uses the analysis results from the previous spending analysis section. This made the chatbot more connected to the user’s actual transaction data because the prompt included total expenses, refunds, net spending, highest spending category, and budget status.

The second task was creating a simple RAG-style financial document system. At first, the code used `rag.create()` and `rag.ask()`, but when I tested it, those functions were not available. This was useful because it showed me that AI-generated code still needs to be tested carefully. I then asked AI to fix the problem, and the final version used normal Python keyword matching instead. This made the code easier to understand and more reliable for a beginner programming project.

Overall, AI helped me create chatbot logic, a simple document retrieval system, debug broken code, and build a custom financial calculator. I still had to check the code, test it, and ask for corrections when something did not work, which helped me understand the importance of debugging and adapting AI-generated code to my actual project environment.

## Week 12 – User Interface and System Testing

### Artifact 1: Gradio User Interface
Evidence for this part is stored in the `AI-CONVERSATIONS/` folder. The relevant files are:

- `AI-CONVERSATIONS/week 12_1.png`
- `AI-CONVERSATIONS/week 12_2.png`
- `AI-CONVERSATIONS/week 12_3.png`
- `AI-CONVERSATIONS/week 12_4.png`
- `AI-CONVERSATIONS/week 12_5.png`

**Context:**  
I used AI to create a Gradio user interface for Budget Buddy. AI helped connect the spending analysis, chatbot, financial advice retrieval, and savings calculator features into a finance assistant interface.

---

### Artifact 2: Foundation Function Tests
Evidence for this part is stored in the `AI-CONVERSATIONS/` folder. The relevant files are:

- `AI-CONVERSATIONS/week 12_6.png`
- `AI-CONVERSATIONS/week 12_7.png`
- `AI-CONVERSATIONS/week 12_8.png`
- `AI-CONVERSATIONS/week 12_9.png`
- `AI-CONVERSATIONS/week 12_10.png`
- `AI-CONVERSATIONS/week 12_11.png`

**Context:**  
I used AI to create foundation tests for Budget Buddy. The tests checked transaction analysis results, refunds, large transactions, missing values, invalid inputs, and business logic calculations using assert statements.

---

### Artifact 3: Integration Testing
Evidence for this part is stored in the `AI-CONVERSATIONS/` folder. The relevant files are:

- `AI-CONVERSATIONS/week 12_12.png`
- `AI-CONVERSATIONS/week 12_13.png`
- `AI-CONVERSATIONS/week 12_14.png`
- `AI-CONVERSATIONS/week 12_15.png`
- `AI-CONVERSATIONS/week 12_16.png`

**Context:**  
I used AI to create integration tests for Budget Buddy. These tests verified that the spending analysis, chatbot, financial advice retrieval system, and savings calculator worked together correctly as a complete workflow.

---

### Reflection

This week, AI helped me improve Budget Buddy by adding a user interface and testing the complete system. The focus was on making the project easier to use and ensuring that the different components worked correctly together.

The first task was creating a Gradio interface. AI helped design a simple interface that combined all features into one application. This made the project feel more like a real personal finance assistant instead of a collection of separate notebook functions.

I also used AI to create foundation tests for the core functions. These tests checked normal transaction data, refunds, large amounts, missing values, invalid inputs, and business logic calculations. Writing tests helped me verify that the functions worked as expected.

Finally, I created integration tests to check the complete workflow. I learned that testing individual functions is important, but testing how components interact is equally important for ensuring system reliability.

Overall, Week 12 focused on usability and quality assurance. AI helped me build a user-friendly interface and develop testing procedures.

