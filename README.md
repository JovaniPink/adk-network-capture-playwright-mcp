# TagGuard Agent

Welcome to the TagGuard Agent, a project dedicated to ensuring compliance and automating audits for Google Tag Manager (GTM) implementations. This agent is built using **Google's Agent Development Kit (ADK)** to orchestrate browser interactions and data capture.

At its core, this project uses the **Playwright MCP server** to perform headless browser automation. It navigates to specified websites, such as the [Hilton Grand Vacations](https://www.hiltongrandvacations.com/index) homepage, to monitor network activity in real-time. The primary goal is to capture detailed network requests related to GTM, which provides deep insight into tag firing, data layer accuracy, and overall tracking health.

All captured network traffic is then saved locally as JSON files using a **Filesystem MCP server**. This modular approach, with separate servers for browser control and file storage, creates a clean and robust system. For our Minimum Viable Product (MVP), this process allows us to gather the essential data needed for GTM audits without requiring complex cloud infrastructure.

As an AI-driven agent, TagGuard is designed to be intelligent and adaptable, forming the foundation of a robust, cloud-based compliance and automation platform.

### Key Resources

* **[Google's Agent Development Kit (ADK)](https://google.github.io/adk-docs/)**: The framework used to build and orchestrate our AI agent.
* **[Playwright MCP](https://github.com/microsoft/playwright-mcp)**: The tool that provides robust, headless browser automation for network capture.
* **[Model Context Protocol (MCP)](https://github.com/modelcontextprotocol)**: The underlying protocol that allows our agent to communicate with various tools and services.
