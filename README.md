<p align="center">
<img src="assets/jules-readme.png" alt="Jules Awesome List" width="600">
</p>

<div align="center">
<h1>Awesome Jules Prompts 🌟 (Enhanced Edition)</h1>
<p>This repository is a community-curated collection of powerful and practical prompts designed to unlock the full potential of Jules, an AI coding agent from Google Labs. This version has been enhanced with insights from the official Jules documentation.</p>
<br>
<a href="https://jules.google.com">Visit Jules</a> •
<a href="https://www.google.com/search?q=%23-contributing">Contribute</a>
</div>

Table of Contents
How to Use

Everyday Dev Tasks

Advanced Feature Implementation

Content Creator & Streaming

AI-Enhanced Development & Tooling

🤖 Gemini & Multimodal Magic

Project Scaffolding & Content

Codebase Refactoring & Maintenance

DevOps & Infrastructure

Debugging

Documentation

Testing

Package Management

AI-Native Tasks

Context & Repo Understanding

Fun & Experimental

Start from Scratch

Contributing

🤔 How to Use
To use these prompts, simply copy the // command and paste it into your chat with Jules. Replace the {placeholder} text with details specific to your project. For prompts with setup scripts, add them to the "Environment setup" section in Jules.

Example
Prompt:
// Refactor {a specific} file from {x} to {y}...

Usage:
// Refactor the user-auth.js file from using Promises to using async/await.

🛠️ Everyday Dev Tasks
// Refactor {a specific} file from {x} to {y}...
<sub>General-purpose, applies to any language or repo.</sub>

// Add a test suite for the '{feature-name}' feature. Use {testing-framework}. The setup command is \npm install && npm run test:setup`.`
<sub>Useful for repos lacking test coverage. Specifies setup.</sub>

// Add type hints to the function \{function_name}` in `{file_path}.py`.`
<sub>Python codebases transitioning to typed code.</sub>

// Generate mock data for the schema defined in \{file_path}`. Create 5 realistic examples.`
<sub>APIs, frontends, or test-heavy environments.</sub>

// Convert all CommonJS modules in the \./src/legacy` directory to ES modules.`
<sub>JS/TS projects modernizing legacy code.</sub>

// Turn the callback-based function \{function_name}` in `{file_path}` into an async/await function.`
<sub>JavaScript or Python codebases improving async logic.</sub>

// Implement a Python data class based on the dictionary structure found in \{file_path}`. Use the `dataclasses` module.<sub>Useful for Python projects moving towards more structured data handling withdataclasses` or Pydantic.</sub>

// Create a script to automate the process of {task}. It should take {input} and produce {output}.
<sub>For automating repetitive tasks in your workflow.</sub>

🚀 Advanced Feature Implementation
// Scaffold a complete user authentication system using Passport.js, including local, Google, and GitHub strategies. The setup command is \npm install passport passport-local passport-google-oauth20 passport-github2`.`
<sub>For Node.js applications needing robust user login options.</sub>

// Implement a real-time chat feature using WebSockets and Redis for message queuing. Add a new file \AGENTS.md` explaining how the WebSocket server and Redis queue interact.`
<sub>For applications looking to add interactive, real-time communication.</sub>

// Add a feature-flag system to the application to allow for A/B testing and phased rollouts. Use the \flipper` library.`
<sub>For teams that want to de-risk feature releases.</sub>

// Integrate the Stripe API to handle one-time payments and recurring subscriptions. Setup script: \npm install stripe`.`
<sub>For applications that need to process payments.</sub>

// Build a recommendation engine that suggests content to users based on their viewing history. The core logic should be in a new file \recommendations.js`.`
<sub>For content-heavy platforms aiming to increase user engagement.</sub>

// Implement a search feature using Elasticsearch that provides real-time suggestions and typo tolerance.
<sub>For applications with large amounts of data to search through.</sub>

🎥 Content Creator & Streaming
// Implement a video upload and processing pipeline that automatically transcodes videos into multiple resolutions (480p, 720p, 1080p) using a background worker with FFMPEG. The setup command is \sudo apt-get update && sudo apt-get install -y ffmpeg`.`
<sub>For video platforms needing smooth viewing on different devices.</sub>

