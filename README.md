# 🌟 Awesome Jules Prompts (2025 Enhanced Edition)

**The most comprehensive, up-to-date collection of prompts for Jules - Google's asynchronous AI coding agent.**

<p align="center">
  <img src="assets/jules-readme.png" alt="Jules Awesome List" width="600">
<br>
  **🚀 Latest Update (October 2025)**: This collection covers **all Jules interfaces** - the powerful web UI, new CLI Tools, and API integration. Choose your preferred workflow: browser-based for visual feedback, terminal for seamless integration, or API for automation.

## 🎯 What's New in This Enhanced Edition

This collection provides prompts for **every way** you can use Jules:

- **🌐 Web Interface** - Rich visual feedback, planning collaboration, GitHub integration
- **⚡ CLI Tools** - Terminal-native workflows and automation
- **🤖 API Integration** - Programmatic access for custom workflows  
- **🔄 Hybrid Workflows** - Combine interfaces for maximum flexibility

## 🛠️ Quick Start Guide

### Web Interface (Browser-based)
```
1. Visit https://jules.google
2. Connect your GitHub account
3. Select repository and branch
4. Chat with Jules using natural language prompts
```

### CLI Tools (Terminal-based)  
```bash
# Install and authenticate
npm install -g @google/jules
jules login

# Launch interactive TUI or create remote sessions
jules  # Interactive terminal UI
jules remote new --repo . --session "your task here"
```

### API Integration (Programmatic)
```bash
# Direct API calls for automation
curl -X POST https://jules.googleapis.com/v1/sessions \
  -H "Authorization: Bearer $JULES_API_KEY" \
  -d '{"repo": "owner/repo", "prompt": "your task"}'
```

## 📚 Table of Contents

