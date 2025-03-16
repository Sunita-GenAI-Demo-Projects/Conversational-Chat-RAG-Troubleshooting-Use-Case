Author: Sunita Shaw
https://wwww.linkedin.com/in/SunitaShaw
sunitashaw2000@gmail.com

# Conversational-Chat-RAG-Troubleshooting-Use-Case

***** **GenAI : RAG Use-case – Troubleshooting for Customers** ******
This project demonstrates the power of Retrieval Augmented Generation for Troubleshooting use-cases in Businesses such as DIY/ Self-Serve Customer Queries.

****** **Description:** ******

This project demonstrates the usage of RAG enabled AI-agent to solve customer troubleshooting queries of an Electronics company. This AI-agent understands customer question, retrieves the relevant information and augments the response for the customer based on prompt engineering. 

********Scenario:** ******

An electronics company encounters a high inflow of troubleshooting queries, requests, asks from customers. The goal for this company is to achieve Operational Efficiency & Scalability by reducing Average response time and Customer queries by 70%, leading to Cost Savings ($), higher Customer Satisfaction. The company then deploys RAG enabled AI-Agent to assist customers troubleshoot using company’s Proprietary documents.

****** **Data:** ****** 

Proprietary documents contains history of customer issues, issue logs, release notes, diagnosis and remediation techniques.


****** **Features:** ******


•	Electronics company has volumes of troubleshooting data (pdfs). This code reads the pdfs and stores them in Vector DB.
•	Customer enters their computer issue in the console prompt
•	I created an AI-Agent which understands the question and has the ability to respond to customer in conversational language.
•	This AI-Agent reads and understands the customer question.
•	Based on Similarity Search, the relevant information is retrieved from the Vector DB
•	AI-agent augments the retrieved information and generates a response in natural language helping the customer with troubleshooting. 
•	Customer continues to chat with the Agent to fix the problem.


****** **Output:** ******
This code generates responses in natural language to the customers’ troubleshooting questions.
Customers self-remediate issues with help of RAG AI-Agent.


****** **Benefits:** ******
•	This code demonstrates how to chat with SQL/ relational database to solve business use-cases, such as reporting. 
•	This code also demonstrates possibility of DIY/ Self-Serve Reporting, Schema Description, Customer or User Learning using AI-agents


****** **Technology used:** ****** 

RAG, Vector Database, OpenAI (gpt LLM), LangChain, GenAI, Python, Prompt Engineering
