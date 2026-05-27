### Entry 1 – Brainstorming Finance Problem

**Artifact:**
![AI Screenshot](week8_ai_1.png)
![AI Screenshot](week8_ai_2.png)
**Context:**
I was trying to get AI chat to help me come up with a problem to solve for my Smart Finance Assistant.

**My Prompt:**
"Help me brainstorm specific personal finance problems that could be solved with a CSV analysis tool."

**AI Response Summary:**
The AI gave ideas related to students and young adults, including budgeting, saving, and tracking their spending.

**My Critique/Improvement:**
Some of the ideas were too general, so I decided to focus specifically on students and young adults. The AI also gave too many ideas, so I narrowed it down to spending habits.

**Reflection:**
I learned that AI can generate many ideas quickly, but I need to choose and refine the one that is most relevant to my project.

### Entry 2- Defining Inputs and Outputs

**Artifact:**
**Artifact:**

![AI Screenshot](week9_ai_1.png)
![AI Screenshot](week9_ai_2.png)


**Context:**
I was trying to get AI chat to help me come up with a problem to solve for my Smart Finance Assistant.

**My Prompt:**
"For a personal finance assistant that analyzes CVS trsnsaction data ,what are the most valuable inputs and outputs i could use."

**AI Response Summary:**
The AI suggested inputs such as transaction data, user preferences, and time periods. It also suggested outputs like spending summaries, category breakdowns, and financial advice.

**My Critique/Improvement:**
Some of the suggestions that the AI gave were not narrow ,they were broad ,so i picked the ones that were relevant and focused more on the relevant data for the system like user preferences

**Reflection:**
I learned that AI can help ideas of generating ,and that collecting data like inputs and outputs help with the structuring of the system before the coding part and the AI will help with the process

### Entry 3- Defining Inputs and Outputs

**Artifact:**
<img width="419" height="145" alt="image" src="https://github.com/user-attachments/assets/b7f8436e-ad8a-48a1-9bf6-c8b4a2577af5" />
<img width="427" height="392" alt="image" src="https://github.com/user-attachments/assets/3e89ced4-5598-448a-aa3c-f2060cdaef34" />
<img width="228" height="73" alt="image" src="https://github.com/user-attachments/assets/1ff577b3-b498-4e4a-9031-8842625eaf3e" />
<img width="453" height="432" alt="image" src="https://github.com/user-attachments/assets/0286c6e4-8b90-481e-8f2e-e1388f6539bd" />




**Context:**
I used AI chat to help generate realistic Australian transaction data examples for my Smart Finance Assistant project. The goal was to practice manual financial calculations and identify spending insights from transaction data.

**My Prompt:**
"Give me 3 realistic examples of Australian transaction data with different scenarios (normal spending, refunds, large purchases). Show me how to manually calculate meaningful financial insights from each scenario."

**AI Response Summary:**
The AI generated transaction examples involving groceries, refunds, shopping expenses, and large purchases such as a laptop. It also calculated total spending, category spending, averages, and financial insights for each example.

**My Critique/Improvement:**
Although the calculations were correct, some transaction values seemed unrealistic for a university student budget, especially large spending amounts and expensive purchases. I adjusted some of the values to better reflect realistic student spending habits and everyday expenses.

**Reflection:**
 learned that AI-generated examples may still need adjustment depending on the target audience and project context. Even when calculations are correct, the data should still make sense for the intended users of the system.
 


### Entry 4 – Improving Pseudocode Logic

**Artifact:** 
<img width="722" height="369" alt="image" src="https://github.com/user-attachments/assets/a6000fbe-9918-4180-97da-7facdee52824" />

**Context:**  
I was working on the pseudocode for my Smart Finance Assistant project. I first wrote a very simple version, but I felt like it was missing important parts that would make the finance analysis more realistic.

**My Prompt:**  
"Review my pseudocode for analyzing spending data from a CSV. Are there any edge cases I'm missing? What business logic should I add to make this more valuable for personal finance insights?"

**AI Response Summary:**  
The AI pointed out that my pseudocode was too basic and suggested adding steps like checking for missing columns, cleaning the Amount column, handling refunds, and calculating averages and percentages.

**My Critique/Improvement:**  
At first my pseudocode only focused on total spending and categories, but after reviewing the AI feedback I added more detail to make it more realistic. I included validation, refund handling, averages, and checks for unusual expenses.

