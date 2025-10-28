# Ruby 常量查找机制演示

深入理解 Ruby 中常量的查找顺序和机制。

## 特性

- 模块常量查找顺序
- 嵌套模块访问
- 继承链中的常量查找
- 单例类常量访问

## 快速开始

### 运行示例
```bash
ruby constant_seach_1.rb
ruby constant_seach_2.rb
# ... 其他示例文件
```

## 项目结构

```
├── constant_seach_1.rb   # 模块查找顺序
├── constant_seach_2.rb   # 访问嵌套模块
├── constant_seach_3.rb   # 访问超类模块
├── constant_seach_4.rb   # 超类访问子类模块
├── constant_seach_5.rb   # 顶层模块附加
├── constant_seach_6.rb   # class_eval
├── constant_seach_7.rb   # class_eval
├── constant_seach_8.rb   # 单例类访问
├── constant_seach_9.rb   # 单例类继承链
└── constant_seach_10.rb  # 嵌套子类访问
```

## 学习要点

- 常量查找遵循特定的优先级规则
- 理解 `Module.nesting` 的作用
- 掌握不同上下文中的常量访问

## 相关链接

- [常量查找参考](http://cirw.in/blog/constant-lookup)