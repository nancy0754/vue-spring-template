<<<<<<< HEAD
# vue-demo

这是一个前后端分离的项目演示。

## 技术架构

### 前端技术栈
- Vue 3 - 渐进式JavaScript框架
- Vite - 下一代前端构建工具
- Vue Router - Vue.js官方路由管理器
- CSS变量 - 实现主题切换功能

### 后端技术栈 
- Spring Boot 3.4.1 - Java后端框架
- MySQL - 关系型数据库
- Lombok - Java实体类简化工具
- Maven - 项目构建工具

## 项目结构

## 推荐开发工具
- 前端: VSCode + Volar插件(需禁用Vetur)
- 后端: IntelliJ IDEA

## 配置说明
- 前端配置请参考 [Vite配置文档](https://cn.vitejs.dev/config/)
- 后端配置请参考 [Spring Boot配置文档](https://docs.spring.io/spring-boot/docs/current/reference/html/application-properties.html)

## 相关文档
- [Vue 3中文文档](https://cn.vuejs.org/)
- [Vite中文文档](https://cn.vitejs.dev/)
- [Spring Boot文档](https://spring.io/projects/spring-boot)

### 后端开发环境
- JDK 17+
- Maven 3.6+
- MySQL 8.0+


├── vue-demo/ # 前端项目目录
│ ├── src/ # 源代码目录
│ │ ├── assets/ # 静态资源(CSS、图片等)
│ │ ├── components/ # Vue组件目录
│ │ │ ├── icons/ # 图标组件
│ │ │ └── .vue # 其他Vue组件
│ │ ├── App.vue # 根组件
│ │ └── main.js # 应用入口文件
│ ├── index.html # HTML模板
│ ├── package.json # 项目依赖配置
│ ├── vite.config.js # Vite配置文件
│ └── README.md # 项目说明文档
│
└── backend/ # 后端项目目录
├── src/
│ ├── main/
│ │ ├── java/ # Java源代码目录
│ │ └── resources/# 配置文件目录
│ └── test/ # 测试代码目录
├── pom.xml # Maven配置文件
└── README.md # 后端说明文档