**Reflection:**  
This part helped me understand that planning the logic properly before coding is important. I also realized that finance data can be messy, so the program needs steps for cleaning and validating data before calculations are done.

## Entry 5

### Foundation Data Processing Functions

#### Artifact

<img width="346" height="158" alt="image" src="https://github.com/user-attachments/assets/10b4773e-ac5e-4e88-9952-6020b051f821" />

These were the final outputs after testing and improvements:

<img width="351" height="440" alt="image" src="https://github.com/user-attachments/assets/05b18848-50f0-4539-932e-45689724e1cd" />

<img width="394" height="240" alt="image" src="https://github.com/user-attachments/assets/d2a3836f-b5d6-43c1-8fb3-957558a5aea3" />


#### Context

In this part, I worked on the foundation data processing section of my Smart Finance Assistant. The aim was to create a function that could load and clean transaction CSV data before running the spending analysis functions.


#### My Prompt

🤖 AI Collaboration Prompt:

"Create a function to load CSV transaction data with Date, Amount, Category, Description columns. Handle dollar signs in Amount, missing values, and data validation. Include clear business-focused error messages."


#### AI Response Summary

The AI generated a data cleaning function that:
- loaded CSV transaction data
- checked required columns
- removed dollar signs from transaction amounts
- converted values into numeric format
- handled missing values
- removed invalid rows before analysis

The cleaned data was later used for spending analysis and financial recommendations in the Smart Finance Assistant.


#### My Critique/Improvement

The function worked well because it loaded the CSV file, checked the required columns, cleaned the Amount column, and removed invalid values before analysis.

However, there were still a few things that could be improved.

First, the function printed error messages instead of returning them properly, which could make it harder for other parts of the system to handle errors later.

Second, the function assumed the CSV structure was mostly correct apart from missing values. If unusual formats were uploaded, some cleaning steps could still fail.

Third, the function filled missing text values with placeholders such as "Unknown Date" and "No Description". While this helped avoid errors, these placeholder values could still affect later analysis if not handled carefully.

Finally, the function cleaned and validated the data well, but it did not provide a summary showing how many rows were removed or corrected during cleaning.

---

#### Reflection

This part helped me understand how important data cleaning is before financial analysis can happen properly. I also realised that real transaction data can become messy very quickly, so validation and error handling are very important when building finance systems.

 ### Part 2 — Spending Analysis Function

#### Artifact

<img width="501" height="219" alt="image" src="https://github.com/user-attachments/assets/8252c9fe-aa35-45e7-b6c5-2bc38869d3a9" />

<img width="415" height="437" alt="image" src="https://github.com/user-attachments/assets/fe779996-4a87-4478-9c05-a1eebf9f267b" />

This was the first output:

<img width="356" height="458" alt="image" src="https://github.com/user-attachments/assets/cadce169-0c1b-4a72-81bb-f2e340266413" />

This was the output after corrections:

<img width="351" height="440" alt="image" src="https://github.com/user-attachments/assets/05b18848-50f0-4539-932e-45689724e1cd" />

---

#### Context

In this part, I worked on the spending analysis function for my Smart Finance Assistant. The aim was to analyse transaction data from the cleaned CSV file and generate financial insights from the spending patterns.

#### My Prompt

🤖 AI Collaboration Prompt:

"Create a function that analyzes spending by category, calculates percentages, identifies top spending areas, and generates actionable financial insights formatted for business presentation."

#### AI Response Summary

The AI generated a spending analysis function that calculated:
- total spending
- spending by category
- spending percentages
- refunds
- highest spending category

The function grouped transactions into categories and generated financial summaries from the spending data.


#### My Critique/Improvement

The function worked well because it separated positive spending, calculated totals, grouped expenses into categories, and identified the highest spending category.

However, the first version did not clearly show how refunds affected the final net spending, so I later improved the calculations to make the summaries clearer.

The function also assumed that the Category column had already been cleaned correctly. If blank categories existed, the results could become inaccurate.

The financial insights were useful, but they still felt a bit basic. I later improved the advice so the spending summaries felt more realistic and useful for students.

Finally, the results were mainly stored as dictionaries, so I later formatted the outputs more clearly for the Gradio interface and financial reports.

---

#### Reflection

This part helped me understand how financial analysis works behind the scenes. I also realised how important data cleaning is before analysis because refunds, missing values, and incorrect categories can affect the final financial insights a lot.

### Part 3 — Financial Recommendation Function

#### Artifact

