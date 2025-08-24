# SurgeRuleset

一个用于 [Surge](https://nssurge.com/) 的规则集仓库，主要用于分流配置、广告屏蔽、常用服务的访问优化。  
方便在 iOS / macOS 上快速导入和更新。

## 功能特色
- **国内直连**：国内常用网站和服务直连，避免不必要的代理。
- **国际加速**：Google、YouTube、ChatGPT、Telegram 等国外服务走代理。
- **广告拦截**：整合常见广告域名规则，提升使用体验。
- **可扩展**：支持自定义规则，灵活适配不同场景（回国 / 出国）。

## 文件结构
- `Direct.list` — 国内直连域名/IP 列表
- `Proxy.list` — 需要代理访问的域名/IP 列表
- `Reject.list` — 广告与追踪域名拦截列表
- `README.md` — 项目说明文档

## 使用方法
1. 在 Surge 配置文件中添加远程规则：
  