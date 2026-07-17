# 🐱 Meow-bot

A simple Slack bot that meows on command and shares random cat facts.

> **Try it:** If you're a member of the Hack Club Slack workspace, you can interact with Meow-bot here:
>
> https://hackclub.enterprise.slack.com/archives/C0BHYS07GSF

---

## Preview

> <img width="1557" height="551" alt="Screenshot 2026-07-16 212641" src="https://github.com/user-attachments/assets/7c7c6ef1-7f33-480b-b23b-d3fb72aaa7c3" />

---

## Why I Built This

I built Meow-bot as a way to learn how Slack bots work and gain experience building backend services with Nest.

The goal wasn't to create a feature-rich chatbot—it was to explore the technologies behind bots, understand how Slack events are handled, and deploy a working service that people can interact with.

---

## Features

-  Responds with a meow
-  Shares random cat facts
-  Runs directly inside Slack
-  Built with NestJS
-  Hosted so members of the workspace can use it anytime

---

## Try It

If you're a member of the Hack Club Slack workspace, visit the public Meow-bot channel:

https://hackclub.enterprise.slack.com/archives/C0BHYS07GSF

---

## Tech Stack

- JavaScript
- NestJS
- Slack API
- Hosted server

---

## How It Works

Meow-bot listens for Slack events and slash commands through a NestJS server.

When a user interacts with the bot, Slack sends an HTTP request to the server. The bot processes the request, determines which command was used, and sends a response back to Slack.

This project was primarily an exercise in learning:

- Slack bot development
- Event-driven applications
- Backend API development with NestJS
- Deploying and hosting a persistent server

---

## Example Commands

```text
/meow-bot-meow
→ Meow! Meow! Meow!

/catfact
→ Cats have over 20 muscles that control their ears.
```

---

## 🔮 Future Improvements

- Add more cat commands
- Support cat images
- Track user statistics
- Configurable responses
- More fun interactions

---

## 📄 License

This project is licensed under the MIT License.
