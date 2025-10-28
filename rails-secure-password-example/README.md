# Rails 安全密码验证演示

演示如何使用 Rails 的 `has_secure_password` 进行安全的密码验证。

## 特性

- 密码加密存储
- 密码确认验证
- 长度验证
- 安全的密码哈希

## 快速开始

### 安装依赖
```bash
bundle install
```

### 运行应用
```bash
rails server
```

### 运行测试
```bash
rails test
```

## 项目结构

```
├── app/
│   └── models/       # 用户模型
├── test/             # 测试文件
└── Gemfile           # 依赖管理
```

## 核心功能

- `has_secure_password`: 自动密码加密
- `validates_confirmation_of`: 密码确认验证
- `validates :password, length: { minimum: 6 }`: 密码长度验证

## 相关链接

- [Rails 安全密码文档](https://api.rubyonrails.org/classes/ActiveModel/SecurePassword/ClassMethods.html)