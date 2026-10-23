# Customer Service Chatbot

This project is an agentic customer service chatbot for a laptop company. It uses three specialized agents to answer customer questions and routes each question to the appropriate agent.

## Required Features

- Google Gemini API
- Secure API key storage using Google Colab Secrets
- A system prompt defining the chatbot’s role
- Product recommendation agent
- Order-status agent
- Refund-policy agent
- Routing logic between the agents
- Conversation memory using `MemorySaver`
- Three-turn conversation memory
- Comments explaining important code sections

## Agents

1. **Product Recommendation Agent**  
   Answers questions about laptop features, specifications, and pricing.

2. **Order-Status Agent**  
   Retrieves order details and allows order information to be updated.

3. **Refund-Policy Agent**  
   Answers questions about returns and refund policies.

## Example Questions

- What are the features of the SpectraBook?
- How much does this laptop cost?
- Please show me the details of order ORD-7311.
- What is your refund policy?
- Can I update the quantity on my order?
- What laptop did I ask about earlier?

## Files

- `Customer_Service_Chatbot.ipynb` – Main Google Colab notebook
- `data/Laptop pricing.csv` – Laptop pricing information
- `data/Laptop Orders.csv` – Customer order information
- `data/Laptop product descriptions.pdf` – Laptop product descriptions

## How to Run

1. Open `Customer_Service_Chatbot.ipynb` in Google Colab.
2. Upload the required data files using the same folder structure shown in the notebook.
3. Add the Google API key through Google Colab Secrets.
4. Run all cells from beginning to end.
5. Test product, order, refund, and follow-up memory questions.
6. Review the chatbot responses and screenshots of the successful outputs.

## Conversation Memory

The chatbot uses `MemorySaver` to remember information from earlier messages. This allows users to ask follow-up questions without repeating previous information.

## Group Members

- Trinity – Created the initial chatbot
- Daniel – Assisted with chatbot development
- Tiffany – Worked on testing and project organization
- Mahnaz – Prepared the presentation slides

## Project Goal

The goal of this project is to demonstrate how multiple specialized AI agents can work together through routing and memory to provide organized customer service responses.
