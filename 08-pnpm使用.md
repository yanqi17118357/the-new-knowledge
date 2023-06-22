## pnpm

将依赖下载到指定的磁盘，该磁盘使用到依赖会从里面找，避免了多个项目重复安装依赖的情况

## 安装

```shell
npm install -g pnpm

pnpm config get registry

pnpm set registry https://registry.npm.taobao.org

pnpm config set store-dir D:/.pnpm-store

# 获取当前仓库地址（仓库不允许跨磁盘）
pnpm store path

# 从store中删除当前未被引用的包释放空间
pnpm store prune

```

