# Ruby Rack 演示

Rack 是 Ruby Web 应用与应用服务器之间的接口标准。

## 特性

- Web 应用与服务器间的标准接口
- 中间件支持
- 兼容多种 Web 服务器
- 简洁的 API 设计

## 快速开始

### 安装依赖
```bash
bundle install
```

### 运行应用
```bash
ruby rack_basic.rb
# 或
rackup
```

访问 [http://localhost:8080](http://localhost:8080) 查看效果。

## 项目结构

```
├── rack_basic.rb     # 基础 Rack 应用
├── rack_middleware.rb # 中间件示例
├── rack_routes.rb    # 路由示例
└── Gemfile           # 依赖管理
```

## 相关链接

- [Rack GitHub](https://github.com/rack/rack)
- [Rack 文档](https://github.com/rack/rack#readme)