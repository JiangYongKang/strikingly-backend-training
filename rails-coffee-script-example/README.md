# Rails CoffeeScript 集成演示

演示如何在 Rails 项目中集成 CoffeeScript、Sass 和前端依赖管理。

## 特性

- CoffeeScript 支持
- Sass 样式预处理
- Yarn 包管理
- 资源管道集成

## 快速开始

### 安装依赖
```bash
bundle install
yarn install
```

### 运行应用
```bash
rails server
```

访问 [http://localhost:3000](http://localhost:3000) 查看效果。

## 项目结构

```
├── app/
│   └── assets/       # 静态资源
│       ├── javascripts/
│       └── stylesheets/
├── package.json      # Node.js 依赖
└── Gemfile           # Ruby 依赖
```

## 相关链接

- [CoffeeScript 文档](https://coffeescript.org/)
- [Sass 文档](https://sass-lang.com/)