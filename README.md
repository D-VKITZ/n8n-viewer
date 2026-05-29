![Module](https://img.shields.io/badge/DEVKiTZ-Module-ff6d5a?style=for-the-badge&labelColor=ffb800)
![Version](https://img.shields.io/badge/version-v1.0.0-ff6d5a?style=flat-square&labelColor=0d0d14)
![License](https://img.shields.io/badge/license-MIT-00ff88?style=flat-square&labelColor=0d0d14)
![Status](https://img.shields.io/badge/status-active-00ff88?style=flat-square&labelColor=0d0d14)
![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=flat-square&logo=html5&logoColor=white)
![Drawflow](https://img.shields.io/badge/Drawflow-Node_Editor-06b6d4?style=flat-square)

# n8n Workflow Viewer

> **Visual Workflow Editor with Drawflow** - Part of the [DEVKiTZ](https://github.com/D-VKITZ) Ecosystem

---

## Preview

```
+----------------------------------------------+
|  n8n Viewer          Search   Import Export   |
+----------+-----------------------------------+
| Templates|                                   |
| 3,815+   |  +------+    +------+   +------+  |
| -------- |  | HTTP |----> Code |---> Send |  |
| webhook  |  | Node |    | Node |   | Mail |  |
| schedule |  +------+    +------+   +------+  |
| ai_agent |                                   |
| postgres |  +------+    +------+             |
| openai   |  | Set  |----> Merge|             |
+----------+--+------+----+------+-------------+
```

## Features

| Status | Feature |
|:-------|:--------|
| Done | Drawflow Node-Editor ComfyUI-Style |
| Done | Template Browser with 3,815+ Templates |
| Done | Tag Filter with Top 12 Tags |
| Done | Full-Text Search by Name, Nodes, Tags |
| Done | JSON Import/Export for n8n and Drawflow |
| Done | Keyboard Shortcuts Ctrl+E/I/F |

## VPS Infrastructure

```
KVM8 (8 vCPU, 16 GB RAM)
+--------------------------------------------+
| nginx :443  --> dkz-n8n :5678              |
| dkz-ontherun :3040 (MCP Gateway)           |
| dkz-postgres :5432 (PostgreSQL 16)         |
| dkz-redis :6379 (AOF Persistence)          |
| vLLM :8811 (8 Models, GPU Inference)       |
| llama-swap :8080 (Model Router)            |
+--------------------------------------------+
```

## Quick Start

```bash
git clone https://github.com/D-VKITZ/n8n-viewer.git
open n8n-viewer/index.html
```

---

<p align="center">
<sub>DEVKiTZ - Made with love by 777 - 2026</sub><br>
<sub>devkitz.eu | dkz.app | github.com/D-VKITZ</sub>
</p>