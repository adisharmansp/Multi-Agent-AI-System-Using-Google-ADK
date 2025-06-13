# Multi-Agent-AI-System-Using-Google-ADK
A goal-driven Multi-Agent AI system using Google ADK. Agents plan, route, and enrich data using APIs like SpaceX and OpenWeatherMap to fulfill complex user goals.

This project demonstrates a goal-driven multi-agent AI system using modular agents built in Python on Google Colab. It processes a user goal such as:

> “Find the next SpaceX launch, check weather at that location, then summarize if it may be delayed.”

# Features

- Modular agents for:
  - Planning
  - SpaceX Launch Data
  - Weather Enrichment
  - Summarization
- Uses 2 public APIs:
  - [SpaceX Launch Library](https://ll.thespacedevs.com)
  - [OpenWeatherMap](https://openweathermap.org/)
- Rule-based reasoning for delay analysis
- Iterative agent chaining and enrichment

---

#Agent Flow

1. Planner Agent — breaks down the user goal into sub-tasks.
2. SpaceX Agent — fetches the next launch info.
3. Weather Agent — checks weather at the launch site.
4. Summarizer Agent — evaluates potential delays.

See flowchart.png for architecture.


# Getting Started
 1. Set up API Keys

Create a .env file with the following:

bash
OPENAI_API_KEY=your_openai_api_key_here
OPENWEATHER_API_KEY=your_openweathermap_api_key_here.

### NOTE== Replace these placeholder API keys with your actual keys before running.###

