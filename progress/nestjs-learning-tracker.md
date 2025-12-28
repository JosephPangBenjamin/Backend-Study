# NestJS 全栈开发学习追踪器

**Last Updated**: December 28, 2025
**Learning Period**: 1 Month (4 weeks)
**Target**: 独立开发NestJS应用程序

本文档追踪你的Node.js和NestJS学习进度，包括：
- 已掌握的主题
- 识别的知识缺口
- 每日学习计划
- 实战项目进度

---

## 学习背景

**学习者**: 前端开发工程师
**当前水平**:
- ✅ JavaScript熟练（前端开发经验）
- ❌ TypeScript不熟悉
- ❌ 无后端开发经验
- ❌ 未接触过NestJS

**学习目标**: 1个月内达到能独立开发NestJS应用
**学习方式**: 实战为主，理论为辅

---

## 进度概览

**总体进度**: 0% (0/25 核心主题)
**已完成周数**: 0/4 周
**实战项目**: 0/3 个项目

---

## 4周学习计划

### 第1周：基础搭建（TypeScript + Node.js基础）

**目标**: 从前端开发思维转到后端开发思维，掌握TypeScript基础

**学习重点**:
- TypeScript基础类型系统
- Node.js运行时和模块系统
- NestJS架构理解
- 第一个NestJS应用

**实战项目**: 简单的Hello World API

**核心主题**:
- [ ] TS.1 TypeScript基础（类型、接口、类）
- [ ] TS.2 TypeScript装饰器（Decorators）
- [ ] Node.1 Node.js模块系统（CommonJS vs ES Modules）
- [ ] Node.2 异步编程（Promise, async/await）
- [ ] Nest.1 NestJS核心概念（Module, Controller, Service）
- [ ] Nest.2 依赖注入理解
- [ ] Project.1 第一个NestJS API（GET/POST端点）

---

### 第2周：RESTful API开发

**目标**: 掌握REST API设计和NestJS标准开发模式

**学习重点**:
- RESTful API设计原则
- 请求验证
- 错误处理
- 数据传输对象（DTO）

**实战项目**: 简单的Todo API（CRUD操作）

**核心主题**:
- [ ] API.1 RESTful API设计原则
- [ ] Nest.3 Controllers详解（路由、参数、状态码）
- [ ] Nest.4 Services和业务逻辑分离
- [ ] Nest.5 DTOs和验证（class-validator）
- [ ] Nest.6 异常处理和过滤器
- [ ] Project.2 Todo API（完整CRUD）

---

### 第3周：数据库集成

**目标**: 连接真实数据库，实现数据持久化

**学习重点**:
- 关系型数据库基础
- ORM概念和使用
- 数据库迁移
- 实体关系

**实战项目**: 扩展Todo API，添加数据库支持

**核心主题**:
- [ ] DB.1 数据库基础（SQL基础，表设计）
- [ ] ORM.1 ORM概念（TypeORM或Prisma）
- [ ] Nest.7 数据库模块集成
- [ ] ORM.2 Entity定义和关系（One-to-Many, Many-to-Many）
- [ ] ORM.3 Repository模式
- [ ] Project.3 Todo API + 数据库（PostgreSQL）

---

### 第4周：企业级功能

**目标**: 掌握认证、授权和部署等生产级功能

**学习重点**:
- JWT认证
- 用户认证流程
- 中间件和守卫
- 部署和测试

**实战项目**: 用户认证系统（注册、登录、权限）

**核心主题**:
- [ ] Auth.1 JWT原理和实现
- [ ] Nest.8 Guards和认证
- [ ] Nest.9 中间件和拦截器
- [ ] Nest.10 环境配置（.env）
- [ ] Test.1 单元测试基础
- [ ] Deploy.1 部署到生产环境（Docker/Vercel/Heroku）
- [ ] Project.4 用户认证API

---

## 详细主题追踪

### TypeScript 基础 (TS)

#### [ ] TS.1 TypeScript基础
**Status**: Not Started
**预计时间**: 2-3小时
**关键概念**:
- 基本类型（string, number, boolean, array）
- 接口（Interface）
- 类（Class）
- 函数类型
- 泛型（Generics）基础
**实战练习**: 用TypeScript重写一个前端组件或工具函数

#### [ ] TS.2 TypeScript装饰器
**Status**: Not Started
**预计时间**: 1-2小时
**关键概念**:
- 装饰器语法和用途
- 类装饰器
- 方法装饰器
- 参数装饰器
- 属性装饰器
**实战练习**: 创建一个简单的装饰器（如日志装饰器）

---

### Node.js 基础 (Node)

