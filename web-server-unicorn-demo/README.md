# Unicorn Web 服务器演示

Unicorn 是基于 Unix 特性的多进程 Web 服务器，适合生产环境使用。

## 特性

- 多进程架构
- 自动进程管理
- 零停机重启
- 负载均衡

## 快速开始

### 安装依赖
```bash
bundle install
```

### 运行应用
```bash
unicorn -c config/unicorn.rb
```

访问 [http://localhost:8080](http://localhost:8080) 查看效果。

## 配置说明

主要配置项：
- `worker_processes`: 工作进程数量
- `listen`: 监听地址和端口
- `timeout`: 超时时间
- `pid`: PID 文件位置

## 相关链接

- [Unicorn GitHub](https://github.com/defunkt/unicorn)
- [Unicorn 文档](https://bogomips.org/unicorn/)