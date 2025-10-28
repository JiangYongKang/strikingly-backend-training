# RSpec 测试框架演示

RSpec 是 Ruby 的企业级测试框架，提供丰富的测试功能和优雅的语法。

## 特性

- 行为驱动开发 (BDD)
- 丰富的匹配器
- 模拟和存根支持
- 详细的测试报告

## 快速开始

### 安装依赖
```bash
bundle install
```

### 运行测试
```bash
rspec
# 或
bundle exec rspec
```

## 项目结构

```
├── spec/             # 测试文件
│   ├── models/       # 模型测试
│   ├── controllers/  # 控制器测试
│   └── spec_helper.rb
├── app/              # 应用代码
└── Gemfile           # 依赖管理
```

## 相关链接

- [RSpec GitHub](https://github.com/rspec/rspec)
- [RSpec 文档](https://rspec.info/)