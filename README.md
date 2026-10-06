# Signal Board

**Concept stage — nothing has been built yet.**

## Vision

Signal Board will be a desktop app that quietly collects metrics from **LinkedIn, X, GitHub, and Instagram**, then presents a short, cinematic daily wrap when you start your PC.

The wrap will show posts published, views, reposts, comments, likes, relevant GitHub activity, and money earned where supported.

The initial focus is simple trends, such as **"Views increased 40% compared with last week."**

- **Green:** an increase.
- **Red:** a decrease.
- **Yellow:** last month's average as a reference.

The goal is to understand your progress in one daily review, then get back to work.

## Proposed Tech Stack

| Technology | Purpose |
| --- | --- |
| Electron / Node.js | Desktop app, startup behavior, and background data collection. |
| React + TypeScript | Wrap interface and application logic. |
| [electron-vite](https://electron-vite.org/guide/) | Development tooling and builds. |
| [SQLite](https://www.sqlite.org/about.html) | Local metric history. |
| CSS | Styling and animations. |

Platform connections will use available APIs. Exact metrics and access requirements still need to be confirmed.
