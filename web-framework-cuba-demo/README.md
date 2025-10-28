# Cuba Web 框架演示

Cuba 是一个轻量级的 Ruby Web 框架，专注于简洁和性能。

## 特性

- 极简设计，代码量少
- 高性能，启动快速
- 基于 Rack 标准
- 支持路由和中间件

## 快速开始

### 安装依赖
```bash
bundle install
```

### 运行应用
```bash
rackup
```

访问 [http://localhost:9292](http://localhost:9292) 查看效果。

## 项目结构

```
├── application.rb    # 主应用文件
├── config.ru        # Rack 配置文件
├── Gemfile          # 依赖管理
└── README.md        # 项目说明
```

## 代码说明

- `application.rb`: 定义 Cuba 应用和路由
- `config.ru`: Rack 服务器启动配置

## 相关链接

- [Cuba GitHub](https://github.com/soveran/cuba)
- [Cuba 文档](https://cuba.is/)