#### [ ] Node.1 Node.js模块系统
**Status**: Not Started
**预计时间**: 1-2小时
**关键概念**:
- CommonJS (require/module.exports)
- ES Modules (import/export)
- 模块加载机制
- npm和包管理
**实战练习**: 创建一个模块，导出函数，在另一个文件中引用

#### [ ] Node.2 异步编程
**Status**: Not Started
**预计时间**: 2-3小时
**关键概念**:
- Event Loop基础
- Promise
- async/await
- 错误处理（try/catch）
**实战练习**: 模拟异步API调用，使用Promise和async/await

---

### NestJS 核心 (Nest)

#### [ ] Nest.1 NestJS核心概念
**Status**: Not Started
**预计时间**: 2-3小时
**关键概念**:
- Modules（模块组织）
- Controllers（处理请求）
- Services（业务逻辑）
- Providers（依赖注入）
**实战练习**: 创建一个简单的用户模块，包含Controller和Service

#### [ ] Nest.2 依赖注入
**Status**: Not Started
**预计时间**: 1-2小时
**关键概念**:
- 什么是依赖注入
- 构造函数注入
- NestJS的DI容器
- Provider的生命周期
**实战练习**: 重构代码，使用依赖注入解耦组件

#### [ ] Nest.3 Controllers详解
**Status**: Not Started
**预计时间**: 2小时
**关键概念**:
- 路由装饰器（@Get, @Post, @Put, @Delete）
- 参数装饰器（@Body, @Param, @Query）
- 状态码（@HttpCode）
- 请求生命周期
**实战练习**: 创建一个完整的CRUD API端点

#### [ ] Nest.4 Services和业务逻辑
**Status**: Not Started
**预计时间**: 2小时
**关键概念**:
- Service的作用（业务逻辑层）
- 单例模式
- Controller和Service的职责分离
**实战练习**: 将业务逻辑从Controller移到Service

#### [ ] Nest.5 DTOs和验证
**Status**: Not Started
**预计时间**: 2小时
**关键概念**:
- 数据传输对象（DTO）
- class-validator装饰器
- 验证管道（ValidationPipe）
**实战练习**: 为API创建DTO，添加验证规则

#### [ ] Nest.6 异常处理和过滤器
**Status**: Not Started
**预计时间**: 2小时
**关键概念**:
- NestJS内置异常
- 自定义异常
- 异常过滤器
- 全局异常处理
**实战练习**: 创建统一的错误响应格式

#### [ ] Nest.7 数据库模块集成
**Status**: Not Started
**预计时间**: 3-4小时
**关键概念**:
- @nestjs/config 环境配置
- TypeORM或Prisma集成
- 数据库连接配置
- Repository模式
**实战练习**: 连接PostgreSQL，配置数据源

#### [ ] Nest.8 Guards和认证
**Status**: Not Started
**预计时间**: 3-4小时
**关键概念**:
- Guards的作用
- canActivate方法
- JWT验证Guard
- 角色权限控制
**实战练习**: 创建JWT Guard，保护需要认证的端点

#### [ ] Nest.9 中间件和拦截器
**Status**: Not Started
**预计时间**: 2-3小时
**关键概念**:
- 中间件（Middleware）
- 拦截器（Interceptor）
- 管道（Pipe）
- 生命周期差异和选择
**实战练习**: 创建日志中间件和响应时间拦截器

#### [ ] Nest.10 环境配置
**Status**: Not Started
**预计时间**: 1小时
**关键概念**:
- .env文件
- ConfigModule
- 环境变量验证
**实战练习**: 配置开发/生产环境的不同设置

---

### 数据库和ORM (DB/ORM)

#### [ ] DB.1 数据库基础
**Status**: Not Started
**预计时间**: 3-4小时
**关键概念**:
- SQL基础（SELECT, INSERT, UPDATE, DELETE）
- 主键、外键
- 索引
- 表关系（1:1, 1:N, N:M）
**实战练习**: 设计Todo应用的数据库schema

#### [ ] ORM.1 ORM概念
**Status**: Not Started
**预计时间**: 2小时
**关键概念**:
- ORM vs 原生SQL
- TypeORM vs Prisma选择
- Entity定义
- Repository模式
**实战练习**: 定义Entity，映射到数据库表

#### [ ] ORM.2 Entity关系
**Status**: Not Started
**预计时间**: 2-3小时
**关键概念**:
- @OneToMany, @ManyToOne, @ManyToMany
- 级联操作
- 懒加载vs急加载
**实战练习**: 为Todo应用添加用户关联（1个用户多个todos）

#### [ ] ORM.3 Repository模式
**Status**: Not Started
**预计时间**: 2小时
**关键概念**:
- Repository API
- 查询构建
- 事务处理
**实战练习**: 使用Repository实现CRUD操作

---

### 认证和授权 (Auth)

