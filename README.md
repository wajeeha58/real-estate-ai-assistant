# real-estate-ai-assistant

🏠 Real Estate AI Assistant (n8n Workflow)
🚀 Project Overview

This project is a simple real estate assistant API built using n8n.

It takes user queries like budget and location and returns property suggestions.

🔧 Tech Stack
n8n (workflow automation)
Webhook API
JavaScript (Code node)
⚙️ How it Works

User → Webhook → Code Node → Response

📥 Sample Request
{
  "query": "2bhk under 20000 whitefield Bangalore"
}
📤 Sample Response
{
  "output": "Here are 3 2BHK options in Whitefield under ₹20,000:\n1. Flat A – ₹18,000\n2. Flat B – ₹19,500\n3. Flat C – ₹17,800"
}
🚀 How to Run
Install n8n
Import workflow.json
Click Execute Workflow
Send POST request to:
http://localhost:5678/webhook-test/real-estate-ai
📌 Note

This is a rule-based version. Future improvements:

Integrate OpenAI for AI responses
Connect real estate dataset
Add filters (budget, location)
💡 Author

Wajeeha

 
