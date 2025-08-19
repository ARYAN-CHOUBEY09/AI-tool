# Quick-Ask AI Chatbot

**Live Demo:** (https://ai-tool-plum.vercel.app/)

---

## Overview

**Quick-Ask** is a sleek AI-powered chatbot built with React and Tailwind CSS, deployed via Vercel. It lets users ask questions via text or voice and displays beautifully formatted answers—complete with markdown and code support. It also stores recent query history and features a responsive, animated mic button indicating voice input activity.

---

## Key Features

* **Voice & Text Input**
  Users can type their questions or click the mic icon—start speaking, and the answer is processed automatically.

* **Animated Mic Indicator**
  Clicking the mic triggers a visual animation, signaling recording is active—and stops when done.

* **Chat History**
  Previously asked questions are saved in `localStorage` and appear in a sidebar for quick repeat queries.

* **AI-Powered Responses**
  Answers are fetched using your configured AI backend and rendered with markdown—including code blocks via syntax highlighting.

* **Responsive UI**
  Designed to adjust seamlessly from mobile to desktop. Only vertical scrolling is used—no horizontal overflow.

---

## Tech Stack

| Purpose            | Tools/Libraries                       |
| ------------------ | ------------------------------------- |
| Frontend Framework | React, Tailwind CSS                   |
| Voice Recognition  | Web Speech API (`SpeechRecognition`)  |
| Markdown Rendering | `react-markdown` + custom `CodeBlock` |
| Deployment         | Vercel                                |

---

