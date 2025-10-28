# Ruby 后端培训项目集合

这是一个综合性的 Ruby 后端技术学习项目集合，涵盖了从基础概念到高级应用的各个方面。每个子项目都专注于特定的技术领域，提供了完整的示例代码和详细的使用说明。

## 📚 项目概览

| 项目名称 | 描述 | 技术栈 | 状态 |
|:--|:--|:--|:--|
| [constant-lookup-example](./constant-lookup-example) | Ruby 常量查找机制详解 | Ruby | ✅ 完成 |
| [nginx-install-process](./nginx-install-process) | Nginx 安装与配置指南 | Nginx | ✅ 完成 |
| [ruby-rack-demo](./ruby-rack-demo) | Rack 中间件框架演示 | Ruby, Rack | ✅ 完成 |
| [unit-test-framework-mini-test-demo](./unit-test-framework-mini-test-demo) | MiniTest 单元测试框架 | Ruby, MiniTest | ✅ 完成 |
| [unit-test-framework-rspec-demo](./unit-test-framework-rspec-demo) | RSpec 企业级测试框架 | Ruby, RSpec, Rails | ✅ 完成 |
| [web-framework-cuba-demo](./web-framework-cuba-demo) | Cuba 轻量级 Web 框架 | Ruby, Cuba | ✅ 完成 |
| [web-framework-grape-demo](./web-framework-grape-demo) | Grape RESTful API 框架 | Ruby, Grape | ✅ 完成 |
| [web-framework-rails-demo](./web-framework-rails-demo) | Rails 全栈 Web 框架 | Ruby, Rails | ✅ 完成 |
| [web-framework-sinatra-demo](./web-framework-sinatra-demo) | Sinatra 轻量级 Web 框架 | Ruby, Sinatra | ✅ 完成 |
| [web-server-puma-demo](./web-server-puma-demo) | Puma 应用服务器 | Ruby, Puma, Rails | ✅ 完成 |
| [web-server-rainbows-demo](./web-server-rainbows-demo) | Rainbows 多线程服务器 | Ruby, Rainbows | ✅ 完成 |
| [web-server-thin-demo](./web-server-thin-demo) | Thin 轻量级 Web 服务器 | Ruby, Thin, Rails | ✅ 完成 |
| [web-server-unicorn-demo](./web-server-unicorn-demo) | Unicorn 多进程服务器 | Ruby, Unicorn | ✅ 完成 |
| [worker-resque-demo](./worker-resque-demo) | Resque 后台任务调度 | Ruby, Resque, Redis | ✅ 完成 |
| [schedule-sidekiq-example](./schedule-sidekiq-example) | Sidekiq 任务调度框架 | Ruby, Sidekiq, Redis | ✅ 完成 |
| [yarn-quick-start-demo](./yarn-quick-start-demo) | Yarn 包管理器快速入门 | Node.js, Yarn | ✅ 完成 |
| [rails-coffee-script-example](./rails-coffee-script-example) | Rails 中 CoffeeScript 集成 | Ruby, Rails, CoffeeScript | ✅ 完成 |
| [rails-email-example](./rails-email-example) | Rails 邮件发送功能 | Ruby, Rails, ActionMailer | ✅ 完成 |
| [rails-secure-password-example](./rails-secure-password-example) | Rails 安全密码验证 | Ruby, Rails, BCrypt | ✅ 完成 |

## 🚀 快速开始

### 环境要求
- Ruby 2.5+ 
- Rails 5.1+
- Node.js 8+
- Redis (用于后台任务)

### 安装依赖
```bash
# 安装 Ruby 依赖
bundle install

# 安装 Node.js 依赖
yarn install
```

## 📖 学习路径建议

### 1. 基础阶段
- **Ruby 基础**: `constant-lookup-example` - 理解 Ruby 常量查找机制
- **Web 基础**: `ruby-rack-demo` - 掌握 Rack 中间件概念
- **测试基础**: `unit-test-framework-mini-test-demo` - 学习单元测试

### 2. Web 框架阶段
- **轻量级框架**: `web-framework-sinatra-demo` - 快速上手 Web 开发
- **API 框架**: `web-framework-grape-demo` - 构建 RESTful API
- **全栈框架**: `web-framework-rails-demo` - 完整的 Web 应用开发

### 3. 服务器与部署阶段
- **应用服务器**: `web-server-puma-demo`, `web-server-unicorn-demo`
- **反向代理**: `nginx-install-process`
- **多线程服务器**: `web-server-rainbows-demo`

### 4. 高级功能阶段
- **后台任务**: `worker-resque-demo`, `schedule-sidekiq-example`
- **前端集成**: `rails-coffee-script-example`, `yarn-quick-start-demo`
- **安全功能**: `rails-secure-password-example`
- **邮件功能**: `rails-email-example`

## 🛠️ 技术栈详解

### 后端技术
- **Ruby**: 主要编程语言
- **Rails**: 全栈 Web 框架
- **Sinatra**: 轻量级 Web 框架
- **Grape**: RESTful API 框架
- **Cuba**: 极简 Web 框架

### 服务器技术
- **Puma**: 多线程应用服务器
- **Unicorn**: 多进程应用服务器
- **Thin**: 轻量级 Web 服务器
- **Rainbows**: 多线程服务器
- **Nginx**: 反向代理服务器

### 测试框架
- **RSpec**: 企业级测试框架
- **MiniTest**: Ruby 内置测试框架

### 后台任务
- **Resque**: GitHub 出品的任务队列
- **Sidekiq**: 高性能任务调度框架

### 前端技术
- **CoffeeScript**: JavaScript 预处理器
- **Sass**: CSS 预处理器
- **Yarn**: 包管理器

## 📝 项目特色

1. **循序渐进**: 从基础概念到高级应用，适合不同水平的学习者
2. **实用性强**: 每个项目都包含完整的示例代码和详细说明
3. **技术全面**: 覆盖了 Ruby 后端开发的各个方面
4. **文档详细**: 每个子项目都有独立的 README 文档

## 🤝 贡献指南

欢迎提交 Issue 和 Pull Request 来改进这个项目！

## 📄 许可证

本项目采用 MIT 许可证。

## 🔗 相关链接

- [Ruby 官方网站](https://www.ruby-lang.org/)
- [Rails 官方网站](https://rubyonrails.org/)
- [RSpec 官方网站](https://rspec.info/)
- [Sidekiq 官方网站](https://sidekiq.org/)

---

**注意**: 这是一个学习项目集合，每个子项目都可以独立运行和学习。建议按照学习路径逐步进行，以获得最佳的学习效果。