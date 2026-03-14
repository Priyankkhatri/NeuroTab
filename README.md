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
