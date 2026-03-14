# PRIYANK KHATRI


# 🧠 NeuroTab

**Your Second Brain for the Internet**

NeuroTab is a browser extension that transforms your internet activity into a searchable, intelligent second brain. It automatically remembers the pages you visit, summarizes them using AI, and allows you to search your browsing history using natural language. 

Instead of manually digging through your browser history or managing chaotic bookmark folders, simply ask:
> *"Find the React authentication GitHub repo I saw last week."*

---

## 🚨 The Problem

Modern internet users consume enormous amounts of information daily—articles, GitHub repositories, tutorials, research papers, tweets, and videos. However:
* **Information gets forgotten:** You remember *seeing* it, but not *where*.
* **Browser history is inefficient:** Standard history relies on exact keyword matching.
* **Tab overload:** Important resources get buried in hundreds of open tabs.
* **Poor recall:** There is no intelligent way to retrieve past research.

This leads to lost productivity and frustrating, repeated searches.

---

## 💡 The Solution

**NeuroTab** solves this by creating an AI-powered, searchable memory bank of your browsing activity. 

The extension seamlessly works in the background to:
1.  **Automatically remember** visited pages.
2.  **Use AI to summarize** and deeply understand page content.
3.  **Store embeddings** to enable powerful semantic search.
4.  **Let you chat** directly with your browsing history.

---

## ✨ Features

* **🔎 Natural Language Search:** Search your browsing history like you're chatting with an AI. *(e.g., "Find the Node.js authentication tutorial I opened yesterday.")*
* **🧠 AI Page Understanding:** Every visited page is automatically summarized, tagged, and indexed.
* **📚 Smart Memory Timeline:** View your browsing activity as a beautiful timeline of knowledge.
* **💬 Chat with Your Internet History:** Ask complex questions about your past reading. *(e.g., "What did I research about MongoDB last week?")*
* **🏷 Auto Tagging:** AI automatically categorizes pages into topics like *Programming*, *Finance*, *Research*, *Tutorials*, and *News*.
* **⭐ Smart Bookmarks:** Important pages and high-value resources are automatically highlighted.

---

## 🏗 Architecture & Workflow

### Workflow
1. **User visits** a webpage.
2. **Extension extracts** the page content.
3. **Content is sent** to the backend.
4. **AI generates** a summary and vector embeddings.
5. **Data is stored** in the database.
6. **User searches** using natural language.

### System Architecture
```text
[ Browser Extension ]
        ↓
[ Content Script ]
        ↓
[ Backend API ]
        ↓
[ AI Processing ]
        ↓
[ Vector Database ]

# 🛠 Tech Stack
Frontend
JavaScript / TypeScript

Chrome Extension API

React (optional)

Backend & Database
Node.js & Express.js

MongoDB (for user data & metadata)

Vector Database (Pinecone / Chroma / Weaviate for embeddings)

AI Layer
OpenAI API / Gemini API

Embeddings (for semantic search)

📷 Example Usage
User Query:

"Find the React login system repo I opened yesterday"

AI Response:

Here are the most relevant results:

1. GitHub - React JWT Authentication

Visited: Yesterday

Summary: Implementation of JWT authentication in React with a Node.js backend.

🎯 Use Cases
Students: Organizing research and sources for papers.

Developers: Saving and retrieving useful code snippets and repositories.

Writers: Tracking reference articles and inspiration.

Knowledge Workers: Managing project information seamlessly.

Anyone: People who open too many tabs and lose track of them!

🚀 Future Improvements
[ ] Cross-device memory sync

[ ] Proactive AI research assistant

[ ] Voice search capabilities

[ ] Knowledge graph visualization

[ ] Automated weekly research reports

🔐 Privacy
Your privacy is our priority. User data is:

Stored securely

Encrypted at rest and in transit

Never shared with or sold to third parties

Fully controlled by you (delete stored data at any time)

🤝 Contribution
Contributions are always welcome! If you'd like to improve AI Internet Memory, please follow these steps:

Fork the repository.

Create a new feature branch (git checkout -b feature/AmazingFeature).

Commit your changes (git commit -m 'Add some AmazingFeature').

Push to the branch (git push origin feature/AmazingFeature).

Open a Pull Request.

📜 License
Distributed under the MIT License. See LICENSE for more information.