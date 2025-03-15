📘 Jains Aadhya - AI Real Estate Agent Project Documentation

🏗️ Project Overview

Project Name: Jains AadhyaLocation: Nookampalayam Road, ChennaiObjective: AI-powered real estate assistant, featuring SIA (a female AI chatbot) designed to assist users in exploring real estate properties interactively.

🔧 Tech Stack

Frontend: ReactJS

Backend: Node.js, ExpressJS

Database: MongoDB

Microservices: WhatsApp follow-ups, Report Generation

Cloud Services: AWS API Gateway, AWS EventBridge, AWS SQS, AWS Lambda

LLM: OpenAI API (GPT-4o)

Speech-to-Text: Deepgram, Google Cloud

Text-to-Speech: ElevenLabs, AWS Polly, Google Cloud

LipSync: AWS Polly

🚀 Features

🎯 Core AI Features

AI Chatbot (SIA):

Interacts with users via Speech and Text.

Supports intent detection using OpenAI API to guide users (e.g., site visit scheduling, cost sheet calculations).

Multimedia Response:

Displays relevant images and videos based on user inquiries.

Speech-to-Text:

Plug-and-Play setup supporting Deepgram and Google Cloud for transcription.

Text-to-Speech:

Supports ElevenLabs, AWS Polly, and Google Cloud for dynamic text-to-voice conversion.

LipSync Animation:

Uses AWS Polly to sync chatbot speech with realistic lip movements.

🔥 User Engagement Features

Site Visit Scheduling:

Allows users to select preferred date and time.

Cost Sheet Calculation:

Users select floor and size to get a detailed cost breakdown.

WhatsApp Follow-Up:

Automated follow-ups via a dedicated microservice.

AWS EventBridge manages reminders.

Feedback Form:

Captures user ratings and comments.

User Intent Ranking:

Ranks users based on their engagement and behavior.

🔧 Backend & Microservices

🎯 Backend Overview

Built with Node.js and ExpressJS.

Manages API routes, chatbot responses, multimedia delivery, and user data handling.

Handles user intents and triggers actions accordingly (e.g., schedule site visit).

🔥 Microservices Breakdown

WhatsApp Follow-Up Service:

Triggered via AWS EventBridge.

Uses AWS SQS and Lambda for message processing.

Integrated with OpenAI for personalized responses.

Report Generation Service:

Runs every hour from 9 AM to 9 PM.

Generates Google Sheets reports:

Consolidated report with all user interactions.

Session-wise report per user.

Captures user name, mobile number, preferred configurations, chat history, and ranking.

MongoDB Charts Dashboard:

Visualizes data through charts, showing engagement insights and conversion trends.

🚀 Deployment Details

Frontend: Deployed under xrvizion subdomain (VPS).

Backend and Microservices hosted on the same VPS.

AWS services handle follow-ups, reminders, and reporting.

📌 Future Enhancements

Dynamic floor plan recommendations based on user preferences.

AI-driven property recommendations (e.g., similar projects in the area).

Chat history personalization (continue where the user left off).

AI-based financial planning tool (e.g., loan calculations, EMI breakdowns).

📘 Additional Pages

For more details:

Setup Guide — Step-by-step project installation and deployment.

API Documentation — Detailed API routes, payloads, and responses.

Microservices Breakdown — In-depth explanation of each microservice.

Report Format Guide — Explanation of report structure and data fields.

✨ Jains Aadhya is revolutionizing real estate sales, one AI conversation at a time. ✨
