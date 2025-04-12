Sure! Here's a simplified and rephrased version of your project description, with no links or images:

---

# Multi-Agent AI Travel Planner

This project is an AI-powered travel planning application that uses multiple intelligent agents to simplify the travel planning process. It helps users find flights, choose hotels, and generate personalized itineraries — all through automated collaboration between AI agents.

## Overview

The system brings together several technologies:
- **Gemini 2.0 LLM** for intelligent decision-making
- **CrewAI** for coordinating multiple AI agents
- **SerpAPI** for getting real-time flight and hotel data
- **FastAPI** for backend API support
- **Streamlit** for the frontend user interface

## Key Features

### Flight Search
- Gets real-time flight data
- Filters based on price, stops, duration
- AI recommends the best flight option

### Hotel Search
- Retrieves current hotel availability
- Filters by location, budget, and amenities
- AI suggests the best hotel for the user

### AI-Based Analysis
- Multiple AI agents analyze and recommend flights and hotels
- AI explains its reasoning behind each choice

### Itinerary Creation
- Generates a day-by-day travel plan
- Includes attractions, food spots, and local transport options

### Easy-to-Use Interface
- Users can input preferences via a simple form
- See recommendations and download the final itinerary

## System Design

The system has specialized agents:
- **Flight Analyst Agent** for choosing the best flights
- **Hotel Analyst Agent** for picking the best hotels
- **Travel Planner Agent** for building a complete trip plan

## Project Structure

- `gemini_travel_v2.5.py`: Backend (FastAPI)
- `gemini_travel_v2.5_frontend.py`: Frontend (Streamlit)
- `requirements.txt`: Project dependencies

## Setup Instructions

1. Clone the project
2. Create a virtual environment
3. Install the dependencies
4. Add your API keys
5. Run the backend and frontend scripts
6. Access the app in your browser and start planning your trip

---