# 🌟 AI Life Coach (LLM-based) 🌟

An interactive AI-powered life coach desktop application built using Python and Tkinter.  
The application uses a Large Language Model (LLM) to detect sentiment from user inputs and provide concise, actionable suggestions.

---

## Features

- **Sentiment Analysis:** Detects whether the user’s mood is **POSITIVE**, **NEGATIVE**, or **NEUTRAL**.
- **Actionable Suggestions:** Provides a short, actionable piece of advice based on the user's mood.
- **Conversation Context:** Considers recent conversation history to give more relevant responses.
- **GUI Interface:** Simple and user-friendly desktop interface built with **Tkinter**.
- **Database Storage:** Stores all user inputs and LLM responses in **SQLite** for persistence.
- **Multithreaded:** Handles LLM requests asynchronously without freezing the GUI.
- **Typing Indicator:** Shows a “Coach is typing…” message while generating responses.
- **Clear Chat Option:** Easily reset the conversation history from the GUI.

---

## Installation

### Prerequisites

- Python 3.9+
- `pip` package manager
