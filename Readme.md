# 🚀 Basic-MCP Client

**Version:** 1.0.0  
**Module Type:** ES Module (`"type": "module"`)

---

## 📖 Overview

This project is a robust client implementation integrating several powerful SDKs and APIs, including:

- **Google GenAI** — for advanced AI-driven functionalities  
- **Model Context Protocol SDK** — to interact with the MCP ecosystem  
- **Twitter API v2** — enabling Twitter data integration  
- **dotenv** — for secure and flexible environment configuration  

This setup facilitates sophisticated AI interactions, API communication, and environment management.

---

## 🧩 Dependencies

| Package                 | Version     | Purpose                                         |
|-------------------------|-------------|------------------------------------------------|
| `@google/genai`         | ^0.7.0      | Google GenAI SDK for AI capabilities           |
| `@modelcontextprotocol/sdk` | ^1.8.0  | Model Context Protocol integration              |
| `dotenv`                | ^16.4.7     | Environment variable management                  |
| `express`               | ^5.1.0      | Lightweight web server framework                 |
| `twitter-api-v2`        | ^1.22.0     | Twitter API v2 client                            |
| `zod`                   | ^3.24.2     | Runtime schema validation and parsing            |

---

## 🛠️ Setup & Usage

1. 🔐 **Configure Environment**  
   Create a `.env` file in the root directory with necessary environment variables.

2. 📂 **Entry Point**  
   The main entry point is `index.js`.

3. 💾 **Install Dependencies**  
   Run:
   ```bash
   npm install

4. 🚧 **Development**
   Extend or customize the client leveraging the integrated SDKs and APIs.

5. ▶️ **Run**
   Execute your application as needed (e.g., `node index.js` or with a process manager).

---

## 🧪 Testing

* Currently, no tests are implemented.
* Placeholder script available:

  ```bash
  npm run test
  ```

---

## ⚖️ License

This project is licensed under the **MIT License**.
