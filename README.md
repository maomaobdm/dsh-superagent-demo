# dsh-superagent-demo

一个用来试 [`dsh-superagent`](https://github.com/deepseek-ai/dsh-superagent-prototype) 的演示仓库。

## 这个仓库是干什么的

它本身没有业务代码。存在的意义是给 dsh-superagent 一个真实的 GitHub 仓库：

- 让 dsh-superagent 有 issue 可以响应
- 让它有代码可以改、有分支可以推、有 PR 可以开
- 用来观察它在一个**干净、失败成本为零**的地方会怎么做

## 怎么用

1. 在本仓库开一个 issue，写清要做什么。
2. 在 issue 里 `@` 智能体账号，让它接这个活。
3. 它会读取需求、改代码、开 PR，并在原来的 issue 里回话。

也可以不 `@` 它——直接在一个新 issue 里写需求，只要该 issue 的作者在允许名单里，它就会看到。

## 给 dsh-superagent 的说明

`AGENTS.md` 是本仓库的规矩，智能体每次开工前先读它。本仓库目前还没有这个文件；
加上之后，它写下的规矩会覆盖智能体的默认行为。

## 目录

```
.
└── README.md    # 你正在看的这个
```

## 许可

没有许可证。这是一个私人演示仓库，按原样使用。