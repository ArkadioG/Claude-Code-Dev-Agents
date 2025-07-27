# Claude Code Development Agents

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![Claude Code](https://img.shields.io/badge/Claude%20Code-Subagents-blue.svg)](https://docs.anthropic.com/en/docs/claude-code/sub-agents)
[![Python](https://img.shields.io/badge/Python-Backend-green.svg)](https://www.python.org/)
[![React Native](https://img.shields.io/badge/React%20Native-Mobile-61DAFB.svg)](https://reactnative.dev/)
[![HTMX](https://img.shields.io/badge/HTMX-Server--Side-orange.svg)](https://htmx.org/)
[![FastAPI](https://img.shields.io/badge/FastAPI-Framework-009688.svg)](https://fastapi.tiangolo.com/)
[![AWS](https://img.shields.io/badge/AWS-Cloud-FF9900.svg)](https://aws.amazon.com/)
[![Terraform](https://img.shields.io/badge/Terraform-IaC-623CE4.svg)](https://www.terraform.io/)
[![PRs Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen.svg)](http://makeapullrequest.com)
[![Made for Developers](https://img.shields.io/badge/Made%20for-Developers-red.svg)](https://github.com/ArkadioG/claude-code-dev-agents)

A comprehensive collection of specialized Claude Code subagents designed to enhance your software development lifecycle. These domain-agnostic experts can be applied to any software project, from web applications to mobile apps, AI-powered systems to enterprise solutions.

## What are Claude Code Subagents?

[Claude Code subagents](https://docs.anthropic.com/en/docs/claude-code/sub-agents) are specialized AI assistants that handle specific types of development tasks. Each agent operates with its own context window, custom system prompts, and specialized expertise. They enable more efficient problem-solving by providing task-specific configurations that Claude Code can automatically delegate to or explicitly invoke.

## ⚠️ Opinionated Technology Framework

This agent collection represents an **opinionated approach** to modern software development with specific technology preferences:

**Backend Preference:**
- Python ecosystem (FastAPI)
- PostgreSQL for data persistence
- RESTful API design patterns

**Frontend Preference:**
- **Server-side first**: HTMX + Alpine.js + Tailwind CSS for web applications
- React Native for mobile applications  
- Progressive enhancement over client-side SPAs

**Infrastructure Preference:**
- Cloud-native deployment
- Containerization with Docker
- Infrastructure as Code with Terraform

**Development Philosophy:**
- API-first design
- Security and compliance by default
- Performance and scalability considerations
- Comprehensive testing strategies

**If your technology stack differs significantly from these preferences, you may want to customize the agent system prompts to better align with your chosen technologies and methodologies.**

## Agent Collection

### 🎯 Strategic Leadership
- **Product Owner/Development Manager** - Project coordination, backlog management, requirements analysis

### 💻 Core Development
- **Backend API Architect** - System architecture, API design, technology decisions  
- **Backend Developer** - Python/FastAPI implementation, business logic, testing
- **Server-Side Web Developer** - HTMX, Alpine.js, Tailwind CSS, modern server-side rendering
- **Mobile App Developer** - React Native, Flutter, mobile-specific integrations
- **Database Engineer** - Schema design, query optimization, data modeling
- **Cloud Infrastructure Engineer** - AWS/GCP/Azure, Terraform, containerization

### 🔧 Specialized Technical
- **AI/ML Integration Specialist** - Model deployment, ML pipelines, AI service orchestration
- **Security & Compliance Auditor** - Security frameworks, data protection, regulatory compliance
- **API Design Specialist** - REST/GraphQL design, API documentation, integration strategies

### ⚡ Quality & Operations  
- **DevOps Pipeline Engineer** - CI/CD automation, deployment pipelines
- **Performance Optimizer** - Load testing, bottleneck analysis, optimization
- **Testing Strategist** - Test automation, QA processes, testing frameworks

### 📚 Support
- **Code Reviewer** - Code quality, best practices, security reviews
- **Technical Documentation Writer** - API docs, architecture guides, user documentation

## Installation & Usage

### Option 1: Project-Level Installation
1. Clone this repository to your project root:
   ```bash
   git clone https://github.com/yourusername/claude-code-dev-agents.git .claude/agents
   ```

2. The agents will be available immediately in your Claude Code session for that project.

### Option 2: User-Level Installation  
1. Clone to your user directory:
   ```bash
   git clone https://github.com/yourusername/claude-code-dev-agents.git ~/.claude/agents
   ```

2. Agents will be available across all your Claude Code projects.

### Managing Agents
Use Claude Code's built-in agent management:
```bash
/agents
```

This opens an interactive interface to view, create, edit, and manage your subagents.

## How to Use

### Automatic Delegation
Claude Code will automatically delegate tasks to appropriate agents based on:
- Task description in your request
- Agent descriptions and expertise areas
- Current context and available tools

### Explicit Invocation
Request a specific agent by mentioning it:
```bash
# Use the backend developer for API implementation
@backend-developer implement the user authentication endpoints

# Use the cloud engineer for deployment
@cloud-infrastructure-engineer deploy this to AWS using Terraform
```

## Customization

Each agent is stored as a Markdown file with YAML frontmatter. You can:

1. **Modify existing agents** to match your team's specific needs
2. **Add new agents** for specialized domains
3. **Adjust tool permissions** for security or focus requirements
4. **Customize system prompts** to reflect your coding standards

Example agent structure:
```markdown
---
name: agent-name
description: "Brief description for Claude Code delegation"
tools: "optional,tool,list"
---

# Agent Name

[Custom system prompt content]
```

## Best Practices

1. **Start with the Product Owner** - Use for breaking down requirements and planning
2. **Architect before implementing** - Use API Architect before Backend Developer
3. **Security first** - Involve Security Auditor for sensitive applications
4. **Document as you go** - Use Technical Documentation Writer throughout development

## Contributing

1. Fork the repository
2. Create agents following the established format
3. Test agents with real development scenarios
4. Submit pull request with clear description of agent capabilities

## License

[MIT License](LICENSE) - Feel free to use, modify, and distribute these agents for your projects.

These agents embody specific technology opinions and best practices. You're encouraged to fork and adapt them to match your preferred technology stack and development methodologies.

## Support

For questions about Claude Code subagents:
- [Claude Code Documentation](https://docs.anthropic.com/en/docs/claude-code/sub-agents)
- [Anthropic Support](https://support.anthropic.com)

---

**Made with ❤️ for the developer community**