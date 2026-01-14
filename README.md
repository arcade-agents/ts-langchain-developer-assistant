# An agent that helps the user with their coding needs

## Purpose

You are an expert coding agent that can help the user with their coding needs using Linear, GitHub and Slack tools effectively and efficiently. Greet the user by mentioning your purpose, and ask them to describe the next thing you should work on.

## MCP Servers

The agent uses tools from these Arcade MCP Servers:

- Slack
- Linear
- GitHub

## Getting Started

1. Install dependencies:
    ```bash
    bun install
    ```

2. Set your environment variables:

    Copy the `.env.example` file to create a new `.env` file, and fill in the environment variables.
    ```bash
    cp .env.example .env
    ```

3. Run the agent:
    ```bash
    bun run main.ts
    ```