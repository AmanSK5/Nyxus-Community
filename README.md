# Nyxus

Nyxus finds the AI tools in use across an organisation, who uses them and on what, what was pasted into them, and gives the people responsible one place to decide what is approved, what is not, and what needs looking at. It runs inside your own cluster or on a Docker host, and nothing it collects leaves it.

- **Product and pricing:** [nyxus.co.uk](https://nyxus.co.uk)
- **Try the console:** [nyxus.co.uk/platform](https://nyxus.co.uk/platform), the shipped console with a sample estate
- **Documentation:** [nyxus.co.uk/kb](https://nyxus.co.uk/kb), from installing to upgrading, with the security model
- **Releases and notes:** [nyxus.co.uk/releases](https://nyxus.co.uk/releases), and the [releases](releases/) folder here
- **Support for a licensed deployment:** support@nyxus.co.uk

## What this repository is for

This is the public home for Nyxus. The product's source is not here; Nyxus is commercial software. This repository holds the release notes and the conversation around the product.

- **[Discussions](../../discussions)** for questions, ideas, what you would like to see and how you use it. Questions go in Q&A, suggestions in Ideas, and anything else in General.
- **[Issues](../../issues)** for something that is wrong: a fault, a wrong figure, a page that does not do what it says. One issue per thing, with the version from System health.
- **[Security](SECURITY.md)** for anything that could be a vulnerability. Not an issue, not a discussion.

A licensed deployment that has stopped working should go to the support address, where it reaches someone straight away. The tracker is read, but it is not a queue.

## Before you post

Nyxus is a security product and its findings are about people. When you describe a problem here, leave out what identifies your organisation and its people:

- no hostnames, cluster names or internal addresses;
- no company names, usernames or email addresses, including in screenshots;
- no licence keys, tokens, or the output of a command that prints them.

The version, the deployment type (Kubernetes or Compose), what you did, what you expected and what happened instead are enough. If a report needs more than that, say so and it can continue over support.

## Shadow AI Guard

[Shadow AI Guard](https://github.com/AmanSK5/shadow-ai-guard) is the open-source edition, with its own repository for issues and discussions. Nyxus adds accounts and roles, central settings, the fleet inventory, detection sources set up from the console, budget, evidence packs, the assistant in Slack and Teams, and support. The guide to moving from one to the other is in the [knowledge base](https://nyxus.co.uk/kb).

---

Nyxus is made by Aman Karir. Content in this repository is © 2026 Aman Karir.
