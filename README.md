# Mihomo 配置文件

个人 Mihomo (Clash Meta) 代理配置，配合 Sub-Store 使用。

## 文件说明

| 文件 | 用途 |
|------|------|
| `mihomo.yaml` | 主配置文件，包含代理组、DNS、分流规则等 |
| `rules.yaml` | Sub-Store 脚本操作用的规则模板 |
| `mihomo配置.json` | Sub-Store 配置文件模板 |
| `sub-store组合订阅模板.json` | Sub-Store 组合订阅配置 |

## 功能特性

- 多地区节点自动选择（香港、台湾、日本、韩国、新加坡、美国、英国、法国、德国）
- 智能分流规则（AI 服务、流媒体、社交媒体、游戏平台、云服务等）
- 广告拦截
- Fake-IP 模式 DNS
- 自动更新 GeoIP/GeoSite 数据

## 代理端口

- HTTP: 7890
- SOCKS5: 7891

## 使用方式

1. 将 `mihomo.yaml` 中的 `proxy-providers.组合订阅.url` 替换为你的订阅链接
2. 导入 Mihomo 客户端使用
