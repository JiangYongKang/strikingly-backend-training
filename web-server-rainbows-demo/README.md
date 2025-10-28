# Rainbows Web 服务器演示

Rainbows 是多线程 Web 服务器，与 Unicorn 出自同一作者。

## 特性

- 多线程架构
- 与 Unicorn 配置兼容
- 支持多种并发模型
- 高 IO 并发处理

## 快速开始

### 安装依赖
```bash
bundle install
```

### 运行应用
```bash
rainbows -c config/rainbows.rb
```

访问 [http://localhost:8080](http://localhost:8080) 查看效果。

## 配置说明

- 支持多种并发模型
- 可配置线程和进程数量
- 与 Unicorn 配置格式兼容

## 相关链接

- [Rainbows GitHub](https://github.com/rosylilly/rainbows)
- [Rainbows 文档](https://bogomips.org/rainbows/)