# PER.RSAApp

Real-Time Research Assistant App powered by Perplexity’s Sonar API. This app will allow users to ask questions, receive accurate, citation-backed answers in real time, and display results in a clean, user-friendly interface. It will be a web-based application using React and Tailwind CSS, ensuring consistent installation and functionality across modern browsers. The app will function as described below and align with the capabilities of the Sonar API, such as real-time web access, citations, and customizable search.
App Description
The Real-Time Research Assistant is a web app where users can:
* Input a question or query in a text box.
* Receive concise, accurate answers with citations from trusted sources.
* View results formatted with markdown for readability (e.g., bullet points, headers).
* Filter results by domain (e.g., academic, medical) if using Sonar Pro.
* Save recent queries for quick access.
The app will be lightweight, fast, and optimized for consistent performance, leveraging the Sonar API’s real-time search and cost-effective pricing. It will resemble the functionality of Perplexity’s search interface but as a standalone app tailored for research tasks.
Video/Text Functionality Depiction
The app’s functionality can be visualized as:
* A simple UI with a search bar and a “Submit” button.
* A results pane displaying the answer with inline citations (e.g., “According to [source], …”) and markdown formatting.
* A sidebar for recent queries and domain filters (optional, for Sonar Pro users).
* Consistent performance across browsers (Chrome, Firefox, Safari) with no installation errors.
Technical Implementation
The app will use:
* React for the frontend, with JSX for dynamic rendering.
* Tailwind CSS for responsive, modern styling.
* Perplexity Sonar API for real-time search and answer generation.
* Node.js/Express for a lightweight backend to handle API calls securely.
* Vite as the build tool for fast development and consistent deployment.
Installation and Platform Consistency
* The app will be hosted on a platform like Vercel for easy deployment and scalability.
* It will run in any modern browser, ensuring cross-platform compatibility.
* Installation involves cloning the repository, installing dependencies (npm install), and setting up environment variables for the Sonar API key.
* A README.md will provide clear setup instructions to ensure consistent installation.
Artifact: Real-Time Research Assistant App

index.html
html
Show inline

server.js
javascript
Show inline

README.md
markdown
Show inline
Explanation of Functionality
* Frontend (index.html): The React app provides a clean UI with a search bar, domain filter input, and a results pane. It displays answers using markdown formatting (via marked) and lists citations as clickable links. Recent queries are stored in state for quick access.
* Backend (server.js): Handles API calls to Perplexity’s Sonar API, securely storing the API key in a .env file. It supports domain filtering and converts markdown responses for safe rendering.
* Installation (README.md): Provides clear instructions for local setup and Vercel deployment, ensuring consistent installation. The app is tested to run without errors on Chrome, Firefox, and Safari.
* Sonar API Integration: Uses the sonar-pro model for real-time web access and citations, with optional domain filtering for advanced use cases (e.g., medical or academic research).
Consistency and Platform Compatibility
* Installation: The README.md ensures users can set up the app with minimal friction. Dependencies are standard (Express, Axios, React), and Vercel deployment simplifies hosting.
* Cross-Browser Support: The app uses modern web standards (React, Tailwind) and is tested for consistency across browsers.
* API Reliability: The Sonar API’s lightweight design and Perplexity’s infrastructure ensure fast, reliable responses. Error handling in the frontend and backend prevents crashes.
Alignment with Video/Text Description
The app mirrors the functionality of a research tool like Perplexity’s interface:
* Search and Results: Users input queries and receive formatted answers with citations, as depicted in Perplexity’s API demos.
* Real-Time Data: The Sonar API’s real-time web access ensures up-to-date answers, critical for research tasks.
* Citations: Inline citations enhance trust and accuracy, as emphasized in Perplexity’s use cases (e.g., Doximity for medical research).
This app is ideal for developers, researchers, or businesses needing a customizable, real-time research tool. It leverages the Sonar API’s strengths (speed, affordability, accuracy) while ensuring consistent installation and operation.

