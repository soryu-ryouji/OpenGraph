# Open Graph

基于 [Project Graph](https://github.com/graphif/project-graph) 项目的二次开发版

旨在去除遥测，并让其在某些方便更贴近 Ryouji 的使用习惯

1. 删除项目中 `.cursor`, `.vscode`, `.trae` 等 ide 的文件夹
2. 关闭项目签名，避免报错
3. 删除自动更新功能
4. 删除 AI 相关功能
5. 删除非功能界面

## 自己编译项目

```shell
# 安装 rust
scoop install rustup
# 安装 pnpm 包管理器
scoop install pnpm

# 下载项目依赖
pnpm install
# 编译项目
pnpm run build:ci
```

### 各平台差异
