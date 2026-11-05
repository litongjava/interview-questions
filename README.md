# interview-questions

后端与前端面试题：基于 Java Tio-Boot、Go Hertz 的登录系统，以及 Cloudflare Workers 书签应用。

- 文档站：https://interview-questions.io.nexus/
- 拆分自 [tio-boot-docs](https://github.com/litongjava/tio-boot-docs)

## 本地开发

```bash
pnpm install
pnpm docs:dev
```

## 构建

```bash
pnpm docs:build
```

构建产物位于 `docs/.vitepress/dist`。

## 部署

推送到 `main` 分支后，Cloudflare Pages 会自动构建并发布。

## AI 语料

构建时生成：[llms.txt](https://interview-questions.io.nexus/llms.txt)、[llms-full.txt](https://interview-questions.io.nexus/llms-full.txt)、[ai/index.json](https://interview-questions.io.nexus/ai/index.json)、[ai/chunks.jsonl](https://interview-questions.io.nexus/ai/chunks.jsonl)，以及 `/ai/pages/<路径>.md` 的 Markdown 原文。
