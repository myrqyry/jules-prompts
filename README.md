<p align="center">
<img src="assets/jules-readme.png" alt="Jules Awesome List" width="600">
</p>

<div align="center">
<h1>Awesome Jules Prompts 🌟</h1>
<p>This repository is a community-curated collection of powerful and practical prompts designed to unlock the full potential of Jules, an AI coding agent from Google Labs.</p>
<br>
<a href="https://jules.google.com">Visit Jules</a> •
<a href="#-contributing">Contribute</a>
</div>

---

## Table of Contents

* [How to Use](#-how-to-use)
* [Everyday Dev Tasks](#️-everyday-dev-tasks)
* [Advanced Feature Implementation](#-advanced-feature-implementation)
* [Content Creator & Streaming](#-content-creator--streaming)
* [AI-Enhanced Development & Tooling](#-ai-enhanced-development--tooling)
* [Project Scaffolding & Content](#-project-scaffolding--content)
* [Codebase Refactoring & Maintenance](#-codebase-refactoring--maintenance)
* [DevOps & Infrastructure](#-devops--infrastructure)
* [Debugging](#-debugging)
* [Documentation](#-documentation)
* [Testing](#-testing)
* [Package Management](#-package-management)
* [AI-Native Tasks](#-ai-native-tasks)
* [Context](#️-context)
* [Fun & Experimental](#-fun--experimental)
* [Start from Scratch](#-start-from-scratch)
* [Contributing](#-contributing)

---

## 🤔 How to Use

To use these prompts, simply copy the `//` command and paste it into your chat with Jules. Replace the `{placeholder}` text with details specific to your project.

### Example

**Prompt:**
`// Refactor {a specific} file from {x} to {y}...`

**Usage:**
`// Refactor the user-auth.js file from using Promises to using async/await.`

---

## 🛠️ Everyday Dev Tasks

* `// Refactor {a specific} file from {x} to {y}...`
    <sub>General-purpose, applies to any language or repo.</sub>
* `// Add a test suite...`
    <sub>Useful for repos lacking test coverage.</sub>
* `// Add type hints to {a specific} Python function...`
    <sub>Python codebases transitioning to typed code.</sub>
* `// Generate mock data for {a specific} schema...`
    <sub>APIs, frontends, or test-heavy environments.</sub>
* `// Convert these commonJS modules to ES modules...`
    <sub>JS/TS projects modernizing legacy code.</sub>
* `// Turn this callback-based code into async/await...`
    <sub>JavaScript or Python codebases improving async logic.</sub>
* `// Implement a data class for this dictionary structure...`
    <sub>Useful for Python projects moving towards more structured data handling with `dataclasses` or Pydantic.</sub>

---

## 🚀 Advanced Feature Implementation

* `// Scaffold a complete user authentication system using Passport.js, including local, Google, and GitHub strategies.`
    <sub>For Node.js applications needing robust and flexible user login options.</sub>
* `// Implement a real-time chat feature using WebSockets and Redis for message queuing.`
    <sub>For applications looking to add interactive, real-time communication between users.</sub>
* `// Add a feature-flag system to the application to allow for A/B testing and phased rollouts.`
    <sub>For teams that want to de-risk feature releases and test new ideas with a subset of users.</sub>
* `// Integrate the Stripe API to handle one-time payments and recurring subscriptions.`
    <sub>For applications that need to process payments and manage user subscriptions.</sub>
* `// Build a recommendation engine that suggests content to users based on their viewing history.`
    <sub>For content-heavy platforms aiming to increase user engagement through personalization.</sub>

---

## 🎥 Content Creator & Streaming

* `// Implement a video upload and processing pipeline that automatically transcodes videos into multiple resolutions (e.g., 480p, 720p, 1080p) using a background worker.`
    <sub>For any video platform that needs to provide a smooth viewing experience on different devices and network conditions.</sub>
* `// Add a real-time chat feature to the live-streaming page using WebSockets, including moderation tools for the streamer.`
    <sub>To increase viewer engagement and build a community around live content.</sub>
* `// Integrate a tipping or "super chat" feature, allowing viewers to send donations to the streamer during a live broadcast, with on-screen alerts.`
    <sub>For creators who want to monetize their live streams through direct fan support.</sub>
* `// Add functionality for creating clips from past live streams, allowing viewers or the creator to share short, highlight-worthy moments.`
    <sub>A great way to make content more shareable and attract new viewers.</sub>

---

## 🤖 AI-Enhanced Development & Tooling

* `// Set up a new Vite project with Tailwind CSS and a basic Python backend. Create a 'concurrently' script to run both the frontend and backend servers with a single 'npm run dev' command.`
    <sub>For quickly scaffolding new projects with your preferred stack.</sub>
* `// Create a new Zustand store for managing user authentication state. Include actions for logging in, logging out, and fetching the user profile from the Python backend.`
    <sub>A common requirement for most web applications, tailored to your state management library.</sub>
* `// Write a Python proxy endpoint that forwards requests from my Vite frontend to a third-party API, securely handling API keys on the backend.`
    <sub>To avoid exposing sensitive credentials on the client-side and to bypass CORS issues during local development.</sub>
* `// Based on the current state of my project, generate a new feature idea that leverages a large language model. Provide a high-level implementation plan, including the necessary frontend components, Zustand store modifications, and Python backend endpoints.`
    <sub>To spark creativity and give you a roadmap for your next AI-powered feature.</sub>

---

## 🎨 Project Scaffolding & Content

* `// Generate three distinct theme files (e.g., 'theme-dracula.css', 'theme-solarized.css') that define custom color palettes for my application using CSS variables. Also, create a 'ThemeSwitcher' React component that allows users to toggle between these themes.`
    <sub>For adding theming capabilities to your application, allowing for greater personalization.</sub>
* `// Create a set of preset data for my application. This should be a JSON file containing at least five different configurations that a user can load to see various examples of what the app can do. Also, update my Zustand store to include a 'loadPreset' action.`
    <sub>Perfect for applications that have a lot of configuration options, giving users a starting point to explore from.</sub>
* `// Scaffold a new example page in my Vite application. The page should demonstrate a key feature and be pre-populated with realistic-looking data. Include a new route for this page and add it to the main navigation.`
    <sub>To showcase the capabilities of your application and provide clear, working examples for your users.</sub>
* `// Create a "template gallery" feature. This should include a set of pre-designed templates (as JSON or another format) that users can select to initialize a new project or document within my application. Update the UI to include a modal for selecting a template.`
    <sub>A powerful feature for any application that involves creation, from documents to dashboards to designs.</sub>

---

## 🧹 Codebase Refactoring & Maintenance

* `// Analyze the entire codebase and identify the top 5 largest files (in terms of lines of code). For each file, provide a brief summary of its responsibilities and suggest a strategy for splitting it into smaller, more focused modules.`
    <sub>A great starting point for any refactoring effort. It gives you a high-level overview of where the "hotspots" are in your codebase.</sub>
* `// I have a large file called 'utils.js' that has become a dumping ground for miscellaneous functions. Analyze this file, group related functions together, and refactor them into separate, more specific utility files (e.g., 'date-utils.js', 'api-utils.js', 'string-utils.js').`
    <sub>A common problem in many projects! This prompt helps you tackle the "junk drawer" file and organize it into a more logical structure.</sub>
* `// This React component has grown too large and is handling too many responsibilities. Analyze the component, identify distinct pieces of functionality (e.g., state management, data fetching, rendering logic), and refactor it into a container component with several smaller, presentational child components.`
    <sub>For frontend development, this is a classic pattern for improving component architecture and reusability.</sub>
* `// This Zustand store is managing state for multiple, unrelated features. Analyze the store, identify the different state "slices," and refactor it into multiple, feature-specific stores. Then, demonstrate how to use them together in a component.`
    <sub>As your application grows, so does your state. This prompt helps you keep your state management clean and organized.</sub>

---

## ☁️ DevOps & Infrastructure

* `// Write a Dockerfile for my Node.js/Python/Go application and a docker-compose.yml file to run it with a database.`
  <sub>For containerizing your application for consistent development and deployment.</sub>
* `// Create a complete GitHub Actions workflow to build, test, and deploy my application to a cloud provider like Vercel or AWS.`
  <sub>For setting up a robust CI/CD pipeline.</sub>
* `// Write a Terraform script to provision the necessary infrastructure for this project on AWS/GCP/Azure.`
  <sub>For managing your cloud resources with infrastructure as code.</sub>
* `// Set up a monitoring dashboard for this application using Prometheus and Grafana.`
  <sub>For observing the health and performance of your application in production.</sub>

---

## 🐛 Debugging

* `// Help me fix {a specific} error...`
    <sub>For any repo where you're stuck on a runtime or build error.</sub>
* `// Why is {this specific snippet of code} slow?`
    <sub>Performance profiling for loops, functions, or queries.</sub>
* `// Trace why this value is undefined...`
    <sub>Frontend and backend JS/TS bugs.</sub>
* `// Diagnose this memory leak...`
    <sub>Server-side apps or long-running processes.</sub>
* `// Add logging to help debug this issue...`
    <sub>Useful when troubleshooting silent failures.</sub>
* `// Find race conditions in this async code`
    <sub>Concurrent systems in JS, Python, Go, etc.</sub>
* `// Add print statements to trace the execution flow of this Python script...`
    <sub>For debugging complex Python scripts or understanding unexpected behavior.</sub>

---

## 📝 Documentation

* `// Write a README for this project`
    <sub>Any repo lacking a basic project overview.</sub>
* `// Add comments to this code`
    <sub>Improves maintainability of complex logic.</sub>
* `// Write API docs for this endpoint`
    <sub>REST or GraphQL backends.</sub>
* `// Generate Sphinx-style docstrings for this Python module/class/function...`
    <sub>Ideal for Python projects using Sphinx for documentation generation.</sub>

---

## ✅ Testing

* `// Add integration tests for this API endpoint`
    <sub>Express, FastAPI, Django, Flask apps.</sub>
* `// Write a test that mocks fetch`
    <sub>Browser-side fetch or axios logic.</sub>
* `// Convert this test from Mocha to Jest`
    <sub>JS test suite migrations.</sub>
* `// Generate property-based tests for this function`
    <sub>Functional or logic-heavy code.</sub>
* `// Simulate slow network conditions in this test suite`
    <sub>Web and mobile apps.</sub>
* `// Write a test to ensure backward compatibility for this function`
    <sub>Library or SDK maintainers.</sub>
* `// Write a Pytest fixture to mock this external API call...`
    <sub>For Python projects using Pytest and needing robust mocking for testing.</sub>

---

## 📦 Package Management

* `// Upgrade my linter and autofix breaking config changes`
    <sub>JS/TS repos using ESLint or Prettier.</sub>
* `// Show me the changelog for React 19`
    <sub>Web frontend apps using React.</sub>
* `// Which dependencies can I safely remove?`
    <sub>Bloated or legacy codebases.</sub>
* `// Check if these packages are still maintained`
    <sub>Security-conscious or long-term projects.</sub>
* `// Set up Renovate or Dependabot for auto-updates`
    <sub>Best for active projects with CI/CD.</sub>

---

## ✨ AI-Native Tasks

* `// Analyze this repo and generate 3 feature ideas`
    <sub>Vision-stage or greenfield products.</sub>
* `// Identify tech debt in this file`
    <sub>Codebases with messy or fragile logic.</sub>
* `// Find duplicate logic across files`
    <sub>Sprawling repos lacking DRY practices.</sub>
* `// Cluster related functions and suggest refactors`
    <sub>Projects with lots of utils or helpers.</sub>
* `// Help me scope this issue so Jules can solve it`
    <sub>For working with Jules on real issues.</sub>
* `// Convert this function into a reusable plugin/module`
    <sub>Componentizing logic-heavy code.</sub>
* `// Refactor this Python function to be more amenable to parallel processing (e.g., using multiprocessing or threading)...`
    <sub>For optimizing performance in computationally intensive Python applications.</sub>

---

## 🗣️ Context

* `// Write a status update based on recent commits`
    <sub>Managerial and async communication.</sub>
* `// Summarize all changes in the last 7 days`
    <sub>Catching up after time off.</sub>

---

## 🎉 Fun & Experimental

* `// Add a confetti animation when {a specific} action succeeds`
    <sub>Frontend web apps with user delight moments.</sub>
* `// Inject a developer joke when {a specific} build finishes`
    <sub>Personal projects or team tools.</sub>
* `// Build a mini CLI game that runs in the terminal`
    <sub>For learning or community fun.</sub>
* `// Add a dark mode Easter egg to this UI`
    <sub>Design-heavy frontend projects.</sub>
* `// Turn this tool into a GitHub App`
    <sub>Reusable, platform-integrated tools.</sub>
* `// Create a generative art piece using p5.js or Three.js.`
    <sub>For creative coding and exploring procedural generation.</sub>
* `// Build a simple Twitter bot that posts {a type of content} every day.`
    <sub>For learning about API integrations and scheduled tasks.</sub>
* `// Make a browser extension that replaces all images on a page with {something funny}.`
    <sub>A classic, fun browser extension project.</sub>
* `// Create a small musical toy using Tone.js that lets users compose simple melodies.`
    <sub>For exploring web audio and interactive art.</sub>

---

## 🚀 Start from Scratch

* `// What's going on in this repo?`
    <sub>Great for legacy repos or onboarding onto unfamiliar code.</sub>
* `// Initialize a new Express app with CORS enabled`
    <sub>Web backend projects using Node.js and Express.</sub>
* `// Set up a monorepo using Turborepo and PNPM`
    <sub>Multi-package JS/TS projects with shared dependencies.</sub>
* `// Bootstrap a Python project with Poetry and Pytest`
    <sub>Python repos aiming for clean dependency and test setup.</sub>
* `// Create a starter template for a Chrome extension`
    <sub>Browser extension development.</sub>
* `// I want to build a web scraper—start me off`
    <sub>Data scraping or automation tools using Python/Node.</sub>
* `// Bootstrap a new blog using Next.js, Tailwind CSS, and MDX.`
    <sub>A modern stack for building content-heavy websites.</sub>
* `// Create a starter project for a desktop application using Electron and React.`
    <sub>For building cross-platform desktop apps with web technologies.</sub>
* `// Initialize a new Discord bot project using discord.js or discord.py.`
    <sub>For building custom bots for Discord servers.</sub>
* `// Set up a basic SvelteKit project with a pocketbase backend.`
    <sub>A great starting point for full-stack applications with a simple, integrated backend.</sub>

---

## 🙌 Contributing

Your contributions are welcome! Add new prompts, fix formatting, or suggest categories.

* 📄 [Contributing Guide](contributing.md)
* 🪄 Open a [Pull Request](https://github.com/YOUR_REPO/pulls)
