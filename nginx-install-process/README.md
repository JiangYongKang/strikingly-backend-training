# Nginx 安装配置指南

Nginx 是一个高性能的 Web 服务器和反向代理服务器。

## 特性

- 高性能、低内存占用
- 反向代理和负载均衡
- 静态文件服务
- SSL/TLS 支持

## 安装方法

### 使用 Homebrew (macOS)
```bash
brew install nginx
```

### 启动服务
```bash
brew services start nginx
# 或
nginx
```

## 配置说明

- 默认端口: 8080
- 配置文件: `/usr/local/etc/nginx/nginx.conf`
- 网站根目录: `/usr/local/var/www`
- 服务器配置: `/usr/local/etc/nginx/servers/`

## 常用命令

```bash
nginx -s quit    # 退出
nginx -s reload  # 重新加载配置
nginx -t         # 测试配置文件
```

## 相关链接

- [Nginx 官方网站](https://nginx.org/)
- [Nginx 文档](https://nginx.org/en/docs/)