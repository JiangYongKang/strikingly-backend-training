# MiniTest 测试框架演示

MiniTest 是 Ruby 内置的测试框架，轻量级且功能完整。

## 特性

- Ruby 内置测试框架
- 轻量级设计
- 支持多种测试风格
- 无需额外依赖

## 快速开始

### 安装依赖
```bash
bundle install
```

### 运行测试
```bash
ruby test_meme.rb
# 或
ruby test_meme_specs.rb
```

## 项目结构

```
├── meme.rb           # 被测试的类
├── test_meme.rb      # 测试文件
├── test_meme_specs.rb # 规格测试文件
└── Gemfile           # 依赖管理
```

## 相关链接

- [MiniTest 文档](https://docs.ruby-lang.org/en/2.0.0/MiniTest.html)