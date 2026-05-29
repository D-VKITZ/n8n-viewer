<div align="center">

![DEVKiTZ](https://img.shields.io/badge/DEVKiTZ-Module-ff6d5a?style=for-the-badge)
![Version](https://img.shields.io/badge/v1.0-ffb800?style=flat-square)
![License](https://img.shields.io/badge/License-MIT-ff6d5a?style=flat-square)
![Status](https://img.shields.io/badge/Status-Active-00ff88?style=flat-square)
![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=flat-square&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=flat-square&logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black)

# n8n Viewer

**Visual n8n Workflow Viewer for DEVKiTZ Ecosystem**

</div>

---

## Preview

```
+--------------------------------------------------------------+
|  n8n Viewer -- Workflow Visualizer                     [x]   |
|--------------------------------------------------------------|
|  Templates: 3815   [Tags v]   [Search]: __________  [Go]     |
|--------------------------------------------------------------|
|                                                              |
|  +----------+     +----------+     +----------+              |
|  | Trigger  |---->| HTTP Req |---->| IF Node  |              |
|  | Webhook  |     | GET /api |     | status=  |              |
|  +----------+     +----------+     +----+-----+              |
|                                    yes/ \no                  |
|                              +--------+ +--------+           |
|                              | Slack  | | Email  |           |
|                              | Notify | | Alert  |           |
|                              +--------+ +--------+           |
+--------------------------------------------------------------+
```

---

## Features

| Feature | Description |
|:--------|:------------|
| Visual Workflow Viewer | Drawflow-based node editor for n8n workflow visualization |
| 3815 Templates | Searchable library of community and official n8n templates |
| Drawflow Node-Editor | Interactive drag-and-drop node editor with connections |
| Tag Filter | Filter workflows by tags, categories and node types |
| Full-Text Search | Search across workflow names, descriptions and node configs |
| JSON Import/Export | Load and save n8n workflow JSON files directly |

---

## Tech Stack

| Technology | Purpose |
|:-----------|:--------|
| HTML5 | Semantic layout and Drawflow container |
| CSS3 | DkZ Design System with orange-amber theme |
| JavaScript ES6+ | Workflow parser and node renderer |
| Drawflow | Visual node-editor library |
| LocalStorage | Offline workflow persistence |

---

## Quick Start

```bash
git clone https://github.com/D-VKITZ/n8n-viewer.git
cd n8n-viewer
# Open index.html in your browser
```

---

<div align="center">

**DEVKiTZ Ecosystem**

[devkitz.eu](https://devkitz.eu) · [dkz.app](https://dkz.app) · [GitHub](https://github.com/D-VKITZ)

Built with the DkZ Design System -- `--accent: #fa1e4e` · `--bg: #060608`

</div>