// Add a real-time chat feature to the live-streaming page using WebSockets, including moderation tools for the streamer. Document the new chat agent in \AGENTS.md`.`
<sub>To increase viewer engagement and build community.</sub>

// Integrate a tipping feature. First, add a new API endpoint to handle payment events from a webhook. Second, create a front-end component that shows an on-screen alert when a tip event is received via a WebSocket.
<sub>For creators who want to monetize their live streams.</sub>

// Add functionality for creating clips from past live streams, allowing viewers or the creator to share short, highlight-worthy moments.
<sub>A great way to make content more shareable.</sub>

🤖 AI-Enhanced Development & Tooling
// Set up a new Vite project with Tailwind CSS and a basic Python backend. Create a 'concurrently' script to run both the frontend and backend servers with a single 'npm run dev' command. Setup: \npm install concurrently && pip install flask`.`
<sub>For quickly scaffolding new projects.</sub>

// Create a new Zustand store for managing user authentication state. Include actions for logging in, logging out, and fetching the user profile from the Python backend.
<sub>A common requirement for most web applications.</sub>

// Write a Python proxy endpoint that forwards requests from my Vite frontend to a third-party API, securely handling API keys on the backend.
<sub>To avoid exposing sensitive credentials on the client-side.</sub>

// Based on the current state of my project, generate a new feature idea that leverages a large language model. Provide a high-level implementation plan and create a new \AGENTS.md` file describing the new AI agent.`
<sub>To spark creativity for your next AI-powered feature.</sub>

🤖 Gemini & Multimodal Magic
// Create a feature that allows users to upload an image and get a description of it using the Gemini API. The setup command is \pip install google-generativeai`.`
<sub>For adding image understanding to your application.</sub>

// Implement a text-to-speech feature that reads out selected text using the Gemini API. The generated audio should be playable in the browser.
<sub>For making your content more accessible and engaging.</sub>

// Build a "storyteller" feature that generates a short story based on a user's prompt and then reads it aloud using Gemini's text-to-speech capabilities.
<sub>A creative use of generative AI for content creation.</sub>

// Create a tool that analyzes a UI mockup image file (e.g., 'mockup.png') from the repository. It should send the image to the Gemini API and ask for a detailed UI/UX review with specific suggestions for improvement.
<sub>For getting instant design feedback.</sub>

// Implement a feature that allows users to upload a short audio file and have the Gemini API transcribe it to text.
<sub>For adding voice-to-text capabilities to your app.</sub>

// Build a generative art feature where a user can input a text prompt and the Gemini API will generate an image. The image should then be displayed on the page.
<sub>For creating unique and artistic content on the fly.</sub>

// Create an "AI Dungeon Master" for a text-based RPG. Use the Gemini API to generate dynamic storylines, character interactions, and world-building based on player input.
<sub>For creating immersive and interactive gaming experiences.</sub>

🎨 Project Scaffolding & Content
// Generate three distinct theme files (e.g., 'theme-dracula.css', 'theme-solarized.css') that define custom color palettes using CSS variables. Also, create a 'ThemeSwitcher' React component.
<sub>For adding theming capabilities to your application.</sub>

// Create a set of preset data for my application in a JSON file. This should contain at least five different configurations. Also, update my Zustand store to include a 'loadPreset' action.
<sub>Perfect for applications with many configuration options.</sub>

// Scaffold a new example page in my Vite application. The page should demonstrate a key feature and be pre-populated with realistic-looking data. Add a new route for this page and add it to the main navigation.
<sub>To showcase the capabilities of your application.</sub>

// Create a "template gallery" feature. This should include a set of pre-designed templates (as JSON) that users can select to initialize a new project. Update the UI to include a modal for selecting a template.
<sub>A powerful feature for any application that involves creation.</sub>

🧹 Codebase Refactoring & Maintenance
// Analyze the entire codebase and identify the top 5 largest files. For each file, provide a brief summary of its responsibilities and suggest a strategy for splitting it into smaller, more focused modules.
<sub>A great starting point for any refactoring effort.</sub>

