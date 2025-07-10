MosaicChats: Next.js Chat and Relationship Analysis Engine


MosaicChats is a client-side chat analysis application built with Next.js and React. It provides a suite of tools for in-depth relationship analysis by processing chat log files directly in the browser. This engine transforms textual conversation data into actionable insights on communication patterns, sentiment, and overall relationship dynamics. You can find the project at MosaicChats.com

Core Features
Comprehensive Conversation Analysis: Generates metrics on message count, word frequency, and user activity.

Sentiment Trend Analysis: Tracks the emotional tone (positive, negative, neutral) of the conversation over time.

Communication Style Profiling: Identifies and visualizes the primary communication styles of each participant.

Reciprocity and Engagement Metrics: Analyzes the balance of a conversation, including initiation rates and response times.

Interactive Data Visualization: Renders all analytics in a responsive dashboard with charts and graphs.

Technology Stack
Framework: Next.js

Language: TypeScript

UI: React, Tailwind CSS


Getting Started
To get a local copy up and running, follow these steps.

Prerequisites

Node.js (v18.17 or later)

Yarn or npm

Installation & Setup

Clone the repository:

Bash
git clone https://github.com/your-username/mosaicchats.git
cd mosaicchats
Install dependencies:

Bash
npm install
# or
yarn install
Set up environment variables:
Create a .env.local file in the root of the project by copying the example file:

Bash
cp .env.example .env.local
No environment variables are required to run the base application, but this file is necessary for future integrations.

Run the development server:

Bash
npm run dev
# or
yarn dev
Open http://localhost:3000 with your browser to see the result. You can start by uploading a .txt chat export file.

License
This project is licensed under the MIT License.
