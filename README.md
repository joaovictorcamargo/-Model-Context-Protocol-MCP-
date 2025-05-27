
# Model Context Protocol (MCP) - Demo App

This is a full-stack demo application showcasing the **Model Context Protocol (MCP)** in action. It includes an MCP Server and an MCP Client that integrates with **Claude Desktop** and the **Vercel AI SDK**, demonstrating how AI tools can interact over the MCP protocol.

The project is built using **NX**, **React**, **Express**, **TanStack Start**, and leverages AI capabilities to handle tool calls seamlessly between client and server.

---

## 🚀 Features

- ✅ MCP Server implementation using SSE (Server-Sent Events)
- ✅ MCP Client implementation with Claude + Vercel AI SDK
- ✅ AI Assistant UI with Markdown rendering and tool invocation
- ✅ Example tool: Guitar Recommendation System
- ✅ Fully typed with TypeScript
- ✅ Modern stack with React, TanStack Start, Express, and NX

---

## 🏗️ Tech Stack

- Monorepo: [NX](https://nx.dev)  
- Frontend: React + TanStack Start + Tailwind CSS  
- Backend: Node.js + Express  
- AI: Vercel AI SDK + Anthropic Claude  
- MCP Transport: SSE (Server-Sent Events)  

---

## 🧠 AI Tools in this Demo

- `getProducts` — Fetches a list of guitars from the database  
- `recommendGuitar` — Recommends a specific guitar based on the ID  

The AI assistant can invoke these tools dynamically based on the conversation context.

---

## 📦 Installation

```bash
pnpm install
pnpm dev
```

The server runs on `http://localhost:8081` and the client on `http://localhost:4200`.

---

## 🎨 UI Example

- Markdown-based message rendering  
- AI vs. User message distinction  
- Tool invocation outputs embedded in the chat (e.g., guitar cards with image, price, and action buttons)  

---

## 🤖 AI Prompt Example

```plaintext
You are an AI for a music store.
You can recommend products and help users place orders.
Fetch products with the getProducts tool.
Recommend items with the recommendGuitar tool.
```

---

## 🛠️ Folder Structure

```
/apps
  /client   → React + TanStack Start
  /server   → Express + AI Logic (MCP Server)
/packages
  /ui       → Shared UI components
  /utils    → Shared utilities
```

---

## ✨ Credits

- Based on the Model Context Protocol (MCP)  
- Powered by TanStack, Vercel AI SDK, and Anthropic Claude  

---

## 💡 Disclaimer

This is a demo project for educational purposes, showcasing how to wire AI tools into full-stack apps using MCP.
