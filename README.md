# Web Tools Library

一个轻量、可扩展的网页工具库。使用原生 HTML、CSS 和 JavaScript 构建，无需安装依赖，适合本地运行和二次开发。

## Features

* **Standalone HTML tools**：每个工具都是独立的 HTML 文件。
* **Category navigation**：通过分类快速查找工具。
* **Search**：搜索工具名称、简介和分类。
* **Easy to extend**：手动修改首页配置即可新增工具和分类。
* **Local-first**：工具默认在浏览器本地运行，不依赖后端服务。

## Getting Started

1. 下载或克隆本仓库。
2. 打开 `index.html`。
3. 通过分类栏或搜索框查找工具。
4. 点击工具卡片进入对应页面。

部分工具可能受浏览器安全策略限制，具体要求请查看工具页面说明。

## Project Structure

```text
web-tools-library/
├── index.html
├── help.html
├── README.md
├── LICENSE
└── tools/
    └── ...
```

## Add a New Tool

1. 在 `tools/` 目录下新增一个独立的 HTML 文件。
2. 在 `index.html` 的 `tools` 数组中增加对应配置。
3. 如需新分类，在 `categories` 数组中添加分类名称。
4. 确保工具配置中的 `category` 与分类名称完全一致。
5. 在浏览器中测试工具链接和功能。

详细说明请查看 `help.html`。

## License

This project is licensed under the MIT License. See [LICENSE](LICENSE) for details.
