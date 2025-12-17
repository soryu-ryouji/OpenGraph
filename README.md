# Project Graph

基于 [Project Graph](https://github.com/graphif/project-graph) 项目的二次开发版

旨在去除遥测，并让其在某些方便更贴近 Ryouji 的使用习惯

1. 删除项目中 `.cursor`, `.vscode`, `.trae` 等 ide 的文件夹
2. 关闭项目签名，避免报错
3. 删除自动更新功能

## 自己编译项目

1. 环境配置

[Rust 官网](https://rust-lang.org/learn/get-started/) 安装 rust-init.exe

安装 pnpm 包管理器

```shell
scoop install pnpm
```

### 执行编译脚本

```shell
pnpm build
```

### 各平台差异
