# 标题
## 1. 文档说明
### 1.1 文档目的
### 1.2 文档范围
### 1.3 参考文档
## 2. 系统架构设计
### 2.1 整体架构
### 2.2 技术栈选择
#### 2.2.1 前端技术栈
React; 依赖：ant-design-vue axios vue vuex vue-router
#### 2.2.2 后端技术栈
Go + GIN 框架 + github.com/go-sql-driver/mysql 
controller → interface → service → interface → repo
示例：
```
backend
    main.go
    go.mod
    routes
        v1
        v2
        ...
    controller
    service
        InterfaceService.go
        UserService.go
        ...
    repository
        InterfaceRepository.go
        UserRepository.go
        ...
    model
        UserModel (struct: User、CreateUserRequest、CreateUserResponse...)
        ...
    middleware
        JwtMiddleware.go
        CorsMiddleware.go
        ...
    utils
        JwtUtils.go
    logs
    test
    config
        config.go
        config.yaml
```
统一response: 
```json
{
    code: 200,
    message: "成功",
    result: {} | [] | ""
}
```
#### 2.2.3 数据库
仅使用关系型数据库：MySQL
#### 2.2.4 部署与运维
## 3. 数据库设计
### 3.1 数据库概述
### 3.2 数据表设计
## 4. API 接口设计
### 4.1 API 设计规范
### 4.2 通用响应格式
### 4.3 API 接口描述
## 5. 前端页面设计
## 6. 开发规范
### 6.1 代码规范
#### 6.1.1 命名规范
#### 6.1.2 注释规范
### 6.2 API 规范
### 6.3 数据库规范
- **文档版本**: 
- **创建日期**: 
- **最后更新**:
- **维护人员**:






















### devflow-web前端
