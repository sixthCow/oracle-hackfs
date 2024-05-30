Oracle uses AI to analyze 500M+ daily posts on X (formerly Twitter), providing real-time insights into public sentiment and emerging trends. Summarize your Twitter timeline effortlessly with our user-friendly interface.
Description

Oracle is an advanced AI tool designed to analyze and summarize vast amounts of data from X, the platform formerly known as Twitter. Each day, over 500 million posts are uploaded to X, presenting an enormous opportunity to gauge real-time public opinion and sentiment on current events and cultural trends. Oracle taps into this data stream, leveraging large language models (LLMs) to provide comprehensive insights that go beyond traditional media and search capabilities.

With Oracle, users can either select from a list of recent news items, prompting the AI to generate relevant keywords for a search, or enter their own custom search queries. The tool uses RapidAPI to fetch a timeline of posts from X, which the AI then analyzes based on a specified prompt. The result is a detailed overview, assessment, and sentiment analysis of user opinions surrounding the chosen subject.
How It's Made

Oracle was developed for the HackFS hackathon, integrating several cutting-edge technologies to achieve its functionalities. Here’s a detailed breakdown of how Oracle was built:

    Backend Server:
        Node.js: The backend server is built using Node.js, a popular JavaScript runtime.
        RapidAPI: This service is used to fetch data from X (Twitter) and news sources. API keys are required for access.

    Frontend (Client):
        React: The client-side application is developed using React, providing a responsive and user-friendly interface.
        Environment Variables: Keys for RapidAPI are stored in a .env file to manage access securely.

    AI Integration:
        Galadriel: Oracle uses Galadriel, the first Layer 1 for AI, for processing and analyzing the data. A private key for Galadriel is necessary to authenticate and use its services.

    Smart Contract:
        Deployment: A smart contract is deployed on the Galadriel blockchain. Users can view the contract details through the Galadriel blockchain explorer.
        Integration: The smart contract integrates with the backend to manage data processing securely.

Detailed Development Process

    Backend Setup: The backend server is set up in a dedicated folder where dependencies are installed using npm install. The server requires a private key for Galadriel, which is stored in a .env file, and is started using npm start.

    Frontend Setup: Similarly, the client-side application is set up in its folder with dependencies installed via npm install. Environment variables for RapidAPI keys are also stored in a .env file, and the client is started with npm start.

    Smart Contract Deployment: The smart contract, located in its folder, requires environment variables for the private key and Oracle address. After configuration, the contract is deployed on the Galadriel blockchain.

    Data Analysis and Summarization: Once the backend and frontend are running, Oracle uses RapidAPI to fetch a timeline of posts based on the user’s query. The AI, powered by Galadriel, processes this data to generate summaries, detailed assessments, and sentiment analyses.

Notable Hacky Features

    Real-Time Data Processing: Oracle's ability to handle real-time data from X and perform quick sentiment analysis is a standout feature.
    Seamless Integration: The integration of Galadriel for AI processing and RapidAPI for data fetching demonstrates effective use of partner technologies.
    User-Friendly Design: Despite its complex backend operations, Oracle offers a simple and intuitive interface for users to interact with.

Oracle stands out by harnessing the power of AI to transform massive data streams into meaningful insights, making it an invaluable tool for understanding public opinion and emerging trends on X.
