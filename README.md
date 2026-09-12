# -- 全局占位符：将 {SITE_URL} 替换为正式站点地址 -->（Java）— 完整源码 + 数据库脚本 + 运行说明
# 基于Java的网上体育用品商城-带论文

本商品为「基于Java的网上体育用品商城-带论文」，基于 JSP+Servlet 技术栈开发。

## 👉 完整项目 / 演示录屏 / 更多项目：{SITE_URL}

## ✨ 功能清单

- 详见源码目录与数据库脚本

## 🛠 技术栈

- 技术栈信息见项目构建文件

## 📁 目录结构

```
ji-yu-java-de-wang-shang-ti-yu-yong-pin-shang-cheng-dai-jspservlet/
├── db/
│   └── tyypsc.sql
├── docs/
│   ├── DESENSITIZE.md
│   └── REVIEW.md
└── 运行必读.txt
```

## 🚀 快速开始

### 环境要求
- JDK 1.8+（以 `pom.xml` 为准）
- Maven 3.x
- MySQL 5.7+ / 8.x

### 步骤
1. 克隆本仓库
2. 用 IDE 打开项目根目录（含 `pom.xml` / `package.json`）
3. 导入 `db/` 或根目录下的 `*.sql` 到 MySQL
4. 修改 `src/main/resources/application.yml`（或 `.properties`）中的数据库账号密码
5. 启动主启动类（`*Application.java`）或执行 `mvn spring-boot:run`
6. 浏览器访问 `http://localhost:8080`

### 端口
- `8080`

### 账号
- 购物前需要登录，如果没有账号则可以先注册
- 用户登录功能：通过账号登录系统。
- 修改登录密码功能：修改管理员的登录密码
- 系统账号信息
- 账号：wxl
- 密码：12345
- 账号：admin
- 密码：77777

## ❓ 常见问题

**跑不起来？**
- 确认 JDK / Maven / MySQL 版本与运行必读一致；先能编译通过再启动。

**端口占用？**
- 修改 `server.port`，或关闭占用 8080 的进程。

**数据库连接失败？**
- 检查库名是否已创建、账号密码、时区与 `allowPublicKeyRetrieval` 等 JDBC 参数。

## 📚 更多开源项目

完整清单见仓库内 [`PROJECTS.md`](./PROJECTS.md)。

## 免责声明与许可

- 本仓库仅供学习交流，不包含商业授权。
- 源码来源于教学/毕设实践整理，使用风险自负。
- 转载请注明出处；请勿用于非法用途。
- 详见 [`LICENSE`](./LICENSE)。

---

**更多完整项目 → {SITE_URL}**