#### [ ] Auth.1 JWT原理和实现
**Status**: Not Started
**预计时间**: 3-4小时
**关键概念**:
- JWT结构（header, payload, signature）
- Token生成和验证
- Token过期和刷新
- 安全最佳实践
**实战练习**: 实现JWT登录流程

---

### 测试和部署 (Test/Deploy)

#### [ ] Test.1 单元测试基础
**Status**: Not Started
**预计时间**: 2-3小时
**关键概念**:
- Jest基础
- 单元测试vs集成测试
- Mock和Stub
- 测试覆盖率
**实战练习**: 为Service编写单元测试

#### [ ] Deploy.1 部署到生产环境
**Status**: Not Started
**预计时间**: 2-3小时
**关键概念**:
- Docker基础
- 环境变量配置
- CI/CD基础
- 部署到Vercel/Heroku/Railway
**实战练习**: 将应用部署到云平台

---

## 实战项目列表

### Project.1: Hello World API
**状态**: 未开始
**难度**: ⭐
**技术点**: Nest.1, Nest.2
**功能**:
- [ ] 创建NestJS项目
- [ ] 实现GET /hello 端点
- [ ] 返回JSON响应
- [ ] 启动并测试

### Project.2: Todo API (CRUD)
**状态**: 未开始
**难度**: ⭐⭐
**技术点**: Nest.3, Nest.4, Nest.5, Nest.6
**功能**:
- [ ] GET /todos - 获取所有todos
- [ ] GET /todos/:id - 获取单个todo
- [ ] POST /todos - 创建todo
- [ ] PUT /todos/:id - 更新todo
- [ ] DELETE /todos/:id - 删除todo
- [ ] DTO验证
- [ ] 统一错误处理

### Project.3: Todo API + 数据库
**状态**: 未开始
**难度**: ⭐⭐⭐
**技术点**: DB.1, ORM.1, ORM.2, ORM.3, Nest.7
**功能**:
- [ ] 配置PostgreSQL数据库
- [ ] 创建Todo Entity
- [ ] 使用TypeORM/Prisma
- [ ] 实现数据持久化
- [ ] 数据库迁移

### Project.4: 用户认证系统
**状态**: 未开始
**难度**: ⭐⭐⭐⭐
**技术点**: Auth.1, Nest.8, Nest.9, Nest.10
**功能**:
- [ ] 用户注册
- [ ] 用户登录（JWT）
- [ ] 密码加密（bcrypt）
- [ ] 保护API端点
- [ ] Token验证Guard
- [ ] 环境配置

---

## 当前学习焦点

**今日目标**: 初始化学习环境，开始TypeScript基础

**下一步行动**:
1. 完成 [ ] TS.1 TypeScript基础
2. 开始第一个NestJS项目

---

## 知识缺口记录

### 🔴 高优先级缺口
- 无后端开发概念（需要快速理解后端开发思维）
- TypeScript类型系统（与JavaScript的重要差异）

### 🟡 中优先级缺口
- 数据库设计经验（关系型数据库）
- 异步编程在服务端的应用

### 🟢 低优先级缺口
- 部署和运维知识（后续补充）

---

## 学习技巧（前端开发者转后端）

**思维转换要点**:
1. **从UI到API**: 不再关注DOM操作，而是关注数据处理和API设计
2. **从客户端到服务端**: 考虑性能、安全性、并发处理
3. **从单机到分布式**: 理解网络请求、数据库连接、会话管理
4. **TypeScript**: 前端的类型推断更自由，后端需要更严格的类型定义

**实战优先原则**:
- 先能跑起来，再理解原理
- 每个概念都用代码验证
- 参考官方文档和示例项目
- 遇到问题直接搜索解决

---

## 资源链接

**官方文档**:
- NestJS官方文档: https://docs.nestjs.com/
- TypeScript官方文档: https://www.typescriptlang.org/docs/
- Node.js官方文档: https://nodejs.org/docs/

**推荐教程**:
- NestJS官方教程: https://docs.nestjs.com/first-steps
- Traversy Media NestJS教程 (YouTube)
- freeCodeCamp NestJS课程

**工具和库**:
- @nestjs/cli - 脚手架工具
- class-validator - 数据验证
- class-transformer - 数据转换
- TypeORM - ORM（可选Prisma）
- bcrypt - 密码加密
- @nestjs/jwt - JWT处理

---

## 每日学习检查清单

- [ ] 今天学习了哪些主题？
- [ ] 完成了哪些实战练习？
- [ ] 遇到了哪些困难？
- [ ] 哪些概念还需要加深理解？
- [ ] 明天的学习计划是什么？

---

**学习日志**:
- *每次学习后会话笔记会记录在 /sessions/ 目录*
