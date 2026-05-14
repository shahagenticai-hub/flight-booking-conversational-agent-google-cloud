# Flight Booking Conversational Agent

A conversational AI agent built using **Google Cloud Conversational
Agents (Dialogflow CX)** that handles end-to-end flight booking
through natural language conversation.

## How It Works
1. User expresses intent to book a flight via chat
2. Agent collects 5 parameters through conversation:
   - Departure City
   - Departure Date
   - Destination City
   - Return Date
   - Passenger Name
3. Agent repeats all collected information back to the user
4. User confirms or corrects the details
5. On confirmation agent books the flight and ends the session
6. On rejection agent resets all parameters and restarts
   collection cleanly

## Tools Used
- Google Cloud Conversational Agents
- Dialogflow CX
- Google Cloud Console
- System Entities (geo-city, date, any)
- Intents, Flows, Pages, Parameters and Fulfillment

## Key Concepts Demonstrated
- Intent creation with training phrases
- Multi-page flow design
- Entity and parameter extraction
- Session parameter management
- Conditional routing logic
- Fulfillment responses
- Positive and negative confirmation handling

## Real Life Use Cases
- ✈️ Airline customer service automation
- 🏨 Hotel and travel booking assistants
- 🚢 Cruise and holiday package booking agents
- 🤖 Any multi-step data collection conversational agent

## Built As Part Of
Google Cloud Skills — Conversational Agents Lab
Certificate: Understand Google Cloud Agents

