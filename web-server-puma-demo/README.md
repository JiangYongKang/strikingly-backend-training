# Puma Web 服务器演示

Puma 是一个简单、高并发的 HTTP 1.1 服务器，Rails 的默认应用服务器。

## 特性

- 基于线程的高并发处理
- Rails 内置默认服务器
- 支持多进程模式
- 内存效率高

## 快速开始

### 安装依赖
```bash
bundle install
```

### 运行应用
```bash
rails server
# 或
puma
```

访问 [http://localhost:3000](http://localhost:3000) 查看效果。

## 配置说明

配置文件位于 `config/puma.rb`，包含以下主要配置：

- `threads`: 线程池配置
- `workers`: 进程数量配置
- `port`: 监听端口
- `environment`: 运行环境

## 相关链接

- [Puma GitHub](https://github.com/puma/puma)
- [Puma 文档](https://puma.io/)