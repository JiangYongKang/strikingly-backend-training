# Rails 邮件发送示例

演示如何在 Rails 应用中发送邮件。

## 特性

- ActionMailer 邮件发送
- 邮件模板支持
- 异步邮件发送
- 邮件预览功能

## 快速开始

### 安装依赖
```bash
bundle install
```

### 运行应用
```bash
rails server
```

### 发送邮件
```bash
rails console
# 在控制台中执行邮件发送代码
```

## 项目结构

```
├── app/
│   ├── mailers/      # 邮件发送器
│   └── views/        # 邮件模板
├── config/           # 配置文件
└── Gemfile           # 依赖管理
```

## 相关链接

- [ActionMailer 指南](https://guides.rubyonrails.org/action_mailer_basics.html)
