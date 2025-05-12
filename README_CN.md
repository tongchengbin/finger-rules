# 指纹规则库 | Finger-Rules

<p align="center">
  <img src="https://img.shields.io/github/license/tongchengbin/finger-rules" alt="License">
  <img src="https://img.shields.io/github/stars/tongchengbin/finger-rules?style=social" alt="Stars">
  <img src="https://img.shields.io/github/forks/tongchengbin/finger-rules?style=social" alt="Forks">
</p>

[English](README.md) | [中文](README_CN.md)

## 简介

Finger-Rules 是一个全面的开源网络应用指纹规则库，用于识别各种网络技术。它包含了各种网络技术的检测规则，包括网络服务器、内容管理系统、框架、Web应用防火墙、网络设备等。

该规则库设计用于与 [AppFinger](https://github.com/tongchengbin/appfinger) 配合使用，AppFinger 是一个多协议指纹匹配工具，可帮助安全研究人员和渗透测试人员识别网络应用程序使用的技术。

## 特点

- **广泛覆盖**：包含数千种网络技术和应用程序的规则
- **多协议支持**：包括 HTTP、FTP、SSH 等多种协议
- **定期更新**：持续维护并添加新的指纹
- **易于使用**：简单的 YAML 格式，便于贡献和集成
- **高准确性**：精确的匹配模式，最小化误报

## 规则类别

- Web 应用防火墙 (WAF)
- 内容管理系统 (CMS)
- Web 框架
- Web 服务器
- 网络设备（路由器、交换机等）
- 物联网设备
- 云服务
- 更多...

## 使用方法

这些规则设计用于与 [AppFinger](https://github.com/tongchengbin/appfinger) 配合使用。使用方法：

1. 克隆此仓库
2. 使用 AppFinger 的 `-d` 参数指定规则目录：

```bash
appfinger -u https://example.com -d /path/to/finger-rules
```

## 贡献

欢迎贡献！贡献方法：

1. Fork 此仓库
2. 为您的功能创建一个新分支
3. 按照现有格式添加或修改规则
4. 提交拉取请求

## 许可证

本项目采用 MIT 许可证 - 详情请参阅 LICENSE 文件。
