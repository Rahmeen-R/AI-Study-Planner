AI Study Planner

An interactive AI‑powered study‑planning tool built with Streamlit, LangChain, and Google Gemini.
Users enter a subject, daily study hours, and total days — the app generates a structured, realistic study plan with daily tasks, revision cycles, and practice recommendations.


Features:

Clean Streamlit UI
Daily study schedule generation
Revision + practice tasks included
LangChain LCEL pipeline
Gemini 2.0 Flash Lite as the LLM
Fast, lightweight, and beginner‑friendly


Notes:

Uses LCEL (prompt | llm) for clean chaining
Gemini model: gemini-2.5-flash
Automatically formats the output into a structured study plan


Run Method :

This app runs on Streamlit and uses the Gemini API through LangChain. After installing the required packages, add your Google API key inside the code or load it from an environment variable. Start the app with streamlit run app.py, enter your study details, and the AI will generate a structured daily study plan using the Gemini 2.0 Flash Lite model.
