# ⚡ FlashDown - 多线程高速下载器

**目前版本1.0**

FlashDown 是一款基于 Java 开发的轻量级、多线程高速下载工具。它拥有现代化的暗色日志界面和极简的扁平化设计，支持文件分块并发下载

支持win10以上的系统

## ✨ 功能

- 🚀 **多线程分块下载**：支持自定义线程数 ***（最大支持128线程下载）***
- 📁 **自定义保存路径**：想下在哪就下在哪
- 🌌 **自定义文件名**：下载前自由指定保存的文件名
- 📊 **实时进度反馈**：**非常准确**的进度条，实时显示下载百分比与已下载大小
- 🟢 **免安装绿色版**：字面意思

## 🤔如何使用

1.去右侧的[release](https://github.com/Toushou-114514/FlashDown/releases/tag/FlashDown)下载*zip*文件

2.解压到你的电脑

3.打开文件夹你大概率会看见:

```
   文件夹
   FlashDown/
   ├── FlashDown.exe
   ├── FlashDown.jar
   └── jre/  (这是运行环境)
```

4.运行`.exe`文件即可打开工具

## 🖼️ 界面预览

> <img width="806.5" weight="592.5" alt="image" src="https://github.com/user-attachments/assets/2f065903-7990-4802-a9d3-0d0fa8c15382" />

> **虽然这个UI很烂，但是工具绝对好用，而且完全免费**

## ⚠️ 注意事项

服务器限制：本工具依赖目标服务器的 Range 请求支持。如果不支持，程序会自动降级为单线程下载。

连接数控制：请不要盲目将线程数拉到 128。过高的并发连接极易触发网站的防爬虫机制（如返回 429 Too Many Requests 或封禁 IP）。建议日常使用 16 - 32 线程。

文件覆盖：如果下载目录中存在同名文件，程序可能会直接覆盖（或清空）旧文件，请小心操作。




![Java](https://img.shields.io/badge/Java-17+-orange.svg)
![Platform](https://img.shields.io/badge/Platform-Windows-blue.svg)
![License](https://img.shields.io/badge/License-MIT-green.svg)

## 📄 许可证

[MIT](LICENSE)

---

> 觉得好用就给仓库点个star吧










