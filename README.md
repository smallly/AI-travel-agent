# 🤖 AI 旅行规划助手 (AI Travel Planner)

一个基于 AI 的个性化智能旅行路线规划工具，旨在帮助用户快速、轻松地创建满足其独特需求的旅行计划。它致力于成为用户的“赛博旅伴”，让旅行体验从规划到分享都充满惊喜。

---

## ✨ 项目特色 (Features)

### 阶段一：旅行前 (Pre-trip) - 从“混乱灵感”到“个性化方案”
* **智能灵感聚合 (Inspiration Aggregator):** 支持从各平台（小红书、微信）分享链接、截图，自动提取关键信息，并汇集成一张专属的交互式“灵感地图”。
* **对话式行程规划 (Conversational Planning):** 用户可基于模糊感觉（如“想chill一点”）提出需求，AI即可生成一个可拖拽调整的动态行程框架，并贴心提供备选方案（Plan B）。

### 阶段二：旅行中 (During-trip) - 从“按部就班”到“动态响应”
* **情境感知与主动建议 (Context-Aware Suggestions):** 结合实时天气、地理位置、用户状态，像朋友一样主动提供动态建议，如“下午要下雨，附近的美术馆人不多，要去看看吗？”。
* **旅行氛围探测器 (Atmosphere Detector):** 根据用户心情（如“想找个安静看日落的地方”）推荐私藏地点，并提供景点的最佳拍照机位与构图建议。

### 阶段三：旅行后 (Post-trip) - 从“杂乱回忆”到“一键分享”
* **一键生成旅行回忆 (Memory Generator):** 可自动整理行程中的照片，一键生成图文并茂的旅行日志、短视频Vlog，或直接套用适配社交平台（小红书、朋友圈）的爆款模板。

## 🚀 技术栈 (Tech Stack)

* **前端**: `HTML5`, `CSS3`, `JavaScript` (未来计划使用 `Vue.js` 或 `React`)
* **后端**: `Python`, `Flask` (或 `Django`)
* **AI 模型**: 调用 OpenAI GPT-4 API (或其他大语言模型)
* **数据库**: `SQLite` (开发阶段) / `PostgreSQL` (生产环境)
* **部署平台**: `Vercel` (前端) / `Render` (后端)

## 🛠️ 如何本地运行 (Getting Started)

**1. 克隆仓库**
```bash
git clone [https://github.com/zoe/ai-travel-planner.git](https://github.com/zoe/ai-travel-planner.git)
cd ai-travel-planner
```

**2. (后端) 创建并激活虚拟环境**
```bash
python -m venv venv
source venv/bin/activate  # on Windows use `venv\Scripts\activate`
```

**3. (后端) 安装依赖**
```bash
pip install -r requirements.txt
```

**4. (后端) 配置环境变量**
* 复制 `.env.example` 文件为 `.env`。
* 在 `.env` 文件中填入你的 OpenAI API Key:
    ```
    OPENAI_API_KEY="sk-xxxxxxxxxxxxxxxxxxxx"
    ```

**5. 启动应用**
```bash
flask run
```
应用将在 `http://127.0.0.1:5000` 上运行。

## 📝 路线图 (Roadmap)

根据“反目标 (Anti-Goals)”中提到的原则，我们将聚焦核心“魔法功能”，分阶段进行开发。

-   [x] **v0.1:** 完成产品核心概念设计与技术选型。
-   [ ] **v0.2 (MVP): 聚焦“旅行前”核心体验**
    -   [ ] 实现`智能灵感聚合`与“灵感地图”功能。
    -   [ ] 实现`对话式行程规划`，生成基础的行程框架。
    -   [ ] 完成与大语言模型API的初步对接。
-   [ ] **v0.3: 拓展“旅行中”的动态体验**
    -   [ ] 开发`情境感知`功能，实现基于位置和时间的基础推荐。
    -   [ ] 增加用户账户系统，用于保存行程。
-   [ ] **v1.0及未来: 完善全链路体验**
    -   [ ] 开发`一键生成旅行回忆`功能。
    -   [ ] 优化AI建议的精准度和个性化水平。
    -   [ ] 探索并无缝整合预订功能。

## 🙌 贡献 (Contributing)

欢迎任何形式的贡献！如果你有好的想法或者发现了 Bug，请随时提交 Pull Request 或创建 Issue。

## 📄 许可证 (License)

本项目采用 [MIT License](LICENSE) 授权。

---
*Created with ❤️ by zoe*
