# Sidekiq 任务调度演示

Sidekiq 是高性能的 Ruby 后台任务处理库，基于 Redis。

## 特性

- 高性能多线程处理
- 基于 Redis 的队列
- 支持定时任务
- 丰富的监控功能

## 快速开始

### 安装依赖
```bash
bundle install
```

### 启动 Redis
```bash
redis-server
```

### 运行应用
```bash
rails server
```

### 启动 Sidekiq
```bash
sidekiq -C config/sidekiq.yml
```

## 项目结构

```
├── app/
│   └── workers/      # 后台任务处理器
├── config/           # 配置文件
└── Gemfile           # 依赖管理
```

## 相关链接

- [Sidekiq GitHub](https://github.com/mperham/sidekiq)
- [Sidekiq 文档](https://github.com/mperham/sidekiq/wiki)