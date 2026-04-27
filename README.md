## My AI Agent ADK ##
A conversational agent orchestrated through the Google Cloud ecosystem, leveraging Agent Development Kit (ADK), Vertex AI and the Gemini model suite for backend processing.\
<br>
**Architecture:**\
•	**agent.py:** The "brain" of the operation. It defines the agent’s identity, selects the Gemini model, and houses the system instructions that govern its behavior.\
•	**__init__.py:** A package initializer that allows the ADK framework to automatically discover and load the agent’s entry point.\
•	**.env:** A secure local vault for managing environment-specific variables, such as Project IDs, API keys, and regional settings.\
<br>
**Infrastructure and backend:**\
The agent is natively integrated with Vertex AI, Google Cloud’s enterprise-grade platform.The solution gains access to enterprise features like grounding with private data, Security as It integrates with IAM to ensure only your specific service account, and robust monitoring that standard API calls lack.\
<br>
**Testing:**\
CLI Mode (adk run): It enables rapid testing and direct conversation with the agent via the terminal.
