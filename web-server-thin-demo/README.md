# Thin Web 服务器演示

Thin 是一个轻量级的 Ruby Web 服务器，基于 EventMachine 构建。

## 特性

- 轻量级设计
- 基于 EventMachine
- 支持 WebSocket
- 易于配置

## 快速开始

### 安装依赖
```bash
bundle install
```

### 运行应用
```bash
rails server thin
# 或
thin start
```

访问 [http://localhost:3000](http://localhost:3000) 查看效果。

## 配置说明

- 支持 YAML 配置文件
- 可配置端口、超时等参数
- 支持守护进程模式

## 相关链接

- [Thin GitHub](https://github.com/macournoyer/thin)
- [Thin 文档](https://github.com/macournoyer/thin#readme)