# Customer Service Chatbot

## About the Project

We are a student development team from San José State University that created an AI-powered customer service chatbot for a laptop company.

The chatbot helps customers receive quick and organized answers about laptop products, order information, and refund policies. Instead of using one general chatbot for every question, the system routes each request to a specialized AI agent.

## Business Value

Businesses can use this chatbot to:

- Answer common customer questions automatically
- Reduce customer service response times
- Provide consistent product and policy information
- Help customers check orders without waiting for an employee
- Improve the overall customer experience
- Reduce the workload for customer service teams

## Chatbot Features

The chatbot includes three specialized agents:

### Product Recommendation Agent

Provides information about laptop features, specifications, pricing, and product recommendations.

### Order-Status Agent

Retrieves order details and helps customers update order information.

### Refund-Policy Agent

Explains return requirements, refund policies, and refund processing information.

### Intelligent Routing

A routing system identifies the purpose of each customer question and sends it to the correct specialized agent.

### Conversation Memory

The chatbot uses `MemorySaver` to remember information from earlier messages. This allows customers to ask follow-up questions without repeating previous details.

## Example Questions

- What are the features of the SpectraBook?
- Which laptop would you recommend?
- Please show me the details of order ORD-7311.
- Can I update the quantity on my order?
- What is your refund policy?
- What laptop did I ask about earlier?

## Technology Used

- Python
- Google Colab
- Google Gemini API
- LangChain
- LangGraph
- Pandas
- `MemorySaver`
- CSV and PDF product data

## How to Run

1. Open `Customer_Service_Chatbot.ipynb` in Google Colab.
2. Upload the required product, order, and product-description files.
3. Add the Google API key through Google Colab Secrets.
4. Run the notebook cells from beginning to end.
5. Test the product, order, refund, and follow-up questions.
6. Review the chatbot responses and routing results.


## Future Improvements

Future versions could include:

- Live connections to inventory and order databases
- Website or mobile-app integration
- Human customer service escalation
- Support for additional languages
- Analytics for tracking customer questions
- More personalized product recommendations
- Secure customer authentication

## Project Goal

Our goal is to demonstrate how specialized AI agents can work together to provide faster, more organized, and more helpful customer service.
