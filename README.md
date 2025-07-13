# Agno Docs 文档

## 开发

安装 [Mintlify CLI](https://www.npmjs.com/package/mintlify) 以在本地运行文档站点：

```
npm i -g mint
```

在你的文档根目录（即 `mint.json` 所在位置）下运行以下命令：

```
mint dev
```

## 发布更改

通过推送到主分支来发布更改：

```
git add .
git commit -m "update message"
git push
```

## 故障排除

- Mintlify 开发环境未运行 - 运行 `mint update` 来更新依赖项。
- 页面加载为 404 错误 - 确保你在包含 `docs.json` 的文件夹中运行。