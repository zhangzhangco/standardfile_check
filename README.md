# :clipboard: README GPT

README GPT 是一个可以帮助你自动生成 Github README 的工具。它使用了 Vercel 和 Next.js 框架来构建，支持多种主题和自定义选项，让你的项目文档更加美观和易懂。

## :rocket: 快速开始

首先，你需要在本地克隆项目：

```
git clone https://github.com/username/README-GPT.git
```

然后进入项目目录并安装依赖：

```
cd README-GPT
npm install
```

接下来，你可以直接运行项目：

```
npm run dev
```

在浏览器中打开 http://localhost:3000 即可访问。

## :gear: 自定义选项

README GPT 支持多种自定义选项，可以让你更加灵活地生成文档。以下是一些常用的选项：

- `title`：项目标题
- `description`：项目描述
- `author`：项目作者
- `license`：项目许可证
- `repoUrl`：项目仓库地址
- `imageUrl`：项目图片地址

你可以在 `config.js` 文件中修改这些选项，也可以在运行时通过 URL 参数进行修改。

## :art: 主题

README GPT 内置了多种主题，可以让你的文档更加美观。以下是一些常用的主题：

- `default`：默认主题
- `dark`：暗黑主题
- `light`：亮色主题

你可以在 `config.js` 文件中选择主题，也可以在运行时通过 URL 参数进行选择。

## :bulb: 贡献

如果你有任何建议或者 Bug 报告，欢迎在 Issues 中提出。如果你想贡献代码，可以 Fork 本项目并提交 Pull Request。

## :page_with_curl: 许可证

本项目基于 MIT 许可证开源。详细内容请查看 LICENSE 文件。