<img width="441" height="197" alt="image" src="https://github.com/user-attachments/assets/976b079a-ede6-4f96-9249-0167499331f5" />

This was the first output:

<img width="443" height="449" alt="image" src="https://github.com/user-attachments/assets/d88da9ac-be05-4657-ad9d-d2a7e2cf5efc" />

This was the final output after corrections:

<img width="497" height="445" alt="image" src="https://github.com/user-attachments/assets/6efebbbb-d023-42ab-bfc1-7b2fbac27785" />

---

#### Context

In this part, I worked on the `generate_financial_recommendations` function for my Smart Finance Assistant. The aim of this function was to generate financial advice and spending recommendations based on the spending analysis results from the transaction data.

---

#### My Prompt

🤖 AI Collaboration Prompt:

"Based on spending analysis data, create professional financial recommendations. Include specific savings opportunities, spending pattern observations, and actionable advice formatted for a personal finance app user."

---

#### AI Response Summary

The AI generated a recommendation function that:
- created financial recommendation reports
- used spending analysis results
- identified the highest spending category
- generated savings advice
- explained spending behaviour
- formatted the results into a readable report

The recommendations were generated from the spending summaries and financial analysis results created earlier in the project.

---

#### My Critique/Improvement

The function worked well because it created a clear recommendation report and used the analysis results to give advice based on the user’s highest spending category.

However, there were still a few things that could be improved.

First, the recommendations were still quite general. They told the user to review the highest category, but they did not give category-specific advice such as different recommendations for food, transport, or entertainment spending.

Second, the function assumed that values such as total spending and percentages were already correct inside the analysis dictionary. If important values were missing, the report could still run but produce weak or incomplete advice.

Third, the refund section only appeared if refunds existed, which worked well, but it still did not clearly explain how refunds affected overall net spending.

Finally, the report was formatted as plain text. While it was readable, it would later need clearer formatting for the Gradio interface and chatbot responses.


#### Reflection

This part helped me understand how recommendation systems use spending analysis data to generate financial advice for users. I also realised that financial recommendations need to feel realistic and personalised instead of giving advice that is too general.

### Part 4 — Chat Interface Integration

#### Artifact

<img width="417" height="224" alt="image" src="https://github.com/user-attachments/assets/133a4e26-1c5d-4cac-b47d-9a6e47c28d23" />

This was the first output:

<img width="475" height="456" alt="image" src="https://github.com/user-attachments/assets/8c87e7da-9b6a-45df-bd39-6534cefc6bb4" />

This was the output after corrections:

<img width="451" height="456" alt="image" src="https://github.com/user-attachments/assets/3b2fa3b7-db67-45eb-acfb-d39e887014be" />



#### Context

In this part, I worked on connecting the financial chatbot to my Smart Finance Assistant. The goal was to create a chatbot that could give budgeting and spending advice based on the user’s transaction data.

---

#### My Prompt

🤖 AI Collaboration Prompt:

"Help me create a system prompt for a friendly, professional financial advisor chatbot that can provide spending advice based on transaction analysis. The personality should be encouraging but practical."

---

#### AI Response Summary

The AI generated a chatbot setup that:
- created a financial advisor personality
- used hands-on-ai for chatbot responses
- generated budgeting and spending advice
- included connection error handling
- connected the chatbot to the finance assistant system

The chatbot was designed to provide simple financial advice through the Gradio interface.


#### My Critique/Improvement

The chatbot setup worked well because it created a clear financial advisor personality, used hands-on-ai for generating responses, and included error handling so the notebook would not crash if the server was unavailable.

However, there were still a few things that could be improved.

First, the chatbot depended fully on the hands-on-ai server connection. When the university server was unavailable, the chatbot returned connection errors instead of financial advice.

Second, the personality prompt was still quite general. It focused mostly on budgeting and spending, but I later realised it could be improved more by including student-specific financial situations and more personalised advice.

Third, the chatbot sent the full personality prompt with every request, which could become inefficient later if the system became larger.

Finally, the earlier version of the chatbot did not include fallback local responses when the AI server failed. Because of this, I later added local fallback responses so the chatbot could still answer simple finance questions even during connection issues.

#### Reflection

This part helped me understand how chatbot systems connect with financial analysis systems. I also learned that external AI services can sometimes fail during development, so adding proper error handling and fallback responses is very important for improving reliability and user experience.

### Part 5 — Custom Financial Tools

#### Artifact

