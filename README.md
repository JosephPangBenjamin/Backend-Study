# NestJS 全栈开发学习系统

这是一个使用AI驱动的交互式学习环境，帮助前端开发者转型全栈，掌握NestJS后端开发。

**学习目标**: 1个月内从零基础到能独立开发NestJS应用程序

---

## 为什么用这个系统？

这个系统帮助通过**实战驱动**的方式学习NestJS：

- **对话式学习** - 像和导师交流一样自然提问
- **苏格拉底方法** - 先问你知道什么，再构建新知识
- **个性化追踪** - 记录每次学习的详细进度
- **知识缺口识别** - 自动识别薄弱环节并优先解决
- **实战为主** - 在代码中理解理论，而非死记硬背

---

## 学习方法

### 每日学习流程

1. **开始学习** - 打开OpenCode，开始自然对话
2. **提问探索** - 询问任何NestJS/TypeScript相关问题
3. **理解验证** - 回答理解检查问题
4. **实战练习** - 编写代码验证概念
5. **自动记录** - 自动记录学习会话和进度

### 学习原则

**✅ DO:**
- 提出任何问题，不管多简单
- 先动手写代码，再理解原理
- 参考官方文档和示例
- 遇到问题立即搜索解决

**❌ DON'T:**
- 试图一次性理解所有概念
- 只看不写代码
- 被错误卡住太久（搜索、提问、继续）
- 完美主义，先跑起来再说

---

## 项目结构

```
/sessions/                    # 每日学习会话记录
  /2025-12-28/              # 按日期组织的会话
    session-notes.md
  SESSION-TEMPLATE.md        # 会话记录模板

/progress/                    # 单一真相源追踪器
  nestjs-learning-tracker.md  # 全面的学习进度追踪器

/projects/                    # 实战项目（后续创建）
  /hello-world-api/
  /todo-api/
  /user-auth-system/

OPENCODE.md                   # AI导师配置（针对OpenCode）
README.md                     # 本文件
```

---

## 4周学习计划

### 第1周：基础搭建（TypeScript + Node.js）
- **目标**: 从前端思维转到后端，掌握TypeScript
- **实战**: Hello World API
- **关键概念**: TypeScript基础、装饰器、依赖注入、Module/Controller/Service

### 第2周：RESTful API开发
- **目标**: 掌握标准API开发模式
- **实战**: Todo API (CRUD)
- **关键概念**: Controllers、Services、DTOs、验证、错误处理

### 第3周：数据库集成
- **目标**: 连接真实数据库，数据持久化
- **实战**: Todo API + PostgreSQL
- **关键概念**: ORM (TypeORM/Prisma)、Entity、Repository、数据库设计

### 第4周：企业级功能
- **目标**: 掌握认证、部署等生产级功能
- **实战**: 用户认证系统
- **关键概念**: JWT认证、Guards、中间件、测试、部署

---

## 核心学习主题 (25个)

### TypeScript基础 (2个)
- TS.1 TypeScript基础（类型、接口、类）
- TS.2 装饰器（Decorators）

### Node.js基础 (2个)
- Node.1 模块系统（CommonJS vs ES Modules）
- Node.2 异步编程（Promise, async/await）

### NestJS核心 (10个)
- Nest.1 NestJS核心概念（Module, Controller, Service）
- Nest.2 依赖注入
- Nest.3 Controllers详解
- Nest.4 Services和业务逻辑
- Nest.5 DTOs和验证
- Nest.6 异常处理和过滤器
- Nest.7 数据库模块集成
- Nest.8 Guards和认证
- Nest.9 中间件和拦截器
- Nest.10 环境配置

### 数据库和ORM (3个)
- DB.1 数据库基础
- ORM.1 ORM概念
- ORM.2 Entity关系
- ORM.3 Repository模式

### 认证和授权 (1个)
- Auth.1 JWT原理和实现

### 测试和部署 (2个)
- Test.1 单元测试基础
- Deploy.1 部署到生产环境

---

## 实战项目

### Project.1: Hello World API ⭐
**难度**: 入门
**技术点**: NestJS基础、控制器
**功能**: 实现简单的GET端点，返回JSON响应

### Project.2: Todo API (CRUD) ⭐⭐
**难度**: 初级
**技术点**: Controllers, Services, DTOs, 验证
**功能**: 完整的Todo CRUD API

### Project.3: Todo API + 数据库 ⭐⭐⭐
**难度**: 中级
**技术点**: ORM, 数据库设计, Repository
**功能**: Todo API + PostgreSQL持久化

### Project.4: 用户认证系统 ⭐⭐⭐⭐
**难度**: 高级
**技术点**: JWT, Guards, 密码加密, 认证流程
**功能**: 用户注册、登录、权限控制

---

## 如何使用

### 开始学习

1. **打开OpenCode**
    ```bash
    cd /home/joseph/work/nestjs-study
    ```

2. **开始对话**
    - 直接提问："什么是NestJS的模块？"
    - 或："帮我创建一个简单的API端点"
    - 或："我不理解依赖注入的概念"

3. **AI会**:
    - 先询问你的现有知识
    - 提供简洁的解释（~200字）
    - 检查你的理解
    - 引导你完成实战练习

4. **学习会话自动记录**在 `/sessions/` 目录

### 查看进度

查看详细的学习追踪器：
```bash
cat progress/nestjs-learning-tracker.md
```

查看今日会话记录：
```bash
cat sessions/2025-12-28/session-notes.md
```

---

## 前端开发者转型提示

### 思维转换要点

**1. 从UI到API**
- ❌ 前端：关注DOM、组件、用户交互
- ✅ 后端：关注数据、逻辑、API设计

