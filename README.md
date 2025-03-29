# AI_Automate
Finding the right product with AI Agents 

## About
Simple use case of CrewAI in automating the search of product from a shopping vendor. 

### Features

- **Search Agent**: Performs a deep product search on e-commerce websites like Amazon
- **Reporting Agent**: Analyzes search results and recommends the top products
- **Modular YAML Configuration**: Easily customize agents and tasks via config files
- **Powered by CrewAI** and tool integrations (e.g., SerperDevTool, ScrapeWebsiteTool)

### Config
agents.yml: Defines roles, goals, and backstories for each agent

tasks.yml: Describes what each agent should do and what output is expected

    Example Use Case

    Search for: "queen size bed set"
    Requirements: "Easy to assemble, sturdy, and comfortable"
    Source site: Amazon.com

    ✅ The search agent fetches at least 50 product listings.
    ✅ The reporting agent analyzes and summarizes the top 5 based on your criteria.

