# Sinatra Web 框架演示

Sinatra 是最轻量级的 Ruby Web 框架，只需几行代码就能启动一个 Web 服务器。

## 特性

- 极简设计，代码量少
- 快速启动和开发
- 灵活的路由系统
- 支持多种模板引擎

## 快速开始

### 安装依赖
```bash
bundle install
```

### 运行应用
```bash
ruby application.rb
```

访问 [http://localhost:4567](http://localhost:4567) 查看效果。

## 项目结构

```
├── application.rb    # 主应用文件
├── views/           # 视图模板
├── Gemfile          # 依赖管理
└── README.md        # 项目说明
```

## 代码示例

```ruby
require 'sinatra'
get '/' do
  'hello sinatra'
end
```

## 相关链接

- [Sinatra GitHub](https://github.com/sinatra/sinatra)
- [Sinatra 官方文档](http://www.sinatrarb.com/intro-zh.html)
