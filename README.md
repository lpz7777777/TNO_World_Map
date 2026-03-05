# TNO-Style Interactive World Map | TNO 风格交互式世界地图 🌐💻

![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)
![D3.js](https://img.shields.io/badge/D3.js-F9A03C?style=for-the-badge&logo=d3.js&logoColor=white)
![Wikidata](https://img.shields.io/badge/Wikidata-006699?style=for-the-badge&logo=wikidata&logoColor=white)

> **SYS.OP. DEFCON 3 | DATA MODE: HYBRID (LIVE + LOCAL) | CONNECTION: SECURE**

## 📖 English Introduction
A web-based, interactive geopolitical world map inspired by the UI aesthetic of the Hearts of Iron IV mod *"The New Order: Last Days of Europe" (TNO)*. It acts as an intelligence terminal, pulling real-time real-world data while presenting it in a dark, retro-CRT aesthetic with deep geopolitical flavor.

### ✨ Key Features
* **Retro Terminal UI:** Immersive CRT scanlines, neon-cyan aesthetics, custom VT323 font, and procedurally generated UI click sound effects (Web Audio API).
* **Live Geopolitical Data Integration:** Fetches real-time Head of State, Head of Government, flags, ruling parties, GDP, and Population via the Wikidata SPARQL API.
* **Dynamic Parliament Charts:** Renders legislative seat distributions using D3.js. It attempts to fetch live parliamentary data and smoothly falls back to rich local datasets if needed.
* **Bilingual Support:** Seamlessly switch between English and Simplified Chinese. Includes highly customized, TNO-style lore descriptions for 80+ major countries.
* **Highly Resilient:** Built-in multi-source proxies, CDN fallbacks, and a comprehensive local database ensure the map works flawlessly even in restricted network environments (e.g., heavily optimized for Chinese networks).

---

## 📖 中文介绍
这是一个受《钢铁雄心4》知名模组 **“The New Order (TNO)”** UI风格启发的交互式世界地图前端项目。它模拟了一个冷战/暗黑地缘政治风格的“情报终端”，以复古 CRT 显示器特效呈现真实世界的实时地缘政治数据。

### ✨ 核心特性
* **复古情报终端 UI：** 深度还原的 CRT 扫描线特效、霓虹青色调、VT323复古终端字体，配合 Web Audio API 动态生成的复古电子按键音效。
* **实时地缘政治网络：** 深度集成 Wikidata SPARQL API，点击国家即可实时拉取真实的国家元首、政府首脑、国旗、执政党徽、GDP与人口数据。
* **动态议会席位图表：** 使用 D3.js 动态绘制半圆形议会席位分布图。支持实时数据查询与详尽的本地备用数据无缝切换。
* **双语无缝切换：** 内置中英双语，一键切换。包含为全球 80 多个核心地缘热点国家专属定制的 TNO 风格暗黑现实主义描述文本。
* **高可用性与网络兜底：** 针对国内网络环境深度优化，拥有完善的 GeoJSON 镜像轮询、图片跨域代理池（Proxy）及全套本地数据兜底机制，断网或 API 失败时依然可秒开顺滑体验。

---

## 🚀 How to Run / 如何运行

This is a pure Front-End project with zero build dependencies. 
这是一个纯前端项目，零环境依赖，无需 npm install。

1. **Clone the repository / 克隆仓库:**
   ```bash
   git clone [https://github.com/lpz7777777/TNO_World_Map.git](https://github.com/lpz7777777/TNO_World_Map.git)
   
Open the file / 打开文件:
Directly double-click TNO_World_Map.html in your browser.
由于所有数据已完成跨域处理和单文件内嵌转换，你可以直接双击运行 TNO_World_Map.html，或使用 VS Code 的 Live Server 插件打开以获得最佳体验。

🛠 Tech Stack / 技术栈
Core: Vanilla JavaScript, HTML5, CSS3

Map & Visualization / 地图与可视化: D3.js (v7) using GeoJSON

Live Data Source / 实时数据源: Wikidata Query Service (SPARQL)

Fallback Data Source / 备用数据源: REST Countries API

📸 Screenshots / 界面截图

<img width="3028" height="1566" alt="image" src="https://github.com/user-attachments/assets/b142f943-8789-48b4-8117-56a5240c49de" />
<img width="3036" height="1568" alt="image" src="https://github.com/user-attachments/assets/62d14afa-add8-4186-a957-76544c1645c8" />


📜 License / 开源协议
This project is licensed under the MIT License.
本项目基于 MIT 协议开源。

Disclaimer: This project is a UI/UX technical demonstration and is not affiliated with the official Hearts of Iron IV or the TNO mod development team. The local textual descriptions are written for aesthetic purposes inspired by the mod's tone.
免责声明：本项目为 UI/UX 技术展示，与《钢铁雄心4》或 TNO 模组官方制作组无关。内置的国家描述文本仅为契合 TNO 风格的艺术加工，不代表任何政治立场。