<img width="393" height="207" alt="image" src="https://github.com/user-attachments/assets/9702cba4-ba66-46ff-bf30-dcfcc88a09a5" />

This was the first output:

<img width="454" height="439" alt="image" src="https://github.com/user-attachments/assets/3323d99e-7b74-469f-93d2-7be6311be4ca" />

This was the output after corrections:

<img width="507" height="442" alt="image" src="https://github.com/user-attachments/assets/f67c3173-1c18-41a1-9cac-4aad75358272" />



#### Context

In this part, I worked on creating a custom savings calculator tool for my Smart Finance Assistant. The purpose of the tool was to help users estimate how long it would take to reach a savings goal based on their current savings and monthly contributions.



#### My Prompt

🤖 AI Collaboration Prompt:

"Create a savings goal calculator function that takes current savings, monthly contribution, and target amount, then calculates time to reach goal. Format output for user-friendly display."



#### AI Response Summary

The AI generated a savings calculator function that:
- accepted current savings
- accepted monthly contribution amounts
- accepted savings targets
- calculated the remaining amount needed
- estimated how many months it would take
- displayed the results in a readable format

The calculator was later added to the financial tools section of the Smart Finance Assistant.


#### My Critique/Improvement

The calculator worked well because it checked the inputs, calculated the remaining amount, estimated the number of months needed, and displayed the results clearly.

However, there were still a few things that could be improved.

First, the calculator assumed the user saved the same amount every month. In reality, savings can change depending on expenses or income.

Second, the calculation did not include interest or investment growth, so the estimates may not be fully realistic for long-term savings goals.

Third, the output was mainly plain text. While it was easy to read, I later realised it would need better formatting for the Gradio interface and chatbot integration.

Finally, the tool only calculated the time needed to reach the savings goal. It could also be improved later by suggesting ways to reach the goal faster, such as increasing monthly contributions.


#### Reflection

This part helped me understand how financial tools combine calculations and user input to generate useful information. I also realised that even simple financial calculators can become more complicated when trying to make them more realistic and useful for users.

### Part 5 — Custom Financial Tools

#### Artifact

<img width="393" height="207" alt="image" src="https://github.com/user-attachments/assets/9702cba4-ba66-46ff-bf30-dcfcc88a09a5" />

This was the first output:

<img width="454" height="439" alt="image" src="https://github.com/user-attachments/assets/3323d99e-7b74-469f-93d2-7be6311be4ca" />

This was the output after corrections:

<img width="507" height="442" alt="image" src="https://github.com/user-attachments/assets/f67c3173-1c18-41a1-9cac-4aad75358272" />

---

#### Context

In this part, I worked on creating a custom savings calculator tool for my Smart Finance Assistant. The purpose of the tool was to help users estimate how long it would take to reach a savings goal based on their current savings and monthly contributions.

---

#### My Prompt

🤖 AI Collaboration Prompt:

"Create a savings goal calculator function that takes current savings, monthly contribution, and target amount, then calculates time to reach goal. Format output for user-friendly display."

---

#### AI Response Summary

The AI generated a savings calculator function that:
- accepted current savings
- accepted monthly contribution amounts
- accepted savings targets
- calculated the remaining amount needed
- estimated how many months it would take
- displayed the results in a readable format

The calculator was later added to the financial tools section of the Smart Finance Assistant.


#### My Critique/Improvement

The calculator worked well because it checked the inputs, calculated the remaining amount, estimated the number of months needed, and displayed the results clearly.

However, there were still a few things that could be improved.

First, the calculator assumed the user saved the same amount every month. In reality, savings can change depending on expenses or income.

Second, the calculation did not include interest or investment growth, so the estimates may not be fully realistic for long-term savings goals.

Third, the output was mainly plain text. While it was easy to read, I later realised it would need better formatting for the Gradio interface and chatbot integration.

Finally, the tool only calculated the time needed to reach the savings goal. It could also be improved later by suggesting ways to reach the goal faster, such as increasing monthly contributions.


#### Reflection

This part helped me understand how financial tools combine calculations and user input to generate useful information. I also realised that even simple financial calculators can become more complicated when trying to make them more realistic and useful for users.

### Part 6 — Gradio User Interface

#### Artifact

<img width="472" height="249" alt="image" src="https://github.com/user-attachments/assets/4b9be495-fa71-48a0-8ea3-be257128318e" />

These were the first outputs:

