# ChatPress 📖
> Turn AI chats, transcripts, and raw Markdown into clean, readable EPUB e-books in seconds.

[![License: MIT](https://img.shields.io/badge/License-MIT-blue.svg)](LICENSE)
[![GitHub Pages](https://img.shields.io/badge/Deployment-GitHub%20Pages-success.svg)](https://ramesh-2001-2100.github.io/chatpress/)
[![Zero Dependencies](https://img.shields.io/badge/Backend-Zero%20Server%20%2F%20100%25%20Local-purple.svg)](#privacy--architecture)

---

## The Problem & Motivation

Modern AI chat interfaces—from Gemini and Claude to ChatGPT and Grok—are built for back-and-forth iteration, not deep reading. 

When you generate long-form research, code explanations, or complete documentation guides inside a chat window, reading it on a computer or mobile screen can be frustrating:
* You spend half your time scrolling up and down through endless vertical chat threads.
* Massive input boxes, prompts, and tool headers eat up valuable screen real estate.
* Re-reading complex, technical content on bright screens leads to eye fatigue.

**ChatPress was created to solve this reading friction.** Instead of struggling through a cluttered chat UI, you can paste your content, click one button, and generate a native, paginated e-book formatted for your favorite e-reader (Kindle, Apple Books, Kobo, Moon+ Reader, or ReadEra).

---

## More Than AI Chats: Universal Markdown Reader

While born from AI conversations, **ChatPress works with any Markdown or formatted text content**, including:
* **Meeting & Lecture Notes:** Paste scratch notes, Obsidian vaults, or meeting logs to compile them into an organized digest.
* **YouTube & Podcast Transcripts:** Turn raw video transcripts into chaptered reading material.
* **Documentation & Guides:** Package multi-section technical write-ups for offline reference.
* **Q&A Logs & Interviews:** Convert human/assistant dialogs into structured transcripts.

---

## Features

- **Zero Installation & Runs Locally:** A self-contained, single-file web app. No servers, no account registration, and no cloud processing.
- **Privacy-First:** 100% of the conversion runs client-side inside your browser's memory. Your chats, prompts, and notes are never sent to external servers.
- **Smart Chapter Splitting:** - Auto-split by headings (`#` or `##`)
  - Auto-split by conversational turns (`User:` / `Assistant:`)
  - Package as a single continuous chapter
- **Android & Mobile Optimized:** Works directly inside mobile Chrome/Firefox on Android tablets and phones.
- **Standards-Compliant EPUB v3.0:** Generates valid EPUB packages featuring:
  - Clean responsive typography with e-ink friendly CSS
  - Formatted code blocks (`<pre><code>`) with syntax structure
  - Native Table of Contents (`nav.xhtml`)
  - Proper metadata tags (title, author, timestamp, unique UUID identifier)
- **Convenient Workflow:** - Optional toggle to prompt for save folder / directory
  - Auto-clearing input field to paste sequential chats quickly
  - Sanitized filenames that prevent mobile download manager hash errors

---

## Quick Start

### 1. Online (GitHub Pages)
Visit the live deployment at:  
👉 **`https://ramesh-2001-2100.github.io/chatpress/`**

1. Paste your copied chat or Markdown text into the content area.
2. Set your **Book Title** and **Author / Source**.
3. Choose your chapter splitting rule.
4. Click **Download EPUB**.
5. Open the downloaded file in your e-reader app of choice.

### 2. Local / Offline Use
1. Clone or download this repository:
   ```bash
   git clone https://github.com/ramesh-2001-2100/chatpress.git
   ```
2. Open `index.html` in any web browser.