// I have a large file called 'utils.js'. Analyze this file, group related functions together, and refactor them into separate, more specific utility files (e.g., 'date-utils.js', 'api-utils.js').
<sub>Helps you tackle the "junk drawer" file.</sub>

// This React component has grown too large. Analyze the component, identify distinct pieces of functionality, and refactor it into a container component with several smaller, presentational child components.
<sub>Improves component architecture and reusability.</sub>

// This Zustand store is managing state for multiple, unrelated features. Analyze the store, identify the different state "slices," and refactor it into multiple, feature-specific stores.
<sub>Keeps your state management clean and organized.</sub>

☁️ DevOps & Infrastructure
// Write a Dockerfile for my Node.js application and a docker-compose.yml file to run it with a PostgreSQL database. The setup command should be \docker-compose build`.`
<sub>For containerizing your application for consistent development.</sub>

// Create a complete GitHub Actions workflow to build, test, and deploy my application to Vercel.
<sub>For setting up a robust CI/CD pipeline.</sub>

// Write a Terraform script to provision the necessary infrastructure for this project on AWS (S3, EC2, RDS).
<sub>For managing your cloud resources with infrastructure as code.</sub>

// Set up a monitoring dashboard for this application using Prometheus and Grafana. Provide the configuration files.
<sub>For observing the health and performance of your application.</sub>

🐛 Debugging
// I'm getting a '500 Internal Server Error' when submitting the feedback form. The setup script to run the app is \npm run dev`. Please add logging to the form submission endpoint to trace the request and find the cause of the error.`
<sub>More specific debugging with setup context.</sub>

// The function \calculate_totals` in `billing.py` is very slow when processing large datasets. Please analyze its performance and apply optimizations.`
<sub>Performance profiling for specific functions.</sub>

// The value of \currentUser` is undefined in the `Dashboard.jsx` component. Trace the data flow from the authentication context to this component to find out why.`
<sub>Frontend and backend JS/TS bugs.</sub>

// I suspect a memory leak in my Node.js server when running the load test script located at \./scripts/load-test.js`. Please help me diagnose it.`
<sub>Server-side apps or long-running processes.</sub>

📝 Documentation
// Write a README for this project. Include a description, installation instructions from the setup script, and a brief explanation of the agents defined in \AGENTS.md`.`
<sub>Leverages existing setup and agent documentation.</sub>

// Add JSDoc comments to all functions in the file \{file_path}`.`
<sub>Improves maintainability of complex logic.</sub>

// Write API documentation in OpenAPI 3.0 format for the endpoint \/api/users/{id}`.`
<sub>REST or GraphQL backends.</sub>

// Generate Sphinx-style docstrings for the Python class \{class_name}` in `{file_path}`.`
<sub>Ideal for Python projects using Sphinx.</sub>

// Create a "Getting Started" guide for new contributors that explains the project structure, how to set up the development environment, and the contribution workflow.
<sub>For making your project more welcoming to newcomers.</sub>

// Generate a PULL_REQUEST_TEMPLATE.md file for this repository. It should include sections for 'Description', 'Related Issue', and a 'Checklist' for the author to complete.
<sub>For making your project more welcoming to newcomers.</sub>

✅ Testing
// Add integration tests for the \/api/auth/login` endpoint. The setup command is `npm install && npm test`. The tests should cover successful login, incorrect password, and non-existent user.`
<sub>Specific testing scenarios with setup.</sub>

// Write a test for the \useUserProfile` hook that mocks the `fetch` call to the user API.`
<sub>Browser-side fetch or axios logic.</sub>

// Convert the tests in \./test/legacy-tests` from Mocha to Jest.`
<sub>JS test suite migrations.</sub>

// Generate property-based tests for the \sortArray` function using `fast-check`.`
<sub>Functional or logic-heavy code.</sub>

// Write a Pytest fixture to mock the Stripe API call in the \process_payment` function.`
<sub>For Python projects using Pytest and needing robust mocking.</sub>

📦 Package Management
// Upgrade my ESLint and Prettier packages to the latest version and autofix any breaking configuration changes. The setup command is \npm install`.`
<sub>JS/TS repos using ESLint or Prettier.</sub>

