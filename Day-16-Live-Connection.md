# Day 16: Live Connection - Google Sheets & Gemini
**Project:** Automating Community Support for KreyolAIHub

### The Engineering Strategy
I moved beyond manual prompting. I designed a live data pipeline where Google Sheets acts as the "Database" and Gemini acts as the "Processing Engine." 

### The Automation Workflow
1. **Input:** Community question entered into Google Sheets.
2. **Process:** Make.com detects the new row, sends it to Gemini with a 'Senior Mentor' persona constraint.
3. **Output:** The AI-generated Kreyòl response is automatically written back to the sheet for my final review.

### Why this is a Specialist Skill
This setup allows KreyolAIHub to scale. Instead of 1-on-1 chats, I can now process 100 questions simultaneously, ensuring every student gets a culturally aligned response in seconds.
