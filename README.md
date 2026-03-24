# learn
这是渗透的开始

# 🔐 渗透测试问题驱动实战学习路线

> 从零开始，通过解决一个又一个实战问题，系统掌握渗透测试全流程。

本项目为你提供一套**问题驱动**的渗透学习方案，包含：

- 30 天详细实战日程（由总日程规划 `total_schedule.html` 呈现）
- 每日具体操作步骤、命令、截图模板
- 一个静态网站入口（`index.html`），双栏布局，左侧日程树，右侧动态加载每日内容
- 所有文件结构清晰，便于在 GitHub 上托管并随时更新

---

## 📁 项目结构
.
├── README.md # 本文件
├── index.html # 主入口页面（侧边栏+iframe）
├── total_schedule.html # 总日程规划（知识体系+30天大纲）
├── today_schedule.html # 今日详细任务（Day 1 环境搭建）
├── day1.html # （可选，可复制 today_schedule.html）
├── day2.html # 后续每日任务
├── ...
└── day30.html # 第30天总结

---

## 🚀 快速开始

1. 克隆本仓库到本地：
   ```bash
   git clone https://github.com/your-username/pentest-learning.git
   用浏览器打开 index.html，即可看到学习导航界面。

左侧“导航”区域点击“总日程规划”查看整体安排；点击“今日任务”开始 Day 1 的实战。

每天学习时，参考 total_schedule.html 中的主题，创建对应 dayX.html 文件，将详细步骤写入其中（可复制 today_schedule.html 作为模板）。左侧侧边栏已预置 Day 1~30 的链接，无需修改 index.html。

📅 学习路线（30天概览）
阶段	天数	核心主题	主要产出
环境搭建	1	虚拟化、Kali、Metasploitable 2	可通信的靶场
信息收集	2-3	Nmap、OSINT、子域名枚举	资产报告
漏洞发现	4-5	Nessus、Burp Suite、漏洞扫描	漏洞清单
漏洞利用	6-9	Metasploit、SQLi、文件上传	获取Shell
权限提升	10-12	Linux/Windows 提权	管理员权限
后渗透	13-16	隧道、横向移动、密码抓取	内网控制权
域渗透	17-19	域环境、Kerberoasting、黄金票据	域管理员
报告与高阶	20-30	报告编写、WAF绕过、代码审计、综合演练	渗透测试报告
详细每日安排请查看 total_schedule.html。

🛠️ 每日任务文件模板
创建新的一天（如 day2.html）时，建议包含以下内容：
<!DOCTYPE html>
<html>
<head>
    <meta charset="UTF-8">
    <title>Day X · 任务名称</title>
    <style>/* 与 today_schedule.html 相同样式 */</style>
</head>
<body>
    <h1>Day X · 任务名称</h1>
    <p><strong>核心问题</strong>：...</p>
    <h2>🎯 今日目标</h2>
    <ul>...</ul>
    <h2>⚙️ 实战步骤</h2>
    <h3>步骤 1 ...</h3>
    <pre><code>...</code></pre>
    <h2>✅ 验收清单</h2>
    <ul>...</ul>
    <h2>📚 扩展知识点</h2>
    <ul>...</ul>
</body>
</html>
样式可直接复制 today_schedule.html 中的 <style> 部分，保持视觉统一。

📌 注意事项
合法性：所有实验请在本机虚拟化环境（如 VMware）中进行，严禁对未授权目标进行扫描或攻击。

网络设置：确保 Kali 和靶机网络适配器均为 NAT 模式，以保证互通。

笔记记录：建议使用 Markdown 或本项目的笔记模板记录每日遇到的问题和解决方案。

🤝 贡献与反馈
如果你在实践过程中发现任何问题，或有改进建议，欢迎提交 Issue 或 Pull Request。

📄 许可证
本项目仅用于教育目的，内容遵循 MIT 许可证。

---

## 使用说明

1. 将上述 `README.md` 内容保存为仓库根目录下的同名文件。
2. 在 GitHub 上创建仓库，将 `index.html`、`total_schedule.html`、`today_schedule.html`、`README.md` 及后续 `dayX.html` 一同推送，即可通过 GitHub Pages 或直接查看本地文件。
3. 若要启用 GitHub Pages 在线访问，可在仓库设置中开启 Pages 功能，选择 `main` 分支的根目录即可。

现在你的项目文档已经完整，可以顺利在 GitHub 上展示了。如有其他需求，欢迎继续提问！