// Show me the changelog for React 19 and identify any breaking changes that will affect my codebase.
<sub>Web frontend apps using React.</sub>

// Analyze my \package.json` and identify any dependencies that are no longer used or can be safely removed.`
<sub>Bloated or legacy codebases.</sub>

// Check if the packages in my \requirements.txt` are still maintained and have no major security vulnerabilities.`
<sub>Security-conscious or long-term projects.</sub>

// Set up Dependabot to automatically create pull requests for dependency updates.
<sub>Best for active projects with CI/CD.</sub>

✨ AI-Native Tasks
// Analyze this repo and generate 3 feature ideas that would be compelling to a {target_user_persona}. For each idea, create a high-level plan.
<sub>Vision-stage or greenfield products.</sub>

// Identify and list the top 3 areas of technical debt in the \{file_path}` file. For each, explain the problem and suggest a refactoring strategy.`
<sub>Codebases with messy or fragile logic.</sub>

// Find all instances of duplicated logic across the entire codebase and refactor them into a single, reusable function.
<sub>Sprawling repos lacking DRY practices.</sub>

// Cluster related functions in the \./utils` directory and suggest a more organized file structure.`
<sub>Projects with lots of utils or helpers.</sub>

// I want to solve GitHub issue #{issue_number}. Please read the issue, formulate a plan, and then implement the solution.
<sub>Directly leverages GitHub integration.</sub>

🗣️ Context & Repo Understanding
// Write a status update for my team based on the last 5 commits to the \main` branch.`
<sub>Managerial and async communication.</sub>

// Summarize all changes merged into the \develop` branch in the last 7 days.`
<sub>Catching up after time off.</sub>

// What is the purpose of the \AGENTS.md` file in this repository? Summarize the agents it describes.`
<sub>Understanding the project's tooling.</sub>

// What's going on in this repo? Provide a high-level overview of the project, its main technologies, and how to run it based on the setup scripts.
<sub>Great for onboarding onto unfamiliar code.</sub>

🎉 Fun & Experimental
// Add a confetti animation from the \react-confetti` library when a user successfully completes a purchase.`
<sub>Frontend web apps with user delight moments.</sub>

// When the CI/CD pipeline successfully completes, post a random developer joke to the team's Slack channel using a webhook.
<sub>Personal projects or team tools.</sub>

// Build a mini CLI game that runs in the terminal. The game should be a simple text-based adventure.
<sub>For learning or community fun.</sub>

// Add a dark mode Easter egg to the UI. It should be triggered by the Konami code.
<sub>Design-heavy frontend projects.</sub>

// Create a generative art piece using p5.js that visualizes the commit history of this repository.
<sub>For creative coding and exploring procedural generation.</sub>

// Create a "code poem" generator that turns a file's source code into a rhyming poem.
<sub>A fun and artistic way to look at code.</sub>

// Generate a simple, text-based SVG logo for this project. The logo should incorporate the project name '{ProjectName}' and be saved as 'logo.svg' in the 'assets' directory.
<sub>A fun and artistic way to look at code.</sub>

🚀 Start from Scratch
// Initialize a new Express app with CORS enabled and a basic \/api/health` endpoint.`
<sub>Web backend projects using Node.js and Express.</sub>

// Set up a monorepo using Turborepo and PNPM with two packages: \web` (a Next.js app) and `ui` (a React component library).`
<sub>Multi-package JS/TS projects.</sub>

// Bootstrap a Python project with Poetry and Pytest. Create a 'hello world' function with a test. Also, generate a basic README.md with setup instructions and a placeholder AGENTS.md file.
<sub>Python repos aiming for clean dependency and test setup.</sub>

// Create a starter template for a Chrome extension that changes the background color of the current page.
<sub>Browser extension development.</sub>

// I want to build a web scraper to get the headlines from Hacker News. Start me off with a Python script using BeautifulSoup and Requests. Setup: \pip install beautifulsoup4 requests`.`
<sub>Data scraping or automation tools.</sub>

🙌 Contributing
Your contributions are welcome! Add new prompts, fix formatting, or suggest categories.

📄 Contributing Guide

🪄 Open a Pull Request