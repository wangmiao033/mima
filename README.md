# 密码管理系统

一个安全的公司内部账号密码管理系统，基于 Flask 和 PostgreSQL 构建。

## 功能特点

- 用户认证和授权
- 安全的密码存储
- 密码加密保护
- 响应式界面设计
- 支持多用户管理

## 技术栈

- Python 3.12
- Flask
- PostgreSQL
- SQLAlchemy
- Flask-Login
- Gunicorn
- Bootstrap 5

## 本地开发

1. 克隆仓库
```bash
git clone https://github.com/wangmiao033/mima.git
cd mima
```

2. 安装依赖
```bash
pip install -r requirements.txt
```

3. 设置环境变量
```bash
cp .env.example .env
# 编辑 .env 文件设置必要的环境变量
```

4. 运行应用
```bash
python app.py
```

## 部署

本项目可以直接部署到 Render.com：

1. Fork 这个仓库
2. 在 Render.com 创建新的 Web Service
3. 连接你的 GitHub 仓库
4. Render 会自动检测配置并部署

## 安全说明

- 所有密码都经过加密存储
- 使用 HTTPS 传输
- 实施了 CSRF 保护
- 实施了 XSS 保护
- 添加了安全响应头

## 许可证

MIT License 