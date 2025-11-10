# TravelPlane Agent

A multi-agent travel planning assistant built with the Google Agent Development Kit (ADK).

## Overview

`TravelPlane` is an intelligent chatbot designed to help users plan their dream vacations. It acts as a travel concierge, providing destination ideas, suggesting activities, and finding key information like nearby places and current events.

The project is structured as a multi-agent system:
-   A main `root_agent` that interacts with the user.
-   Supporting agents like `travel_inspiration_agent`, `news_agent`, and `places_agent` that handle specialized tasks.

## Features

-   **Conversational Interface**: Chat with the agent to plan your trip.
-   **Multi-Agent System**: Delegates tasks to specialized agents for better results.
-   **Tool Integration**: Uses tools for Google Search and location finding.

## Screenshot

Here's a look at the `TravelPlane` agent in action:

![TravelPlane Agent Screenshot](https://github.com/salmansajidsattar/End_To_End_MutliAgent_ADK_Project/blob/main/Screenshot%202025-11-10%20151950.png)

## Getting Started

### Prerequisites

-   Python 3.12+
-   [uv](https://github.com/astral-sh/uv) - An extremely fast Python package installer and resolver.

### Installation & Running

1.  **Clone the repository:**
    ```sh
    git clone https://github.com/salmansajidsattar/End_To_End_MutliAgent_ADK_Project.git
    cd End_To_End_MutliAgent_ADK_Project
    ```

2.  **Install dependencies:**
    ```sh
    uv sync
    ```

3.  **Run the ADK web server:**
    ```sh
    uv run adk web
    ```

4.  Open your browser and navigate to the URL provided by the server (usually `http://127.0.0.1:8000`).