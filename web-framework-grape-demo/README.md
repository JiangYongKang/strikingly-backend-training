# Grape API 框架演示

Grape 是一个为 Ruby 设计的 RESTful API 框架，专注于构建优雅的 API 服务。

## 特性

- RESTful API 设计
- 自动 JSON 序列化
- 内置参数验证
- 支持版本控制
- 集成 Swagger 文档

## 快速开始

### 安装依赖
```bash
bundle install
```

### 运行应用
```bash
rackup
```

访问 [http://localhost:9292/api](http://localhost:9292/api) 查看 API 响应。

## 项目结构

```
├── application.rb    # API 定义文件
├── config.ru        # Rack 配置文件
├── Gemfile          # 依赖管理
└── README.md        # 项目说明
```

## API 端点

- `GET /api/` - 返回欢迎信息

## 代码说明

- `application.rb`: 定义 Grape API 类和端点
- `config.ru`: Rack 服务器启动配置

## 相关链接

- [Grape GitHub](https://github.com/ruby-grape/grape)
- [Grape 文档](https://github.com/ruby-grape/grape#readme)
