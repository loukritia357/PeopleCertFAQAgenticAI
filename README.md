# PeopleCertFAQAgenticAI
FAQ Agentic AI is a smart AI agent that helps users quickly find answers to questions about certifications and exams offered by PeopleCert, as well as account management, problem resolution, and more .It improves itself via feedback and question logs, tracks unanswered questions for future learning, provides step-by-step guidance for exam scheduling, registration, and preparation, helps users understand certification requirements and exam policies, suggests personalized next steps based on users' certifications or progress, and adapts and refines responses based on trends in user queries to become more effective over time.


Why did we choose this as an alternative to the regular Frequently Asked Questions page?
The agent uses information pulled directly from the company’s FAQ page, giving users faster, more convenient access to relevant answers without having to manually search through long lists.
In more detail, the advantages of using the AI FAQ Agent over browsing the FAQ page are:
1. Instant access to top questions: Users are immediately shown the 10 most frequently asked questions, making it easier to find common answers with a single click.
2. Searchable, conversational interface: Instead of scanning static text, users can simply type their question and get a direct, AI-generated answer—reducing effort and saving time.
3. Adaptive and continuously improving: When a user’s question can’t be answered after three attempts, the question is logged for review, helping the system improve over time by expanding its knowledge base.
4. Seamless escalation to human support: If the AI can’t help, users are offered the option to provide their email for human follow-up, ensuring no question goes unresolved.


How it works:
It starts with greeting he user and presenting them the 10 most frequently asked questions. When the user clicks on one of them, they receive a reply for that question. 
When the user types their own question, if the Agent has the relevant information, the user receives a reply for that question. 
If the user asks a question for which the AI Agent does not have the information, the AI Agent prompts the user to rephrase the question. 
If after the 3rd time the user asks the question, the AI Agent still does not have the information for the answer two things happen:
1. The question gets logged into an Excel table that contains the unanswered questions. 
2. The AI Agent asks the user if they want to provide their email so that a support agent can assist them. If the user provides an email, the AI Agent sends an email to a support email that contains the User's email, the unanswered question and the conversation id, so that they can investigate and get back to the user via email.
