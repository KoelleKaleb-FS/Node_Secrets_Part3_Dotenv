# Node_Secrets_Part3_Dotenv# Node Secrets Management - Part 3: Non-Shared Secrets

This is the third and final part of a project demonstrating secure secrets management in a Node.js application. In this part, secrets are stored in a `.env` file and managed using the `dotenv` package.

---

## Description

The application uses environment variables to securely manage sensitive information, such as API keys. The `.env` file containing secrets is excluded from the repository using `.gitignore`, ensuring they are not shared publicly.

---

## Getting Started

### Prerequisites

- Node.js installed on your system.
- Git installed.

---

### Installation

1. Clone the repository and switch to the `part-3` branch:
   ```bash
   git clone git@github.com:KoelleKaleb-FS/Node_Secrets_Part3_Dotenv.git
   cd Node_Secrets_Assignment
   git checkout part-3
   npm install
   ```
2. Create the dotenv file
   API_KEY=env_secret_key_#####