- [🌐 Web Interface Prompts](#-web-interface-prompts) - *Rich, Interactive Development*
- [⚡ CLI & Terminal Prompts](#-cli--terminal-prompts) - *Command-Line Workflows*  
- [🛠️ Universal Prompts](#️-universal-prompts) - *Work in Any Interface*
- [🤖 API & Automation](#-api--automation) - *Programmatic Integration*
- [🎨 Visual Development](#-visual-development) - *UI-Focused Tasks*
- [🔧 Advanced Workflows](#-advanced-workflows) - *Multi-Interface Projects*

***

## 🌐 Web Interface Prompts

*Perfect for interactive development, visual feedback, and collaborative planning*

### Interactive Planning & Collaboration
```
I want to add a user authentication system with social login support. Please analyze my current codebase, ask clarifying questions about my preferred approach, and collaborate with me to create the optimal implementation plan before starting.
```
*Uses Jules' interactive planning mode for complex features*

### Visual UI Development
```
Create a responsive dashboard component with data visualization charts. I need to see visual feedback of how it looks across different screen sizes, and I want you to show me screenshots of the rendered components during development.
```
*Leverages Jules' visual feedback capabilities in the web UI*

### Codebase Analysis & Architecture Review
```
Perform a comprehensive analysis of my entire codebase architecture. Create detailed documentation explaining the current structure, identify any architectural issues, and recommend improvements. Present this as an interactive report I can discuss with you.
```
*Uses the web interface's rich feedback and discussion capabilities*

### Real-time Code Review
```
I'm working on this pull request [link or description]. Please review the changes in real-time as I make them, provide instant feedback on code quality, security issues, and suggest improvements. Let's collaborate interactively to refine the implementation.
```
*Interactive review process using web interface*

### Research-Driven Development
```
Research the latest trends in React Server Components and Next.js App Router (search online for 2025 best practices). Based on your findings, help me migrate my existing Pages Router application. Show me examples and let's plan this migration step by step.
```
*Uses Jules' web browsing capability with interactive planning*

---

## ⚡ CLI & Terminal Prompts

*Seamless terminal integration for workflow automation*

### Quick Task Creation
```bash
# Single command task creation
jules remote new --repo . --session "add comprehensive test coverage with Jest and Playwright, including visual regression tests"

# Batch processing from files
cat backlog.md | while IFS= read -r line; do
  jules remote new --repo . --session "$line"
done
```

### GitHub Integration Workflows
```bash
# Work on assigned issues automatically
gh issue list --assignee @me --limit 1 --json title \
| jq -r '.[0].title' \
| jules remote new --repo .

# AI-powered issue prioritization
gemini -p "analyze these issues and pick the most critical one\n$(gh issue list)" \
| jules remote new --repo .
```

### Repository Management
```bash
# Multi-repo maintenance
for repo in $(gh repo list --json name --jq '.[].name'); do
  jules remote new --repo $repo --session "update dependencies and create security audit report"
done

# Cross-repository analysis
jules remote new --repo torvalds/linux --session "analyze memory management patterns in recent commits for educational blog post"
```

### Automated Monitoring & Maintenance
```bash
# Daily automated tasks (add to crontab)
# 0 9 * * * jules remote new --repo . --session "run security audit and create PR for fixes"
# 0 17 * * * jules remote new --repo . --session "update documentation for any code changes today"

# CI/CD integration
jules remote new --repo . --session "analyze failing tests in CI and create fixes with proper error handling"
```

***

## 🛠️ Universal Prompts

*These work great in both web interface and CLI*

### Modern Development Tasks

#### Smart Refactoring
```
Refactor the user authentication system from session-based to JWT with refresh tokens. Research current security best practices for 2025, implement proper token management, update all related middleware, and ensure backward compatibility during migration.
```

#### Performance Optimization
```
Analyze the application's performance bottlenecks using modern profiling techniques. Focus on Core Web Vitals, implement lazy loading, optimize bundle size, and create comprehensive performance monitoring. Provide before/after benchmarks.
```

#### Security Enhancement
```
Perform a comprehensive security audit of the entire codebase. Check for common vulnerabilities, update dependencies, implement proper input validation, add rate limiting, and create security monitoring. Document all security measures implemented.
```

#### Testing Strategy Implementation
```
Design and implement a modern testing strategy including unit tests (Vitest), integration tests (Playwright), visual regression testing, and performance testing. Set up automated test pipelines with proper coverage reporting and failure notifications.
```

### Advanced Architecture Tasks

#### Microservices Migration
```
Analyze the current monolithic architecture and create a migration plan to microservices. Design service boundaries, implement proper API gateways, set up inter-service communication, and create deployment strategies with monitoring and logging.
```

#### Cloud-Native Implementation
```
Convert the application to cloud-native architecture using containers, Kubernetes, and proper DevOps practices. Implement auto-scaling, health checks, monitoring dashboards, and disaster recovery procedures.
```

#### AI/ML Integration
```
Research and implement machine learning capabilities for [specific use case]. Create data preprocessing pipelines, implement model inference endpoints, add proper monitoring and versioning, and integrate with the existing application architecture.
```

***

## 🎨 Visual Development

*Optimized for Jules' web interface visual capabilities*

### UI Component Development
```
Create a comprehensive design system with reusable React components. I want to see visual previews of each component in different states, color schemes, and sizes. Build Storybook stories with interactive controls and automated visual regression testing.
```

### Responsive Design Implementation  
```
Implement responsive design for the entire application using modern CSS Grid and Container Queries. Show me visual comparisons across mobile, tablet, and desktop viewports. Create automated visual testing to prevent regression.
```

### Interactive Prototyping
```
Build interactive prototypes for the new user onboarding flow. Create multiple variations with different UX approaches, show visual mockups of each step, and implement user testing capabilities to gather feedback on the flow.
```

### Accessibility Implementation
```
Audit and improve accessibility across the entire application. Show visual indicators of accessibility issues, implement proper ARIA labels, ensure keyboard navigation, and create visual accessibility testing reports with before/after comparisons.
```

***

## 🤖 API & Automation

*Advanced integration patterns using Jules API*

### ChatOps Integration
```javascript
// Slack bot integration example
const { JulesAPI } = require('@google/jules-api');

app.post('/slack/commands', async (req, res) => {
  const task = req.body.text;
  const session = await jules.createSession({
    repo: process.env.DEFAULT_REPO,
    prompt: `${task} - requested via Slack by ${req.body.user_name}`,
    notify_webhook: process.env.SLACK_WEBHOOK
  });
  res.json({ text: `Task started: ${session.id}` });
});
```

### CI/CD Pipeline Integration
```yaml
# GitHub Actions workflow
- name: Auto-fix failing tests
  run: |
    if [ "${{ job.status }}" == "failure" ]; then
      jules remote new --repo . --session "analyze failing tests and implement fixes with proper error handling and documentation"
    fi
```

### Automated Code Review
```bash
# Webhook handler for PR reviews
jules remote new --repo $REPO --session "Review PR #$PR_NUMBER for security vulnerabilities, performance issues, and code quality. Create detailed feedback with specific line-by-line suggestions and security recommendations."
```

### Development Dashboard Integration
```python
# Python automation example
import requests

def monitor_repos():
    for repo in get_monitored_repos():
        response = requests.post('https://jules.googleapis.com/v1/sessions', {
            'repo': repo,
            'prompt': 'Check for security updates, dependency vulnerabilities, and code quality issues. Create PRs for any fixes needed.',
            'headers': {'Authorization': f'Bearer {JULES_API_KEY}'}
        })
```

***

## 🔧 Advanced Workflows

*Complex projects using multiple Jules interfaces*

### Multi-Interface Development Workflow
```bash
# 1. Start with CLI for quick setup
jules remote new --repo . --session "set up modern TypeScript React project with Vite, ESLint, Prettier, and testing framework"

# 2. Switch to web interface for interactive planning
# Visit jules.google, continue the session for collaborative UI design

# 3. Use API for automated testing
curl -X POST https://jules.googleapis.com/v1/sessions \
  -H "Authorization: Bearer $API_KEY" \
  -d '{"repo": ".", "prompt": "run comprehensive test suite and create performance benchmarks"}'
```

### Hybrid Debugging Session  
```
# CLI: Quick issue identification
jules remote new --repo . --session "analyze error logs and identify root cause of performance degradation"

# Web: Interactive problem-solving with visual feedback
# Continue in browser for step-by-step debugging with visual outputs

# API: Automated fix deployment  
# Use API to deploy fixes across environments
```

### Cross-Repository Architecture Project
```bash
# Use CLI for bulk repository analysis
for service in auth payments notifications; do
  jules remote new --repo $ORG/$service --session "analyze current architecture and document API endpoints, dependencies, and performance characteristics"
done

# Use web interface for interactive architecture planning
# Design overall system architecture with visual feedback

# Use API for automated implementation across services
# Deploy coordinated changes using API integration
```

***

## 📖 Interface-Specific Usage Tips

### 🌐 Web Interface Best Practices
- **Visual Tasks**: Use for UI development, design systems, and visual testing
- **Interactive Planning**: Leverage collaborative planning for complex features  
- **Real-time Feedback**: Great for iterative development and debugging
- **Repository Selection**: Easy visual repository and branch selection

### ⚡ CLI Best Practices  
- **Automation**: Perfect for scripted workflows and CI/CD integration
- **Bulk Operations**: Efficient for processing multiple tasks or repositories
- **Terminal Integration**: Seamless with existing terminal-based workflows
- **Quick Tasks**: Fast task creation without leaving the terminal

### 🤖 API Best Practices
- **Custom Integration**: Build Jules into your existing tools and platforms
- **Automated Workflows**: Create event-driven development processes
- **Monitoring**: Implement continuous code quality and security monitoring
- **Scaling**: Handle large-scale or enterprise development workflows

***

## 🔄 Choosing Your Interface

| Use Case | Best Interface | Why |
|----------|---------------|-----|
| Visual UI Development | Web Interface | Screenshot feedback, interactive design |
| Quick Bug Fixes | CLI Tools | Fast terminal integration |
| Automated Monitoring | API | Event-driven, programmatic access |
| Complex Feature Planning | Web Interface | Interactive collaboration |
| Bulk Repository Updates | CLI Tools | Efficient scripting |
| Custom Tool Integration | API | Maximum flexibility |
| Learning/Exploration | Web Interface | Rich feedback and guidance |

***

## 📄 Resources & Links

### Official Jules Resources
- **[Jules Web Interface](https://jules.google)** - Browser-based development[1]
- **[Jules CLI Documentation](https://jules.google/docs/cli)** - Terminal integration guide[2]
- **[Jules API Reference](https://developers.google.com/jules/api)** - Programmatic access[3]
- **[Jules Changelog](https://jules.google/docs/changelog/)** - Latest features and updates[4]

### Installation & Setup
- **[CLI Installation](https://www.npmjs.com/package/@google/jules)** - `npm install -g @google/jules`[5]
- **[CLI Examples](https://jules.google/docs/cli/examples)** - Practical usage patterns[6]
- **[API Documentation](https://developers.google.com/jules/api)** - Integration examples[3]

***

## ⚡ Quick Reference

### Web Interface
| Action | Method | Purpose |
|--------|--------|---------|
| Start Session | Visit jules.google | Rich interactive development |
| Visual Feedback | Enable screenshots | UI development and testing |
| Collaborate | Interactive chat | Complex feature planning |
| Repository | GUI selection | Easy project management |

### CLI Tools  
| Action | Command | Purpose |
|--------|---------|---------|
| Install | `npm install -g @google/jules` | Get CLI tools |
| Login | `jules login` | Authenticate |
| Interactive | `jules` | Terminal UI |
| Quick Task | `jules remote new --repo . --session "task"` | Fast execution |
| Monitor | `jules remote list --session` | Track progress |

### API Integration
| Action | Method | Purpose |
|--------|--------|---------|
| Create Session | `POST /v1/sessions` | Programmatic tasks |
| Monitor | `GET /v1/sessions/{id}` | Check status |
| Results | `GET /v1/sessions/{id}/result` | Get output |
| Webhooks | Configure endpoints | Event notifications |

***

**Built with ❤️ for the Jules community** | **Updated October 2025** | **All Interfaces Supported**

*Choose your perfect Jules workflow: Visual web interface, seamless CLI integration, or powerful API automation.*
