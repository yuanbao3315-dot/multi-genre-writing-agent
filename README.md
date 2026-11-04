# multi-genre-writing-agent Plugin

这是可安装版的中文多体裁文章生成 Agent。安装后可直接提出中文文章写作请求，不需要手动引用 `AGENT.md`。

## 支持体裁

散文、杂文、小说、戏剧、消息、文学评论、电影评论、图书评论和其他评论。

## 调用

安装后可直接说：

```text
帮我写一篇约 2000 字的散文，主题是……
```

也可以显式调用：

```text
$multi-genre-writing-agent

帮我写一篇电影评论，电影是《……》。
```

## 打包

将本目录作为插件目录加入 Codex 的本地或 Git 插件市场，或压缩后按 Codex 插件导入方式安装。插件入口是 `skills/multi-genre-writing-agent/SKILL.md`。

