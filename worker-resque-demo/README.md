# Resque 后台任务演示

Resque 是 GitHub 出品的 Ruby 后台任务处理库，基于 Redis。

## 特性

- 基于 Redis 的队列系统
- 支持多种队列类型
- 失败任务重试机制
- Web 管理界面

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

### 启动 Worker
```bash
QUEUE=* rake resque:work
```

## 项目结构

```
├── app/
│   └── jobs/         # 后台任务
├── config/           # 配置文件
└── Gemfile           # 依赖管理
```

## 相关链接

- [Resque GitHub](https://github.com/resque/resque)
- [Resque 文档](https://github.com/resque/resque#readme)