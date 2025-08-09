# 🤖 AI 旅行规划助手 (AI Travel Planner)

一个基于 AI 的个性化智能旅行路线规划工具，旨在帮助用户快速、轻松地创建满足其独特需求的旅行计划。

---

## ✨ 项目特色 (Features)

* **个性化推荐**: 根据用户的兴趣（如美食、历史、自然风光）、预算和时间来生成目的地和活动建议。
* **智能路线规划**: 自动规划每日最优路线，减少交通时间和成本。
* **动态行程调整**: 可以根据天气变化或突发状况，实时调整行程。
* **多语言支持**: 计划支持中文和英文界面及输出。

## 🚀 技术栈 (Tech Stack)

* **前端**: `HTML5`, `CSS3`, `JavaScript` (未来计划使用 `Vue.js` 或 `React`)
* **后端**: `Python`, `Flask` (或 `Django`)
* **AI 模型**: 调用 OpenAI GPT-4 API (或其他大语言模型)
* **数据库**: `SQLite` (开发阶段) / `PostgreSQL` (生产环境)
* **部署平台**: `Vercel` (前端) / `Render` (后端)

## 🛠️ 如何本地运行 (Getting Started)

**1. 克隆仓库**
```bash
git clone [https://github.com/YourUsername/your-repo-name.git](https://github.com/YourUsername/your-repo-name.git)
cd your-repo-name
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

- [x] 完成项目初步构想和技术选型
- [ ] 开发核心的用户输入界面 (UI)
- [ ] 对接大语言模型 API 实现基本规划功能
- [ ] 增加用户账户系统和历史行程保存功能
- [ ] ……

## 🙌 贡献 (Contributing)

欢迎任何形式的贡献！如果你有好的想法或者发现了 Bug，请随时提交 Pull Request 或创建 Issue。

## 📄 许可证 (License)

本项目采用 [MIT License](LICENSE) 授权。

---
*Created with ❤️ by [zoe]*
