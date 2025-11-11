# Project-Ideas
A list of projects that I wanna work on

## Ideas
- Webiste where users can upload documents to search through and give them what they want
- Website where users can give specifications along with budget to get reccommended parts to get trying to maximise cost efficiency while also resulting in high performance along with a Video on how to build a PC

- Personal Finance Data Analyzer
    - Concept: The user pastes anonymized transaction data (e.g., a CSV or table format, removing sensitive details). The AI is instructed to act as a financial consultant.

    - Categorize: Assign every transaction to one of five user-defined categories (e.g., "Necessity," "Luxury," "Investment").

    - Analyze: Identify spending anomalies or trends (e.g., "Your restaurant spending increased 20% this month").

    - Recommend: Provide three actionable, personalized budget recommendations in a structured JSON output.

    - API Focus: Structured data analysis, enforcing output format (JSON), and multi-turn conversation/follow-up questions.

    - Skills: Data cleaning/parsing, JSON schema enforcement, and state management.

- Smart Study Assistant with Context Grounding
    - Concept: The user uploads a PDF of a textbook chapter or lecture notes (like the scenario in your initial code). The application then allows the user to ask complex questions. The key feature is Grounding: before answering, the AI first scans the uploaded documents to find relevant quotes/sections, and then uses that retrieved information (RAG - Retrieval-Augmented Generation) to formulate the answer and cite the specific page/section from the source document.

    - API Focus: File/Document uploads, multi-step agent logic, and enforced structured output for citations.

    - Skills: Backend file handling, RAG pipeline implementation, structured JSON output.

- The Multi-Agent Code Review & Refactor System 🧑‍💻
    - This project showcases a modern agentic workflow where different AI models take on specialized roles.

    - Project Name: DevTeam AI (The Coder & The Critic)

    - Concept: The user pastes a block of code (e.g., a Python class). Two specialized agents collaborate:

    - The Auditor Agent: Focuses on security, best practices, and efficiency. Its output is a structured JSON report identifying potential bugs or non-compliant code.

    - The Refactor Agent: Takes the original code and the Auditor's JSON report. Its sole job is to rewrite and refactor the code to address the issues, providing a clean, final version and a detailed explanation of its changes.

    - API Focus: Chaining API calls, using system instructions to strictly define agent personalities/roles, and using structured output (JSON) for inter-agent communication.

    - Key Challenge: Ensuring the Refactor Agent accurately interprets and implements the fixes suggested by the Auditor.