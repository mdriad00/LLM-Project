It was during my database course that I felt why machines cannot provide results if we make mistakes while querying or engage in conversation without explicit queries, similar to human language interaction. We know that obtaining results from a database requires knowledge of SQL. However, this process can become challenging and time-consuming.

Upon the introduction of OpenAI's ChatGPT and Google's Bard AI model, I conceived the idea of creating a model using their APIs. What if this model would translate my human language text into a SQL query, execute it in the database, and retrieve the answer? Since then, thinking about how to solve this problem. While studying LLM, I realized how I have to work for it and I made a project for myself to enhance my SQL learning quality by solving this problem. This innovative approach simplifies the interaction between users and the database, eliminating the need for nontechnical users to have an in-depth understanding of query languages.


This is an end-to-end LLM project based on Google Palm and Langchain. I build a system that can talk to MySQL database. The user asks questions in a natural language and the system generates answers by converting those questions to an SQL query and then executing that query on MySQL database. 

Riad_Khan_T_Shirt_store is a T-shirt store that maintains its inventory, sales, and discount data in the MySQL database. A store manager may ask questions such as,

- how many total t-shirts have in my database?
- If we have to sell all Levi's t-shirts today with a discount applied, how much revenue our store will generate?
