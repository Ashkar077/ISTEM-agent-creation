# ISTEM-agent-creation
Platform: Vapi AI Agent  Name: Admissions Counselor Agent  Submission: Prompt Engineering Task – Abdul Kader Askhr M A
Tools Used
•	Platform: Vapi AI (no-code)
•	Data Storage: Embedded course data in system prompt
•	Deployment: Public voice link (web interface)
Prompt Flow
•	Greets caller and asks for name, course interest, and preferred start date
•	Provides duration, annual fee, and scholarship fee for 18 courses
•	If asked something out of scope, replies:
“I’m afraid I don’t have that information yet, but I can pass your query to our human counselor.”
Data Handling
•	Course data hardcoded in System prompt (no external API or DB)
•	Includes BBA, BSc IT, BCom, MSc Animation, BFA, etc.
Edge Cases
•	Unavailable courses like MBA → fallback response
•	Generic fee queries → prompts user for course name
•	Master’s program query → responds with MSc IT and MSc Animation
Agent Link: https://vapi.ai?demo=true&shareKey=30179354-7cc7-4b59-ac80-4a987ea8d7c4&assistantId=cef62b39-c605-41d5-8349-5254d21272d0