**2. 从客户端到服务端**
- ❌ 前端：运行在浏览器，单用户
- ✅ 后端：运行在服务器，多用户并发

**3. TypeScript使用差异**
- ❌ 前端：类型可以宽松，依赖IDE提示
- ✅ 后端：类型严格，API契约必须明确

**4. 异步编程**
- ❌ 前端：主要是fetch、事件监听
- ✅ 后端：大量的数据库查询、文件操作、HTTP请求

### 快速上手技巧

1. **先跑起来**: `npm run start`，看控制台输出
2. **用Postman测试**: 不要只看代码，发送真实请求
3. **看日志**: `console.log`是你的好朋友
4. **参考官方示例**: NestJS官方示例是最好的参考
5. **善用搜索**: 遇到错误直接复制错误信息搜索

---

## 推荐学习资源

### 官方文档
- [NestJS官方文档](https://docs.nestjs.com/) - 必读，从First Steps开始
- [TypeScript官方文档](https://www.typescriptlang.org/docs/) - 查阅语法
- [Node.js官方文档](https://nodejs.org/docs/) - 理解运行时

### 视频教程
- [NestJS官方教程](https://www.youtube.com/results?search_query=nestjs+tutorial) - YouTube搜索
- [Traversy Media - NestJS Crash Course](https://www.youtube.com/watch?v=GHTA111_bL8)
- [freeCodeCamp - NestJS Course](https://www.youtube.com/watch?v=3dHNOWTI0Hk)

### 实战项目参考
- [NestJS官方示例](https://github.com/nestjs/nest/tree/master/sample)
- [RealWorld示例应用](https://github.com/gothinkster/nestjs-realworld-example-app)

### 工具推荐
- **Postman** - API测试工具
- **Docker** - 本地数据库环境
- **VS Code** - 推荐IDE，有丰富的NestJS插件
- **TablePlus** 或 **DBeaver** - 数据库管理工具

---

## 学习环境准备

### 必需工具
```bash
# Node.js (18+)
node --version

# npm 或 yarn/pnpm
npm --version

# NestJS CLI
npm install -g @nestjs/cli
nest --version

# Git
git --version
```

### 推荐IDE设置 (VS Code)
安装以下VS Code插件：
- ESLint
- Prettier
- NestJS Snippets
- TypeScript Importer
- Error Lens

### 数据库选择
- **PostgreSQL** (推荐) - 功能强大，广泛使用
- 或 **MySQL** - 也是不错的选择
- 或 **SQLite** - 本地开发简单

---

## 进度追踪

查看你的综合学习进度：

```bash
# 查看总体进度
cat progress/nestjs-learning-tracker.md

# 查看今日学习
cat sessions/$(date +%Y-%m-%d)/session-notes.md
```

---

## 学习检查清单

### 每日学习
- [ ] 今天学习了哪些主题？
- [ ] 完成了哪些代码练习？
- [ ] 遇到了什么困难？如何解决的？
- [ ] 哪些概念还需要加深理解？
- [ ] 明天的学习计划是什么？

### 每周回顾
- [ ] 本周完成了哪些项目？
- [ ] 哪些主题掌握了，哪些还需要复习？
- [ ] 下周的重点是什么？
- [ ] 需要调整学习计划吗？

---

## 常见问题 (FAQ)

### Q: 我完全没有后端经验，能学好吗？
**A**: 完全可以！你有前端基础，JavaScript和TypeScript你都会，只是思维需要转换。这个系统会引导你逐步掌握。

### Q: TypeScript一定要学吗？
**A**: NestJS强烈推荐使用TypeScript，虽然可以用JavaScript，但TypeScript能提供更好的开发体验和类型安全。建议花1-2天掌握基础。

### Q: 1个月能学会吗？
**A**: 能达到"能独立开发简单NestJS应用"的水平。深度掌握需要更多实战经验，但基础框架1个月完全够用。

### Q: 遇到错误怎么办？
**A**:
1. 先看错误信息，Google错误关键词
2. 检查官方文档是否有说明
3. 问OpenCode（我就是你的导师）
4. 看GitHub Issues或Stack Overflow

### Q: 需要学Express吗？
**A**: 不需要。NestJS本身基于Express，但NestJS封装得很好，你不需要直接操作Express。如果学有余力，可以了解Express底层原理。

---

## 学习成功标志

当你能独立完成以下任务时，说明你已经掌握了NestJS基础：

✅ **基础能力**:
- 创建NestJS项目
- 实现CRUD API
- 连接数据库
- 实现用户认证

✅ **理解能力**:
- 解释依赖注入的作用
- 区分Module/Controller/Service的职责
- 设计RESTful API
- 理解TypeScript类型系统

✅ **实战能力**:
- 从零开始搭建NestJS应用
- 查阅官方文档解决问题
- 编写可维护的代码
- 部署应用到生产环境

---

## 开始学习

现在就可以开始了！你可以问：

- "我想开始学习NestJS，应该从哪里开始？"
- "帮我创建第一个NestJS项目"
- "TypeScript和JavaScript有什么区别？"
- "什么是依赖注入？"

**AI会引导你完成每一步，并自动记录你的学习进度。**

---

## 保持动力

1. **设定小目标**: 每天完成1-2个小目标
2. **记录成就**: 看到完成的打勾项很有成就感
3. **分享进度**: 告诉朋友或同事你在学习NestJS
4. **实战驱动**: 用代码说话，看到自己的程序运行很开心
5. **允许犯错**: 错误是最好的学习机会

---

**记住**: 这个系统和你一起学习。不懂就问，遇到问题就解决，持续练习，你一定能成为全栈工程师！

**开始你的NestJS学习之旅吧！** 🚀
