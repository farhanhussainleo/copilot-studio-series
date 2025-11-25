# Episode 4: Consuming MCP Servers from Microsoft Copilot Studio

[![Video Thumbnail](./images/IC3_Content_Thumb_copy.png)](https://www.youtube.com/watch?v=gcYz-l6R6FQ)

Welcome to Episode 4 of the **Copilot Studio for Beginners** series!

In this episode, Milan Kaur demonstrates how to consume an MCP (Model Context Protocol) server from within Microsoft Copilot Studio by integrating an MCP server with your own agent to use exposed capabilities such as sending emails automatically.

---

## What is MCP?

**MCP (Model Context Protocol)** is an open, standardized way for language models to connect with external APIs, data sources, and tools.  
You can think of it as a "USB-C port" for AI applications—letting smart apps connect to any system in a consistent, standardized way, so developers don't have to worry about the communication details under the hood.

---

## Key Topics Covered

- **Recap of Previous Episodes**  
  - Creating an agent in Copilot Studio in under 10 minutes  
  - Extending agents using tools for specific actions

- **Introducing MCP Integration**
  - Overview of what MCP is and its value for developers
  - How MCP enables agents to connect to external APIs and tools

- **Demo: Adding an MCP Server**
  - Using the "Conference Room Assistant" agent from previous episodes
  - Adding “email sending” capability to your agent via MCP server
  - Navigating to the Tools tab in Copilot Studio
  - Showing available MCP servers, including Office 365 Outlook Email Management
  - Providing credentials for MCP server usage

- **Selecting and Configuring Capabilities**
  - Enabling/disabling individual capabilities of an MCP server (e.g., sending emails)

- **Testing the Enhanced Agent**
  - Example scenario: asking the agent to find rooms with >15 seating
  -  Agent invoking “send via email” tool path.
  - Walking through the Activity Pane: initialization, knowledge-based search, invoking the email tool

---

## Notable Steps (Video Timeline Outline)

- **00:00** – Series introduction & recap
- **00:26** – What is MCP?  
- **01:56** – Where to add MCP Server as an available tool for your agent
- **02:24** – Adding and configuring the Office 365 Outlook MCP server
- **04:13** – Demo: using the agent, checking results, automatic email sending

---

## Additional Resources

- [MCP Server .NET video](https://aka.ms/add-your-mcp-server)
- [MCP Server .NET Sample](https://github.com/microsoft/mcp/tree/main/samples/dotnet)


---

Thank you for watching!  
*For questions or suggestions, feel free to open an issue or contribute to this repository.*

---
