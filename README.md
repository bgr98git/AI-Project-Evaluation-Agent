🚀Imagine a scenario where judges or Faculty  have to review dozens of student projects in an academic competition like reading detailed descriptions, analyzing LinkedIn posts, and watching demo videos for each submission. It’s time-consuming, and difficult to maintain consistency at scale.

💁‍♀️what if this entire process could be automated? 🤔

💡 During my Generative AI Course journey, I worked on solving this real challenge by building an AI Project Evaluation Agent specifically designed to evaluate projects submitted by participants in the "AIverse academic competition" conducted by our Parul University

The AI agent collects student project data directly from Google Sheets and performs intelligent evaluation using AI. It analyzes key inputs such as project title, project category, detailed description, LinkedIn post content (including images), and demo videos from Google Drive. Using an AI agent, the system evaluates each project based on well-defined criteria—innovation, technical complexity, practical application, presentation, and overall impact. It then generates structured scores along with meaningful, personalized feedback and automatically shares results with students via email.

🚀 Key Features:
* End-to-end automated evaluation of AIverse competition participant projects 
* Intelligent analysis and checking of LinkedIn posts, images, and demo videos 
* Criteria-based evaluation ensuring fairness and consistency,Transparency 
* Auto feedback with mistake identification & improvement suggestions to students
* Seamless integration with Google Sheets & Gmail 
* Significant time savings for judges and faculty 
* Scalable architecture for handling multiple submissions


⚙️ Tech Stack :
Built using n8n (No-Code/Low-Code) automation platform with LLM Model

🔄 Workflow (Node by Node Execution)
1️⃣ Google Form → Collect student project submissions
2️⃣ Google Sheets → Store and manage responses
3️⃣ Data Extraction Node → Fetch LinkedIn post content (description, images) & Google Drive video links
4️⃣ Media Processing Node → Extract and analyze video frames for better evaluation
5️⃣ n8n Workflow Trigger → Initiate automated evaluation pipeline
6️⃣ LLM (Gemini Flash 2.5) → Perform criteria-based project assessment
7️⃣ Processing Node → Generate scores, total marks, and detailed feedback
8️⃣ Google Sheets → Store evaluated results in structured format
9️⃣ Gmail Node → Send personalized result emails to students

🎯 Impact & Extensibility:

This system transforms traditional evaluation into a fast, scalable, transparent, and unbiased process, significantly reducing manual effort while improving accuracy and consistency. Moreover, this AI agent can be easily adapted for other academic assessments, competitions, or review systems by modifying evaluation criteria and inputs.