<img width="535" height="442" alt="image" src="https://github.com/user-attachments/assets/2b87690a-371c-4796-8831-0d8087ced915" />

<img width="513" height="435" alt="image" src="https://github.com/user-attachments/assets/e630de8a-ddf9-4f7e-abdb-ee1085b0a6e6" />

<img width="544" height="432" alt="image" src="https://github.com/user-attachments/assets/a22444a3-8f88-41de-b59e-7496a2bd2da0" />

<img width="535" height="424" alt="image" src="https://github.com/user-attachments/assets/dc4481c0-7191-4d9a-b115-025f1d83c428" />

These were the outputs after improvements and testing:

<img width="503" height="398" alt="image" src="https://github.com/user-attachments/assets/b9bf31bf-49c1-4056-9763-b45314a136d2" />

<img width="515" height="401" alt="image" src="https://github.com/user-attachments/assets/3ab5352c-78bf-4d57-8526-50cb87cac638" />

<img width="487" height="430" alt="image" src="https://github.com/user-attachments/assets/43c9493d-9547-4ff5-9627-517f4bc44fb4" />

<img width="515" height="435" alt="image" src="https://github.com/user-attachments/assets/121702cb-6bb5-4de6-a1ca-a042e338103c" />

---

#### Context

In this part, I worked on building the Gradio interface for my Smart Finance Assistant. The aim was to bring together the main parts of the project into one application, including CSV upload, spending analysis, chatbot support, and financial tools.

---

#### My Prompt

🤖 AI Collaboration Prompt:

"Help me design a Gradio interface that combines CSV upload, spending analysis, chat functionality, and custom tools in a user-friendly layout suitable for a personal finance application."

---

#### AI Response Summary

The AI generated a Gradio interface that:
- included CSV upload
- displayed spending analysis results
- connected the chatbot
- added custom financial tools
- organised the application into tabs and sections
- launched the application using Gradio

The interface combined the earlier functions into one Smart Finance Assistant application.

---

#### My Critique/Improvement

The Gradio UI worked well because it brought together the main parts of the Smart Finance Assistant, including CSV upload, spending analysis, chatbot support, and the savings calculator.

However, there were still a few things that could be improved.

First, the chatbot was still quite basic because it mainly checked for keywords like budget, saving, and refund instead of fully using advanced hands-on-ai chat features.

Second, the CSV analysis depended on the earlier backend functions working correctly. If one of those functions had an error, the uploaded file would not analyse properly.

Third, the RAG system was not fully added into the interface yet, so users could not ask questions directly from uploaded financial documents.

Finally, while the layout worked well overall, it could still be improved later by adding clearer instructions, example CSV formats, and cleaner output formatting.



#### Reflection

This part helped me understand how frontend interfaces connect with backend Python functions to create a complete application. I also realised that building the interface is not only about making it look good, but also about making the system easier to use and more organised for users.

## Entry 6

### Comprehensive Test Suite

#### Artifact

<img width="493" height="245" alt="image" src="https://github.com/user-attachments/assets/924c0c00-d3c9-4aaa-a7c3-130f1d28fea8" />

These were the first outputs:

<img width="561" height="432" alt="image" src="https://github.com/user-attachments/assets/015989ea-cba6-4c37-82c3-b1910e7ba328" />

<img width="550" height="391" alt="image" src="https://github.com/user-attachments/assets/c93f35d2-968b-4ee3-a698-a950de857bdc" />

<img width="498" height="408" alt="image" src="https://github.com/user-attachments/assets/23fba3c6-abf7-4b0e-83b0-18c9c6528d98" />

These were the outputs after corrections and testing:

<img width="481" height="402" alt="image" src="https://github.com/user-attachments/assets/54750759-1399-4d22-874d-53a0b3845bc0" />

<img width="487" height="433" alt="image" src="https://github.com/user-attachments/assets/3a5ad07d-244f-4104-9001-e428199897d4" />

<img width="475" height="429" alt="image" src="https://github.com/user-attachments/assets/f093f4b5-f052-4c2a-a82e-4ff73e82cf9b" />

<img width="491" height="438" alt="image" src="https://github.com/user-attachments/assets/a850bad8-f9d2-42ee-bae2-ef266f82501f" />

---

#### Context

In this part, I worked on creating a testing section for my Smart Finance Assistant. The aim was to test whether the different functions in the system were working properly using different finance situations and transaction examples.

---

#### My Prompt

🤖 AI Collaboration Prompt:

