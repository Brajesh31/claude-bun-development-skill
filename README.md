# Claude Bun Development Skill

A development reference for using the Bun JavaScript and TypeScript runtime. It covers project setup, package management, execution, built-in APIs, testing, bundling, and migration from Node.js.

## What It Covers

- **Project setup:** Initialize JavaScript and TypeScript projects and configure TypeScript.
- **Package management:** Install, update, and remove dependencies with Bun.
- **Execution:** Run TypeScript and JavaScript files, scripts, and watch-mode processes.
- **Built-in APIs:** Use Bun file handling, HTTP server, WebSocket, SQLite, and password hashing APIs.
- **Testing:** Write and execute tests with the built-in test runner, including mocks and coverage.
- **Bundling:** Build and compile applications for supported targets.
- **Migration:** Understand Node.js compatibility and replace selected tools with Bun-native equivalents.
- **Performance:** Apply runtime-specific practices and production bundling guidance.

## Installation

Install Bun using the official installation instructions at [bun.sh](https://bun.sh), then clone this repository into your Claude skills directory:

```bash
git clone https://github.com/Brajesh31/claude-bun-development-skill.git ~/.claude/skills/bun-development
```

## Using the Skill

Example request:

```text
Use the bun-development skill to set up a TypeScript service with
Bun, add tests, and prepare a production bundle.
```

The skill contains command examples and TypeScript patterns for Bun's package manager, runtime, built-in APIs, test runner, and bundler. See [SKILL.md](SKILL.md) for the full reference.

## Note

This skill is specifically about Bun. Use it when the project or user explicitly chooses the Bun runtime. For Node.js projects, retain the Node.js toolchain and avoid introducing Bun unnecessarily.
