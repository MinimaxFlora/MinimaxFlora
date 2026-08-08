<div align="center">

# 👋 Hi there, I'm MinimaxFlora

### 🦞 OpenWrt 爱好者 · 固件构建自动化 · 插件分发

[![OpenWrt](https://img.shields.io/badge/OpenWrt-24.10%20%7C%2025.12-00A98F?style=for-the-badge&logo=openwrt&logoColor=white)](https://openwrt.org)
![GitHub followers](https://img.shields.io/github/followers/MinimaxFlora?style=for-the-badge&color=blue)
![GitHub stars](https://img.shields.io/github/stars/MinimaxFlora?style=for-the-badge&color=yellow)
![Visitor](https://api.visitorbadge.io/api/visitors?path=MinimaxFlora&label=访客&countColor=%23263759&style=for-the-badge)

</div>

---

## 🧑💻 About Me

> 热爱折腾 OpenWrt 路由器生态，专注把「编译固件」和「安装插件」这两件事
> 做到**开箱即用**。相信好的工具应该让用户少操心，一键完成。

- 🔧 **固件构建**：云端自动化编译定制 OpenWrt 固件（x86 / Rockchip），官方源自动检测最新版本
- 📦 **插件分发**：插件按架构分类直接打包为 `.ipk` / `.apk`，随分支自动导入，无需手动安装
- 🚀 **自动化**：GitHub Actions 深度玩家，能脚本化的绝不动手

---

## 🗺️ 项目生态

```
        ┌───────────────────────────────────────────┐
        │              Firmware-Build               │
        │        一键触发 · 参数选好点一下就跑         │
        └───────────────┬───────────────────────────┘
                        │ 调用
        ┌───────────────▼───────────────────────────┐
        │          gh-action-imagebuilder            │
        │     GitHub Action · 云端构建 OpenWrt 固件   │
        └───────┬───────────────────────┬───────────┘
                │ 自动导入               │ 发布
        ┌───────▼───────────┐   ┌───────▼───────────┐
        │  Extras_Paclages  │   │  action-gh-release │
        │ ipk(24)/apk(25)   │   │  Release + 产物上传│
        │ 按架构分类存放      │   │  零依赖 · 功能对齐  │
        └───────────────────┘   └───────────────────┘
```

| 项目 | 说明 | 状态 |
| :--- | :--- | :--- |
| [**Firmware-Build**](https://github.com/MinimaxFlora/Firmware-Build) | 一键触发固件构建的工作流仓库，选好参数点一下就跑 | 🟢 活跃 |
| [**gh-action-imagebuilder**](https://github.com/MinimaxFlora/gh-action-imagebuilder) | GitHub Action：官方源直下 ImageBuilder 构建定制固件，自动检测 24.x/25.x 最新版 | 🟢 活跃 |
| [**Extras_Paclages**](https://github.com/MinimaxFlora/Extras_Paclages) | 第三方插件仓库：ipk/apk 分支按架构（x86_64 / aarch64_generic / aarch64_cortex-a53）直接存放插件包 | 🟢 活跃 |
| [**action-gh-release**](https://github.com/MinimaxFlora/action-gh-release) | GitHub Action：创建 Release 并上传产物，零依赖实现，功能对齐 softprops/action-gh-release | 🟢 活跃 |

> 💡 想加新插件？往 Extras_Paclages 对应分支的架构文件夹丢一个 `.ipk` / `.apk` 就行，构建时自动带上！

---

## 🛠️ Tech Stack

| 领域 | 技术 |
| :--- | :--- |
| 🖥️ 系统 | OpenWrt 24.10 / 25.12、Linux、Shell / Bash |
| 🤖 自动化 | GitHub Actions、CI/CD、Composite Action |
| 📦 打包 | opkg (ipk)、apk (OpenWrt 25.x)、makeself (兼容 .run) |
| 🧰 工具 | ImageBuilder、Docker、Git、Python、Node.js |

---

## 📊 GitHub Stats

<div align="center">

![MinimaxFlora's GitHub stats](https://github-readme-stats.vercel.app/api?username=MinimaxFlora&show_icons=true&theme=vue&count_private=true)
![Top Langs](https://github-readme-stats.vercel.app/api/top-langs/?username=MinimaxFlora&layout=compact&theme=vue)

</div>

---

## 📫 Contact

<div align="center">

[![GitHub](https://img.shields.io/badge/GitHub-MinimaxFlora-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/MinimaxFlora)
[![Issues](https://img.shields.io/badge/反馈-Issue-2ea44f?style=for-the-badge&logo=github)](https://github.com/MinimaxFlora/gh-action-imagebuilder/issues)

</div>

---

<div align="center">

**⭐ 如果这些项目对你有帮助，欢迎点个 Star 支持！**

**让 OpenWrt 更简单，让网络更自由 🚀**

</div>