"Create realistic test datasets for a finance assistant including:
1. Normal spending data with various categories
2. Edge cases: refunds (negative amounts), missing data, zero amounts
3. Data quality issues: invalid formats, extreme values
4. Business scenarios: high spending months, savings patterns
Include Australian business names and realistic amounts."

---

#### AI Response Summary

The AI generated a testing section that:
- created finance test datasets
- included refunds and missing values
- tested invalid transaction formats
- tested spending analysis calculations
- tested recommendation functions
- tested chatbot responses
- used assert statements to check outputs

The tests were created to help check whether the Smart Finance Assistant functions were working correctly under different situations.

---

#### My Critique/Improvement

The testing section worked well because it tested different parts of the Smart Finance Assistant, including data cleaning, spending analysis, recommendations, and chatbot responses.

However, there were still a few things that could be improved.

First, most of the tests mainly checked whether outputs existed, but they did not fully verify whether every calculation was completely accurate.

Second, some of the assert statements were still quite simple. For example, checking whether total spending was greater than zero did not fully confirm whether the financial calculations were correct.

Third, the test datasets were useful, but they were still much smaller compared to real-world transaction datasets.

Finally, the tests focused mostly on backend functions and did not directly test the Gradio interface, so some user interaction issues could still happen during actual use.

---

#### Reflection

This part helped me understand how important testing is during software development. I also realised that testing is not only about checking whether code runs successfully, but also about making sure the results are correct and reliable when different situations or errors happen.

### Part 2 — Integration Testing

#### Artifact

<img width="470" height="253" alt="image" src="https://github.com/user-attachments/assets/2691db89-6f37-418f-9ec1-4a696e43f2d3" />

These were the first outputs:

<img width="500" height="441" alt="image" src="https://github.com/user-attachments/assets/21e419fe-db38-414c-9678-82e845bfd2c4" />

<img width="490" height="393" alt="image" src="https://github.com/user-attachments/assets/a074a792-ebea-4884-a4a0-c3fcb98f9f10" />

<img width="501" height="397" alt="image" src="https://github.com/user-attachments/assets/b411d26e-29a0-4237-9caf-16cb1856b390" />

These were the outputs after corrections and testing:

<img width="546" height="410" alt="image" src="https://github.com/user-attachments/assets/4a8a919f-4168-4e4e-a702-6627bfd14372" />

<img width="566" height="427" alt="image" src="https://github.com/user-attachments/assets/00762adb-a4cb-4ec4-a88d-a124feb210a4" />

<img width="533" height="423" alt="image" src="https://github.com/user-attachments/assets/3ffae547-b851-4f72-aaa2-417adda38e55" />

<img width="527" height="344" alt="image" src="https://github.com/user-attachments/assets/2b1a1791-731e-43ee-877a-260ab8d77836" />

---

#### Context

In this part, I worked on integration testing for my Smart Finance Assistant. The aim was to test whether the different parts of the system could work together properly instead of only testing each function separately.

---

#### My Prompt

🤖 AI Collaboration Prompt:

"Create an end-to-end test that:
1. Loads sample CSV data
2. Runs complete analysis pipeline
3. Generates chat responses about the data
4. Verifies RAG system retrieval
5. Tests custom tool functionality
Ensure all components work together seamlessly."

---

#### AI Response Summary

The AI generated integration tests that:
- loaded sample finance data
- tested the spending analysis process
- tested recommendation generation
- tested chatbot responses
- tested RAG retrieval
- tested custom financial tools
- checked whether the different parts of the system worked together correctly

The tests were designed to simulate how the Smart Finance Assistant would behave during actual use.

---

#### My Critique/Improvement

The integration tests worked well because they checked whether the main parts of the Smart Finance Assistant worked together, including spending analysis, recommendations, chatbot responses, RAG retrieval, and the savings calculator.

However, there were still a few things that could be improved.

First, the test data was created directly inside the code using a DataFrame, so it did not fully test the CSV upload and cleaning process.

Second, most of the tests mainly checked whether outputs existed and returned the correct data type, but they did not fully verify whether every result was accurate.

Third, the RAG and chatbot tests could still depend on fallback responses if the hands-on-ai server was unavailable during testing.

Finally, the Gradio interface itself was not directly tested, so some user interface problems could still appear later during actual use.

---

#### Reflection

This part helped me understand how important integration testing is in software development. I also realised that even when individual functions work correctly on their own, problems can still happen when all the different parts of the system are connected together.






